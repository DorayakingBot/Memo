# commands.jsonの書き方

```json
{
  "name": "コマンド名",
  "description": "説明",
  "alias": ["短縮コマンド名", "B"],
  "use": "使用方法",
  "slash": "スラッシュコマンドの利用例",
  "args": ["args0の説明", "args1の説明", "..."],
  "botPermissions": ["Bot内部権限"],
  "botRequirePermissions": ["実行サーバーでBotが必要な権限"],
  "memberRequirePermissions": ["実行サーバーで実行メンバーが必要な権限"]
}
```

※name・descriptionは必須 aliasはない場合は`[]` その他はなければ記載なし
