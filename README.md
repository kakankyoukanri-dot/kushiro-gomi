# kushiro-gomi
# 釧路市ごみ分別検索システム

釧路市環境事業課が提供するごみ分別検索システムです。

## 公開URL
https://kushiro-kankyou.github.io/kushiro-gomi/

## 概要
市民が家庭ごみの捨て方を素早く検索できるシステムです。
品目名を入力するだけで、分別区分・処分方法・持込先を確認できます。

## 機能
- キーワード検索（ひらがな・カタカナ・漢字対応）
- 606件のごみ品目データベース
- スマートフォン・PC対応
- 検索履歴の記録

## システム構成
- フロントエンド：HTML/CSS/JavaScript（GitHub Pages）
- データベース：gomi_db.json（GitHub上で管理）
- ログ保存：Google Apps Script
- アクセス解析：Google Analytics

## データベースの更新方法
1. Googleスプレッドシートのデータを修正
2. GASエディタで`updateGithubDBManual()`を実行
3. 自動的にgomi_db.jsonが更新される

## 管理者
釧路市 市民環境部 環境事業課
Tel: 0154-24-4146（平日9:00〜17:00）

## 更新履歴
- 2026年3月　システム公開
