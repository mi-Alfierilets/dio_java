# dio_java
import java.util.Scanner;

public class main {
    static void main(String [] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("olá qual é o seu nome ?");
        String nome = scanner.next();
        System.out.println("Qual é a sua idade?");
        int idade = scanner.nextInt();
        System.out.printf("olá %s usa idade %s /n", nome, idade  );


        }
