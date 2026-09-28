# S2J Content Dates Service - CHANGELOG

## unreleased

## 0.0.1 - 2026-09-29

### Added

* サービス仕様ドラフトを `docs_mod/service_spec.md` に記載 (算出とプラグインの境界、コンテンツタイプ表、未決事項)
* `docs_mod/specs.md` からサービス仕様ドラフトへの参照を追加

### Changed

* textlint の許容語に `kis-wordpress` と旧名 `s2j-post-dates-service` / `post-dates-service` を追加
* npm プロジェクト名を `s2j-content-dates-service` に変更
* Composer ライブラリ名を `s2j/content-dates-service` に変更
* 表示名を `S2J Content Dates Service` に変更
* オートロード名前空間を `S2J\ContentDatesService\` に変更

## 0.0.1 - 2026-09-28

### Added

* `composer.json` を追加 (v0.0.1、`s2j/post-dates-service`)。PHP `>=8.0`、オートロードは `S2J\PostDatesService\` → `src/`
* 開発用依存に `phpunit/phpunit` ^13.1、`phpstan/phpstan` ^2.1、`squizlabs/php_codesniffer` ^4.0を追加

* `package.json` を追加 (v0.0.1)。説明は公開日・更新日の算出と表示ロジック (WordPress 非依存)
* ドキュメント lint を追加 (`@s2j/docs-linter` ^1.0.25、`npm run lint:docs`)
* npm v12以降向けに `.npmrc` の `allow-git=all` と `package.json` の `allowScripts` を追加

### Changed

* README の見出しを `S2J Post Dates Service` に変更
* `.gitignore` を Composer、Node、テスト成果物向けに拡張
