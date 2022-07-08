
public class CursoJava {
  public static void main(String[] args) {
    System.out.print("\n");

    // Variaveis e Impressao no console


     int n1 = 10;
     int n2 = 20;
     int n3 = 40;
     int resp = n1 + n2 + n3;
     String name = "Welisson";
    
     System.out.print("PRINT\n");
     System.out.println("Curso de Java");
     System.out.printf("Canal:%s -  Ano:%d\n", "CFB cursos", 2021);

     System.out.printf("Valor da variavel name: %s\n", name);  
     System.out.printf("Valor da soma entre %d, %d e %d é: %d\n", n1, n2, n3, resp);  

     // Estrutura de Selecao

     int nota = 49;
     int faltas = 15;
     int maxFaltas = 15;

     String respFaltas = (faltas < maxFaltas ? "Aprovado" : "Reprovado");

     if(faltas >= maxFaltas) {
       System.out.printf("%s por faltas\n", respFaltas);
     } else {
       if( nota >= 70) {
         System.out.println("Aprovado");
       } else if (nota <= 69 && nota >= 50) {
         System.out.println("Recuperação");
       }
       else {
         System.out.println("Reprovado");
       }
     }
     System.out.println("Final");

    int pos = 7;

    switch(pos) {
      case 1:
        System.out.println("Select 1");
        break;
      case 2:
        System.out.println("Select 2");
        break;
      case 3:
        System.out.println("Select 3");
        break;
      default: 
        System.out.println("Default");
    }

  }
}









