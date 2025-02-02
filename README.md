class Animal{
    void eat(){
        System.out.println("This Animal eat");
    }
}
class Dog extends Animal{
    void bark(){
        System.out.println("Dog bark");
    }
}
class Puppy extends Dog{
    void Weep(){
        System.out.println("Puppy weep");
    }
}
public class Main{
    public static void main(String[]args){
        Puppy obj=new Puppy();
        obj.eat();
        obj.bark();
        obj.Weep();
    }
}
