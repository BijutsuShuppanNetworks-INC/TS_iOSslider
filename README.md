TS_iOSslider
============
## 概要
HTML5から追加されたinputのスライダー(type="range)の動作検証

## 検証内容
- input type="range"の挙動確認(iOS,Android,PCブラウザ)
- スライダーで変更した値をCSSに反映
- インターフェースの変更
- (ついでに)ボタンで文字サイズ変更のインターフェースも確認

## 検証先URL
http://bijutsushuppannetworks-inc.github.io/TS_iOSslider/  

## 懸念事項
- type="range"はiOS5以上の対応
- Android2.3以下の端末で未検証
- iOS7.0.6でたまにスライダーのコントロールの反応が悪いことがある。
- コントロールの領域を大きめに取ったほうが良さそう。
