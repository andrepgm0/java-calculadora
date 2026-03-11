import java.util.Scanner;
public class Calculadora {

    public static void main(String[] args) {

        Scanner entrada = new Scanner(System.in);

        System.out.println("Digite o primeiro valor:");
        int n1 = entrada.nextInt();

        System.out.println("Digite o segundo valor:");
        int n2 = entrada.nextInt();

        System.out.println("Qual operação irá utilizar? (+, -, /, *)");  
        String operacao = entrada.next();

        if (operacao.equals("+")) {
            System.out.println("Resultado: " + (n1 + n2));
        } 
        else if (operacao.equals("-")) {
            System.out.println("Resultado: " + (n1 - n2));
        } 
        else if (operacao.equals("*")) {
            System.out.println("Resultado: " + (n1 * n2));
        } 
        else if (operacao.equals("/")) {

            if (n2 == 0) {
                System.out.println("Não é possível dividir por zero.");
            } else {
                System.out.println("Resultado: " + (n1 / n2));
            }

        } 
        else {
            System.out.println("Operação inválida.");
        }

        entrada.close();
    }
}
