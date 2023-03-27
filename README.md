# 勤怠ちゃん 〜Kintai-chan〜
Support Page of Kintai-chan App. 勤怠ちゃんアプリのサポートページ

Japanese description is under English.  
日本語の記述は英語の次にあります。  
Last update: March 27, 2023

　　　 <img src="https://user-images.githubusercontent.com/8732417/127726905-7c6fa973-8f36-4694-96f1-498110dfc35a.png" width="150">
<BR>
<BR>
<a href="https://apps.apple.com/jp/app/%E5%8B%A4%E6%80%A0%E3%81%A1%E3%82%83%E3%82%93/id1577214020?itsct=apps_box_badge&amp;itscg=30200" style="display: inline-block; overflow: hidden; border-top-left-radius: 13px; border-top-right-radius: 13px; border-bottom-right-radius: 13px; border-bottom-left-radius: 13px; width: 150px; height: 83px;"><img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=250x83&amp;releaseDate=1627603200&h=72b0c8495c2c0af1291efef280c4c2c1" alt="Download on the App Store" style="border-top-left-radius: 13px; border-top-right-radius: 13px; border-bottom-right-radius: 13px; border-bottom-left-radius: 13px; width: 150px; height: 60px;"></a>
<a href="https://apps.apple.com/jp/app/%E5%8B%A4%E6%80%A0%E3%81%A1%E3%82%83%E3%82%93/id1577214020?itsct=apps_box_badge&amp;itscg=30200" style="display: inline-block; overflow: hidden; border-top-left-radius: 13px; border-top-right-radius: 13px; border-bottom-right-radius: 13px; border-bottom-left-radius: 13px; width: 150px; height: 83px;"><img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/ja-jp?size=250x83&amp;releaseDate=1627603200&h=67f860c8a4424c97a47065fb78d09e10" alt="Download on the App Store" style="border-top-left-radius: 13px; border-top-right-radius: 13px; border-bottom-right-radius: 13px; border-bottom-left-radius: 13px; width: 150px; height: 60px;"></a>

## App update history

|App Version|Date|MEMO|
|:--:|:--:|:--|
|1.0.0|Jul 31, 2021|v1.0.0 has been released.|
|1.0.1|Oct 31, 2021|・watchOS 8 Support<BR>・Fixed the app crashing when registering / editing.|
|1.0.2|Apr 08, 2022|Minor revision|
|1.0.3|Oct 22, 2022|・watchOS 9 Support<BR>・Multi-Post available<BR>・Fixed list not showing on watchOS 7 devices.|
|1.0.4|Mar 27, 2023|Bug fixes and stability improvement|

## Commentary article

This app is a sample app made for Qiita Advent Calendar 2019.  
The commentary is as follows. Written in Japanese.  
I remaked for watchOS 7 and later. Of course I use SwiftUI.  

