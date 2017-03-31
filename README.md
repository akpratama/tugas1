using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
namespace tugas1
{
class Program
{
static void Main(string[] args0
{
//deklarasi
string Nama, NIM, Jenis Kelamin;
double Berat, Tinggi, BMI;
//judul
Console.Title = "Kalkulator BMI';
//Selamat Datang
Console.WriteLine("Selamat Datang di + Console.Title);
Console.WriteLine("Kami akan membantu menghitung apakah berat badan anda ideal atau tidak");
//Masukkan Nama
Console.WriteLine();
Console.WriteLine("Masukkan Nama Anda : ");
Nama = Console.ReadLine();
Console.WriteLine("/nHai" + nama + ", selamat datang);
//masukkan NIM
Console.WriteLine();
Console.WriteLine("Masukkan NIM anda : ");
NIM = Console.ReadLine();
Console.WriteLine(); 
Console.WriteLine("Oke, " + Nama + " NIM " + NIM + ".");
//jenis kelamin?
Console.WriteLine();
Console.WriteLine("Apakah anda laki-laki atau perempuan");
JenisKelamin = Console.ReadLine();
//masukkan berat badan
Console.WriteLine();
Console.WriteLine("Berat badan(dalam Kilogram)");
Berat = Convert.ToInt32 (Console.ReadLine());
//menghitung BMI
BMI = (1000 * Berat / Match.Pow(Tinggi, 2));
BMI = Match.Round (BMI, 2);
Console.WriteLine("BMI Anda adalah " + BMI);
if (JenisKelamin = "laki-laki")
{
if (BMI < 18)
{
Console.WriteLine("Kurus");
}
else if (BMI >= 18 & BMI <= 25)
{
Console.WriteLine("Normal");
}
else if (BMI >= 25 & BMI <= 27)
{
Console.WriteLine("Kegemukkan");
}
else
{
Console.WriteLine("Obesitas");
}
}
else
{
if (BMI < 17)
{
Console.WriteLine("Kurus");
}
else if (BMI >= 17 & BMI <= 23)
{
Console.WriteLine("Normal");
}
else if (BMI >= 23 & BMI <= 25)
{
Console.WriteLine("Kegemukkan");
}
else
{
Console.WriteLine("Obesitas");
}
}
Console.Write("/nTerimakasih");
Console.WriteLine("/nTekan enter untuk keluar");
Console.Read();
}
}
