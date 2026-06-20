# Privacy Policy for Language Shadowing for YouTube

**Last updated:** June 21, 2026

This privacy policy governs your use of the Chrome extension "Language Shadowing for YouTube" (the "Extension").

## 1. Collection and Use of User Data
We highly value your privacy. The Extension **does not collect, store, or transmit any personally identifiable information (PII), voice recordings, or browsing history to external servers.** 

The only data handled by the Extension consists of user configuration settings, which are processed and stored strictly within your local environment as detailed below:

- **Microphone Access:** Used solely to record your voice for real-time echo-back practice. Audio data is processed entirely in the browser (locally), temporarily held in memory, and is instantly overwritten or deleted after playback. It is never saved to persistent storage or transmitted externally.
- **Storage (`chrome.storage.local`):** Used only to save your configuration settings (such as custom shortcut keys and auto-pause options) locally within your browser. 
- **Offscreen Documents:** Used strictly to comply with modern Chrome Extension (Manifest V3) security standards. This API allows the Extension to safely handle background audio recording (`getUserMedia`) and playback (`AudioContext`), which cannot be executed within a standard Service Worker.
- **Host Permissions (YouTube Access):** Used exclusively to detect and control the video player (such as auto-pausing and resuming video playback) on YouTube pages. The Extension does not read, modify, or access web pages or user data on any other domains.

## 2. Data Retention and Deletion
All configuration settings are stored locally using Chrome's secure storage API (`chrome.storage.local`). This data remains on your device solely for the purpose of maintaining your preferences. **Once you uninstall the Extension from your browser, all locally stored settings and data are automatically and permanently deleted.**

## 3. Third-Party Sharing and Analytics
Since we do not transmit or collect any user data, we do not share, sell, or trade any personal or technical information with third parties. The Extension does not use any third-party analytics tools, tracking cookies, or crash reporting services.

## 4. Changes to This Privacy Policy
We may update our Privacy Policy from time to time to reflect changes in our practices or regulatory requirements. Any changes will be posted on this page.

## 5. Contact Us
If you have any questions regarding privacy while using the Extension, please contact us at:
- **Email:** mkatsdev@gmail.com
- **GitHub:** https://github.com/mkats4412/language_shadowing

---

# プライバシーポリシー (Privacy Policy)

**最終更新日:** 2026年6月21日

本プライバシーポリシーは、Chrome拡張機能「Language Shadowing for YouTube」（以下、「本拡張機能」）の利用におけるユーザーデータの取り扱いについて説明するものです。

## 1. ユーザーデータの収集および利用について
当開発者は、ユーザーのプライバシーを最優先に考えています。本拡張機能は、**個人を特定できる情報、録音された音声データ、および閲覧履歴を外部サーバーへ送信・保存することは一切ありません。** 

本拡張機能が扱うデータはユーザーの設定情報のみであり、以下の通りすべてローカル環境（ブラウザ内）でのみ処理・保存されます。

- **マイクへのアクセス:** ユーザーの音声をリアルタイムで録音し、エコーバック（シャドーイング練習）を行う目的のみに使用されます。音声データはローカル環境のメモリ上で一時的に処理されるだけであり、再生終了後は即座に破棄されます。外部への送信やファイルとしての永続保存は行われません。
- **ストレージ（`chrome.storage.local`）:** ユーザーがカスタマイズしたショートカットキーや、動画の自動一時停止設定などのオプション（設定値）を、ブラウザ内に安全に記憶するためだけに使用されます。
- **オフスクリーンドキュメント（Offscreen Documents）:** 最新のChrome拡張機能（Manifest V3）のセキュリティ仕様に従い、Service Worker内では実行できない「バックグラウンドでのマイク音声の取得」および「オーディオ再生」を安全かつ安定して実行するためにのみ使用されます。

## 2. データの保存期間と削除方法
すべての設定データは、ブラウザの安全な領域（`chrome.storage.local`）にローカル保存されます。このデータはユーザーの快適な利用（設定の維持）のためだけに保持されます。**ユーザーがブラウザから本拡張機能をアンインストール（削除）すると、ローカルに保存されていた設定データもすべて自動的かつ完全に消去されます。**

## 3. 第三者へのデータ提供および解析ツールについて
本拡張機能はユーザーデータを一切外部に送信しないため、いかなる個人情報や技術的データを第三者に販売、共有、または開示することはありません。また、外部のアクセス解析ツール、クラッシュレポート、広告配信等の外部APIも一切組み込んでいません。

## 4. プライバシーポリシーの変更
本プライバシーポリシーは、機能の追加や法的要件の変更に応じて、必要に応じて更新されることがあります。変更があった場合は、このページにて通知いたします。

## 5. お問い合わせ
本拡張機能のプライバシーに関するお問い合わせやご質問は、下記までご連絡ください。
- **メールアドレス:** mkatsdev@gmail.com
- **GitHub:** https://github.com/mkats4412/language_shadowing
