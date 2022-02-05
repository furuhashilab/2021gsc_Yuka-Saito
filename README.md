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
 ITプロダクトやweb上の様々なサービスで欠かせないツールである地図だが、現在ではそれらのブランドイメージや使用事例にあったデザイン地図が多用されており単に道案内や空間情報を伝達する役割だけでなくその地図を使用するユーザーにブランドのイメージを適切に構築させる重要な要素となっている。 [Mapbox Studio](https://www.mapbox.jp/mapbox-studio) では地図のデザインを使用用途やサービスのイメージに合わせて、フォントやカラーなど様々なデザイン要素を細かくカスタマイズすることができる。今回のゼミ論ではそのMapbox Studioを使用し論文の読み手により伝わりやすいように、現在社会現象を巻き起こした「鬼滅の刃」を例とする。なかでも特徴的なキャラクターをピックアップし手法の開発をおこなう。尚、筆者は鬼滅の刃の大ファンでありアニメや単行本もさることながらファンブックや公式キャラクターズブックなども読破済みの為それらの情報をもとに、より忠実にそのキャラクター自体や鬼滅の世界観やブランドイメージをもタイトル通り崩すことなく再現したい。 
##  Methods
Mapbox Studioを使用したオリジナル地図デザインの作成 
 
例：　漫画・TVアニメ「鬼滅の刃」  
起用キャラクター：※1竈門禰豆子/ 竈門炭治郎 / 胡蝶しのぶ / ※2煉獄杏寿郎 / 宇髄天元  
※1 禰豆子の「禰」は「ネ＋爾」が正しい表記となります。※2 煉獄の「煉」は「火+東」が正しい表記となります。

地図制作では、web地図との親和性を考慮し特に原作コミックスのキャラクターデザインではなく"TVアニメ版"の鬼滅の刃のキャラクターデザインやカラーを参考にする。 
TVアニメで登場する主要キャラクターのモチーフや服装などの設定資料を収録した[公式キャラクターズブック](https://books.shueisha.co.jp/items/contents.html?isbn=978-4-8342-1721-6)や公式グッズを参考に制作を行う。下記、その制作過程と方法を「材料の準備（要素や素材あつめなどの下準備）」と「組立（素材を地図デザインに落とし込む方法と手順）」の大きく２つにわけて説明をする。  
   
       
          

##### 「材料の準備」-要素や素材あつめなどの下準備-   
① イメージカラー (メインカラー 1個 サブカラー2,3個 アクセントカラー 2,3個 )  
② モチーフ; そのキャラクターを代表するような柄やアイテムなど ( 2,3個 )  
③ その他の要素; 性格や雰囲気などを形容詞化したもの  
  
##### 「素材の集め方」  
 
【　①イメージカラー　】 キャラクターを連想させるようなカラー  
例えば、髪の毛や瞳の色、洋服の色（隊服や羽織りの色）、その他アクセサリー類（髪飾りやメイク）の色などが該当する。地図デザインにおいて、メイン、サブ、アクセントカラーを分けて用意しておくと便利であり次にそれらの定義を簡単に記す。本研究におけるメインカラーとは主役となりデザインの中心になる色のことで基本的には使用される面積も比較的多く、全体のベースを作るような色である。また、サブカラーとは一般的にメインカラーと同じような色を選択する場合が多いが、本デザインにおいてはメインカラーの次に使用面積が広くメインカラーが作り出すイメージを補うためのカラーとする。最後に、アクセントカラーについては最も使用面積は少ないもののその色味が足されることによってメインとサブが作り出すイメージを一段とキャラデザインに近づけるような文字通りアクセント的な役割をするカラーとする。  

例：胡蝶しのぶ ）  
メイン：薄紫のような白（羽織り)  
サブ：濃い紫（隊服、瞳と髪の色）、黒紫（羽織り）、紫よりの薄いピンク（羽織、リップ)  
アクセント：薄めのエメラルドブルー（羽織り、刀の柄）、オレンジ（鍔)  

