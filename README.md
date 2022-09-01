- 👋 Hi, I’m @EluriTrishanka
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
EluriTrishanka/EluriTrishanka is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>


int isEven(int num)
{
    return !(num & 1);
}


int main()
{
    int num;
    
    printf("Enter any number: ");
    scanf("%d", &num);
    
    if(isEven(num))
    {
        printf("The number is even.");
    }
    else
    {
        printf("The number is odd.");
    }
    
    return 0;
}


output:
Enter any number: 4
The number is even.
