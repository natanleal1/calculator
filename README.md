### Calculadora Básica 🧮

Este projeto é uma **calculadora web** simples e funcional, desenvolvida com **HTML**, **CSS** e **JavaScript**. Ela permite que os usuários realizem operações matemáticas básicas como adição, subtração, multiplicação e divisão diretamente no navegador.

---

### Lógica do JavaScript 🧠

A lógica da calculadora é controlada por três funções principais, que interagem diretamente com o display e os botões da interface.

* **`appendToDisplay(input)`**: Esta função é chamada toda vez que um número ou operador é clicado. Ela recebe o valor do botão como um argumento (`input`) e o adiciona ao final do conteúdo atual do display. Isso permite construir a expressão matemática progressivamente.
* **`clearDisplay()`**: Quando o botão "C" é pressionado, esta função é acionada para apagar todo o conteúdo do display, redefinindo-o para uma string vazia.
* **`calculate()`**: Esta é a função central que realiza o cálculo. Ela usa a função `eval()` do JavaScript para avaliar a expressão matemática completa que está no display. O método `eval()` executa a string como um código JavaScript, resolvendo a operação. Para garantir a robustez, a lógica de `try...catch` é usada para capturar e exibir um "Error" caso a expressão seja inválida (por exemplo, "5 + /").
