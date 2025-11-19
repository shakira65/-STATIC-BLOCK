# -STATIC-BLOCK

Author- Shakira Murshida

class StaticBlock {

    static int x;
    static double b;
    
    static{
        x=10;
        b=20.2;}

  static void display(){
  
      System.out.println(x+b);
      System.out.println(x+", "+b);
  }        
}     
class Main {

    public static void main(String[]args) {
    
    StaticBlock.display();
    System.out.println(StaticBlock.x);
    System.out.println(StaticBlock.b);
    }
}
