#  Kseniya Gavrilova
### Future content manager
___
#### Contacts:
**Phone:** (+375)447328858 | **Email:** ksuga311002@gmail.com
___
#### Soft skills:
-Critical thinking    
-Flexibility    
___
#### Skills:
-C++    
-Microsoft Excel     
-Microsoft Word    
___
#### Current studying:
Content management, 1 grade, VSU named after P.M. Masherov
___
#### English level:
B2
___
#### Some codes:
```с++
class Circle   
{    
protected:    
    double R;    
public:    
    Circle(double R)    
    {    
        this->R = R;    
    }    
    double s1()    
    {    
        return 3.14 * (R * R);    
    }    
};    
    
class Ring :public Circle    
{    
protected:    
    double r;    
public:    
    Ring(double r, double R) : Circle(R)    
    {      
        this->r = r;    
    }    
    double s2()    
    {    
        return (3.14 * R * R) - (3.14 * r * r);    
    }    
};    
    
int main()    
{    
    setlocale(0, "rus");    
    double r, R;    
    cout << "Введите радиус большей окружности: ";    
    cin >> R;    
    cout << "Введите радиус меньшей окружности: ";   
    cin >> r;    
    Circle Ci(R);    
    Ring Ri(r, R);    
    cout << "Площадь круга равна " << Ci.s1() << "\n";    
    cout << "Площадь кольца равна " << Ri.s2() << "\n";   
    system("pause");   
    return 0;   
}   
```
