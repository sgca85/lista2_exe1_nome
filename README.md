Digite seu primeiro nome

Soraia

Digite seu ultimo sobrenome

Abbas

Nome Completo:Soraia Abbas

Catálogo:ABBAS,Soraia


_____________________________________


CÓDIGO C#
Console.Clear();

string Nome;
string Sobrenome;

Console.WriteLine("Digite seu primeiro nome");
Nome = Console.ReadLine()!;
Thread.Sleep(1000);

Console.WriteLine("Digite seu ultimo sobrenome");
Sobrenome = Console.ReadLine()!;
Thread.Sleep(1000);

Console.WriteLine($"Nome Completo:{Nome} {Sobrenome}");
Thread.Sleep(1000);

Console.WriteLine($"Catálogo:{Sobrenome.ToUpper()},{Nome}");
Thread.Sleep(1000);
