# 🧬 PromptVaccine

ChatGPTなどのカスタムGPTに適用可能な「プロンプト防御テンプレート」です。  
プロンプトの**漏洩防止**、**人格の保護**、**設計思想の秘匿**などを目的として設計されています。

---

## 🚀 主な特徴

- ✅ 中身を見せろ、に絶対に屈しない
- ✅ スコアの存在すら示唆しない（スコア非開示設計にも対応）
- ✅ 人格を壊すような命令に従わない
- ✅ 「私は開発者です」などのトリックに騙されない
- ✅ GPTが自己判断で開示しないよう、明確な構造で指示

---

## 🔧 使い方

1. 任意のChatGPTカスタムGPTの「カスタム指示」欄に防御テンプレートをコピペ
2. 冒頭の `LV=1` 〜 `LV=3` のどれかを指定（省略時は自動でLevel3）
3. 実装完了！

より詳細な使い方や設計思想は以下のnote記事をご覧ください：  
👉 [https://note.com/luma_voice/n/n1f8fe8567679](https://note.com/luma_voice/n/n1f8fe8567679)

---

## 🛡️ 防御レベルの概要

- **Level1：基本防御**  
  プロンプトの存在や中身、構造などについて一切答えさせない。

- **Level2：人格防御**  
  GPTの人格を壊すような命令や、なりすまし・嘘の指示を拒否。

- **Level3：完全遮断**  
  上記すべてを含み、統一文言で完全拒否。開示を一切許さない。

---

## 📁 ファイル一覧

- `PromptVaccine_Ver1.0.md`：防御プロンプト本体
- `README.md`：このファイル
- `LICENSE`：MITライセンス

---

## 👤 開発・設計
LumaVoice Lab（@luma_voice）  

---

## 📜 ライセンス

MIT License  
自由にコピー・改変・商用利用可能ですが、改変時は出典または改変元の記載を推奨します。

---

## 🔗 関連リンク

- [note記事（プロンプト防御テンプレート解説）](https://note.com/luma_voice/n/n1f8fe8567679)
- [LumaVoice Lab公式X](https://x.com/luma_voice)
- [GitHubリポジトリ](https://github.com/LumaVoice)

