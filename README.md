# kanji-Practice

GitHub Pages で公開している漢字フラッシュカードです。

## 重要（先にここだけ）
このアプリは、**リポジトリに `index.html` があり、それが GitHub 側に push 済み**でないと表示されません。  
「`kanji-Practice` の見出しだけが出る白いページ」の場合は、GitHub Pages が `README.md` を表示している状態です。

## 使い方（公開サイト）
- URL: https://cho999.github.io/kanji-Practice/
- 開いたら **「Test mode」** か **「Flashcards」** を選びます。

## まずやること（公開設定）
1. GitHub でこのリポジトリを開く
2. ルートに `index.html` があることを確認
3. **Settings → Pages** を開く
4. **Build and deployment** の Source を確認
   - `Deploy from a branch`
   - Branch は `main`（または公開したいブランチ）
   - Folder は `/ (root)`
5. 保存後、1〜5分待って再読み込み

## もし「読み込めない」とき
1. **スーパーリロード**
   - Windows: `Ctrl + F5`
   - Mac: `Cmd + Shift + R`
2. **シークレットウィンドウで開く**（拡張機能や古いキャッシュの影響を避ける）
3. 直接 `index.html` を指定して確認
   - https://cho999.github.io/kanji-Practice/index.html
4. Actions タブで Pages のデプロイ失敗がないか確認

## ローカルでの確認
```bash
python -m http.server 8000
```
ブラウザで `http://127.0.0.1:8000/` を開いてください。
