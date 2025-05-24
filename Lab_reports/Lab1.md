## *Lab No : 01*

## *Lab Workout : Solve some basic problem in c*

## *Submission Date : 24 May,2025*

---

## *Problem 1 :*
<div align="justify">
   A C program to print your name, date of birth, and mobile number.
</div>

## *Code :*
```C
#include <stdio.h>

int main() {

    printf("Name: Zubaer Ahmed Siam\n");
    printf("Date of Birth:12 May,2006\n");
    printf("Mobile: +8801326883885\n");

    return 0;
}



## *Output :* 
*Doing a Sum*
<p align="center">
<img alt="2410020_lab1_prob_1" src="<img width="443" alt="task 1" src="https://github.com/user-attachments/assets/15d45bd6-7e35-4067-9b2a-c3f5040a6305" />
">
</p>




## *Problem 2 :*
<div align="justify">
 A C program to compute the perimeter and area of a rectangle with a
height of 7 inches and width of 5 inches.
</div>

## *Code :*
```C
#include <stdio.h>

int main() {
    int height, width;
    int perimeter, area;


    printf("Height of the rectangle: ");
    scanf("%d", &height);

    printf("Width of the rectangle: ");
    scanf("%d", &width);

    perimeter = 2 * (height + width);
    area = height * width;

    printf("Perimeter = %d inches\n", perimeter);
    printf("Area = %d square inches\n", area);

    return 0;
}





## *Output :* 
*convertING specified days into years, weeks and days*
<p align="center">
<img alt="2410020_lab1_prob_2" src="<img width="371" alt="task 2" src="https://github.com/user-attachments/assets/b8a43279-ebfd-42f2-aece-efea105f11b3" />
">
</p>



## *Problem 3 :*
<div align="justify">
  A C program to convert specified days into years, weeks and days.
Note: Ignore leap year.

## *Code :*
```C
include <stdio.h>

int main() {
    int total_days, years, weeks, days;


    printf("Total number of days: ");
    scanf("%d", &total_days);


    years = total_days / 365;
    weeks = (total_days % 365) / 7;
    days = (total_days % 365) % 7;

    printf("%d days = %d year(s), %d week(s), and %d day(s)\n", total_days, years, weeks, days);

    return 0;
}


```


## *Output :* 
*calculating distance*
<p align="center">
<img alt="2410020_lab1_prob_3" src=<img width="442" alt="task 3" src="https://github.com/user-attachments/assets/f04afead-e6d2-42b9-b40f-57a1bb5a30bb" />
">
</p>



## *Problem 4 :*
<div align="justify">
  Write a C program that accepts two item's weight and number of purchases
(floating point values) and calculates their average value..
</div>

## *Code :*
```C
#include <stdio.h>

int main() {
    float weight1, weight2;
    int quantity1, quantity2;
    float average;

    printf("Weight of item 1: ");
    scanf("%f", &weight1);

    printf("Quantity of item 1: ");
    scanf("%d", &quantity1);

    printf("Weight of item 2: ");
    scanf("%f", &weight2);

    printf("Quantity of item 2: ");
    scanf("%d", &quantity2);

    average = (weight1 * quantity1 + weight2 * quantity2) / (quantity1 + quantity2);

    printf("Average Value = %.7f\n", average);

    return 0;
}


```


## *Output :* 
*Calculating Average*
<p align="center">
<img alt="2410020_lab1_prob_4" src="<img width="349" alt="task 4" src="https://github.com/user-attachments/assets/fc473ed9-65cb-4cc1-8658-c92eb3d2b4c0" />
">
</p>




## *Problem 5 :*
<div align="justify">
   A C program to accept two integers and check whether they are equal
or not.
</div>

## *Code :*
```C
#include <stdio.h>

int main() {
    int number1, number2;

    printf("Enter two numbers: ");
    scanf("%d %d", &number1, &number2);


    if (number1 == number2) {
        printf("Number1 and Number2 are equal\n");
    } else {
        printf("Number1 and Number2 are not equal\n");
    }

    return 0;
}


```


## *Output :* 
*checking prime or not*
<p align="center">
<img alt="2410020_lab1_prob_5" src="<img width="360" alt="task 5" src="https://github.com/user-attachments/assets/f52f69e1-2444-4a92-8592-e32c7bb3ea62" />
">
</p>


---

## *Problem 6 :*
<div align="justify">
A  C program to check whether a given number is even or odd.
Test Data : 15</div>

## *Code :*
```C
#include <stdio.h>

int main() {
    int number;

    printf("enter an number: ");
    scanf("%d", &number);

    if (number % 2 == 0) {
        printf("%d is an even number\n", number);
    } else {
        printf("%d is an odd number\n", number);
    }

    return 0;
}

```


## *Output :* 
*Calculating sum*
<p align="center">
<img alt="2410020_lab1_prob_6" src="<img width="341" alt="task 6" src="https://github.com/user-attachments/assets/5a3993e6-2164-487a-b336-d8a4ba7e9ec7" />
">
</p>


