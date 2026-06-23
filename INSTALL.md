# INSTALL

## インストール手順

1. Releases ページから `Mapping-SFA-0.3.1-arm64.dmg` をダウンロードします
2. ダウンロードした DMG を開きます
3. `Mapping-SFA.app` を `Applications` フォルダへドラッグします
4. `Applications` フォルダから `Mapping-SFA` を起動します

## 初回起動時の注意

この配布版はad-hoc署名済みですが、Apple Developer IDによる署名・公証は未実施です。初回起動時にそのまま開けない場合は、以下の手順を実施してください。

### 「開発元を確認できません」と表示された場合

1. `Applications` フォルダを開きます
2. `Mapping-SFA.app` を右クリックします
3. `開く` を選択します
4. 確認ダイアログでもう一度 `開く` を選択します

必要に応じて、`システム設定` → `プライバシーとセキュリティ` から `このまま開く` を選択してください。

## 対応環境

- macOS
- Apple Silicon 搭載 Mac 専用

## アップデート方法

1. Releases ページから新しい DMG をダウンロードします
2. 新しい `Mapping-SFA.app` を `Applications` フォルダへ上書きします
3. 起動時に警告が出た場合は、再度 `右クリック → 開く` を実施してください

## アンインストール方法

1. `Applications` フォルダから `Mapping-SFA.app` を削除します
2. 必要に応じて、アプリ内で出力したバックアップ JSON を手元で整理してください
