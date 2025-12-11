package Superclass;


public class Animal {
  void sound()//parent method
  {
      System.out.println("Animal makes a sound");
  }
}
public class Cat extends Animal{
    void sound(){
        super.sound();//called the parent method
   System.out.println("Cat makes sound meow ");     
    }
}
public class Main {
   public static void main(String[]args)
   {
       Cat c= new Cat();
       c.sound();
   }
}



