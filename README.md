# コンポーネントの依存関係管理：課題と解決策

Managing Component Dependencies: Challenges and Solutions (4D Technical Note 25-06): Japanese edition.

4Dのプロジェクト依存関係（dependencies）を使ってコンポーネントを管理する際に生じやすい問題と、その対策をまとめたテクニカルノートの日本語版です。`dependencies.json` と `environment4d.json` の役割、「プロジェクト依存関係」画面での依存関係の追加と更新、インタープリターモードとコンパイルモードの違い、タグとバージョンの命名規則、よくある問題とその解決策を解説しています。最後のチュートリアルでは、プライベートリポジトリでコンポーネントを公開し、アクセストークンを設定して依存関係として追加する流れを説明しています。

## Download

| | |
|---|---|
| PDF (Japanese) | [25-06_ManagingDependencies_ja.pdf](https://github.com/miyako/ManagingDependencies/releases/latest/download/25-06_ManagingDependencies_ja.pdf) |
| 4D demo | [ManagingDependencies.zip](https://github.com/miyako/ManagingDependencies/releases/latest/download/ManagingDependencies.zip) |
| Original (English) | `document/25-06_ManagingDependencies.pdf` |

## Demo

- Open `demo/ManagingDependencies/Project/ManagingDependencies.4DProject`.
- The project has no methods, forms or tables of its own. It only declares two GitHub dependencies in `Project/Sources/dependencies.json` (`addkomo4d/testComponent` and `technote-25-06/Jauge`).
- `technote-25-06/Jauge` is a private repository, so the tutorial can't be reproduced as is. The Japanese text presents it as an explanation rather than a hands-on exercise.
- The menu bar uses 4D's built-in strings, which 4D shows in the UI language. Nothing in the project needed translating.

## Differences from the original

- The tutorial section (デモアプリケーション → チュートリアル) is written as an explanation, because the Jauge repository is private.
- The technical note number is removed from the title page.
- Screenshots of the Dependency Manager and related dialogs (figures 1–7, 9–12, 16, 17) have their UI text replaced with the Japanese 4D UI labels. Error messages in help bubbles stay in English, as in the Japanese 4D UI. Figures 8, 13–15, 18 and 19 are unchanged.
- The GitHub personal access token printed in the original is replaced with a placeholder.
- Errors in the original are fixed in both languages: a duplicated paragraph, a missing comma in the `environment4d.json` example, and an inconsistent component name (`theLocalComponent` → `theLocalComponent2`).

## Editing and rebuilding

The PDF is generated from plain-text sources. Edit them and run `make`.

| File | What |
|---|---|
| `src/ja.md` | Translated body text. **Don't touch code blocks** (`make check` verifies them). |
| `figures/fig-NN.ja.txt` | Text drawn in figure NN. Line N corresponds to line N of `fig-NN.en.txt`: an identical line keeps the original, an empty line erases it. |
| `figures/layout/fig-NN.json` | Per-label overrides for size, weight, alignment and position; `"replace"` uses a ready-made image |
| `glossary.md` | Terminology |

```sh
make            # check → figures → build/25-06_ManagingDependencies_ja.pdf
make check      # code blocks unchanged, figure references complete
make review     # contact sheets of the figures (build/contact-N.png)
make release-assets
```

Requirements: Python 3, Google Chrome, CJK fonts, and Tesseract (only needed for re-extraction).
See the [localisation template](https://github.com/miyako/4d-technote-localisation-template) for the full workflow.

## Credits

- Original: Abir HSAINI, Technical Services Engineer, 4D Inc.
- Produced with [4d-technote-localisation-template](https://github.com/miyako/4d-technote-localisation-template) and GitHub Copilot.
