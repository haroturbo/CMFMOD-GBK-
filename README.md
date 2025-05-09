CWCheat Memory File MOD（CMFMOD-GBK）ドキュメント
概要
CMFMOD-GBK は、PSP 用のチートプラグイン「CWCheat」のメモリファイル（CMF）を編集・変換するためのツールです。
特に、GBK（簡体字中国語）エンコーディング に対応しており、中国語環境での使用を想定しています。このツールは、CWCheat のメモリダンプファイルを解析・編集し、再構築する機能を提供します。

主な機能
CWCheat のメモリファイル（CMF）の読み込みと解析

メモリダンプデータの編集および再構築

GBK エンコーディングへの対応

各種エンコーディング（SHIFT_JIS、EUC、BIG5）への変換バッチファイルの提供

システム要件
Windows 環境（Windows 7 以降推奨）

C コンパイラ（Makefile に対応した環境）

libiconv ライブラリ（文字コード変換用）

インストール方法
GitHub リポジトリ からリポジトリをクローンまたは ZIP でダウンロードします。

必要に応じて、libiconv ライブラリをインストールします。

コマンドプロンプトを開き、リポジトリのディレクトリに移動します。

make コマンドを実行してビルドします。

使用方法
CWCheat で取得したメモリファイル（CMF）を用意します。

コマンドプロンプトで、以下のようにコマンドを実行します：

bash
コピーする
編集する
cmfmod input.cmf output.cmf
ここで、input.cmf は入力ファイル、output.cmf は出力ファイルです。

必要に応じて、提供されているバッチファイルを使用してエンコーディングを変換します。

バッチファイル一覧
リポジトリには、以下のバッチファイルが含まれています：

GBK.bat：GBK エンコーディングへの変換

BIG5.bat：BIG5 エンコーディングへの変換

SHIFTJIS.bat：SHIFT_JIS エンコーディングへの変換

EXTENDED_UNIX_CODE.bat：EUC エンコーディングへの変換

これらのバッチファイルを実行することで、CMF ファイルのエンコーディングを簡単に変換できます。

注意事項
本ツールは、CWCheat のメモリファイルを編集するためのものであり、使用には注意が必要です。

エンコーディングの変換を行う際は、元のファイルのバックアップを取ってから実行してください。

本ツールの使用によって生じた問題について、開発者は一切の責任を負いません。

参考リンク
GitHub リポジトリ: https://github.com/haroturbo/CMFMOD-GBK-

アーカイブされた旧公式ドキュメント: https://web.archive.org/web/20160713085332/http://ijiro.daiwa-hotcom.com/data/CMF.html
