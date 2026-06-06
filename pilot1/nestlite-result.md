## 今後の課題

NestLiteのパイロット版により、Chat / Idea / Note を1つの画面で扱う軽量統合版の方向性は確認できた。

一方で、現時点ではNote機能が単純なメモ編集に近く、NoteNestが持つ「プロジェクト管理ノート」としての思想、すなわち複数ノート、タスク、マーカー、関連情報の管理までは十分に反映できていない。

今後NestLiteを継続検討する場合は、以下を課題とする。

- Noteを単なるメモではなく、Project Notesとして扱う
- Project Titleなど、プロジェクト単位の概念を持たせる
- [TODO] [NOTE] [FIXME] などの簡易マーカー検出を検討する
- IdeaカードからNoteを作成した際、関連元Ideaを保持する
- Markdownエクスポート時に、Project / Chat / Ideas / Notes / Markers の流れで出力する
- 既存の .notenest / .ideanest / .chatnest ファイルへの直接読み書きは、当面対象外とする
- NestLiteは現行3ツールの置き換えではなく、統合思想を検証する別系統として扱う
