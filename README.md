# While and Do While Loop Lectures

## Remain Positive
    #include <iostream>
    using namespace std;
    {
    float myNum = 20; // could also use double instead of float
    while (myNum > 0)
    {
        cout << myNum << endl;
        (myNum -= 0.5);
    }
    }
    
## Reverse 9
    #include <iostream> 
    using namespace std;
    int main() 
    {
    int num = 108;


    while (num > 0) {
        cout << num << endl;
        (num -= 9);
    }
    cin.get();
    return 0;
    }
    
    
## Pointless Box
    #include <iostream> 
    using namespace std;
    int main()
    {
    cout << "This is a useless contraption. 1 or 2? \n";
    int num;
    cin >> num;

    while (num==1 || num ==2) {
        cin.clear();
        if (num = 1) {
            cout << "Yes this is a 1. \n";
            cout << "This is useless. 1 or 2? \n";
            cin >> num;
        }
        else if (num = 2) {
            cout << "Yes this is a 2. \n ";
            cout << "This is useless. 1 or 2? \n";
            cin >> num;
        }
    }
    cout << "Yes, no. 1 and 2 only, buddy.";
    }

## Would you like to quit? (Fix)
    #include <iostream> 
    using namespace std;
    int main() {
    char input;
    do {
        cout << "Would you like to Quit (Y/N)?" << endl;
        cin >> input;
    } while ((input != 'Y') && (input != 'y')); //i shouldnt be N because there is no point if you dont quit



    return 0;
    }
