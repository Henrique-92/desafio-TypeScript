# Desafio DIO utilizando TypeScript (BootCamp Full-Stack - Santander)
<br>

Foi proposto o desafio de reajustar o código abaixo com alguns erros a fim de colocar em prática conceitos básicos. Para deixar estilizado utilizei algumas propriedades do CSS 3. 

        O código abaixo tem alguns erros e não funciona como deveria. Você pode identificar quais são e corrigi-los em um arquivo TS?

        let botaoAtualizar = document.getElementById('atualizar-saldo');
        let botaoLimpar = document.getElementById('limpar-saldo');
        let soma = document.getElementById('soma');
        let campoSaldo = document.getElementById('campo-saldo');

        campoSaldo.innerHTML = 0

        function somarAoSaldo(soma) {
        campoSaldo.innerHTML += soma;
        }       

        function limparSaldo() {
        campoSaldo.innerHTML = '';
        }

        botaoAtualizar.addEventListener('click', function () {
        somarAoSaldo(soma.value);
        });

        botaoLimpar.addEventListener('click', function () {
        limparSaldo();
        });