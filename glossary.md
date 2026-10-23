# 用語集 / Glossary

Keep terminology consistent across `src/<target>.md` and `figures/*.<target>.txt`.
Change an entry here first, then search and replace in both places.

Style (ja): です・ます調. Half-width alphanumerics, no space between Japanese and Latin text (e.g. `4D.Vector型`).
Full-width `（）` and `：` in prose. First occurrence of a technical term: 日本語（English）.

## 4D terms (from the official 4D Japanese documentation)

| English | 日本語 | Notes |
|---|---|---|
| entity / entity selection | エンティティ / エンティティセレクション | |
| datastore | データストア | |
| dataclass | データクラス | |
| attribute | 属性 | |
| computed attribute | 計算属性 | |
| collection | コレクション | |
| object | オブジェクト | |
| method | メソッド | |
| project method | プロジェクトメソッド | |
| function | 関数 | |
| class | クラス | |
| parameter | 引数 | |
| form | フォーム | |
| form object | フォームオブジェクト | |
| list box | リストボックス | |
| web area | Webエリア | |
| 4D Web Server | 4D Webサーバー | |
| worker | ワーカー | |
| process | プロセス | |
| query | クエリ | |
| formula | フォーミュラ | |
| component | コンポーネント | |

## Document-specific terms

| English | 日本語 | Notes |
|---|---|---|
| dependency / project dependencies | 依存関係 / プロジェクト依存関係 | First occurrence: 依存関係（dependencies） |
| Dependencies panel | 依存関係パネル | Official doc term |
| Dependency Manager | 依存関係マネージャー | First occurrence: 依存関係マネージャー（Dependency Manager） |
| Design → Project Dependencies menu | **デザイン**／**プロジェクト依存関係**メニュー | Official doc: デザイン/プロジェクト依存関係 |
| origin tag | オリジンタグ | First occurrence: オリジンタグ（origin tag） |
| origin: 4D Component / dependencies.json / Environment / Project Component | 4Dビルトイン / プロジェクトで宣言 / environmentで宣言 / Componentsフォルダー | Japanese UI labels (official doc) |
| dependency rule | 依存関係ルール | |
| Latest | 自動更新する(latest) | Japanese UI label |
| Up to Next Major Version | メジャー更新の手前まで | Japanese UI label |
| Up to Next Minor Version | マイナー更新の手前まで | Japanese UI label |
| Exact Version (Tag) | 自動更新しない(タグ指定) | Japanese UI label |
| Follow 4D Version | 4Dのバージョンに追随する | Japanese UI label |
| Check for updates | 更新をチェックする | Japanese UI label |
| Update on next startup | 次回起動時に更新 | UI shows 次回起動時に<name>を更新 |
| Automatic update | 自動アップデート | Japanese UI label |
| Add a GitHub personal access token... | GitHubパーソナルアクセストークンを追加... | Japanese UI label |
| Edit the GitHub personal access token... | GitHubパーソナルアクセストークンを編集... | Confirmed by editor |
| personal access token / access token | パーソナルアクセストークン / アクセストークン | |
| Update available | 更新利用可能 | Status label in the Japanese UI (confirmed by editor) |
| Not found | 見つかりません | Status label (confirmed by editor) |
| Update all remote dependencies on next startup | 次回起動時に全てのリモート依存関係を更新する | Options menu (confirmed by editor) |
| Select a .4dbase package or a .4DProject file | .4dbase パッケージか.4DProject ファイルを選択してください | Add dependency dialog (confirmed by editor) |
| Dependency Rule | 依存関係のルール | Dialog label (confirmed by editor) |
| Address of the GitHub repository | GitHubリポジトリのアドレス | Dialog label (confirmed by editor) |
| Add a dependency... / Edit the dependency... / Remove the dependency | 依存関係を追加... / 依存関係を編集... / 依存関係の削除... | Official doc |
| Local / Add / Apply / Cancel / Browse | ローカル / 追加 / 適用 / キャンセル / 参照 | Dialog buttons and tabs |
| All / Active / Inactive / Conflicts (tabs) | 全て / アクティブ / 非アクティブ / コンフリクト | Official doc |
| error messages (The download archive…, Unable to find…) | kept in English in 「」 + エラー | The help bubble messages are always English in the 4D UI (confirmed by editor) |
| built-in component | ビルトインコンポーネント | |
| interpreted / compiled (mode, component) | インタープリター / コンパイル済み；インタープリターモード / コンパイルモード | Official doc |
| host project | ホストプロジェクト | |
| release / tag / version | リリース / タグ / バージョン | |
| Semantic Versioning | セマンティックバージョニング | |
| LTS / R-Release | LTS版 / Rリリース | |
| repository (public / private) | リポジトリ（パブリック / プライベート） | |
| developer mode | 開発モード | |
| notarization | 公証（notarization） | macOS |
| gauge | ゲージ | |
| developer | デベロッパー | 4D doc style |

## Proper nouns in examples

| English | 日本語 | Notes |
|---|---|---|
| JohnSmith, theGitHubComponent1, theLocalComponent1–3, theFirstGitHubComponent | unchanged | Inside code |
| jauge / Jauge, launchJauge | unchanged | Demo component and method |
| technote-25-06 | unchanged | GitHub account |
