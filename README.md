# prime-number

{
    int num,i;
printf("Enter a positive number");
scanf("%d", &num);
for(i=2;i<num/2;i++)
{
    if (num%i==0)
    {printf("Number is not prime");
    break;}
    
}
if (i==num/2)
{printf("Number is prime");}
return 0;
}
