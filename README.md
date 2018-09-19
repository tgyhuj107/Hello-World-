# Hello-World-
test1

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scn =new Scanner(System.in);
        int a = scn.nextInt();
//        if (a>=0 && a<=100){
//            if (a>=90){
//                System.out.println("A");
//            }
//            else if (a>=80){
//                System.out.println("B");
//            }else if (a>=70){
//                System.out.println("C");
//            }else if (a >=60 ){
//                System.out.println("D");
//            }else {
//                System.out.println("F");
//            }
//        }else {
//            System.out.println("error");
//        }

        if (a%2==0){
            System.out.println("偶數");
        }else {
            System.out.println("奇數");
        }
    }
}
