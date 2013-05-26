qvadr
=====

#include &lt;iostream> using namespace std; int main() {     double x1,x2;     double a, b, c;     cout&lt;&lt;"The quadratic decision
Enter in one line value of factors and press &lt;Enter>
";     cin>>a>>b>>c;     if(a==0)     {         cout&lt;&lt;"The equation isn't square";     }     else     {         double d=b*b-4*a*c;         if(d&lt;0)         {             cout&lt;&lt;"The equation has no decision in the valid area";         }         if(d==0)         {             cout&lt;&lt;"The equation has 2 identical roots of the equation:
";             x1=-b/(2*a);             cout&lt;&lt;"x = "&lt;&lt;x1;         }         if(d>0)         {             cout&lt;&lt;"Equation roots:
";             d=sqrt(d);             x1=(-b+d)/(2*a);             x2=(-b-d)/(2*a);             cout&lt;&lt;"x1 = "&lt;&lt;x1&lt;&lt;"
"&lt;&lt;"x2 = "&lt;&lt;x2;         }     }     return 1; }
