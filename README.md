# Compile-time-polymorphism

Coding-

package polymorphism;

public class Polymorphism {
    public int addition(int x,int y){
        return x+y;
    }
    public int addition(int x,int y,int z){
        return x+y+z;
    }
    public double addition(double x,double y){
        return x+y;
    }

    
    public static void main(String[] args) {
        // creating objects
        Polymorphism number=new Polymorphism();
        //calling overloaded methods
        int res1=number.addition(11,20);
        System.out.println("Addition of two integers:"+res1);
        int res2=number.addition(110,120,280);
        System.out.println("Addition of three integers:"+res2);
        double res3=number.addition(10.15, 20.15);
        System.out.println("Addition of two doubles:"+res3);
        
        
    }
    
}


Output-

Addition of two integers:31
Addition of three integers:510
Addition of two doubles:30.299999999999997
