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
                                                       cout << "Nice! I can get a coffee." << endl;
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
                      
Earthquake

           #include <iostream>
           using namespace std;
           int main()
           {
               int theMagni;
               cout << "State the magnitude of the earthquake.\n";
               cin >> theMagni;

               if (theMagni <= 2.0)
               {
                   cout << "the Earthquake is considered: Micro\n";
               }
               else if ((theMagni > 1.99) && (theMagni < 3.0))
               {
                   cout << "The Earthquake is considered: Very Minor\n";
               }
               else if ((theMagni > 2.99) && (theMagni < 4.0))
               {
                   cout << "The Earthquake is considered: Minor\n";
               }
               else if ((theMagni > 3.99) && (theMagni< 5.0))
               {
                   cout << "The Earthquake is considered: Light\n";
               }
               else if ((theMagni > 4.99) && (theMagni < 6.0))
               {
                   cout << "The Earthquake is considered: Moderate\n";
               }
               else if ((theMagni > 5.99) && (theMagni < 7.0))
               {
                   cout << "The Earthquake is considered: Strong\n";
               }
               else if ((theMagni > 6.99) && (theMagni < 8.0))
               {
                   cout << "The Earthquake is a considered: Major\n";
               }
               else if ((theMagni > 7.99) && (theMagni < 10.0))
               {
                   cout << "The Earthquake is considered: Great\n";
               }
               else
               {
                   cout << "The Earthquake is a Meteoric.\n";
               }

           }

