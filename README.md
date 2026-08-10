# gratet-official.github.io

iPhone 向けパズルゲーム **GRATET** の公開ページ。GitHub Pages で配信している。

| ファイル | 公開 URL | 用途 |
|---|---|---|
| `index.html` | `https://gratet-official.github.io/` | App Store Connect の **サポート URL**（必須項目） |
| `privacy-policy.html` | `https://gratet-official.github.io/privacy-policy.html` | App Store Connect の **プライバシーポリシー URL**（必須項目）／アプリ内リンクの飛び先 |

**このリポジトリにゲームのソースコードは含めない。** 公開が必要なのは上記 2 ページだけで、
本体は別のリポジトリで管理する。

## 更新のしかた

プライバシーポリシーの原稿はゲーム側のリポジトリ (`GRATETO/docs/privacy-policy.html`) が正本。
内容を変えたらそちらを直し、ここへコピーして push する。ページ内の「最終更新日」も忘れず更新する。

## メモ

- `.nojekyll` は Jekyll による前処理を止めるための空ファイル。素の HTML をそのまま配信する
- ユーザーページ (`<ユーザー名>.github.io`) は既定ブランチの内容が自動で公開される。
  反映されないときは Settings → Pages で Branch を `main` / `/ (root)` に設定する
- 連絡先は `gratet.official@gmail.com`
