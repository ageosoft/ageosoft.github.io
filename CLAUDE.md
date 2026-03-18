# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

ageosoft.com の公式ウェブサイト。GitHub Pages でホスティングされている静的サイト。
HTMLファイルはGoogle Sitesからエクスポートされたもので、各ページが個別のHTMLファイルとして存在する。

## Site Structure

- `index.html` — トップページ（Home）
- `BMCalc.html`, `Azimuth Map for *.html`, `Music Browser for iOS.html` — アプリ紹介ページ
- `Privacy Policy - *.html` — 各アプリのプライバシーポリシー
- `Contact Us.html` — お問い合わせページ
- 各ページ名と同名のディレクトリ（`Home/`, `BMCalc/` など）に画像アセットが格納されている
- `CNAME` — カスタムドメイン設定（ageosoft.com）
- `app-ads.txt` — Google AdMob 広告設定

## Deployment

- `main` ブランチへの push で GitHub Pages に自動デプロイされる
- ビルドステップなし。HTMLファイルがそのまま配信される

## Notes

- HTMLファイルはGoogle Sites エクスポート由来のため非常に大きい（各約1.8MB）。インライン化されたCSS/JSを含む
- ファイル名・ディレクトリ名にスペースが含まれるため、パス指定時はクォートが必要
