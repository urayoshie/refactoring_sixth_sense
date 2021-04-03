# Sixth Sense

## description

主人公が直感で A または B の道を選び、先へ進みます。

道中で敵に出会ってダメージを受けたり、
アイテムで HP を上げてゴールを目指します。

1000 以上の HP を目指して直感で道を選びましょう。

## file structure

このアプリは以下のファイルで構成されています。
 データ名 | ファイル内容 
--- | ---
main.rb | 実行プログラム
character.rb | 主人公のデータ、主人公のHPの計算
player.rb | プレイヤーの行動の処理(主人公の選択と、A 道 または B 道の選択)
message.rb | ゲーム内で表示される全メッセージの内容
waylist.rb | aまたはbのデータからランダムに１つのデータを取得
way_list.csv | A 道と B 道のデータ

## how to play

- ゲーム開始準備

```

git clone https://github.com/urayoshie/refactoring_sixth_sense.git
cd refactoring_sixth_sense
ruby main.rb

```

- ゲーム準備後のプレイ方法

```

(1) 1, 2, 3 より主人公を選択。
(2) 直感のみで A または B の道を選択。
(3) 主人公の HP が 1000 以上になればゲームクリア。
(4) 主人公の HP が 0 になるとゲームオーバー。

```

## ruby --version

Ruby 2.7.2
