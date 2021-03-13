package fr.krykox.lobby;

import java.util.Arrays;

public class Test {

    public static void main(String[] args) {
        final String[] name = {"KryKox" , "Lilian"};
        final int age = 18;
        final String studying = "Computer Developer";

        System.out.println("My name is: " + Arrays.toString(name).substring(1, 15) + " I'm " + age + " years old" + " I study in " + studying + " !");


    }
}
