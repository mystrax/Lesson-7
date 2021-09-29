# Lesson-7
Mark my  Words

           #include <iostream>
        using namespace std;

        int main()
        {
            int myGrade;
            cout << "Type the percentage of your grade?\n";
            cin >> myGrade;

            if (myGrade >= 70)
            {
                cout << "Your grade is A.\n";
            }
            else if ((myGrade>59)&&(myGrade<69))
            {
                cout << "Your grade is B.\n";
            }
            else if ((myGrade>49)&&(myGrade<59))
            {
                cout << "Your grade is C.\n";
            }
            else if ((myGrade>39)&&(myGrade<49))
            {
                cout << "Your grade is D.\n";
            }
            else
            {
                cout << "Your grade is F.\n";
            }
        }
