## Q1. 得意なプログラミング言語 Favorite Programming Language
あなたの得意なプログラミング言語を記載してみてください。
Write what your favorite programming language is here.

using System;

public class MainApp
{
    static public void Main(string[] args)
    {
	for (int i = 0; i < args.Length; i++)
        {
           string output = String.Format("Hello {0}!",args[i]);
           Console.WriteLine(output);
        }
    }
}


## Q2. コードの説明 Code Explanation
あなたのコードがどのように動作するのか、簡潔に説明してください。
Write a brief explanation about how your code works here.

