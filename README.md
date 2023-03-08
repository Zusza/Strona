//Szablon:
//typ_wyniku nazwa(arg)
//{
//    instrukcje
//    return? -> opcjonalnie
//}

//void przywitaj()
//{
//    Console.WriteLine("Cześć, Marcia pobiera Visual Studio 2022 XD");
//}
//przywitaj();

//Funkcja obliczająca sumę 2 podanych liczb

//int suma(int a, int b)
//{
//    return a + b;
//}
//Console.WriteLine(suma(4, 6));

//Funkcja odwracająca stringa

//string odwrocStringa(string napis)
//{
//    char[] chars = napis.ToCharArray();
//    Array.Reverse(chars);
//    return new string(chars);
//}
//Console.WriteLine(odwrocStringa("metorwop z i mat ilyzc tibboH"));

//Funkcja, która przyjmuję dowolną ilość argumentów

//Suma wszystkich argumentów (tyle ile ich jest)

int bigSuma(int[]T)
{
    int suma = 0;
    foreach (int item in T)
    {
        suma += item;
    }
    return suma;
}
Console.WriteLine(bigSuma(new int[] {1, 2, 3}));

//Rekurencja
void rekurencja()
{
    Console.Write("Marcia UwU" + " ");
    rekurencja();
}
rekurencja();
