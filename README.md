# __My Portfolio__  
<br/>
# [flutter_memo_widget](https://github.com/eight50/flutter_memo_widget/tree/main)  
## Overview  
Androidのホームスクリーン上にメモを作成できる  
ウィジェットごとに異なる内容を記述できる  

## Demo  
![memo_widget_demo](https://github.com/eight50/flutter_memo_widget/assets/84005278/edd98bad-e586-45a4-b1a9-4fd5300ec025)  

## Technologies Used
言語：Flutter, Kotlin  
アーキテクチャ：MVVM
- dartVM  
- SharedPreferences  

## Features  
- ネイティブ側から、FlutterEngineを用いてテキスト編集画面を新規作成している  
- appWidgetIdはdartVMの引数として渡している  


# [SeamlessTranslation](https://github.com/eight50/SeamlessTranslation)(Ongoing)
## Overview  
ウィジェット上で完結する音声翻訳アプリ  
ウィジェットから録音を開始し、翻訳結果を表示する  
VoiceToTextはVosk、翻訳はDeepLAPIで行う  

## Demo  
![Image](https://github.com/user-attachments/assets/6685ef75-2ce8-4341-b78f-dca9665abb70)  

## Technologies Used  
言語：Kotlin  
アーキテクチャ：Clean Architecture + MVVM  
・ForegroundService  
・Jetpack Glance  
・Jetpack Compose  
・Media Recorder  
・Retrofit 
・Vosk  

## Features  
・ForegroundServiceを使用して、自由に録音の開始・停止が行える  

## Class Diagram  
![Image](https://github.com/user-attachments/assets/824f8abe-9bbf-4bec-84a9-fee99f0ea66f)  