カラーの抽出方法：①本やweb上で必要な部分を写真にとる ②[カラーピッカー](https://lab.syncer.jp/Tool/Image-Color-Picker/)）でカラーコードを抽出(複数候補の色が出た場合はmapboxに反映されたときに実際の色に一番近いものor他の使用色との相性を見て判断) 

![スクリーンショット 2022-01-30 14 40 08](https://user-images.githubusercontent.com/62432677/151691048-6ded7411-282d-4480-a22e-4db97feac135.png)

【　②モチーフ　】 そのキャラクターを代表するような柄やアイテム  
例えば、洋服（羽織り）の柄やマーク、キャラクターの持ち物やアクセサリー、キャラクターのシンボルマークなどが該当する。地図デザインにおいて、アニメや漫画上で自由に描かれているモチーフそれら全てを忠実に再現することはかなり難しい。そのため、地形や道の曲線など予め地図を構成するそれらの要素のみで表現が可能そうなモチーフを積極的に挙げておくと後の地図デザインに落とし込む際に作業がしやすい。また、そのモチーフが主にどんな要素（色や大きさ、形など）で構成されているかを考えておくと多少、地図上で再現が難しそうなものでも近づけることは可能である。さらに、前述の方法でも地図上にモチーフを落とし込めない場合は後述するやり方で自身で作成したモチーフを地図のパターン（柄）として挿入することもできるため別途地図パターンように自分でモチーフを用意しておくと便利である。  

例：胡蝶しのぶ ）  
羽織の蝶々の模様（ドレスのひだのような、枝分かれしているような繊細な線）  
蝶々（蝶そのもの,あまりリアルでなくても良い）  
鍔 （蝶々の形がさらに簡略化されたような形、特徴的な薄いエメラルドブルーとオレンジ色のコントラスト）  

![スクリーンショット 2022-01-30 15 00 38](https://user-images.githubusercontent.com/62432677/151691656-63faa6de-94ca-4942-b53f-687d58b7275e.png)

【　③その他の要素　】性格や雰囲気などを形容詞化したもの  
例えば、”華奢で可憐さを感じる繊細なイメージ”, "大胆で、ハデな感じ", "やわらかく調和を感じるふんわりとした感じ"など。ブランドないしはキャラクターが形作る印象や雰囲気、コンセプトを言語化する。ここで挙げられた形容詞が地図デザインをするにあたっての指標のようなものになる。道幅やフォント選び、全体の情報量などあらゆるデザイン要素の決定に役立つ。目に見えるデザインには直接的には関わらないものの必ず行いたい重要な材料である。  

例：胡蝶しのぶ ）  
「華奢で繊細かつ、華やかな感じ」（→ 華奢感を出すために道幅はほそめ。派手すぎず華やかさを出すために、カラーはグラデーション感を意識しながら少し多めに使用。） 

  
  
##### 「組立」 - 材料を地図デザインに落とし込む方法と手順 -   
ここでは、「材料の準備」でカラー・モチーフ・その他要素の主に３種類の素材を３つのステップで調理していく。説明の便宜上３段階の順序を設定しているが、実際の作業では３ステップを何回も繰り返しながら細かな調整を行なっている。また、それぞれの素材をデザインに落とし込む方法もいくつかtipsとして挙げるがそれらの方法が当てはまらない場合もある。その場合、自分の直感や感覚を信用しつつ思い立ったアイディアをまずは手を動かして形作ろうとトライすることも大切であると考える。  


【　STEP1: カラー挿入 】  
唯一このステップだけは、どのキャラクターのデザインであっても共通して最初に行うべきだと思ったものである。まず材料準備で用意したメインカラーをbaseカラーとして設定し、サブカラーである２色をWater,roadに設定。さらにアクセントカラーをあまったカテゴリ(schoolやHospitalがおすすめ)に仮で割り振っていく。このようにキャラクターデザイン上で多く使用されていた色を使用面積の広い順に地図デザインに落とし込んでいき、メインカラーとサブカラーの地図上での彩色の相性をみて色の光度や彩度を調整する。この段階では地図デザインのメインエリアとなる場所決めを行う必要はないため作業時のエリアは問わない。しかし使用カラーの発色やそれぞれの色との相性を見るために、画面上にbaseやroad以外の森林や川、学校や病院など多くのカテゴリが密集する都市でこの作業を行うことをお勧めしたい。

![スクリーンショット 2022-01-30 16 27 17](https://user-images.githubusercontent.com/62432677/151694186-c5b74d1b-e495-432f-85e2-fc6524f552b6.png)


【　STEP2: 最適エリアの選定とモチーフデザイン 】  
ここでは、本デザインにおいて最も全体の出来を左右させる作業であるモチーフを地形に落とし込む作業を行う。STEP１を終えたら材料下準備で用意したモチーフを、roadの線を用いた表現またはパターン挿入（柄をつける機能）なのかはたまた別の表現方法でデザインするのかを考えながら実際に様々なエリアを１つ１つ大雑把にチェックしていく。  
例えば、「胡蝶しのぶ」の場合は蝶々の繊細で複雑な模様とグラデーションを基調とした華やかな色使いが特徴であるため、規則的に道路が整備されている場所や一画面に様々なカテゴリが密集していないような地方は相性が悪いということが想像できる。逆に言えば、様々な道幅の道が入り組んでいて且つ川や森林エリアや病院・学校・その他ビルのような建物が密集する都会の方がデザインしやすいことがわかる。さらに、特徴的な蝶模様は不規則な線で表現されたデザインであるためroadで表現ができそうだ。このようにある程度見当をつけつつ拡大と縮小を繰り返しながらエリア選定を行い、相性の良さそうなエリアがあった場合には地形似合った色選びや調整を行うことでモチーフを形作っていく。  
tipsとして、地図上では基本的に幾何学模様のような直線を基本とした規則正しい模様やモチーフは表現が難しいためその場合は先述のパターン挿入が有効である。Mapbox Studioでは、100種類ほど既存パターンが用意されているためそれらを自身が表現したいモチーフに見立てて挿入すると簡単に雰囲気を演出することが可能である。   

例：）  
竈門禰豆子→パリ,フランス  
胡蝶しのぶ→エユップ,イスタンブル,トルコ  

![スクリーンショット 2022-01-31 11 22 13](https://user-images.githubusercontent.com/62432677/151738652-029e70bc-5615-4111-9bf7-ba2c0fb5049d.png)

例：胡蝶しのぶ ）  
羽織の蝶々の模様（ドレスのひだのような、枝分かれしているような繊細な線) → 地図全体（base×road）を羽織りに見立てる, 羽織の裾部分は川(＋川の上の２つの陸地)で表現  
蝶々（蝶そのもの,あまりリアルでなくても良い）→ 紫色のお花パターンを全体に挿入し蝶々に見立てる  
鍔 （蝶々の形がさらに簡略化されたような形、特徴的な薄いエメラルドブルーとオレンジ色のコントラスト）→ roadの一部にオレンジ色の楕円形を挿入,フォントカラーをエメラルドブルーに  
![スクリーンショット 2022-01-31 11 25 55](https://user-images.githubusercontent.com/62432677/151738876-745a0e56-a98d-4566-bfe5-4ebbab46275c.png)
  


【　STEP3: 細かな調整(フォント、色調整) 】  
このSTEPはもちろん最終調整の段階で行う作業でもあるが、それよりも他の２個のSTEPと並行して行うようなものであると認識してほしい。主に行う作業としては、材料③のその他の要素であげたそのキャラクターの代名詞になるような雰囲気やイメージ等をベースとしたコンセプトと今まで作成した地図のデザインがマッチしているかを確認し色の彩度や光度、トーンやフォント選定など細かな調整を行う。例えばフォント選びに関して、胡蝶しのぶであれば「華奢で繊細かつ、華やかな感じ」とコンセプトを置いており全体のデザインも複雑で曲線を有効活用した線ベースの表現が目立つためフォントもそれに合わせて細く、丸みと華奢さが特徴的なフォントを選定している。  


##  Result
[竈門禰豆子デザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2nghbv3mq917lewdd4eyut.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![スクリーンショット 2021-01-25 16 56 38](https://user-images.githubusercontent.com/62432677/151735322-6d8867ba-943b-4445-b491-d17a7e8bb923.png)

[竈門炭治郎デザイン](https://api.mapbox.com/styles/v1/yukasaito/ckw0wlstu980c14pl5nwn4uyo.html?title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ&zoomwheel=true&fresh=true#15.32/35.454896/139.631341/44.8)
![スクリーンショット 2022-01-30 0 51 03](https://user-images.githubusercontent.com/62432677/151735364-e3a624bd-e0be-4cf5-8916-8311ba0552d8.png)
      
[胡蝶しのぶデザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2i5son0cv017p3t034mk0m.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![スクリーンショット 2022-01-30 0 30 58](https://user-images.githubusercontent.com/62432677/151735440-69827c1a-b76e-4b06-a9d1-ddbb51810585.png)

[煉獄杏寿郎デザイン](https://api.mapbox.com/styles/v1/yukasaito/ckk2p8f233odv17nzpgpn4hzz.html?fresh=true&title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ)  
![Kyojyuro Rengoku](https://user-images.githubusercontent.com/62432677/105671286-ccd6f400-5f25-11eb-8741-0fa3df7ee12c.png)  

[宇髄天元デザイン](https://api.mapbox.com/styles/v1/yukasaito/ckyy075a8007a15ldalvo56q9.html?title=view&access_token=pk.eyJ1IjoieXVrYXNhaXRvIiwiYSI6ImNrZDYxdjRzcTFrN2wycW8zNnBvZndwcGEifQ.rblEBet0xcsjyEvxDI1SzQ&zoomwheel=true&fresh=true#9.93/55.7684/37.5012/20/52)
![スクリーンショット 2022-01-30 0 15 22](https://user-images.githubusercontent.com/62432677/151735564-8b9768f5-f6a8-4df1-a92f-4fe1d88bb1db.png)


##  Discussion 
本研究のゴールとしてウェブ地図スタイリング手法の開発があるが、いまだにデザインの方法が製作者の感覚に頼るようなものであったり地図の特性とキャラクターの相性によって完成度にばらつきが出てしまったりなど手法としてやや曖昧で不確定な要素が多い。例えば、竈門禰豆子デザインのパリの放射線状の街並みをキャラクターの特徴的な麻の葉模様にみたてられたことで全体の完成度やイメージの確立の成功がなされた事もそれに該当するだろう。竈門禰豆子のキャラクターデザインの中でもそれだけ麻の葉模様はイメージの大部分を構成するものであり、これがroadでみたてられていなければ薄い桃色と茶色といった色だけでのなんとなくの表現にしかならない恐れもある。これは2020年度のゼミ論文時にも出てきた課題ではあるが、その頃は[カラーの選択と配色][モチーフや特徴的要素の地図上での再現][イメージを崩さないフォント選び]の３つが地図デザインにおける重要なポイントでありそれぞれのポイントもtips等はないような体系立てられるところもまだ詰めきれていないような結論だった。  
そのため本研究で導き出した３種の材料を３ステップで組み立てるという具体性とシステマチックさが改善されたところを鑑みると「デザイン」というそもそもが作成者の感性とスキル頼りの作業を、少しでも体系的手法に落とし込むことで完成度を担保できるものになっていると考える。  
例として今回ゼロから新規作成した宇髄天元デザインを見たい。まず宇髄天元のキャラクターデザインは今まで上手くデザインできたキャラに共通して見られる線ベースの柄といったモチーフがない。そこを他の細かなモチーフや色使いで補填していく必要があった。最終的に材料選びで選定した"黄・赤・薄緑の特徴的な色使いの鍔"と"目周りの太陽のようなメイク"となんといっても”派手”さと”ゴツさ”の４つを、モスクワという都会と田舎のコントラストがきいた街並みにうまく落とし込むことができた。都市部にみられる歪な円状に広がる道の密集具合はどことなく鍔の形のようにも見え、且つその円に沿って散りばめた赤色が目周りのメイクを表現。また、キャラクターデザイン上で大部分を占める隊服の紺色が田舎のだだっ広いエリアのおかげで地図上でも印象付けることができた。  
  
ポスターデザインやロゴデザインと同じように、何度も繰り返しウェブ地図デザインをやっていく事で材料選びの段階から、このモチーフを地図上のあの要素に見立てて表現することができるかもしないとったような想像がしやすくなり効率性や完成度も高まっていくと今回の実践を通して感じた。そのため、手法はあくまでも「手法×感性・感覚×スキル=デザインの完成度」という式の一要素でありどの要素も満遍なく確保することが重要であると考える。


##  Conclusion 
ブランドイメージを崩さないウェブ地図スタイリング手法の開発と実践というテーマのもと鬼滅の刃を例とし、実際に５キャラクターの地図制作を行いながらその手法の開発を試みた。結果としてスタリング手法は、「材料準備」と「組立」の２段階にわけることができ、「材料準備」で用意した３種類の材料であるカラー・モチーフ・その他要素を「組立」３STEPのカラー挿入・地形選びとモチーフデザイン・細かな調整の手順に沿って行うという体系的な方法を組み立てることができた。感覚やスキル頼りである部分も十分に理解して楽しみながら、この手法を用いて今までよりもウェブ地図デザインのスタイリングが身近になり且つある程度の完成度をもって製作物ができるようになれば幸いだ。

##  参考文献

[参考文献リスト](https://docs.google.com/spreadsheets/d/1AQOKlf3PrHLxROyGEIvP08MMFDqMS1xr7-e97pEbLLE/edit?usp=sharing)

##  先行事例
吉田桃子(2016)　[現代の江戸切絵図](https://g-expo.jp/2016/geocon/pdf/geocon_presenter05.pdf) 慶応義塾大学石川初研究会　

##  謝辞
本研究を進めるにあたり地球社会共生学部の古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。  

##  2020年度発表用プレゼンテーション
 [発表スライド](https://docs.google.com/presentation/d/1rZg_0igUzBBMqVaE7acKVi1N6eq_Ws1DZAswYk2U7nI/edit#slide=id.gbb410e4814_2_1)  
## 2021年度 中間報告プレゼンテーション
 [発表スライド](https://docs.google.com/presentation/d/1HPFAN4-ck84yJVDlLfvUs7P0WPy5Q6LDRvPoqtNMtfM/edit?usp=sharing)  
## 2021年度 最終発表用プレゼンテーション
 [発表スライド](https://docs.google.com/presentation/d/14gikp98qlIxJhhtSTgTmEMaBLPv5lCoS3T5QTZ4n09I/edit?usp=sharing) 
