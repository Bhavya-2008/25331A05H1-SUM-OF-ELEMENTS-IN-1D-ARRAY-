# 25331A05H1-SUM-OF-ELEMENTS-IN-1D-ARRAY-
#include <stdio.h>
int main() {
int n, i, sum = 0, arr[100];
printf("Enter number of elements: ");
scanf("%d", &n);
printf("Enter %d elements:\n", n);
for(i = 0; i < n; i++) 
{
  scanf("%d", &arr[i]);
  sum += arr[i];
 }
printf("Sum of array elements = %d\n", sum);
return 0;
 }
