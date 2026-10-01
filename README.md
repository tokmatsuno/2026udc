# いえネコ v9.0 MEETING EDITION + CAPYBARA ME! Kids

GitHub Pages向け一式です。リポジトリ直下にこのフォルダの中身をそのままアップロードしてください。

## 1. 現行版 いえネコ v9.0

- 100匹の基準猫 + 根拠表示
- 5問は維持し、各問は「具体的な1場面 + 1本のスライダー」に変更
- 4種類の場面をセッションごとに入れ替え（5問で偏りが出にくいローテーション）
- 中間値をそのまま回答として利用
- イベント・調査タグ（例：NAGASAKI-2026）を結果に付与可能
- ニックネームを使った自己紹介共有に対応
- 家猫MAP・概略位置・100匹の根拠・CSV更新方式は維持

入口: `/index.html`
MAP: `/ienekomap.html`
基準データ: `/家猫_データソース.csv`

## 2. Kids版 CAPYBARA ME!

入口: `/kids/index.html`

- 100匹のカピバラを集めるスマホ向けゲーム
- 5つのスライダーで「今日使いやすい力」を見つける
- 固定的な性格タイプに断定しない
- 100匹コレクション + 日替わりGET
- ニックネーム・好きなこと・声のかけられ方を使った自己紹介カード
- GitHub Pages上では自己紹介URLをスマホ/ブラウザで共有可能
- 回答履歴を自分の端末で可視化する「データラボ」
- 自分の回答履歴をCSVで保存可能
- 回答・コレクションはlocalStorageのみ。サーバ送信なし
- 研究・教育枠組みの引用をアプリ内と `kids/capybara_data.csv` に記載

### Kids版で参照する主な根拠

- CASEL SEL Framework
- Ryan & Deci (2000) Self-Determination Theory
- Ryan, Pintrich & Midgley (2001) Help Seeking
- Yeager et al. (2019) Growth Mindset
- Baumeister & Leary (1995) Need to Belong

## GitHub Pages

Settings → Pages → Deploy from a branch → main / root を選択します。

公開後:

- 現行版: `https://<user>.github.io/<repo>/`
- Kids版: `https://<user>.github.io/<repo>/kids/`

## 注意

どちらも医学・心理学的な診断ではありません。現行版のX/Yは基準猫を比較するための設計座標です。Kids版は子どもの強みを固定ラベル化せず、自己紹介やデータの見方を学ぶためのツールとして設計しています。
