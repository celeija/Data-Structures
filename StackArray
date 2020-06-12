#include <iostream>
using namespace std;

int main()
{
    stackArray<int> intstack;

}

template<class T>
class stackArray 
{
public:
    int size;
    int top;
    T * element;
    stackArray();
    bool isEmpty();
    bool isFull();
    void print();
    void push(T);
    void pop(T&);

};


template<class T>
stackArray<T>::stackArray()
{
    size = 10;
    top = -1;

}

template<class T>
bool stackArray<T>::isFull()
{
    if(top == -1)
        return true;
    return false;
}

template<class T>
void stackArray<T>::push(T v)
{
    if(!isFull())
    {
        top++;
        element[top] = v;
    }
}

template<class T>
void stackArray<T>::pop(T& x)
{
    if(!isEmpty())
    {
        x = element[top];
        top--;
    }
}

template <class T>
void stackArray<T>::print()
{

}
