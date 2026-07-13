# 折り紙の折り順自動生成 — デモページ

逆方向探索による折り紙の折り順自動生成のデモページです。
展開図から完成形までの折り順を自動で生成し、各作品の**展開図**・**折り順**・**折りたたみアニメーション**を確認できます。

## 対応作品

| 作品 | 展開図 | 折り順 | アニメーション |
|------|--------|--------|----------------|
| 鶴 | `crease_patterns/crane.png` | `steps/crane_fold.png` | `animations/crane.gif` |
| 兜 | `crease_patterns/armet.png` | `steps/armet_fold.png` | `animations/armet.gif` |
| にわとり | `crease_patterns/chicken.png` | `steps/chicken_fold.png` | `animations/chicken.gif` |
| カニ | `crease_patterns/crab.png` | `steps/crab_fold.png` | `animations/crab.gif` |
| 犬の顔 | `crease_patterns/dogface.png` | `steps/dogface_fold.png` | `animations/dogface.gif` |
| 花 | `crease_patterns/flower.png` | `steps/flower_fold.png` | `animations/flower.gif` |
| 家 | `crease_patterns/house.png` | `steps/house_fold.png` | `animations/house.gif` |
| セミ | `crease_patterns/semi.png` | `steps/semi_fold.png` | `animations/semi.gif` |
| 風車 | `crease_patterns/windmill.png` | `steps/windmill_fold.png` | `animations/windmill.gif` |

## ディレクトリ構成

```
origami-demo/
├── index.html            # デモページ本体
├── crease_patterns/      # 各作品の展開図 (PNG)
├── steps/                # 各作品の折り順一覧画像 (PNG)
└── animations/           # 折りたたみアニメーション (GIF)
```

## 使い方

`index.html` をブラウザで開くと、全作品の展開図・折り順・アニメーションを一覧で確認できます。

## 折り順の生成方法

折り順の画像やアニメーションは、リポジトリルートの `howtofold.py` で生成されています。

```
python howtofold.py <展開図(.opx) or 完成形(.fold)ファイルのパス>
```

## 凡例

- **白** — 表面
- **緑** — 裏面
- **赤の破線** — 折り線
