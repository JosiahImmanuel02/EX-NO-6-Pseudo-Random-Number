# EX-NO-6-Pseudo-Random-Number

## Name: Josiah Immanuel 
## Reg no: 212223043003

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
### Step1- Start the program and import the required libraries.
### Step2- Seed the random number generator using the current time(i.e) rand(time(0));
### Step3- Get the number of randon number to generate.
### Step4- Pass the value for number of iterations and print the numbers.
### Step5- End the program.

# PROGRAM:
```
 #include <stdio.h>
 #include <stdlib.h>
 #include <time.h>
 int main()
 {
 int count, min, max;
 printf("Enter the number of random numbers to generate: ");
 scanf("%d", &count);
 printf("Enter the minimum value: ");
 scanf("%d", &min);
 printf("Enter the maximum value: ");
 scanf("%d", &max);
 srand(time(NULL));
 printf("Pseudorandom numbers:\n");
 for (int i = 0; i < count; i++)
{
 int random_number = (rand() % (max- min + 1)) + min;
 printf("%d\n", random_number);
 }
 return 0;
 }
```

# OUTPUT:

![Screenshot 2025-04-07 082433](https://github.com/user-attachments/assets/85ac81cd-88cc-4755-a1cc-75b978012f2c)


# RESULT:

The Program Excuted Successfully 
