# <Gather Bands>

## サイト概要
ライブを行いたいバンドがライブイベントを企画・募集できるアプリケーション。

### サイトテーマ
アマチュアでバズる！

### テーマを選んだ理由
学生の頃にバンドをしていたことがあり、ライブを開催する際共催してくれるバンドを見つけることに苦労をしたことがある。
また、ライブハウスとしても箱を貸すためにバンドを集める必要があり、横の繋がりが必要となる。
同じようなジャンルで共にライブを共催したいバンドはたくさんいると思われるため、
互いのバンドがマッチングしライブを行いやすい環境を提供できたらと思いこのテーマを選んだ。

### ターゲットユーザ
・ライブを開催したいバンドマン

### 主な利用シーン
・バンドの開催の募集
・募集しているライブへの参加
・他SNS機能でバンドメンバーの募集、つぶやき等も可能

## 設計書

会員制
-会員登録　（名前、お所、ニックネーム、バンド名、パスワード、アドレス、連絡先、演奏動画の投稿）

ライブ募集
-チケット代　¥2000（ドリンク込み）、オンライン観覧チケット¥500（当日youtube等で閲覧可能 IDを発行）
-ジャンル、出演日を選択
-ライブ時間は固定の２時間(転換含め2時間30分)　各バンドの持ち時間　A. 20分＊6、B.30分＊4、C.40分＊3から選択
-１ヶ月前に応募締め切り、出演者人数が集まった際、またはライブ3ヶ月前で開催、非開催を選択。
　チケット代が集まった場合は出演者にキックバック
　
アドミン
-会員リスト
-バンドリスト確認
-ライブスケジュール確認
-直近のライブ内容を確認（直近のライブ）
-入金確認


### 機能一覧
https://docs.google.com/spreadsheets/d/1E6yjGa7ux_Ymr5YRCvkr3iLtn-Guq9zbe-Ob_gOLZH4/edit?usp=sharing

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- 仮想環境：Vagrant,VirtualBox

## 使用素材
- 外部サービスの画像素材・音声素材を使用した場合は、必ずサービス名とURLを明記してください。
- 使用しない場合は、使用素材の項目をREADMEから削除してください。
