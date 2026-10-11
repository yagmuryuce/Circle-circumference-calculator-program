# Circle-circumference-calculator-program
#include <stdio.h>
#include <stdlib.h>

int main() {
	const double PI=3.14159;
	double radius;
	double circumference;
	double area;
	printf("\n Enter the radius of the circle.: ");
	scanf("%lf",&radius);
	
	circumference= 2*PI*radius;
	area= PI*radius*radius;
	printf("\n circumference of the circle: %lf",circumference);
	printf(" \n area of ​​the circle:%lf",area);
	return 0;
}
