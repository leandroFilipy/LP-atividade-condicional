# Exercícios Java - If-Else e Cadastro

## 1. Cadastro simples (Nome, Idade, Email)

```java
import java.util.Scanner;

public class CadastroSimples {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        System.out.print("Digite seu nome: ");
        String nome = sc.nextLine();
        
        System.out.print("Digite sua idade: ");
        int idade = sc.nextInt();
        sc.nextLine(); // Consumir a quebra de linha
        
        System.out.print("Digite seu email: ");
        String email = sc.nextLine();
        
        System.out.println("\nDados cadastrados:");
        System.out.println("Nome: " + nome);
        System.out.println("Idade: " + idade);
        System.out.println("Email: " + email);
        
        sc.close();
    }
}
