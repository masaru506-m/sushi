# 寿司カレッジ東京 - デプロイメントガイド

## 📦 必要なファイル

以下のファイルが必要です：

```
sushi-college-tokyo/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── hero-bg-sushi.jpg
│   └── hero-bg.jpg
└── README.md
```

## 🚀 Netlifyでの無料公開手順

### 方法1: Netlify Drop（最速・アカウント不要）

1. **URLにアクセス**
   https://app.netlify.com/drop

2. **フォルダをドラッグ&ドロップ**
   - プロジェクトフォルダ全体をドラッグ
   - または、ZIPファイルをドロップ

3. **即座に公開！**
   - 自動的にURLが発行されます
   - 例：https://random-name-123.netlify.app

4. **サイト名を変更**（オプション）
   - アカウント作成（無料）
   - Site settings → Change site name
   - 例：sushi-college-tokyo.netlify.app

### 方法2: Netlify CLI（上級者向け）

```bash
# Netlify CLIをインストール
npm install -g netlify-cli

# プロジェクトフォルダに移動
cd sushi-college-tokyo

# デプロイ
netlify deploy --prod
```

## 🌐 独自ドメインを後から追加する場合

1. **ドメインを購入**（推奨レジストラ）
   - お名前.com: https://www.onamae.com/
   - ムームードメイン: https://muumuu-domain.com/

2. **Netlifyで設定**
   - Site settings → Domain management
   - Add custom domain
   - ドメイン名を入力

3. **DNS設定**
   お名前.comの管理画面で：
   
   **Aレコード:**
   ```
   Type: A
   Host: @
   Value: 75.2.60.5
   TTL: 3600
   ```
   
   **CNAMEレコード:**
   ```
   Type: CNAME
   Host: www
   Value: your-site.netlify.app
   TTL: 3600
   ```

4. **SSL証明書**
   - Netlifyが自動的に無料SSL証明書を発行
   - HTTPSで安全にアクセス可能

## ✅ デプロイ後の確認

- [ ] サイトが正しく表示される
- [ ] すべての画像が表示される
- [ ] リンクが正しく動作する
- [ ] モバイルで正しく表示される
- [ ] 連絡先情報が正確
- [ ] SSL証明書が有効（HTTPSで表示）

## 📞 連絡先情報

以下の連絡先が正しく設定されていることを確認：

- Email: sushi.college2@season-2.com
- LINE: https://line.me/R/ti/p/@591oxcen
- Instagram: @sushi.college.tokyo
- TikTok: @sushi.college.tokyo
- 住所: 〒150-0013 東京都渋谷区恵比寿2-8-13 KHビル 1F

## 🎯 おすすめの無料URL

Netlifyでのおすすめサイト名：
- sushi-college-tokyo.netlify.app
- tokyo-sushi-college.netlify.app
- sushicollege-ebisu.netlify.app

## 💡 今後のステップ

1. **無料サブドメインで運用開始**
2. **反響を見る**
3. **必要に応じて独自ドメインを購入**
4. **Netlifyで簡単に独自ドメインに移行**

## 🔗 便利なリンク

- Netlify: https://www.netlify.com/
- Netlify Drop: https://app.netlify.com/drop
- Netlifyドキュメント: https://docs.netlify.com/

---

**質問があれば、Season 2 Inc. にお問い合わせください**
https://season2-group.com/
