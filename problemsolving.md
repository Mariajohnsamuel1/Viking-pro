@Mariajohn Antony

//finding the factors of a given number
#include<iostream>
using namespace std;
int main() {
   int num = 20, i;
   cout << "The factors of " << num << " are : ";
   for(i=1; i <= num; i++) {
      if (num % i == 0)
         cout << i << " "; 
   }
   return 0;
}
