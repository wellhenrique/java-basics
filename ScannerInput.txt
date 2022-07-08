import java.util.Scanner;

public class CursoJava {
  public static void main(String[] args) {
    System.out.print("\n");

    // Scaner values input console

    Scanner input = new Scanner(System.in);

    int n1 = 0, n2 = 0;    
    String name = "";
    
    System.out.print("Digite o seu nome: ");
    name = input.next();

    System.out.printf("\n%s digite um numero: ", name);
    n1 = input.nextInt();

    System.out.printf("\n%s digite outro numero: ", name);
    n2 = input.nextInt();

    System.out.printf("\nO valor da soma entre %d e %d é igual a: %d\n", n1, n2, (n1 + n2));
  }
}









