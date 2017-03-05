# ALI
/*
 Created by:
 
 Ali Alqublani.
 
 ]Muni ridership calculator
 (110A Practice Problem 3)
 
 survey about Muni ridership calculator how much the average of riders per day
 */

#include<iostream>
using namespace std;

int main()
{
    char muni_line[50];
    
    int days,riders;
    
    float average;
    
    
    cout<<"Hello! welcome to the Muni Ridership Calculator.\n";
    cout<<"Which Muni line did you survey?"<<" ";
    cin>>muni_line;
    
    cout<<"How many days did you survey it?"<<" ";
    cin>>days;
    
    cout<<"How many riders did you count?"<<" ";
    cin>>riders;
    
    average= static_cast<float>(riders)/days;
    
    cout<<"According to your survey, an average of"<<" "<<average<<" ";
    cout<<"people rode the "<<" "<<muni_line<<" per day.\n";
    
    return 0;
}

/* THE OUTPut:c++

Hello! welcome to the Muni Ridership Calculator.
Which Muni line did you survey? Bush
How many days did you survey it? 7
How many riders did you count? 53423
According to your survey, an average of 7631.86 people rode the  Bush per day.
Program ended with exit code: 0

*/
