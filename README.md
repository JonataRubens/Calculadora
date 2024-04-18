# Calculadora

 
Este é um programa simples de calculadora em C# que permite ao usuário realizar operações de soma, subtração, multiplicação e divisão entre dois números.

1. **Declaração de `using`**:
   - O programa utiliza o namespace `System` para ter acesso às funcionalidades básicas de entrada e saída.

2. **Namespace `Calculator`**:
   - Define um namespace chamado `Calculator` para o código.

3. **Classe `programa`**:
   - Declara uma classe chamada `programa` (observe que o nome está em minúsculas, mas geralmente segue a convenção PascalCase para nomear classes em C#).

4. **Método `Main`**:
   - O ponto de entrada do programa, onde `Menu()` é chamado para exibir as opções de operação disponíveis.

5. **Método `Menu`**:
   - Exibe um menu para o usuário com as opções de operação disponíveis.
   - Lê a opção escolhida pelo usuário.
   - Com base na opção escolhida, chama o método correspondente para realizar a operação selecionada.

6. **Métodos para operações matemáticas**:
   - `Soma()`, `Subtracao()`, `Multiplicacao()` e `Divisao()` são métodos para realizar as operações de soma, subtração, multiplicação e divisão, respectivamente.
   - Cada método solicita ao usuário que insira dois valores, realiza a operação correspondente e exibe o resultado na tela.
   - Após exibir o resultado, chama o método `Menu()` novamente para permitir que o usuário escolha outra operação.

7. **Método `Sair`**:
   - Exibe uma mensagem de agradecimento e encerra o programa quando o usuário seleciona a opção "Sair" no menu.

Este programa oferece uma maneira simples de realizar operações matemáticas básicas e pode ser facilmente estendido para incluir mais funcionalidades, como operações com mais operandos ou tratamento de erros de entrada do usuário.
