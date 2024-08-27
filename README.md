# Experiment---11 

##### Aim 
To study and implement Classes and Objects.  

##### Software 
VS Code 

##### Theory  

##### Code 

(A) <br> 
```

# include<iostream>
using namespace std;
class cuboid
{
    public:
    double h = 2.0;
    double b = 3.0;
    double l = 4.0;
};
int main()
{
  cuboid c1;
  double vol = c1.h * c1.b * c1.l;
  cout<<"Volume "<<vol<<endl;
}
```

(B) <br> 
```
# include<iostream>
using namespace std;
class cuboid
{
    public:
    double h = 2.0,b = 3.0,l = 4.0;
    double volume()
    {
        double vol = h * b * l;
        cout<<"Volume "<<vol<<endl;
    }

};
int main()
{
    cuboid c1;
    c1.volume();
  
}
```

(C) <br> 
```
# include<iostream>
using namespace std;
class cuboid
{
    private:
    double h = 3.0,b = 2.0,l = 4.0;
    public:
    double volume()
    {
        double vol;
        vol = h * b * l;
        cout<<"Volume "<<vol<<endl;
    }

};
int main()
{
    cuboid c1;
    c1.volume();
  
}
```

(D) <br> 
```
# include<iostream>
using namespace std;
class cuboid
{
    private:
    double h = 2.0,b = 3.0,l = 4.0;
    public:
    double volume()
    {
        double vol;
        vol = h * b * l;
        return vol;
    }

    void disp(double vol)
    {
        cout<<"Volume "<<vol<<endl;

    }

};
int main()
{
    cuboid c1;
    double v = c1.volume();
    c1.disp(v);
  
}

```

(E) <br> 
```
```

##### Output 

(A) <br> 
![](https://github.com/Shloka-Patel/Experiment---11/blob/main/Output_11A.png)

(B) <br> 
![](https://github.com/Shloka-Patel/Experiment---11/blob/main/Output_11B.png) 

(C) <br> 
![](https://github.com/Shloka-Patel/Experiment---11/blob/main/Output_11C.png) 

(D) <br> 
![]() 

(E) <br> 
![]()

##### Conclusion 
