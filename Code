int evenDigits(int n)
{
  int sum=0;
  if(n==0)
    return 0;
  else if(n%2==0)
  {
    sum=n%10+10*evenDigits(n/10);
  }
  else
    sum=evenDigits(n/10);
  return sum;
}
