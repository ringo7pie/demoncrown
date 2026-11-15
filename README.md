# Demon of the Crown（デーモン・クラウン）― アルファテスト版

個人で開発しているゲームのアルファテスト版です。未完成で、不具合があります。無料です。

## ダウンロード
**[DemonCrown-0.1.0-alpha-win64-setup.exe（インストーラー・709 MB）](https://github.com/ringo7pie/demoncrown/releases/download/v0.1.0-alpha/DemonCrown-0.1.0-alpha-win64-setup.exe)**

- 上のリンクを押すと、ダウンロードが始まります。ダウンロードの前に、下の「プレイ記録の送信」を必ずお読みください。
- [SHA-256 のファイル](https://github.com/ringo7pie/demoncrown/releases/download/v0.1.0-alpha/DemonCrown-0.1.0-alpha-win64-setup.exe.sha256) ／ [リリースのページ](https://github.com/ringo7pie/demoncrown/releases/tag/v0.1.0-alpha)（このページの右の「Releases」からも開けます）

予告動画: https://youtu.be/uC_fTwHhQyI

## どんなゲームか
- AI の仲間に、声（または文字）で指示を出して進むダンジョン探索ゲームです。「レンは前で」「ソラ、魔法で攻撃して」「みんな下がって」のように話しかけます。
- 仲間は声で答え、自分で考えて戦います。仕掛けは協力して解きます。
- 音声認識・会話・音声合成は、あなたの PC の中で動きます。
- アルファテストで遊べるのは、最初の 5 マップです。

## 生成 AI の利用について
このゲームは生成 AI を使って作っています: 敵とボスの 3D モデル（Tripo3D）、仲間の声（音声合成）と会話（PC の中で動く言語モデル）、アイコンの絵、プログラムの一部。BGM と効果音は、プログラムで合成した音です。

## ダウンロードの前に必ずお読みください（プレイ記録の送信）
- アルファ版は、プレイ記録を開発者のサーバーへ送ることを承諾した方だけが遊べます。最初の起動で確認の画面が出て、承諾しない場合はゲームが終了します。
- 送る物: 話しかけた言葉を文字にした物、仲間の返事と行動、進行、設定、PC の構成、エラー、接続元の国、無作為の匿名の ID（同じプレイヤーの記録かどうかを見分けるための物）。接続元の IP アドレスは記録しません。
- 送らない物: 音声（録音・マイクの波形）、名前、アカウント、メールアドレス、ファイルの場所、画面の画像。
- 話した言葉は、聞き取った文のまま送ります。個人的なことは話さないでください。
- 送った記録の削除の依頼は、原則として受け付けていません（法令で必要な場合を除きます）。サーバー上の元のデータは 60 日で自動的に消え、開発用の写しは製品版の公開から 1 年以内に消します。
- 全文は、ゲームの最初の画面と README に書いてあります。

## 動作環境
- Windows 10 / 11（64 ビット）、Vulkan または Direct3D 12 に対応した GPU。開発は Windows 11・RTX 3070（VRAM 8 GB）で調整しています。VRAM 4 GB・メモリ 16 GB の PC でも動くことを確かめました（声の返事が少し遅れます）。ほかの機種は未確認です。
- 最初の起動のあと、音声の道具（約 10 GB）を自動でダウンロードします（GitHub・Hugging Face・AivisHub から）。空きは約 16 GB 必要です。
- インストール先は、短い名前の場所にしてください（フルパス 115 文字以内）。

## インストール
1. 上の「ダウンロード」のリンクからインストーラー（setup.exe）をダウンロードして実行します。署名のない exe なので、Windows が「PC が保護されました」と出すことがあります（「詳細情報」→「実行」）。
2. SHA-256: aa0034004d933ac28b16ba421db5486f4baced8254fcb3b105753db237fbcfa2（Releases の .sha256 のファイルにも同じ値があります）
3. 消すときは、Windows の「アプリ」からアンインストールできます。セーブと設定（%APPDATA%\DungeonQuest）は残ります。

## 不具合の報告・感想
- 不具合の報告: https://forms.gle/Hv767PDzebpdgLKn9（F12 の「記録の送信」に出る 8 文字の ID を添えてもらえると、調べやすくなります）
- 感想は、YouTube の予告動画のコメント欄へお願いします。
- 再配布・販売はしないでください。

---

## English
An alpha test build of a game in development by a solo developer. Unfinished, with bugs. Free.
**Download: [DemonCrown-0.1.0-alpha-win64-setup.exe (installer, 709 MB)](https://github.com/ringo7pie/demoncrown/releases/download/v0.1.0-alpha/DemonCrown-0.1.0-alpha-win64-setup.exe)** ([SHA-256](https://github.com/ringo7pie/demoncrown/releases/download/v0.1.0-alpha/DemonCrown-0.1.0-alpha-win64-setup.exe.sha256), [release page](https://github.com/ringo7pie/demoncrown/releases/tag/v0.1.0-alpha)). Please read the play-data notice below before downloading.

- Lead AI companions by voice (or typed text) through dungeons. They answer by voice, fight on their own judgment and solve puzzles with you.
- Speech recognition, conversation and speech synthesis run on your own PC. Japanese by default; English can be chosen on the first launch.
- The alpha covers the first 5 maps.
- Made with generative AI: enemy and boss 3D models (Tripo3D), voices (speech synthesis), conversation (a local language model), icon art, and part of the code.
- Play data: you can play only if you agree to send play data (recognized text of what you say, companions' actions, progress, settings, PC specs, errors, the country you connect from, a random anonymous ID used to tell whether records come from the same player; your IP address is not recorded). Audio is never sent. As a rule, requests to delete data already sent are not accepted (except where the law requires it). The full text is shown on the first launch and in the README.
- Requirements: Windows 10 / 11 (64-bit), a GPU that supports Vulkan or Direct3D 12 (tuned on an RTX 3070). About 10 GB of voice tools are downloaded after the first launch (about 16 GB of free space needed).
- The installer is not signed; Windows may show a SmartScreen warning. Please do not redistribute or sell this build.
- Bug reports: https://forms.gle/Hv767PDzebpdgLKn9
