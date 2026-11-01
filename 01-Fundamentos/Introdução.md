# Sintaxes

## Hello Word

- using System = Pegando dependências do sistema
- namespaces "Algum NOME" = Serve como conteiner Pai para classes , para referência e chamar igual ao System
- class = classe para programar dados e metodos , um outro conteiner
- static void Main = 	Indica que o método pertence à classe (static) , void sendo o tipo da função (void não retorna variavel) e main sendo a primeira função a ser regida
- console = É uma classe do namespace System, utilizada para interagir com o console (janela) . e depois possui o metodo WriteLine para pegar e escrever o que estiver em parênteses() 

Obs:"Se você não quiser usar a dependência , o console terá que ter System antes"

## Codigo

```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```
