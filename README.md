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
Hierachical inheritance in java
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
class Cat extends Animal{
    void cat(){
        System.out.println("cat a meow");
    }
}
public class Main{
    public static void main(String[]args){
        Puppy obj=new Puppy();
        obj.eat();
        obj.bark();
        obj.Weep();
        Cat Obj = new Cat();
        obj.eat();
        Obj.cat();
    }
}



///output
This Animal eat
Dog bark
Puppy weep
This Animal eat
cat a meow
