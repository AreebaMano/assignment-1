# assignment-1
 
class triangle
 { 
         // data members 
         int base,perp,hypo ; 
  
         // constructor 
   Triangle(int b, int p, int h); 
         { 
                 base = b;
                 perp = p; 
                 hypo= h;
         } 
  
         // methods 
  
         int area() 
         { 
                 return (base*perp/2); 
         } 
  
         int perimeter() 
         { 
                 return 2 (base+ perp+ hypo); 
         } 
  
 }



class TriangleCalculator 
 { 
         public static void main(String[] args) 
         { 
  
                 Triangle r = new Triangle(7,6,9); 
  
                 System.out.println("Area = " + r.area()); 
                 System.out.println("Perimeter = " + r.perimeter()); 
         } 
  
 }
