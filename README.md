# CRT-CIVIL-C-P#include <stdio.h>

int main() {
    // Write C code here
    int age;
    scanf("%d,age");
    if(age>=18);
    printf("eligiblie for vote");
    
    return 0;ROGRAM   cherry
    new code 11
#include <stdio.h>
void main()
{
    int number;
    scanf("%d",&number);
    switch(number)
    {
        case 0:
                  printf("it is sunday");
                  break;
        case 1:
        printf("it is monday");
        break;
        case 2:
        printf("it is tuesday");
        break;
        case 3:
        printf("it is wednesday");
        break;
        case 4:
        printf("it is thirsday");
        break;
        case 5:
        printf("it is friday");
        break;
        case 6:
        printf("it is saturday");
    default:
    printf("invalid number give number 0 to 6");
    }

}
  new code positive number code
  #include <stdio.h>
int main()
{
    int n, num, sum = 0, rem, fact, i;
    scanf("%d", &n);
    num = n;
    while (n > 0)
    {
        rem = n % 10;
        fact = 1;
        i = 1;
        while (i <= rem)
        {
            fact = fact * i;
            i++;
        }
        sum = sum + fact;
        n = n / 10;
    }
    if (sum == num)
    {
        printf("%d is a strong number", num);
    }
    else
    {
        printf("%d is not a strong number", num);
    }
    return 0;
}
  code of the  factor of the -

  #include <stdio.h>

int facto(int i) {
    if (i == 0) {
        return 1;
    } else {
        return i * facto(i - 1);
    }
}

int main() {
    int n, j;
    scanf("%d", &n);
    j = facto(n);
    printf("%d\n", j); // Print factorial result
    return 0;
}
