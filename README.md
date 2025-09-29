# Brand-assets ページ編集用汎用素材

## 既存言語バッチ
<!-- 現行 .NET（.NET 6/8）版 WinForms -->
![type](https://img.shields.io/badge/app-Windows%20Forms-blue?style=flat-square&logo=windows)
![runtime](https://img.shields.io/badge/.NET-6.0%20(or%208.0)-512BD4?style=flat-square&logo=dotnet)
![tfm](https://img.shields.io/badge/TFM-net6.0--windows-0B7285?style=flat-square)

```
<!-- 現行 .NET（.NET 6/8）版 WinForms -->
![type](https://img.shields.io/badge/app-Windows%20Forms-blue?style=flat-square&logo=windows)
![runtime](https://img.shields.io/badge/.NET-6.0%20(or%208.0)-512BD4?style=flat-square&logo=dotnet)
![tfm](https://img.shields.io/badge/TFM-net6.0--windows-0B7285?style=flat-square)
```

<!-- .NET Framework 版 WinForms -->
![type](https://img.shields.io/badge/app-Windows%20Forms%20(.NET%20Framework)-236192?style=flat-square&logo=windows)
![runtime](https://img.shields.io/badge/Framework-4.8.1-5C2D91?style=flat-square&logo=dotnet)
![tfm](https://img.shields.io/badge/TFM-net48-0B7285?style=flat-square)

```
<!-- .NET Framework 版 WinForms -->
![type](https://img.shields.io/badge/app-Windows%20Forms%20(.NET%20Framework)-236192?style=flat-square&logo=windows)
![runtime](https://img.shields.io/badge/Framework-4.8.1-5C2D91?style=flat-square&logo=dotnet)
![tfm](https://img.shields.io/badge/TFM-net48-0B7285?style=flat-square)
```

<!-- WPF (.NET 6/8 など) -->
![WPF](https://img.shields.io/badge/app-WPF-512BD4?style=flat-square&logo=dotnet)
![runtime](https://img.shields.io/badge/.NET-6.0%20(or%208.0)-512BD4?style=flat-square&logo=dotnet)
![tfm](https://img.shields.io/badge/TFM-net6.0--windows-0B7285?style=flat-square)

```
<!-- WPF (.NET 6/8 など) -->
![WPF](https://img.shields.io/badge/app-WPF-512BD4?style=flat-square&logo=dotnet)
![runtime](https://img.shields.io/badge/.NET-6.0%20(or%208.0)-512BD4?style=flat-square&logo=dotnet)
![tfm](https://img.shields.io/badge/TFM-net6.0--windows-0B7285?style=flat-square)
```

<!-- Python (3.10.4) -->
![Python](https://img.shields.io/badge/language-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![version](https://img.shields.io/badge/version-3.10.4-3776AB?style=flat-square&logo=python&logoColor=white)

```
<!-- Python (3.10.4) -->
![Python](https://img.shields.io/badge/language-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![version](https://img.shields.io/badge/version-3.10.4-3776AB?style=flat-square&logo=python&logoColor=white)
```

<!-- Excel VBA -->
![Excel](https://img.shields.io/badge/app-Excel%20VBA-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

```
<!-- Excel VBA -->
![Excel](https://img.shields.io/badge/app-Excel%20VBA-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
```

## カスタムバッジ作成手順
https://simpleicons.org/

作成する画像のURLは
```
https://img.shields.io/badge/{バッジ左の文字}-{バッジ右の文字}-{色}.svg?logo={ロゴ名}
```
です。?以降のGETリクエストパラメータは複数あり、[全量はこちら](https://shields.io/badges)  
よって今回は、左の文字なし、「Vim」、緑、vimのロゴにしたいので

```
https://img.shields.io/badge/-Vim-019733.svg?logo=vim
```

...とします。出来上がったものがこちら（Qiitaにimgタグ入れてます）
<img src="https://img.shields.io/badge/-cplusplus-019733.svg?logo=cplusplus&style=flat">

<br>
テーブル付の場合は下記のように記載
<br>

```
<table>
  <!-- ヘッダ -->
  <tr>
    <td>License</td>
    <td>Env</td>
  </tr>
  <!-- ボディ -->
  <tr>
    <td>
      <a href="./LICENSE">
        <img src="http://img.shields.io/badge/license-MIT-blue.svg?style=flat">
      </a>
    </td>
    <td>
      <img src="https://img.shields.io/badge/-Docker-EEE.svg?logo=docker&style=flat">
      <br>
      <img src="https://img.shields.io/badge/-k8s-EEE.svg?logo=kubernetes&style=flat">
    </td>
  </tr>
</table>
```
<table>
  <!-- ヘッダ -->
  <tr>
    <td>License</td>
    <td>Env</td>
  </tr>
  <!-- ボディ -->
  <tr>
    <td>
      <a href="./LICENSE">
        <img src="http://img.shields.io/badge/license-MIT-blue.svg?style=flat">
      </a>
    </td>
    <td>
      <img src="https://img.shields.io/badge/-Docker-EEE.svg?logo=docker&style=flat">
      <br>
      <img src="https://img.shields.io/badge/-k8s-EEE.svg?logo=kubernetes&style=flat">
    </td>
  </tr>
</table>

## ダウンロードボタン
自作した画像からカスタムダウンロードボタンを作成したので下記のhtml呼び出しから実行可能
### Github
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_1.png"
    alt="Download .zip"
    height="48"
  />
</a>

```
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_1.png"
    alt="Download .zip"
    height="48"
  />
</a>
```

### Getuploader
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_2.png"
    alt="Download .zip"
    height="48"
  />
</a>

```
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_2.png"
    alt="Download .zip"
    height="48"
  />
</a>
```

### DropBox
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_4.png"
    alt="Download .zip"
    height="48"
  />
</a>

```
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_4.png"
    alt="Download .zip"
    height="48"
  />
</a>
```

### その他
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_3.png"
    alt="Download .zip"
    height="48"
  />
</a>

```
<a href="<ダウロード遷移先URL>">
  <img
    src="https://raw.githubusercontent.com/Sadc2h4/brand-assets/main/button/Download_Button_3.png"
    alt="Download .zip"
    height="48"
  />
</a>
```

## 折り畳みエリア
HTMLの詳細折りたたみ要素を使えます。  
追加情報としたい内容を、detailsタグで囲みます。そして、要約として表示したい文章をsummaryタグで記載します。  
open属性をつけると折りたたみを広げた状態にできます。  

<!-- open属性なし -->
<details><summary>サンプルコード（open属性なし）</summary>

(上に空行が必要)

```rb
puts 'Hello, World'
```
<br>
</details>


```
<!-- open属性なし -->
<details><summary>サンプルコード（open属性なし）</summary>

(上に空行が必要)

```rb
puts 'Hello, World'
```
</details>
<br>
```

<!-- open属性あり -->
<details open><summary>サンプルコード（open属性あり）</summary>

(上に空行が必要)

```rb
puts 'Hello, World'
```
</details>
<br>

```
<!-- open属性あり -->
<details open><summary>サンプルコード（open属性あり）</summary>

(上に空行が必要)

```rb
puts 'Hello, World'
```
</details>
<br>
```

## 強調表示
> [!TIP]
> Tips表示

> [!NOTE]
> NOTE表示

> [!IMPORTANT]
> IMPORTANT表示

> [!WARNING]
> WARNING表示

> [!CAUTION]
> CAUTION表示

```
> [!TIP]
> Tips表示

> [!NOTE]
> NOTE表示

> [!IMPORTANT]
> IMPORTANT表示

> [!WARNING]
> WARNING表示

> [!CAUTION]
> CAUTION表示
```

## 太線 スプリッター
『---』を記載することでスプリッターとして表示が可能

---
