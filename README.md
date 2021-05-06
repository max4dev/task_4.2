# task_4.2

public class Main {

    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.setAge(2);
        dog.setName("Пузик");
        System.out.println("Собаку зовут - " + dog.getName());
        System.out.println("Возраст собаки - " + dog.getAge() );
    }
}

class Dog {

    private String name = "";
    private int age = 0;

    public void setAge(int age) {
        this.age = age;
    }

    public int getAge() {
        return age;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getName() {
        return name;
    }
}
