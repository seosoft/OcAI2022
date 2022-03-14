# 環境構築

画像分類アプリ作成の体験の最初に環境を構築します。

> 体験授業ではすでに環境構築が完了しているかもしれません。  
> 講師やスタッフの指示に従ってください。

この体験授業では、[**Lobe**](https://www.lobe.ai/) という無償のツールを使用して画像分類モデルを作成します。  
LobeはWindows専用のアプリケーションなので、他のOSでは使用できません。

環境構築は以下の手順で進めます。

1. Lobeのダウンロード、インストール
1. Node.js, yarn のダウンロード、インストール

---

## 1. Lobeのダウンロード、インストール

[**Lobe**](https://www.lobe.ai/) は簡単に画像分類モデルを作成できるツールです。  
Windows専用のアプリケーションで無償で利用できます。

1. [Lobe](https://www.lobe.ai/) のホームページをWebブラウザーで開き、[Download] ボタンでインストーラーをダウンロードします。  
   [Download] ボタンは2個あり、どちらを使ってもかまいません。 

   <img src="./images/01/lobe_home.jpg" width="480px" />

2. インストーラーがダウンロードできたらインストールします。  
   インストール先は変更しないで進めます。  

   <img src="./images/01/lobe_installer.jpg" width="400px" />

3. インストーラーの最後で [Run Lobe] をチェックしたままで [Finish] します。  

   > [Run Lobe] のチェックを外して [Finish] した場合はWindowsのスタートボタンからLobeを起動してみます。

   <img src="./images/01/installer_runlobe.jpg" width="400px" />

4. Lobeの初回起動時にファイアウォールの設定ダイアログが開きます。  
   [アクセスを許可する] でファイアウォールの設定を行います。

   <img src="./images/01/lobe_firewall.jpg" width="480px" />

5. Lobeの初回起動時はさらにLobe自体の確認画面が3枚表示されます。  
   すべてデフォルトのボタンをクリックして先に進めます。

   <img src="./images/01/lobe_firstrun1.jpg" width="300px" />
   <img src="./images/01/lobe_firstrun2.jpg" width="300px" />
   <img src="./images/01/lobe_firstrun3.jpg" width="300px" />

6. Lobeが起動すればインストール成功です。
   
   <img src="./images/01/lobe_launch.jpg" width="480px" />