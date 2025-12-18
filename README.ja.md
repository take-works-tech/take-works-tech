# 🧑‍💻 Take

---

## 🔗 ポートフォリオ・リンク集

- GitHub: [github.com/take-works-tech](https://github.com/take-works-tech)
- YouTube: [youtube.com/channel/UCwLIgx3f8fYu5EdJJEMhh7A](https://www.youtube.com/channel/UCwLIgx3f8fYu5EdJJEMhh7A)
- X: [@tzero3\_](https://twitter.com/tzero3_)

---

## 🛠 技術スタック

<table width="100%" style="table-layout: fixed;">
  <colgroup>
    <col style="width:50%;">
    <col style="width:50%;">
  </colgroup>
  <tr>
    <td valign="top">

### 🤖 AI・機械学習

| 技術分野           | スキル                                     |
| ------------------ | ------------------------------------------ |
| **フレームワーク** | TensorFlow, PyTorch, scikit-learn          |
| **生成 AI**        | Stable Diffusion, HuggingFace Transformers |
| **データ処理**     | Python, NumPy, Pandas                      |
| **可視化**         | Matplotlib                                 |

- **経験**:
  - 学習用合成データ生成（3D）
  - データ前処理・パイプライン自動化
  - 画像認識モデルの学習・チューニング
  - 機械学習を用いたデータ分析・予測

### 🌐 Web 開発

| 技術分野               | スキル                            |
| ---------------------- | --------------------------------- |
| **フロントエンド**     | TypeScript, JavaScript, HTML, CSS |
| **フレームワーク**     | React, Next.js                    |
| **バックエンド**       | Python, Django, PHP               |
| **API 開発**           | REST API 設計・実装               |
| **決済システム**       | Stripe 統合                       |
| **認証・セキュリティ** | 認証システム構築, API 管理        |

</td>
<td valign="top">

### 🎨 3D 技術

| 技術分野            | スキル                                                                  |
| ------------------- | ----------------------------------------------------------------------- |
| **プログラミング**  | C++, Python, Verse (Epic Games 開発言語)                                |
| **ゲームエンジン**  | Unreal Engine 5, UEFN, Unity                                            |
| **3D ソフトウェア** | Blender, Substance 3D Painter, ZBrush                                   |
| **3D 技術**         | 3D モデリング全般（テクスチャペインティング、リギング、アニメーション） |
| **特殊技術**        | G-code (3D プリンター制御)                                              |

### 🔩 工学・解析

| 技術分野           | スキル                       |
| ------------------ | ---------------------------- |
| **CAE 解析**       | ANSYS（構造解析）            |
| **CAD**            | Autodesk Inventor, Fusion360 |
| **プログラミング** | Python（解析自動化、可視化） |
| **可視化**         | Matplotlib                   |
| **学術背景**       | 機械工学修士                 |

### 📊 その他スキル

| 技術分野   | スキル            |
| ---------- | ----------------- |
| **Adobe**  | Photoshop         |
| **Office** | Excel, PowerPoint |

</td>
  </tr>
</table>

---

## 🚀 ポートフォリオの主なプロジェクト

### 🧠 ARC Prize 2025 ハイブリッドソルバー（ARC-AGI2 ベンチマーク向け）

**技術スタック**: Python, PyTorch, DSL（独自設計）, プログラム合成

- **ARC Prize 2025 (ARC-AGI2)** ベンチマーク向けのハイブリッドソルバー
- ルールベース DSL ランタイムとニューラルプログラム合成モデルを統合したエンドツーエンドワークフロー
- **DSL Runtime**: 完全カスタム DSL エンジン（パーサー、インタプリタ、エグゼキューター）を実装
  - 89+ の描画・変換コマンドを定義
  - 空間整合性、衝突、色管理を処理
- **Neural Inference (with Rule-based Assistance)**: ニューラルプログラム合成を主手法とし、ルールベースオブジェクトマッチングを補助として使用
  - ビームサーチと温度制御による候補生成
  - DSL ランタイムによる候補評価とスコアリング
- **Extended Dataset Generation Pipeline**: 確率的ルールによる合成データ生成
  - 難易度、グリッドサイズ、色分布の制約を考慮
  - DataPairs（DSL + グリッドペア）を圧縮形式で保存・ストリーミング
- **End-to-End CLI**: データ生成、学習、検証を統合したコマンドラインインターフェース
- 実験管理、ログ、可視化ツールを含む再現可能なワークフロー

📄 プロジェクト → [arc-agi2-arc2025](https://github.com/take-works-tech/arc-agi2-arc2025)

<img src="assets/ganerated_dataset.png" alt="ARC Prize 2025 generated dataset" style="max-width: 400px; height: auto;">

---

### 🌾 エッジ AI × 画像認識（IoT 向け）

**技術スタック**: Python, YOLOv8, ONNX, TensorRT, Jetson Nano, Raspberry Pi

- スマート農業向け果樹検出 AI システム
- ドローン／カメラからの映像をリアルタイムで解析
- 軽量モデル（YOLOv8-Nano）の学習・量子化・最適化
- エッジデバイス向けフォーマット変換・デプロイ

📄 プロジェクト → [Smart Agriculture Edge AI](https://github.com/take-works-tech/smart-agri-edge-ai)


<img src="assets/ImgReco.gif" alt="ImgReco" style="max-width: 400px; height: auto;">

---

### 🎭 3D フェイス合成データセット生成パイプライン

**技術スタック**: Python, Blender

- 機械学習向け多様な 3D フェイス画像自動生成システム
- 肌色、しわ、メイク、髪色などのバリエーション展開
- 属性ラベル付きデータセットの自動構築

📄 プロジェクト → [blender-face-dataset-generator](https://github.com/take-works-tech/3d-face-dataset-generator)

<img src="assets/geneFace.png" alt="geneFace" style="max-width: 400px; height: auto;">

---

### 🤖 AI 生成パイプライン

**技術スタック**: Python

- ゲーム用効果音パックの自動生成スクリプト
- 音声生成＋ビデオプレビューの自動生成機能

📄 プロジェクト → [soundpack-generator](https://github.com/take-works-tech/soundpack-generator)

🎞️ Video ↓

[![Demo SOUNDS](https://img.youtube.com/vi/qlhQRn4cVPc/0.jpg)](https://www.youtube.com/watch?v=qlhQRn4cVPc)

---

### 📝 WordPress 固定ページテンプレート（ゲーム情報）

**技術スタック**: PHP

- 独自 DB や IGDB API からゲーム情報を取得し一覧表示
- API 連携による自動更新機構
- WordPress 用カスタムテンプレート

📄 プロジェクト → [Cocoon Child – Game Detail](https://github.com/take-works-tech/cocoon-child-game-list)

<img src="assets/Php.png" alt="Php" style="max-width: 400px; height: auto;">

---

### 🌐 SaaS Web アプリケーション

| 領域           | フレームワーク                                   | 言語       |
| -------------- | ------------------------------------------------ | ---------- |
| フロントエンド | Node.js, Vite, React, Shadcn UI または Bootstrap | TypeScript |
| バックエンド   | Django REST Framework, PostgreSQL                | Python     |

- AI 音声生成サービスの完全な SaaS アプリケーション
- 認証システム・決済処理・API 管理・使用制限機能を実装
- エンドツーエンドの商用サービス構築

📄 プロジェクト → [AudioGen SaaS](https://github.com/take-works-tech/audiogen-saas-app)

<img src="assets/Saas.png" alt="Saas" style="max-width: 400px; height: auto;">

---

### 🎮 UEFN 個人ゲーム制作

**技術スタック**: Blender, Substance 3D Painter, Verse, UEFN

- 3D モデリング、アニメーション、プログラミングを一貫して担当
- Fortnite 向けのインタラクティブ体験を開発中

🎞️ Video ↓

[![Demo UEFN](https://img.youtube.com/vi/PbdRH_HzAqM/0.jpg)](https://www.youtube.com/watch?v=PbdRH_HzAqM)

<img src="assets/UEFN.gif" alt="UEFN" style="max-width: 400px; height: auto;">

---

### 🖼️ 画像認識モデル + 画像処理（C++, Python）

**技術スタック**: C++17, Python, pybind11, Eigen3, MediaPipe

- フェイシャルランドマークから UV マップを生成する独自ライブラリ
- C++と Python バインディングによる高性能処理
- MediaPipe Face Mesh + アフィン変換による 3D テクスチャ整列

📄 プロジェクト →

Python: [face_uvmap_py](https://github.com/take-works-tech/face_uvmap)

C++: [face_uvmap_cpp](https://github.com/take-works-tech/face_uvmap_cpp)

---

### 🔩 有限要素解析と形状最適化【非公開】

**技術スタック**: Python, ANSYS, Matplotlib

- 大学、大学院で研究。論文執筆。
- Python による解析の自動化と Matplotlib, Excel による可視化。


---

## 🎯 専門分野

### 得意領域

- **AI 開発**: 画像認識、生成 AI
- **Web 開発**: フルスタック開発、SaaS 構築
- **3D 技術**: モデリング全般
- **工学**: 機械工学
- **Python 開発**: 可視化、データ処理、自動化

---

## 📈 技術的強み

### 🤝 多領域シナジー

Web・3D・AI・工学を横断する知識

### 🌐 フルスタック Web 開発力

フロントエンド（React/Next.js）からバックエンド（Python/Django）、AI 統合まで一貫した開発が可能

### 💼 商用アプリケーション構築

認証、決済、API 管理を含む実用的な SaaS アプリケーション開発経験

### 🎨 3D・クリエイティブ技術

工学的バックグラウンドを活かした高度な 3D 処理と可視化技術

### ⚡ 高性能コンピューティング

C++による最適化と Python バインディングを組み合わせた効率的なソリューション開発

---

## 🛠️ 開発環境・ツール

**バージョン管理**: Git/GitHub
**AI・Web 開発**: VSCode, Cursor, Visual Studio
**3D 制作**: Blender, ZBrush, Substance 3D Painter
**ゲーム開発**: Unreal Engine 5, UEFN

---

## 📧 お問い合わせ

プロジェクトのご相談やコラボレーションをご希望の方は、X 経由でお気軽にご連絡ください。

- X: [@tzero3\_](https://twitter.com/tzero3_)

**専門領域**: 3D 技術 | AI 開発 | Web 開発 | Python 自動化
