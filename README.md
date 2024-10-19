# rust-atmega328p-template

AVR マイコンの Rust プロジェクトを素早く立ち上げるための [`cargo-generate`] テンプレートです。

[`cargo-generate`] template for jumpstarting projects on common AVR
microcontroller.

## Usage 使い方

[`cargo-generate`] をインストールしていなければ、次のコマンドでインストールしてください。

If you don't have them already, install [`cargo-generate`]:

```bash
cargo install cargo-generate
```

そして、この GitHub リポジトリをテンプレートに、プロジェクトを作成します。

Then instantiate this template:

```bash
cargo generate --git https://github.com/BerandaMegane/rust-atmega-template.git
```

and see a blinky flashed to your board!

[`cargo-generate`]: https://github.com/cargo-generate/cargo-generate

## License

この GitHub リポジトリ自体はパブリックドメインです。

