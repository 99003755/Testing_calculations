

#include <factorial_logarithm.h>

          //Logarithm Product Function

float product(float a, float b)
{
    if(a==0)
    {
      //  printf("ERROR");
      return 0;
    }
    else if(b==0)
    {
       // printf("ERROR");
       return 0;
    }
    else
    {
          double result;
          result=log(a)+log(b);
        //  printf("result of product is=%d ",result); 
        return result;
    }
}

                //Logarithm Ratios Function

float ratios(float a, float b) 
{
    if(a==0)
    {
       // printf("ERROR");
       return 0;
    }
    else if(b==0)
    {
     //   printf("ERROR");
     return 0;
    }
    
     else
    {
        double result;
        result=log(a)-log(b);
       return result;
       // printf("result of ratios is=%d ",result); 
    }
}
              //Factorial Function

int factorial(int n)
{
    int i,fact=1;
    
    if(n==1)
    {
	
       return 0;
       // printf("Factorial of a number is 1");
    
    }
    else
    {
	
    for(i=1; i<=n; i++)
    {
        fact=fact*i;
    }
        return fact;
        // printf("Factorial of a number is= %d",fact);
    }

}
                    // Main Function

/* int fact_input(void);
{

    int num;
    
    // Passing parameters 
    printf("Enter the number for factorial : ");
    scanf(" %d",num);
    factorial(num);

    return 0; 
}   */
