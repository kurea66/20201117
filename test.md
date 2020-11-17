# 定期テスト
-問横()内は配点

## unix

**問1(2)ホームディレクトリを表す記号はどれか**  
1. $
1. %
1. ~
1. ./

**問2(2)フォルダ毎コピーする為に必要なオプションはどれか**
1. -r
1. -m
1. cp
1. mv

**問3(2)現在作業しているディレクトリの中身を全て削除する`滅びの呪文`はどれか**
1. rm ./*
1. rm -r /
1. rm -r ./*
1. rm /*

**問4(4)test.txtというファイルを作成しtestと書き込むコマンドを１行で実行せよ**
- 解答記入欄

___
## vim

**問1(2)複数行削除するコマンドはどれか**
1. 数値dw
1. 数値dd
1. 数値de
1. 数値dO

**問2(2)Redo(取り消しの取り消し)はどれか**
1. Shift + u
1. Ctrl + y
1. Ctrl + r
1. Shift + r

**問3(2)カーソルから行末までの文字検索はどれか**
1. :f 文字
1. /文字
1. ?文字
1. ?f文字

**問4(2)直前に作業していた行に戻るコマンド、進コマンドの組み合わせとして正しいものはどれか**
1. Shift+o,Shift+i
1. Ctrl+o,Shift+i
1. Shift+d+o,Shift+d+i
1. Ctrl+o,Ctrl+i

**問5(2)changeという文字を検索しhogeに置換を行うコマンドを記述せよ(１行で記述すること)**
- 解答記入欄


___
## git

**問1(2)branchを切ると同時に切ったブランチに移動するコマンドはどれか**
1. git checkout ブランチ名
1. git checkout -r ブランチ名
1. git branch -u ブランチ名
1. git checkout -b ブランチ名

**問2(2)git add コマンドを実行すると変更が上がるエリアはどれか**
1. アドエリア
1. コミットエリア
1. ステージングエリア
1. ブランチエリア

**問3(2)devブランチをmasterブランチにマージするコマンドはどれか**
1. git marge dev
1. git marge master
1. git merge dev
1. git merge master

**問4(2)gitclone後ブランチ作成、追跡設定、checkoutまで一気にやるコマンドはどれか**
1. git clone checkout -b ブランチ名
1. git checkout -b ブランチ名 origin/ブランチ名
1. git checkout -b ブランチ名　pull/ブランチ名
1. git checkout -b ブランチ名 ブランチ名

**問5(2)現在作業しているブランチの最新コミットオブジェクトを指すポインターを記載せよ**
- 解答記入欄

___

##Html,css

**問1(2)cssとは何の略か**
1. custom style sheet
1. custom special style
1. cascading style sheet
1. cascading special sheet

**問2(2)票を作成する際の行と列のタグの組み合わせで正しいものはどれか**
1. tr,td
1. table,th
1. th,td
1. tr,tc

**問3(2)RGBカラー(cssの色指定)で白はどれか**
1. #aaa
1. #bbb
1. #000
1. #fff

**問4(2)文字に打消し点線をつけるための宣言はどれか**
1. text-decolation:overline;
1. text-decolation:line-through dotted;
1. text-decolation:overlin dotted;
1. text-decolation:overline dotted;

**問5(2)position:abusoluteの要素は何を基準として絶対配置しているか**
1. position:staticの親要素
1. 直前の親要素
1. 直前の要素
1. position:static以外の親要素

**問6(5)下記のソースでhead内にmetaタグで文字コードを指定しtitleをtestとして記述してください。**

```
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

- 解答欄


____

**問7(5)下記のcssソースでcontainer要素の中央揃え、背景色を青に指定するソースを記述せよ**

```
.container{
  
}
```
- 解答欄


___


## Java

**問1(2)下記のソースコードを実行した際、出力内容にxの値が入るように〇の中を埋めよ**
```java
int x=10;
System.out.println("xの値は"〇"です。");
```

- 解答欄


___
**問2(2)下記のソースコードを実行した際、一行ごとに改行されるように〇の中を埋めよ**
```java
System.out.printf("%d〇",2);
System.our.printf("%d〇",6);
```

- 解答欄

___
**問3(2)下記のソースコードで配列の要素を出力させるために１行目にパッケージをインポートせよ**
```java
1行目------------------
int[] arr=new int{1,2,3}
System.out.println(Arrays.toString(arr));
```
- 解答欄

___
**問4(2)下記のソースコードを実行した際の出力結果を記載せよ**
```java
import java.util.*;
int[] arr=new int[4]
System.out.println(Arrays.toString(arr));
```
- 解答欄

___
**問5(2)下記のソースコードを実行した際の出力結果を記載せよ**
```java
import java.util.*;
int[][] arr=new int[3][3]
for(int i=0;i<2;i++){
  for(int j=0;j<arr[i].length;j++){
    arr[i][j]=j+100;
   }
}
for(int i=0;i<arr.length;i++){
 for(int J=0;j<arr[i].length;j++{
    System.out.printf("%2d"arr[i][j]);
  }
  System.out.println();
}
```
- 解答欄


___
