# CsHelloWorld
HelloWorldと表示（.NET Core）

## 処理
コンソールアプリとして画面にHelloWorldと表示

## コード
```
using System;

namespace Hello
{
    class Hello
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");

            // 実行結果確認のための処理 ここから
            Console.WriteLine();
            Console.WriteLine("何かキーを押してください");
            Console.ReadKey();
            // ここまで
        }
    }
}
```

## 出力結果  
```
Hello World!

何かキーを押してください
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 統合開発環境(IDE) | Visual Studio Community 2017 |
| 開発言語 | Visual C# |
