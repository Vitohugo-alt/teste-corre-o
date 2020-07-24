# teste-corre-o

using System;

namespace ProjetodeSoftware
{
    class Program
    {
        static void Main(string[] args)
        {
            string nome; 
            string todosItens;
            string Itemescolhido;
            string Itemescolhido = Item1, Item2, Item3;
            string Item1;
            string Item2;
            string Item3;
            string Teclado;
            string Mouse;
            string CPU;
            string todosItens = Item1, Item2, Item3;

            Console.WriteLine("\n-*-Lojinha do Billu-*-\n");

            Console.WriteLine("Bem vindo a nossa loja Virtual.");
            Console.WriteLine("Eu sou o Bilu, irei guiá-lo(s) pela nossa loja.");
            Console.Write($"Por favor digite os seu nome: ");
            nome = Console.ReadLine();
            Console.WriteLine($"Olá {nome}, vamos ás compras.");


                todosprodutos = ("produto1, produto2, produto3");
            Console.WriteLine("\nEsses são os nossos produtos:\nItem 1:Teclado--R$60,00\nItem 2: Mouse--10,00\nItem 3: CPU--2.000,00\n");
            Console.WriteLine("\nQual item Você deseja? ");

            Itemescolhido = Console.ReadLine();

            switch(Itemescolhido)
            {

                case "Item1":
                    Console.WriteLine($"O seu produto foi Teclado");
                    break;
            }



            
        }
    }
}
