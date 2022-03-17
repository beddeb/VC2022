#include <iostream>

using namespace std;

class AB
{
    private:
        int a;
        int b;
    public:
        
        int globalAB = 0;
    
        AB(int A, int B)
        {
            a = A;
            b = B;
            cout << "Работа конструктора начинается здесь!" << endl;
            cout << "a = " << a << endl;
            cout << "b = " << b << endl;
        }
        void setAB(){
            cout << "Введите целое число а: ";
            cin >> a;
            std::cout << "Введите целое число b: ";
            cin >> b;
        }
        void getAB(){
            cout << "a = " << a << endl;
            cout << "b = " << b << endl;
        }
        int returnA(){
            return a;
        }
        int returnB(){
            return b;
        }
        ~AB(){
            cout << "Work destroyer" << endl;
        }
};

int main(){
    int result;
    
    AB obj1(5, 10);
    obj1.setAB();
    obj1.getAB();
    
    AB obj2(6, 12);
    obj2.getAB();
    
    

    return 0;
}
