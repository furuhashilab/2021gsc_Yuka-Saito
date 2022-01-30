# 2021gsc_Yuka-Saito
'21 ゼミ論用レポジトリ
 
 学籍番号：1A118074      
 氏名：斎藤 祐花   
 地球社会共生学部 地球社会共生学科 3年A組80番   
 指導教員：古橋 大地 教授  
 © Furuhashi Laboratory/Yuka Saito, CC BY 4.0  
***

# 【2021年度ゼミ論】 ブランドイメージを崩さないウェブ地図スタイリング手法の開発と実践  〜鬼滅の刃を例として〜
##  概要
##### 本研究ではブランドイメージを崩さないウェブ地図スタイリングの手法の開発を、漫画・アニメ「鬼滅の刃」のキャラクターを例にしたmapbox Studioでのデザイン地図制作実践をもとに行う。
##  Introduction
 ITプロダクトやweb上の様々なサービスで欠かせないツールである地図だが、現在ではそれらのブランドイメージや使用事例にあったデザイン地図が多用されており単に道案内や空間情報を伝達する役割だけでなくその地図を使用するユーザーにブランドのイメージを適切に構築させる重要な要素となっている。 [Mapbox Studio](https://www.mapbox.jp/mapbox-studio) では地図のデザインを使用用途やサービスのイメージに合わせて、フォントやカラーなど様々なデザイン要素を細かくカスタマイズすることができる。今回のゼミ論ではそのMapbox Studioを使用し論文の読み手により伝わりやすいように、現在社会現象を巻き起こし老若男女問わず愛される「鬼滅の刃」を例とする。なかでも特徴的な印象をもつキャラクターをピックアップし手法の開発をおこなう。尚、筆者は鬼滅の刃の大ファンでありアニメや単行本もさることながらファンブックや公式キャラクターズブックなども読破済みの為それらの情報をもとに、より忠実にそのキャラクター自体や鬼滅の世界観やブランドイメージをもタイトル通り崩すことなく再現したい。 
##  Methods
Mapbox　Studioを使用したオリジナル地図デザインの作成 
 
例：　漫画・TVアニメ「鬼滅の刃」  
起用キャラクター：※1竈門禰豆子/ 竈門炭治郎 / 胡蝶しのぶ / ※2煉獄杏寿郎 / 宇髄天元  
※1 禰豆子の「禰」は「ネ＋爾」が正しい表記となります。※2 煉獄の「煉」は「火+東」が正しい表記となります。

地図制作では、web地図との親和性を考慮し特に原作コミックスではなく"TVアニメ版"の鬼滅の刃のキャラクターデザインやカラーを参考にする。 
TVアニメで登場する主要キャラクターのモチーフや服装などの設定資料を収録した[公式キャラクターズブック](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1721-6)や公式グッズをもとに制作を行う。下記、その制作過程と方法を「材料（要素や素材あつめなどの下準備）」と「組立（素材を地図デザインに落とし込む方法と手順）」の大きく２つにわけて説明をする。  
   
       
          

「必要な素材」-要素や素材あつめなどの下準備-   
① イメージカラー (メインカラー 1個 サブカラー2,3個 アクセントカラー 2,3個 )  
② モチーフ; そのキャラクターを代表するような柄やアイテムなど ( 2,3個 )  
③ その他要素; 性格や雰囲気などを形容詞化したもの  
  
「素材の集め方」  
 
【　①イメージカラー　】 キャラクターを連想させるようなカラーのこと   
例えば、髪の毛や瞳の色、洋服の色（隊服や羽織りの色）、その他アクセサリー類（髪飾りやメイク）の色などが該当する。地図デザインにおいて、メイン、サブ、アクセントカラーを分けて用意しておくと便利であり次にそれらの定義を簡単に記す。本研究におけるメインカラーとは主役となりデザインの中心になる色のことで基本的には使用される面積も比較的多く、全体のベースを作るような色である。また、サブカラーとは一般的にメインカラーと同じような色を選択する場合が多いが、本デザインにおいてはメインカラーの次に使用面積が広くメインカラーが作り出すイメージを補うためのカラーとする。最後に、アクセントカラーについては最も使用面積は少ないもののその色味が足されることによってメインとサブが作り出すイメージを一段とキャラデザインに近づけるような文字通りアクセント的な役割をするカラーとする。  

例：胡蝶しのぶ ）  
メイン：薄紫のような白（羽織り)  
サブ：濃い紫（隊服、瞳と髪の色）、黒紫（羽織り）、紫よりの薄いピンク（羽織、リップ)  
アクセント：薄めのエメラルドブルー（羽織り、刀の柄）、オレンジ（鍔)  

