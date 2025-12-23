#include <iostream.h>
#include <conio.h>
#include <math.h>   // for pow()

float simpleInterest(float p, float r, float t) {
    return (p * r * t) / 100;
}

float compoundInterest(float p, float r, float t) {
    return p * pow((1 + r / 100), t) - p;
}

void main() {
    clrscr();

    float p, r, t;

    cout << "Enter Principal amount: ";
    cin >> p;

    cout << "Enter Rate of Interest: ";
    cin >> r;

    cout << "Enter Time (in years): ";
    cin >> t;

    cout << "\nSimple Interest = " << simpleInterest(p, r, t);
    cout << "\nCompound Interest = " << compoundInterest(p, r, t);

    getch();
}
