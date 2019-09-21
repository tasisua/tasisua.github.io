# tasisua.github.io
Beginning stages

package project.eightball;

import java.util.Random;

public class Magic8 {


    public static void main(String[] args) {


        /*
        Random rand = new Random();

        int rand1 = rand.nextInt(5);


        System.out.println("Your fortune for today is: ");
        System.out.println("Random number: " + rand1);



        if (rand1 == 1) {

            System.out.println("Today it's up to you to create the peacefulness you long for.");

        }
        if (rand1 == 2) {
            System.out.println("A friend asks only for your time not your money.");
        }

        if (rand1 == 3) {
            System.out.println("If you refuse to accept anything but the best, you very often get it.");
        }

        if (rand1 == 4) {
            System.out.println("A smile is your passport into the hearts of others.");
        }

        if (rand1 == 5) {
            System.out.println("A good way to keep healthy is to eat more Chinese food.");
        }
   */

        Random rand = new Random();

        int rand1 = rand.nextInt(5);


                switch(rand1) {

                    case 1:
                        System.out.println("Thoughts of the day: ");
                        System.out.println("Today it's up to you to create the peacefulness you long for.");
                        break;

                    case 2:
                        System.out.println("Thoughts of the day: ");
                        System.out.println("A friend asks only for your time not your money.");
                        break;

                    case 3:
                        System.out.println("Thoughts of the day: ");
                        System.out.println("If you refuse to accept anything but the best, you very often get it.");
                        break;

                    case 4:
                        System.out.println("Thoughts of the day: ");
                        System.out.println("A smile is your passport into the hearts of others.");
                        break;

                    case 5:
                        System.out.println("Thoughts of the day: ");
                        System.out.println("A good way to keep healthy is to eat more Chinese food.");
                        break;

                    default:
                        System.out.println("Please try again");
                        break;
