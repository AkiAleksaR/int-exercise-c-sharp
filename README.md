📌 Praktične Vežbe za int
✅ Vežba 1: Sabiranje brojeva
📌 Unesite dva broja sa tastature i ispišite njihov zbir.
solution
Console.WriteLine("Unesite prvi broj:");
int prviBroj = int.Parse(Console.ReadLine());

Console.WriteLine("Unesite drugi broj:");
int drugiBroj = int.Parse(Console.ReadLine());

int zbir = prviBroj + drugiBroj;
Console.WriteLine("Zbir oba broja je: " + zbir);

✅ Vežba 2: Provera da li je broj paran ili neparan
📌 Unesite broj i proverite da li je paran ili neparan.
solution
Console.WriteLine("Unesite broj:");
int broj = int.Parse(Console.ReadLine());

if (broj % 2 == 0)
{
    Console.WriteLine("Broj je paran.");
}
else
{
    Console.WriteLine("Broj je neparan.");
}


✅ Vežba 3: Prebrojavanje do unetog broja
📌 Unesite broj i ispišite brojeve od 1 do tog broja.
solution
Console.WriteLine("Unesite broj:");
int broj = int.Parse(Console.ReadLine());

for (int i = 1; i <= broj; i++)
{
    Console.WriteLine(i);
}
