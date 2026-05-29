# Student Dashboard (Neo-Brutalism Style)

HTML/CSS/JavaScriptのみで構築された、GitHub Pagesで公開可能な学生向けダッシュボードアプリです。

## 機能
- **Pomodoro Timer**: 25分/5分の切り替えが可能なタイマー。
- **Task Manager**: Todoリスト。データはブラウザのLocalStorageに保存されます。
- **GPA Tracker**: 成績と単位数からGPAを計算。
- **Schedule**: 週間時間割の表示。
- **Quick Notes**: 自由に書き込めるメモ帳（自動保存）。
- **Weather**: Open-Meteo APIを使用した現在の天気の表示。

## デザイン
個性的な **Neo-Brutalism** スタイルを採用しています。
- 太い黒枠（Border）
- 強いドロップシャドウ
- ビビッドな配色

## GitHub Pagesへの公開手順
1. このリポジトリをGitHubにプッシュします。
2. GitHubリポジトリの `Settings` > `Pages` を開きます。
3. `Build and deployment` > `Branch` で `main`（または `master`）を選択し、`/ (root)` を指定して `Save` をクリックします。
4. 数分後、公開されたURLにアクセスできるようになります。

## カスタマイズ
- `js/weather.js`: 緯度・経度を変更することで、お住まいの地域の天気に変更できます。
- `css/style.css`: `--border-size` や `--shadow-offset` を変更することで、デザインの強さを調整できます。
