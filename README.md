# PyTorch-Model-Optimization

PyTorch のモデル最適化リポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── 8_1_profiler_jp.ipynb
│   ├── 8_2_hyperparameter_tuning_tutorial_jp.ipynb
│   ├── 8_3_pruning_tutorial_jp.ipynb
│   ├── 8_4_beta_dynamic_quantization_on_an_lstm_word_language_model_jp.ipynb
│   └── 8_5_bata_quantized_transfer_learning_for_computer_vision_tutorial_jp.ipynb
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/PyTroch-Model-Optimization）

```
cd Desktop/PyTroch-Model-Optimization
```

- Dockerによる環境構築（フォルダをマウント：Desktop/PyTroch-Model-Optimization）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
