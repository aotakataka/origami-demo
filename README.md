# 折り紙の折り順自動生成 — デモページ

逆方向探索による折り紙の折り順自動生成のデモページです。
展開図から完成形までの折り順を自動で生成し、各作品の**展開図**・**完成形**・**折り順**・**折りたたみアニメーション**を確認できます。

## 対応作品

| 作品 | 展開図 | 完成形 | 折り順 | アニメーション |
|------|--------|--------|--------|----------------|
| 鶴 | `crease_patterns/crane.png` | `finished/crane_{front,back}.png` | `steps/crane_fold.png` | `animations/crane.gif` |
| 兜 | `crease_patterns/armet.png` | `finished/armet_{front,back}.png` | `steps/armet_fold.png` | `animations/armet.gif` |
| にわとり | `crease_patterns/chicken.png` | `finished/chicken_{front,back}.png` | `steps/chicken_fold.png` | `animations/chicken.gif` |
| カニ | `crease_patterns/crab.png` | `finished/crab_{front,back}.png` | `steps/crab_fold.png` | `animations/crab.gif` |
| 犬の顔 | `crease_patterns/dogface.png` | `finished/dogface_{front,back}.png` | `steps/dogface_fold.png` | `animations/dogface.gif` |
| 花 | `crease_patterns/flower.png` | `finished/flower_{front,back}.png` | `steps/flower_fold.png` | `animations/flower.gif` |
| 家 | `crease_patterns/house.png` | `finished/house_{front,back}.png` | `steps/house_fold.png` | `animations/house.gif` |
| セミ | `crease_patterns/semi.png` | `finished/semi_{front,back}.png` | `steps/semi_fold.png` | `animations/semi.gif` |
| 風車 | `crease_patterns/windmill.png` | `finished/windmill_{front,back}.png` | `steps/windmill_fold.png` | `animations/windmill.gif` |

## ディレクトリ構成

```
origami-demo/
├── index.html            # デモページ本体
├── crease_patterns/      # 各作品の展開図 (PNG)
├── finished/             # 各作品の完成形 (表面 _front / 裏面 _back, PNG)
├── steps/                # 各作品の折り順一覧画像 (PNG)
└── animations/           # 折りたたみアニメーション (GIF)
```

## デモページ

https://aotakataka.github.io/origami-demo/

## 使い方

デモページをブラウザで開くと、完成形のサムネイル一覧が表示されます。作品を選ぶと、展開図・完成形・折り順・アニメーションを確認できます。

## 凡例

- **白** — 表面
- **緑** — 裏面
- **赤の破線** — 折り線
- **赤の実線** — 山折り（展開図）
- **青の実線** — 谷折り（展開図）
