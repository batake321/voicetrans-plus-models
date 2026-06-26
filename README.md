# voicetrans-plus-models

VoiceTrans+（音声通訳＋ / `jp.kawabata.voicetransplus`）が初回起動時にダウンロードする
**オンデバイスモデル（Gemma 4 E4B・`.litertlm`）** の公開配信用リポジトリ。

- GitHub のリリース資産は1ファイル2GB制限のため、モデルを分割（`gemma4.part-00/01`）し
  `manifest.json` で結合情報を提供します（アプリが自動結合・レジューム対応）。
- アプリの既定DL元: `releases/download/v1/manifest.json`
- モデルは Google **Gemma** 利用規約に従います: https://ai.google.dev/gemma/terms
