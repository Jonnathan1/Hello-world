using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Perguntas
{
    class Program
    {
        static void Main(string[] args)
        {
            // Um diretor de uma quer saber se os seus funcionários estão gostando da empresa, porém caso alguém não goste ele quer
            // saber o motivo. APENAS UM FUNCIONARIO.

            string situacaoFuncionario;
            string respostaSeNao;

            Console.WriteLine("Você está gostando de trabalhar aqui? (Sim ou Não)");
            situacaoFuncionario.ToLower  = Console.ReadLine();

            if(situacaoFuncionario.ToLower() == "Sim")
            {
                Console.WriteLine("Que legal! Muito bom saber que você gosta de trabalhar aqui");
            }
            else
            {
                if (situacaoFuncionario.ToLower() == "não")
                {


                    Console.WriteLine("Mas por que você não gosta de trabalhar aqui?");
                    respostaSeNao = Console.ReadLine();
                    Console.WriteLine("A sua resposta é: " + respostaSeNao);


                }             
            }
            Console.ReadKey();
        }
    }
}
