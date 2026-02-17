# zmk-config-cool642tb (`zmk-v0.3`)

このブランチはフォーク元の構成をベースに、`zmk-v0.3` 向けに調整した設定です。

## 変更点

- ZMK を `v0.3` 系（`v0.3-branch`）に対応
- PMW3610 ドライバを `badjeff/zmk-pmw3610-driver`（`zmk-0.3`）へ変更
- PMW3610 の設定方式を、`.conf` 直指定ではなく listener 設定型へ変更

## 補足

- 詳細な依存モジュールは `config/west.yml` を参照
- フォーク元: https://github.com/telzo2000/zmk-config-cool642tb
