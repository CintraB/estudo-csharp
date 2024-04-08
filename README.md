# Screen Sound - Sistema de Avaliação de Bandas

Este é um simples sistema de avaliação de bandas em C#.

## Descrição

O Screen Sound permite registrar bandas, avaliá-las e calcular a média das avaliações. As principais funcionalidades incluem:

- Registro de bandas
- Listagem de bandas cadastradas
- Avaliação de bandas
- Cálculo da média de notas de uma banda

## Pré-requisitos

Para executar este projeto, é necessário ter o SDK do .NET instalado em seu ambiente de desenvolvimento.

## Como Executar

1. Clone o repositório para o seu ambiente local.
2. Navegue até a pasta do projeto.
3. Compile o projeto com o comando `dotnet build`.
4. Execute o projeto com o comando `dotnet run`.

## Funcionalidades

- **Registrar Bandas:** Permite registrar uma nova banda no sistema.
- **Listar Bandas:** Mostra todas as bandas cadastradas no sistema.
- **Avaliar Banda:** Permite atribuir uma nota a uma banda existente.
- **Média de Notas:** Calcula e exibe a média das notas atribuídas a uma banda.

## Uso

Ao iniciar o programa, o usuário será apresentado com um menu interativo, onde poderá escolher uma das opções disponíveis.

## Exemplo de Código

```csharp
// Exibir Logo
void ExibirLogo()
{
    // Logo do Screen Sound
    Console.WriteLine(@"
    ░██████╗░█████╗░██████╗░███████╗███████╗███╗░░██╗  ░██████╗░█████╗░██╗░░░██╗███╗░░██╗██████╗░
    ██╔════╝██╔══██╗██╔══██╗██╔════╝██╔════╝████╗░██║  ██╔════╝██╔══██╗██║░░░██║████╗░██║██╔══██╗
    ╚█████╗░██║░░╚═╝██████╔╝█████╗░░█████╗░░██╔██╗██║  ╚█████╗░██║░░██║██║░░░██║██╔██╗██║██║░░██║
    ░╚═══██╗██║░░██╗██╔══██╗██╔══╝░░██╔══╝░░██║╚████║  ░╚═══██╗██║░░██║██║░░░██║██║╚████║██║░░██║
    ██████╔╝╚█████╔╝██║░░██║███████╗███████╗██║░╚███║  ██████╔╝╚█████╔╝╚██████╔╝██║░╚███║██████╔╝
    ╚═════╝░░╚════╝░╚═╝░░╚═╝╚══════╝╚══════╝╚═╝░░╚══╝  ╚═════╝░░╚════╝░░╚═════╝░╚═╝░░╚══╝╚═════╝░
    ");
    Console.WriteLine("");
    Console.WriteLine(mensagemDeBoasVindas);
}

// Exibir Opções do Menu
void ExibirOpcoesDoMenu()
{
    ExibirLogo();

    Console.WriteLine("\nDigite 1 para registrar uma banda");
    Console.WriteLine("Digite 2 para mostrar todas as bandas");
    Console.WriteLine("Digite 3 para avaliar uma banda");
    Console.WriteLine("Digite 4 para exibir a média de uma banda");
    Console.WriteLine("Digite 5 para sair");

    Console.Write("\nDigite a sua opção: ");
    string opcaoEscolhida = Console.ReadLine()!;
    int opcaoEscolhidaNumerica = int.Parse(opcaoEscolhida);

    switch (opcaoEscolhidaNumerica)
    {
        // Opções do Menu
    }
}
