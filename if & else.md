Estudo básico (if e else)

if e else:
if: É uma estrutura condicional que permite executar um bloco de código se uma condição específica for verdadeira.

Exemplo:



if (condição) {
    // Código a ser executado se a condição for verdadeira
}


else: É uma extensão do if que permite especificar um bloco de código a ser executado se a condição no if for falsa.


Exemplo:




if (condição) {
    // Código a ser executado se a condição for verdadeira
} else {
    // Código a ser executado se a condição for falsa
}



else if: É usado para adicionar outra condição à verificação, útil quando há mais de duas possibilidades de resultados.

Exemplo:




if (condição1) {
    // Código a ser executado se a condição1 for verdadeira
} else if (condição2) {
    // Código a ser executado se a condição1 for falsa e a condição2 for verdadeira
} else {
    // Código a ser executado se todas as condições anteriores forem falsas
}



Exemplo de Uso:





int main() {
    int numero = 10;

    // Verificar se o número é positivo, negativo ou zero
    if (numero > 0) {
        printf("O número é positivo.\n");
    } else if (numero < 0) {
        printf("O número é negativo.\n");
    } else {
        printf("O número é zero.\n");
    }

    return 0;
}




Neste exemplo, o programa verifica se o número é positivo, negativo ou zero. Se o número for maior que zero, ele imprime "O número é positivo.". Se for menor que zero, imprime "O número é negativo.". Se nenhuma dessas condições for verdadeira (ou seja, o número for igual a zero), ele imprime "O número é zero.".


Vou mostrar exemplos de como usar if e else com float, char e int.

  Exemplo com int:


  

  int main() {
      int idade;

      printf("Digite sua idade: ");
      scanf("%d", &idade);

      if (idade >= 18) {
          printf("Você é maior de idade.\n");
      } else {
          printf("Você é menor de idade.\n");
      }

      return 0;
  }



  
  Neste exemplo, o programa solicita ao usuário inserir sua idade como um número inteiro (int). Em seguida, verifica se a idade é maior ou igual a 18. Se for, imprime "Você é maior de idade.". Caso contrário, imprime "Você é menor de idade.".

  Exemplo com float:




  int main() {
      float temperatura;

      printf("Digite a temperatura em graus Celsius: ");
      scanf("%f", &temperatura);

      if (temperatura < 0.0) {
          printf("Está muito frio!\n");
      } else {
          printf("Está quente!\n");
      }

      return 0;
  }



  
  Neste exemplo, o programa solicita ao usuário inserir a temperatura em graus Celsius como um número de ponto flutuante (float). Em seguida, verifica se a temperatura é inferior a 0.0. Se for, imprime "Está muito frio!". Caso contrário, imprime "Está quente!".

  Exemplo com char:




  int main() {
      char letra;

      printf("Digite uma letra: ");
      scanf(" %c", &letra);

      if (letra == 'a' || letra == 'e' || letra == 'i' || letra == 'o' || letra == 'u') {
          printf("A letra digitada é uma vogal.\n");
      } else {
          printf("A letra digitada é uma consoante.\n");
      }

      return 0;
  }



  
  Neste exemplo, o programa solicita ao usuário inserir uma letra como um caractere (char). Em seguida, verifica se a letra é uma vogal (a, e, i, o, u). Se for, imprime "A letra digitada é uma vogal.". Caso contrário, imprime "A letra digitada é uma consoante.". Note que para caracteres individuais em C, você precisa usar aspas simples (') ao invés de duplas (").
