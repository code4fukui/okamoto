# 越前市 岡本地区 シビックテック (okamoto)

> [!WARNING]
> **このプロジェクトは移行されました。**
>
> このリポジトリは現在アーカイブされており、新しいプロジェクトへ自動的にリダイレクトされます: [code4fukui/kidssafe-okamoto](https://github.com/code4fukui/kidssafe-okamoto/)。

## ライブデモ

地図は以下のURLでホストされています:

- **[Kidssafe MAP in Okamoto](https://code4fukui.github.io/kidssafe-okamoto/)**

## このリポジトリについて

このリポジトリはもともと、越前市岡本地区のインタラクティブなシビックテック地図をホストしていました。現在の主な役割は、ユーザーをアクティブな最新版のプロジェクトへリダイレクトすることです。

アーカイブされたプロジェクトファイルは引き続き残されており、以下のものが含まれます:

- **`index.html`**: 新しい地図へリダイレクトするJavaScriptを含むシンプルなページ。
- **`point.csv`**: 元の位置情報データファイル。`名称`、`Geo3x3`（グリッドコード）、`URL`の各フィールドを持つ地点（POI）データが含まれています。
- **`images/`**: 元のUIアセット。メニュー/閉じるアイコン（`icon_menu.svg`、`icon_close.svg`）、緊急アラートアイコン（`aioi_3.png`）、ドローンアイコン（`drone_icon.png`）が含まれます。
- **`.nojekyll`**: GitHub Pagesでのデプロイ用にJekyllの処理を無効化します。
- **`.gitignore`**: Jupyter Notebookのチェックポイントファイル（`.ipynb_checkpoints`）を無視するように設定されています。

## ライセンス

MIT License
