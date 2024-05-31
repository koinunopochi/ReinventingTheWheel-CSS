# ReinventingTheWheel CSS - Utility Classes

ReinventingTheWheel CSSには、様々なユーティリティクラスが用意されており、HTMLでクラス名を追加するだけで簡単にスタイルを適用できます。

## Cyber Dream関連のユーティリティクラス

### テキストの色
- `.text-cyber-green`: テキストをサイバーグリーンにします。
- `.text-cyber-blue`: テキストをサイバーブルーにします。
- `.text-cyber-pink`: テキストをサイバーピンクにします。

### 背景色
- `.bg-cyber-green`: 背景色をサイバーグリーンにします。
- `.bg-cyber-blue`: 背景色をサイバーブルーにします。
- `.bg-cyber-pink`: 背景色をサイバーピンクにします。
- `.bg-cyber-black`: 背景色をサイバーブラックにします。

### ボーダー
- `.border-neon`: ネオンカラーのボーダーを適用します。
- `.border-neon-thick`: 太いネオンカラーのボーダーを適用します。

### ボタン
- `.btn`: サイバーチックなボタンのスタイルを適用します。

詳細な使用例については、`cyber-dream-showcase.html`を参照してください。

## 共通のユーティリティクラス

### マージンとパディング
- `.m-1`, `.m-2`, `.m-3`: それぞれ0.5rem、1rem、1.5remのマージンを適用します。
- `.p-1`, `.p-2`, `.p-3`: それぞれ0.5rem、1rem、1.5remのパディングを適用します。
- レスポンシブマージン: `.m-md-1`, `.m-md-2`, `.m-md-3`
- レスポンシブパディング: `.p-md-1`, `.p-md-2`, `.p-md-3`

### 幅と高さ
- `.w-full`: 要素の幅を100%に設定します。
- `.w-40`: 要素の幅を10remに設定します。
- `.h-full`: 要素の高さを100%に設定します。

### テキストの折り返し、オーバーフロー、省略記号
- `.whitespace-nowrap`: 要素内のテキストを折り返さず、1行で表示します。
- `.overflow-hidden`: 要素のオーバーフローを非表示にします。
- `.overflow-auto`: 要素のオーバーフローをスクロール可能にします。
- `.text-ellipsis`: オーバーフローしたテキストを省略記号で切り詰めます。

### テキストアラインメント
- `.text-left`: テキストを左寄せにします。
- `.text-center`: テキストを中央寄せにします。
- `.text-right`: テキストを右寄せにします。

### フォントの太さとサイズ
- `.font-normal`: フォントの太さを通常に設定します。
- `.font-bold`: フォントの太さを太字に設定します。
- `.text-xs`, `.text-sm`, `.text-base`, `.text-lg`, `.text-xl`, `.text-2xl`: フォントサイズを設定します。

### 要素の表示方法
- `.block`: 要素をブロックレベル要素として表示します。
- `.inline-block`: 要素をインラインブロック要素として表示します。
- `.inline`: 要素をインライン要素として表示します。

### 垂直方向の配置
- `.align-baseline`: 要素を基準線に合わせて配置します。
- `.align-top`: 要素を上端に合わせて配置します。
- `.align-middle`: 要素を中央に合わせて配置します。
- `.align-bottom`: 要素を下端に合わせて配置します。

### 角の丸み
- `.rounded`: 要素の角を少し丸くします。
- `.rounded-md`: 要素の角を中程度に丸くします。
- `.rounded-lg`: 要素の角を大きく丸くします。
- `.rounded-full`: 要素の角を完全に丸くします。

### 不透明度
- `.opacity-0`: 要素を完全に透明にします。
- `.opacity-25`: 要素の不透明度を25%に設定します。
- `.opacity-50`: 要素の不透明度を50%に設定します。
- `.opacity-75`: 要素の不透明度を75%に設定します。
- `.opacity-100`: 要素を完全に不透明にします。

### その他のユーティリティクラス
- Flexbox: `.flex`, `.flex-col`, `.flex-wrap`, `.justify-*`, `.items-*`
  - レスポンシブFlexbox: `.flex-md-row`, `.flex-md-col`, `.justify-md-*`, `.items-md-*`
- ポジショニング: `.relative`, `.absolute`, `.fixed`, `.top-0`, `.right-0`, `.bottom-0`, `.left-0`
- z-index: `.z-0`, `.z-10`, `.z-20`