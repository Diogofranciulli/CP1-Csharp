//Checkpoint 1 - Desenvolver uma calculadora em aplicação Console C#.

//O programa deve permitir ao usuário realizar operações básicas como adição, subtração, multiplicação e divisão. 
//Utilizem estruturas de controle e fluxo, como if/else, switch, for, while e do-while.

//Requisitos do Trabalho:
//1 - O programa deve apresentar o título "Calculadora (Adição / Subtração / Multiplicação / Divisão)", logo abaixo, deve apresentar menu com as seguintes opções:

//Escolha uma opção:
//1 - Adição
//2 - Subtração
//3 - Multiplicação
//4 - Divisão
//5 - Sair

//2 - O usuário deve escolher uma operação digitando o número correspondente.
//3-Após escolher a operação, o programa deve solicitar dois números ao usuário.
//4-O programa deve realizar a operação escolhida e exibir o resultado.
//5-O programa deve continuar executando até que o usuário escolha a opção de sair.
//6-O programa deve tratar erros, como divisão por zero.

//Entrega:
//O código-fonte deve ser postado como 'público' no GitHub, a entrega será o link deste repositório!
//Adicione ao readme do GitHub:
//-O nome dos integrantes (até 5 pessoas)
//- O print da tela com as opções da calculadora carregada (1-Adição, 2-Subtração, etc).
//- 4 Print de evidência de teste, um print evidenciando o correto funcionamento de cada operação (1-Adição, 2-Subtração, etc).

//Critérios de Avaliação:
//Uso correto dos operadores de fluxo if/else ou switch/case	4 pts
//Uso correto de tipos de dados das variáveis 4 pts
//Boas práticas: Nomes das variáveis (PascalCase)	2 pts
//Total	10 pts

double Somar(double num1, double num2) {
    return num1 + num2;
}

double Subtrair(double num1, double num2) {
    return num1 - num2;
}

double Multiplicar(double num1, double num2) {
    return num1 * num2;
}

double Dividir(double num1, double num2) {
    double resultado;
    if (num2 == 0)
    {
        return -1;
    }

    return num1 / num2;
}


void IniciarCalculadora() {
    Console.WriteLine("===========Calculadora (Adição / Subtração / Multiplicação / Divisão)===========");

    while (true)
    {
        Console.WriteLine("=== 1 - Adição ===");
        Console.WriteLine("=== 2 - Subtração ===");
        Console.WriteLine("=== 3 - Multiplicação ===");
        Console.WriteLine("=== 4 - Divisão ===");
        Console.WriteLine("=== 5 - Sair ===");
        Console.WriteLine("===== Escolha uma opção: =====");
        int opcaoEscolhida = int.Parse(Console.ReadLine());

        if (opcaoEscolhida == 5)
        {
            Console.WriteLine("Obrigado pelos cálculos! Até mais!!");
            return;
        }

        Console.WriteLine("Escolha o primeiro número: ");
        Double numeroEscolhido1 = Double.Parse(Console.ReadLine());

        Console.WriteLine("Escolha o segundo número: ");
        Double numeroEscolhido2 = Double.Parse(Console.ReadLine());

        double resultado;

        switch (opcaoEscolhida)
        {
            case 1:
                Console.WriteLine("===RESULTADO===");
                resultado = Somar(numeroEscolhido1, numeroEscolhido2);
                Console.WriteLine(resultado);
                Console.WriteLine("===============");
                break;
            case 2:
                Console.WriteLine("===RESULTADO===");
                resultado = Subtrair(numeroEscolhido1, numeroEscolhido2);
                Console.WriteLine(resultado);
                Console.WriteLine("===============");
                break;
            case 3:
                Console.WriteLine("===RESULTADO===");
                resultado = Multiplicar(numeroEscolhido1, numeroEscolhido2);
                Console.WriteLine(resultado);
                Console.WriteLine("===============");
                break;
            case 4:
                Console.WriteLine("===RESULTADO===");
                resultado = Dividir(numeroEscolhido1, numeroEscolhido2);
                Console.WriteLine(resultado == -1 ? "Não pode haver divisões por 0" : resultado);
                Console.WriteLine("===============");
                break;
            case 5:
                Console.WriteLine("Obrigado pelos cálculos! Até mais!!");
                return;
        }


    }

}

IniciarCalculadora();
