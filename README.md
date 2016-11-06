# RAIDEN: Rescue Application using Iot and Drone in Emergency and Nebulous situations
## 製品概要
### Emergency Tech

### 背景（製品開発のきっかけ、課題等）
一人暮らしのお年寄りの緊急事態に迅速に対応したい．  
例えば，急な発作があった際に救急車を呼べない可能性がある．  
また，呼べたとしても症状を詳しく説明する余裕がない可能性も考えられる．  
そこで，緊急時にいち早く，正確な対応をするためのドローンとセンサを用いたアプリケーションを考える．


### 製品説明（具体的な製品の説明）
ドローンとIoTを用いた緊急時対応システムを作成する．

### 特長
####特長1
緊急時にかかりつけ医がドローン視点の映像を見ることが可能．  

####特長2
ブラウザ上でドローンを操作することが可能で，患者の状態を詳しく知ることができる．

####特長3
ドローンのマイクとスピーカーで患者とのやり取りが可能．

####特長4
心拍センサーを用いて患者の状態を判別．

### 解決出来ること
緊急時（急な発作など）に救急車が呼べないといった事態を防げる．  
また，かかりつけ医がドローンを通して患者の状態を詳しく知ることで，救急隊員に正確な現状を伝えられ，素早い初動が期待できる．


### 今後の展望
心拍センサーだけではなく，多種多様なセンサを用いることでより正確な異常検知が期待できる．  
簡単な処方を行うことができるドローンの開発．

### 注力したこと（こだわり等）
*簡単に操作可能：ブラウザから操作可能なDrone
*Droneから映像を獲得することができる

## 開発技術
### 活用した外部技術
#### API・データ
*特になし

#### フレームワーク・ライブラリ・モジュール
*Express
*Node.js
*Bottle
*WebSocket
*Arduino_HttpClient_ESP8226

#### デバイス
* Parrot Jumping Night Drone
* Arduino
* 心拍センサー(SFE-SEN-11574)
* Arduino用wifiモジュール(AE-ESP-WROOM-02)
* (Raspberry pi)

### 独自技術
#### 期間中に開発した独自機能・技術
* 2つのサーバを用いることでDroneとブラウザ（クライアント）をつなぐ機能

#### 研究内容（任意）
* もし、製品に研究内容を用いた場合は、研究内容の詳細及び具体的な活用法について、こちらに記載をしてください。
*
