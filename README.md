# Lesson-7
Mark my Words

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

Killing time
  
                       include <iostream>
                      using namespace std;
                      int main()
                      {
                                 int time;
                                 int money;
                                 cout << "State if your friend is going to be late or early than 15 minutes\n";
                                 cin >> time;
                                 if (time >= 15)
                                 {
                                            cout << "If you have more than 5 AED you can buy a coffee.\n";
                                            cin >> money;
                                            if (money > 5)
                                            {
                                                       cout << "Nice! I can buy a coffee and wait for him." << endl;
                                            }
                                            else
                                            {
                                                       cout << "Go around the town for a walk.\n";
                                            }
                                 }
                                 else
                                 {
                                            cout << " I'll wait for him in the meeting up place.\n";
                                 }
                                 return 0;

                      }
