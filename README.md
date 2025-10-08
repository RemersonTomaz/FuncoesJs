# Atividade
#### Como Funcionam os: Function Declaration, Function Expression, Arrow Function.
## O Que São Funções e Como Funcionam?
>As **funções** em JavaScript são partes do código que criamos para executar alguma tarefa específica.  
Elas servem pra deixar o código mais organizado, evitar repetir comandos e facilitar a manutenção do programa.

De forma bem simples, uma função pode:
- **Receber valores** (que chamamos de parâmetros);
- **Fazer alguma ação** com esses valores;
- E depois **devolver um resultado** (chamado de retorno).

# Como Criar Funções em JavaScript

>Funções são **blocos de código que fazem uma tarefa específica**.  
Elas ajudam a **organizar o código**, **evitar repetir coisas** e **deixar o programa mais fácil de entender**.
1. Escreva `function` seguido do nome da função.  
2. Entre `{ }` coloque o que a função vai fazer.  
3. Pode receber **valores** (parâmetros) e **devolver um resultado** com `return`.
Exemplo:
```
function dobro(num) {
  return num * 2;
}

// Chamando a função aqui:
console.log(dobro(5)); // 10
// O Número 5 é Dado porque a função recebe o numero 5, que foi escrita pelo usuário, e 10 porque é a saida do console
```

## Funções e seus tipos:
- Function Declaration
- Function Expression
- Arrow Function
### 1. Function Declaration
Função para **somar dois números**.
-Pode ser usada em qualquer lugar do código, mesmo antes de ser definida.
> Este mesmo antes de ser definida, diz que a função pode ser "guardada" no código

```
** Somas Dois Numeros
function somarnum(a, b) {
  return a + b;
}

console.log(somarnum(22, 15)); // 37
```

### 2. Function Expression
- Função guardada em uma variável.
- Só pode ser usada depois de ser criada.
- Permite criar funções dentro de variáveis e usar quando quiser.
```
** Subtrair Dois Números
const subtrair = function(a, b) {
  return a - b;
}

console.log(subtrair(10, 4)); // 6
```
### 3. Arrow Function
- Sintaxe curta e fácil de escrever.
- Ótima para Funções curtas, ou até mesmo callbacks
```
** Calcular o Quadrado Do Numero Colocado
const quadrado = (numero) => numero * numero;

console.log(quadrado(5)); // 25
```

## Final
> Em resumo: **funções permitem que você escreva código uma vez e use várias vezes**, tornando seu programa mais limpo e eficiente.
