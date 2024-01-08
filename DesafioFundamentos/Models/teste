using System;

class Program
{
    static void Main()
    {
        // Solicitar informações ao usuário
        Console.WriteLine("Digite o nome de usuário:");
        string nomeUsuario = Console.ReadLine();

        Console.WriteLine("Digite o email de cadastro:");
        string emailCadastro = Console.ReadLine();

        Console.WriteLine("Digite a senha:");
        string senha = Console.ReadLine();

        // Construir a mensagem de saída
        string mensagemSaida = ConstruirMensagem(nomeUsuario, emailCadastro);

        // Exibir a mensagem
        Console.WriteLine(mensagemSaida);
    }

    static string ConstruirMensagem(string nomeUsuario, string emailCadastro)
    {
        // Construir a mensagem formatada
        string mensagem = $"{nomeUsuario}, verifique o email: {emailCadastro} para ativar.";

        return mensagem;
    }
}