[https://qiita.com/MilanistaDev/items/dbc4d2c2cc4522f12972](https://qiita.com/MilanistaDev/items/dbc4d2c2cc4522f12972)

## Support Languages

* English - 英語
* Japanese - 日本語

## Support OS

* watchOS 7.0 and later - watchOS 7 以降

> You need an iOS 13 or higher iPad or iPhone paired with your Apple Watch to input the information needed to post Slack.

## Support Devices

* Apple Watch Series 3
* Apple Watch Series 4
* Apple Watch Series 5
* Apple Watch SE
* Apple Watch Series 6
* Apple Watch Series 7
* Apple Watch Series 8
* Apple Watch Ultra

---

## Overview of this app

Make attendance contact smart with Apple Watch.  
Opening the app on your PC or smartphone and  
contacting attendance is surprisingly troublesome.  

With this app, you can make smart attendance notifications  
with just a few taps on the screen of your Apple Watch.  
Register the Slack post settings and each attendance word in advance,  
and tap the corresponding cell from the list to complete the post.  

It may be possible to use it as a to-do list for housework and share it with your family.  

From `v1.0.3`, it is possible to post to multiple Slack channels.

This app is a Watch app written in Swift and SwiftUI.   

![KintaichanAppMovie_EN](https://user-images.githubusercontent.com/8732417/126958053-c9b265ae-1391-4b6f-b8b0-9991c72235e1.gif)

## How to use

1. Install this App
2. Enter the required information in Slack Settings
3. Register the activity you want to post
4. Select from the list and tap the cell to post to Slack

## Register / Edit / Delete activities

Preset data with a set of Emoji and words is provided at the time of installation. Register, edit, or delete as necessary.

You can register by tapping the "New entry" cell at the bottom of the activity list.

To edit the activity, tap the 3-point button on the upper right of the cell and edit as appropriate.

You can delete an activity by swiping the cell to the left.

|List|Edit|New entry|Add|delete|
|:--:|:--:|:--:|:--:|:--:|
|![01_EN](https://user-images.githubusercontent.com/8732417/126951057-ee595713-e738-441c-9feb-1036703e9a67.png)|![03_EN](https://user-images.githubusercontent.com/8732417/126951076-966996c7-4afd-4857-abaa-58a8be4297dc.png)|![04_EN](https://user-images.githubusercontent.com/8732417/126951080-9d828340-c783-41ef-8fe1-697e1e6be74b.png)|![05_EN](https://user-images.githubusercontent.com/8732417/126951088-a58d7be9-d8b2-4d03-b53e-f84509bb99cf.png)|![delete_EN](https://user-images.githubusercontent.com/8732417/126951385-5c77bc94-3848-4e3c-8848-6ad6c1372d4c.png)|

## Slack Settings

The information required for a Slack post is a Webhook URL and a GitHub account. Get the Webhook URL for the attendance channel you want to post and enter it. The GitHub account is used to get the poster's nickname and image. If you enter a nickname, that will be given priority.

Your favorite color is reflected in the color of the Attachment bar. If there is no input, the theme color of this app (#009944) will be used.
Enter each value on the paired iPhone. Copy and paste is also possible.

<img src="https://user-images.githubusercontent.com/8732417/126945890-fa3a3032-158e-4c29-aab5-80740a043055.png" width="300">

### Multi-Post

From `v1.0.3`, it is possible to post to multiple Slack channels.  
On the "Slack settings" screen, turn on the "Enable multi-post" switch,  
Enter the link of the channel you want to post in the "Webhook URL 2" field.  

|Turn on the switch|Enter Webhook URL 2 field|
|:--:|:--:|
|![Simulator Screen Shot - Apple Watch Series 8 (45mm) - 2022-10-22 at 04 31 25](https://user-images.githubusercontent.com/8732417/197275161-e8947695-c44a-420b-8da4-fd8c916102c4.png)|![Simulator Screen Shot - Apple Watch Series 8 (45mm) - 2022-10-22 at 04 31 30](https://user-images.githubusercontent.com/8732417/197275165-f9759f61-7ebe-41c9-8a57-0689bc800479.png)|

Multi-post will be disabled if not entered.  
Please turn off the switch if you do not multi-post.  
Entered link are not deleted.(No need to re-enter)  

### Supplement

On "Slack Settings" screen, enter the information required when posting Slack and use it as a parameter when sending.

Similarly, text input is performed on the iOS 13 iOS device that is paired.
Enter Slack's Webhook URL and GitHub account name,
User name and favorite color code.  
This information will be used when posting to Slack.  
When the "?" Button is tapped, an explanation screen is displayed for each item in a modal manner.

Slack Webhook URL can be obtained from the following link.  
Set the icon and user name for Slack posting in this site.

[https://slack.com/services/new/incoming-webhook](https://slack.com/services/new/incoming-webhook)

## Post Settings

The activity is a set of Emoji and words. If you turn on the switch, you can post Emoji as a set when posting. You can also post only words, too.

<img src="https://user-images.githubusercontent.com/8732417/126944952-75326ff2-4cce-4b5a-b388-7cc2984545c4.png" width="300">

## Set Complication

Please consider setting Complication. And then you can launch this App immediately, and posting is completed with 2 taps!

<img src="https://user-images.githubusercontent.com/8732417/126945054-bdc5ddad-02af-4f34-9a1d-eae438f7a61a.png" width="300">


## Contact

Please feel free to contact us if you find a bug or have any feedback.  
Suggestions for adding functions and code corrections are also welcome.

```swift
let name = "Takuya Aso"
let email = "milanista224" + "@" + "me.com"
let profession = "iOS Engineer"
let location = "Tokyo"
let fan = "AC Milan"
```
---

## アプリ概要

Slackの勤怠連絡を手首で完結。

PCやスマホでアプリを開いて勤怠連絡をするのは意外と手間で億劫です。  
このアプリでは，Apple Watchの画面を数回タップするだけでスマートに勤怠連絡ができます。事前にSlack投稿の設定と各勤怠のワードを登録しておいて，リストから該当のセルをタップするだけ投稿完了です。

家事などのやることリストとして使って家族にシェアするみたいな使い方も可能かもしれません。  
`v1.0.3` より Slack の複数チャネルへの投稿が利用可能になりました。

![KintaichanAppMovie](https://user-images.githubusercontent.com/8732417/126958044-b1de1545-d1b4-4516-a3c4-e83ac38f6ce2.gif)

## 使い方

1. アプリをインストール
2. Slack設定で必要項目を入力
3. 投稿したいアクティビティを登録
4. リストから選びセルをタップしてSlackへ投稿

## アクティビティの登録・編集・削除

インストール時に絵文字とワードがセットのサンプルデータが用意されています。必要に応じて新規登録，編集，削除をしてください。アクティビティリストの一番下の『新規登録』セルをタップすると新規登録ができます。アクティビティを編集する場合は，セルの右上の3点ボタンをタップして適宜編集します。アクティビティの削除はセルを左にスワイプすることで可能です。

|編集ボタン|編集画面|新規登録セル|追加画面|アクティビティ削除|
|:--:|:--:|:--:|:--:|:--:|
|![01](https://user-images.githubusercontent.com/8732417/126951720-850ea6f5-e619-41e4-a96d-9f20643ce7d6.png)|![03](https://user-images.githubusercontent.com/8732417/126951730-186b9027-7772-4944-a5a0-14c47b746fc0.png)|![04](https://user-images.githubusercontent.com/8732417/126951731-ca2f5432-b5c3-48ad-a1be-c986c78e96e6.png)|![05](https://user-images.githubusercontent.com/8732417/126951739-58a7f518-ee52-48ce-95a6-9a1194a6f77e.png)|![delete](https://user-images.githubusercontent.com/8732417/126951745-1eb65fed-d431-43ed-bdc2-1b5252ea7429.png)|

## Slack設定

Slack投稿に必要な情報はWebhook URLとGitHubアカウントです。Webhook URLは投稿したい勤怠チャンネルのものを取得し入力すると良いです。GitHubアカウントは投稿主のニックネーム，画像取得に使われます。ニックネームを入力するとそちらが優先して利用されます。お気に入りカラーはAttachmentのバーの色に反映されます。入力がない場合はこのアプリのテーマカラー(#009944)が使用されます。
それぞれの値の入力は，ペアリングしているiPhoneで行ってください。コピーアンドペーストも可能です。

<img src="https://user-images.githubusercontent.com/8732417/126945900-4ca24d72-f30e-4c9e-a28e-ba13d20f0dcf.png" width="300">

### 補足

「Slack設定」画面で，Slackを投稿する際に必要な情報を入力します。  
これらの情報は投稿時のパラメータとして使用します。

同様に、テキスト入力は、ペアリングされているiOS 13以上のiOSデバイスで実行されます。  
入力できる項目は，SlackのWebhookURLとGitHubアカウント名，ユーザー名とお気に入りのカラーコードです。

「？」 ボタンをタップすると、各項目の説明画面がモーダルで表示されます。

Slack WebhookのURLは、次のリンクから取得できます。  

[https://slack.com/services/new/incoming-webhook](https://slack.com/services/new/incoming-webhook)

### 複数チャネルへの投稿

`v1.0.3` より Slack の複数チャネルへの投稿が利用可能になりました。  
「Slack設定」画面で，「複数投稿を利用」のスイッチをオンにして，  
「Webhook URL 2」の項目に投稿したいチャネルのリンクを入力してください。  

|複数投稿を利用のスイッチをオンに|Webhook URL 2に入力|
|:--:|:--:|
|![Simulator Screen Shot - Apple Watch Series 8 (45mm) - 2022-10-22 at 04 14 20](https://user-images.githubusercontent.com/8732417/197274100-ae5468d1-8c12-43b0-a03c-c794122f0e08.png)|![Simulator Screen Shot - Apple Watch Series 8 (45mm) - 2022-10-22 at 04 14 26](https://user-images.githubusercontent.com/8732417/197274107-13220550-ed6a-438a-abaf-f3416102df6f.png)|

スイッチをオンにしても未入力の場合は，  
複数投稿は無効になり「Webhook URL」のチャネルのみに投稿されます。  
複数投稿しない場合はスイッチをオフにしてください。  
その際入力されたリンクは削除されません(再入力は不要です)。  

## 投稿設定

アクティビティは絵文字とワードがセットになっています。スイッチをオンにすると投稿時に絵文字もセットで投稿できます。ワードだけの投稿も可能です。

<img src="https://user-images.githubusercontent.com/8732417/126944960-b4f25945-f205-41ed-bc14-a4ad02bd8434.png" width="300">

## コンプリケーション設定

文字盤の編集でコンプリケーションにセットするとすぐにアプリケーションを起動できます。すぐに起動できるようになり，2タップで投稿完了です！

<img src="https://user-images.githubusercontent.com/8732417/126945067-292a1be4-121c-4fc2-91b6-a285d314264b.PNG" width="300">

## フィードバック

バグを見つけたり，フィードバックがある場合はお気軽にお問い合わせください。  
機能追加や改善の提案も大歓迎です。

```swift
let name = "Takuya Aso"
let email = "milanista224" + "@" + "me.com"
let profession = "iOS Engineer"
let location = "Tokyo"
let fan = "AC Milan"
```
