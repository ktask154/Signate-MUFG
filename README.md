# Signate MUFG

## 課題
クラウドファンディングプロジェクトの調達目標金額やアピール文章といった定量及び定性データを元に分析モデルを構築して、資金調達の成否の予測する。
2値の分類タスク。[link](https://signate.jp/competitions/754)

### 評価関数
F1score

</br>

## Models
- deberta-v3-base
- deberta-v3-large
- deberta-xlarge
- bart-large-mnli

</br>

## Work
- 


</br>

## Result
13 / 145 位
</br>
cv : 0.8305
</br>
public LB : 0.8328
</br>
private LB : 0.8374
</br>

## 注意
- 最終提出で使ったノートブックは残っていないものが多いがモデルが違うだけで形は同じものがほとんど
- 最終提出ノートブックはexp106（提出時間とcolabの実行時間の関係で実行の途中でエラーが出ているがそのまま提出→再現性は後で確認済み)
- train inference フォルダ以外のノートブックは「ensemble weight search.ipynb」以外つかっていない
