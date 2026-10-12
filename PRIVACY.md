# プライバシーポリシー（原稿）

ストア提出時に必要な「プライバシーポリシー URL」で公開する文面の原本。
公開用の HTML は `tools/make_store_pages.py` が `store/pages/waffle/site/privacy.html` に生成する。
公開先: GitHub Pages（omakeworks/waffle-player-site）

> 内容はコード・実機で確認した事実に基づく（2026-10-12）:
> - 外部と通信する処理は、購入状況の確認（native/store-license の StoreLicense.exe が Windows.Services.Store を呼ぶ）だけ。
>   自動更新・クラッシュレポート・アクセス解析は無い。
> - ビルド済みのアプリで文字入力をしても、外部への TCP 接続は無く、スペルチェック辞書のダウンロードも無かった
>   （Windows 標準のスペルチェックが使われる）。
> - PC 内に保存するのは localStorage の設定だけ（captionMode / captionPos / captionScale / volume / captureColor / captureSize と表示言語）。
>   プレイリスト・再生履歴・ファイルのパスは保存しない。
> - 通信や保存の仕組みを変えたら、この文面も直して公開し直すこと。

---

## 日本語

### Waffle Player プライバシーポリシー

omake works（以下「当方」）は、複数の動画・画像を並べて同時に再生する Windows アプリケーション「Waffle Player」（以下「本アプリ」）における
利用者の情報の取り扱いについて、以下のとおり定めます。

**1. 外部への送信について**

本アプリは、利用者の情報を当方や第三者へ送信することは一切ありません。読み込んだ動画・画像の内容や
ファイル名を外部へ送ることもありません。広告・アクセス解析・クラッシュレポートの送信機能も含んでいません。

ただし、ライセンス（無料試用の期間や購入の状態）を確認するため、Windows の Microsoft Store の仕組みを通じて
Microsoft と通信することがあります。この通信で、当方に情報が送られることはありません。

**2. 本アプリが PC 内に保存する情報**

本アプリは、次の情報だけを利用者の PC 内に保存します。

| 種類 | 内容 |
|---|---|
| 設定 | キャプションの表示方法・位置・大きさ、音量、キャプチャーモードの注釈の色と大きさ、表示言語 |

読み込んだ動画・画像の内容、ファイル名や保存場所、プレイリスト、再生の履歴は保存しません（本アプリを閉じると消えます）。

キャプチャーした画像は、利用者が保存またはコピーを選んだときにだけ、利用者が指定した場所への保存、
またはクリップボードへのコピーを行います。

**3. 保存場所**

Windows がアプリごとに用意する保存場所に保存します。

**4. 情報の削除**

本アプリをアンインストールすると、保存された設定も削除されます。

**5. 購入に関する情報**

本アプリの購入・支払い・返金は Microsoft Store が取り扱います。当方が利用者の氏名・住所・
クレジットカード情報などを受け取ることはありません。

**6. 第三者への提供**

当方は、利用者の情報を保有していないため、第三者へ提供することはありません。

**7. 本ポリシーの変更**

本ポリシーを変更する場合は、このページを更新します。

**8. お問い合わせ**

{{CONTACT_EMAIL}}

制定日: {{PUBLISHED_DATE}}
omake works

---

## English

### Waffle Player Privacy Policy

This policy explains how "Waffle Player" (the "App"), a Windows application that plays multiple videos and images side by side published by
omake works ("we"), handles your information.

**1. Information sent outside your PC**

The App never sends any information about you to us or to anyone else. It does not send the
contents or file names of the videos and images you open. It contains no advertising, analytics,
or crash-reporting functionality.

The App may, however, communicate with Microsoft through Windows' Microsoft Store services to check
its license (the free trial period and purchase status). No information is sent to us through this.

**2. What the App stores on your PC**

The App stores only the following on your PC.

| Type | Contents |
|---|---|
| Settings | Caption display mode, position, and size; volume; annotation color and size in capture mode; display language |

The App does not store the contents of videos or images, their file names or locations, playlists,
or playback history (they are cleared when you close the App).

Captured images are saved to a location you choose, or copied to the clipboard, only when you
choose to save or copy them.

**3. Where it is stored**

In the storage Windows sets aside for each app.

**4. Deleting the information**

Uninstalling the App deletes the stored settings.

**5. Purchases**

Purchases, payments, and refunds are handled by the Microsoft Store. We never receive your
name, address, credit card details, or similar information.

**6. Sharing with third parties**

We hold no information about you, so there is nothing to share with third parties.

**7. Changes to this policy**

If this policy changes, this page will be updated.

**8. Contact**

{{CONTACT_EMAIL}}

Effective date: {{PUBLISHED_DATE}}
omake works
