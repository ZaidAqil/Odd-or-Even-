# Odd-or-Even-
//Za8s 
#include <iostream>
#include <string>
using namespace std;
#include <cmath>


int main()
{
  int num;char test;
  int Y; int y;
  do
  {
      cout<<"Enter A Number\n";
      cin>>num;
      if (num %2==0)
      cout<<"It is even number\n";
      else
      cout<<"It is an odd number\n";
      
      cout<<"Do you want to test another number? Enter Y\n";
      cin>>test;
  }
  
  while (test=='Y' || test=='y');
  return 0;
}
      
  

