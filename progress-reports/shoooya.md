# 成果報告 - 2017.08.02
## 目標
 - １画面で電卓作成

## 進捗
### 完了
 - 電卓もどきを作成
  - 加算・減算・乗算・除算を実装

### 未完了
 - 算出した解に対し再度計算を行う
 - 手順以外の操作等で起こるエラーのハンドリング
 - コードの可読性向上
 - デザイン

## 完了項目詳細
### 計算
 - 数字ボタン（０〜９）が連続で押下された際、１の位・１０の位・１００の位・・・とする
 - 数字ボタンが押下された後、演算子ボタン（＋、ー、×、÷）が押下された際、その演算子・入力されていた数値を記憶しテキストエリアをクリア
 - 演算子ボタンが押下された後に数字ボタンが押下された際、再度テキストエリアに数値を表示する
 - 上記の後、イコールボタンが押下された場合、記憶していた数値・演算子・入力されている値を用いて計算を行う
 - クリアボタンが押下された際、記憶している数値・演算子・テキストエリアの数値をクリアする
 
### レイアウト
 - RelativeLayout、LinearLayoutを用いてボタンの配置等を整形
  - レイアウトの種類についてはこちらを参照→https://techacademy.jp/magazine/4457

## 成果物
 - https://github.com/shoooya/calculator_app
