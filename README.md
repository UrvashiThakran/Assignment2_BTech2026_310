# Assignment2_BTech2026_310

# Coding Questions : 28.01.25

OOPS:

Problem Statement:

Ques1:Vrindavan

Code 1:

#include<iostream>
#include<string>
using namespace std;
class Vrindavan
{
    protected :
    string name1,name2,name3;
    public:
    void getname(string,string,string);
};
class Radha:public Vrindavan
{
    public:
    void getdata(string str1,string str2,string str3)
    {
        name1=str1;
        name2=str2;
        name3=str3;
    }
    void display()
    {
        cout<<"Vridavan Ke Jaan :"<<endl;
        cout<<"name1 :"<<name1<<endl;
        cout<<"name2 :"<<name2<<endl;
        cout<<"name3 :"<<name3;
    }
};
int main()
{
    Radha radha;
    radha.getdata("RadhaVallabh Ji","RadhaRaman Ji","KunjBuhari Ji");
    radha.display();
    return 0;
}


DBMS:

Platform Used:LeetCode

 Ques 1:Employee Bonus

 Code 1:

SELECT Employee.name,Bonus.bonus
From Employee LEFT OUTER JOIN Bonus
ON Employee.empId=Bonus.empId
where bonus<1000 OR bonus IS Null;


 DSA:

 
