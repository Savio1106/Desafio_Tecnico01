using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {

            {
                string 名前;
                string 姓;
                float 生年;
                double 身長;
                int 誕生日;
                string ユーザー_インスタグラム;
                string 父親の名前;
                string 母親の名前;
                string 兄弟の名前;
                int リビングファミリーメンバー;
                float '25000' ;
                float '210';
                float フォロワー_since_2017;
                
                float x = 25000 - 210;
                bool check = true;





                Console.WriteLine("Cadastre-se:");


                {
                    Console.WriteLine("Entre com seu nome");
                     string= 名前  (Console.ReadLine());
                    Console.WriteLine("Entre com seu sobrenome");
                     string = 姓(Console.ReadLine());
                    Console.WriteLine("entre com seu ano de nascimento");
                     float.Parse = 生年(Console.ReadLine());
                    Console.WriteLine("Entre com sua altura");
                      double.Parse = 身長(Console.ReadLine());
                    Console.WriteLine("Entre com sua data de aniversáro");
                     int.Parse = 誕生日(Console.ReadLine());
                    Console.WriteLine("entre com seu usuário do instagram");
                     string = ユーザー_インスタグラム(Console.ReadLine());
                    Console.WriteLine("Entre com o nome do seu pai");
                     string = 父親の名前(Console.ReadLine());
                    Console.WriteLine("Entre com o nome da sua mãe");
                      string = 母親の名前(Console.ReadLine());
                    Console.WriteLine("entre com o nome do seu irmão");
                    string = 兄弟の名前(Console.ReadLine());
                    Console.WriteLine("digite quantos membros de sua familia você não matou");
                     int.Parse = リビングファミリーメンバー(Console.ReadLine());
                    Console.WriteLine("seu nome é: " + 名前);
                    Console.WriteLine("Seu sobrenome é:" + 姓);
                    Console.WriteLine("Seu ano de nascimento é: " + 生年);
                    Console.WriteLine("sua altura é " + 身長);
                    Console.WriteLine("seu aniversário é : " + 誕生日);
                    Console.WriteLine("Seu user do instagram é é:" + ユーザー_インスタグラム);
                    Console.WriteLine("o nome do seu pai é: " + 父親の名前);
                    Console.WriteLine("o nome da sua mãe é :" + 母親の名前);
                    Console.WriteLine("o nome do seu irmão é:" + 兄弟の名前);
                    Console.WriteLine("o número de membro da sua família que você não matou é" + リビングファミリーメンバー);
                    Console.WriteLine("O numero de seguidores desta conta desde 2017 é:" + x);
                    Console.WriteLine(check ? "Checked" : " checked");

                    Console.WriteLine(false ? "Checked" : " checked");
                }
                Console.ReadKey();
            }
        }
    }
}
