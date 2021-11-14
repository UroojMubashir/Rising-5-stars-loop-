#include <iostream>
using namespace std;
int main()
{
    int o = 1;
    int j = 1;

    while (o <= 5)
    {
        j = 1;
        while (j <= o) {
            cout << "*";
            j++;
        }
        cout << endl;
        o++;
    }
}