カラーの抽出方法：①本やweb上で必要な部分を写真にとる ②[カラーピッカー](https://lab.syncer.jp/Tool/Image-Color-Picker/)）でカラーコードを抽出(複数候補の色が出た場合はmapboxに反映されたときに実際の色に一番近いものor他の使用色との相性を見て判断) 

![スクリーンショット 2022-01-30 14 40 08](https://user-images.githubusercontent.com/62432677/151691048-6ded7411-282d-4480-a22e-4db97feac135.png)

【　②モチーフ　】 
先にまとめたキャラクターのイメージを構成する要素を地図上にどうにか落とし込む。例えば、鬼滅の刃の主人公の妹である竹をくわえた少女の鬼”禰豆子”であれば着用している着物の麻の葉模様や竹筒、額の左上の薄桃色の髪飾りなどである。 それらのモチーフの形や配色を、地図上の道の張り巡らせ方や地形に着目しすり合わせていく。 

【　③フォント　】
キャラクターのイメージや性格、雰囲気などに合わせてフォントを選択する。また、カラーとフォントの相性も見ながら調整する。

【　テクスチャー/パターン　】 
  
##  Result
[竈門禰豆子デザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2nghbv3mq917lewdd4eyut.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Nezuko Kamado](https://user-images.githubusercontent.com/62432677/105676810-61ddeb00-5f2e-11eb-80b7-4fb928c2cb93.png)  

   
   
[煉獄杏寿郎イメージデザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2p8f233odv17nzpgpn4hzz.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Kyojyuro Rengoku](https://user-images.githubusercontent.com/62432677/105671286-ccd6f400-5f25-11eb-8741-0fa3df7ee12c.png)  
   
[胡蝶しのぶイメージデザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2i5son0cv017p3t034mk0m.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Shinobu Kocho](https://user-images.githubusercontent.com/62432677/105671367-eed07680-5f25-11eb-921d-b5c7b461705b.png)  

  

##  Discussion 


##  Conclusion 

##  参考文献

> 松澤(2020), TVアニメ『鬼滅の刃』 [公式キャラクターズブック 壱ノ巻](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1721-6), 集英社, 原作 吾峠呼世晴, ©︎吾峠呼世晴/集英社・アニプレックス・ufotable  
> 木下(2021), TVアニメ『鬼滅の刃』 [公式キャラクターズブック 参ノ巻](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1723-0), 集英社, 原作 吾峠呼世晴, ©︎吾峠呼世晴/集英社・アニプレックス・ufotable  

##  先行事例
吉田桃子(2016)　[現代の江戸切絵図](https://g-expo.jp/2016/geocon/pdf/geocon_presenter05.pdf) 慶応義塾大学石川初研究会　

##  謝辞

##  2022年卒業論文提出用
##  2020年度発表用プレゼンテーション
 [発表スライド](https://docs.google.com/presentation/d/1rZg_0igUzBBMqVaE7acKVi1N6eq_Ws1DZAswYk2U7nI/edit#slide=id.gbb410e4814_2_1)
## 2021年度 中間報告プレゼンテーション
 [発表スライド](https://docs.google.com/presentation/d/1HPFAN4-ck84yJVDlLfvUs7P0WPy5Q6LDRvPoqtNMtfM/edit?usp=sharing)
