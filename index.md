## Welcome to sunilshukla's code archive 

You can find this and other code and some amazing projects in future. Find my code archive website [sunil-shukla](sunil-shukla.github.io).

This is updated regularly on a daily basis.

### let's get started :yawning_face:

Below is the code to multilply matrix of upto 10x10.


# C++ code to multiply upto 10x10 matrix
### You can copy code from upper-right corner button and run code [here](https://ide.usaco.guide/), currently copy feature not available on website but on github [link](https://github.com/sunil-shukla/sunil-shukla.github.io/blob/main/index.md)

```cpp
#include <iostream>
using namespace std;

// loops
#define FOR(i, b) for (int i = 0; i < (b); ++i)

int main()
{
    int r, c, x, y, z;
    int a[10][10], b[10][10], mul[10][10];
    cout << "enter no of row : ";
    cin >> r;
    cout << "enter no of columns : ";
    cin >> c;

    cout << "enter elements of 1st array :\n";
    FOR(x, r)
    {
        FOR(y, c)
        {
            cin >> a[x][y];
        }
    }

    cout << "enter elements of 2nd array :\n";
    FOR(x, r)
    {
        FOR(y, c)
        {
            cin >> b[x][y];
        }
    }

    cout << "multiplication of both matrices is :\n";
    FOR(x, r)
    {
        FOR(y, c)
        {
            mul[x][y] = 0;
            FOR(z, c)
            {
                mul[x][y] += a[x][z] * b[z][y];
            }
        }
    }
    FOR(x, r)
    {
        FOR(y, c)
        {
            cout << mul[x][y]<<"\t";
        }
        cout << "\n";
    }
    return 0;
}

```
## Run code [here](https://ide.usaco.guide/)

### Support or Contact

Having trouble with code? Catch me on [dummyforsunil@gmail.com](mailto:dummyforsunil@gmail.com) and we’ll help you sort it out.

Made in :india: 
![indiaflag](https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/800px-Flag_of_India.svg.png "INDIA")

