# 環境構築メモ
HPは、Windows環境での環境構築だったので、Mac環境で実行したい場合のメモ
## 実行環境
- iMac 2013
- MacOS 10.15.7

## 環境構築
※Homebrewがインストール済み前提

- Icarus Verilogのインストール  
Verilog シミュレータである、Icarus Verilogは、以下でインストールできた。
  ```
  brew install icarus-verilog
  ```

- gtkwaveのインストール  
gtkwaveは、波形ビューアである。
  こちらは、参考HP通りには行かなかった。以下で、うまくインストールできた。
  ```
  brew install --cask gtkwave
  ```
## 参考HP
- [Icarus Verilog (iverilog) の Mac へのインストール](https://scrapbox.io/craftmemo/Icarus_Verilog_(iverilog)_%E3%81%AE_Mac_%E3%81%B8%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
- [craftmemo, gtkwave の Mac へのインストール](https://scrapbox.io/craftmemo/gtkwave_%E3%81%AE_Mac_%E3%81%B8%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)