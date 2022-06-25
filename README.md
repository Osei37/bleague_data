# B.LEAGUE Data

B.LEAGUE のデータです．現在はボックスコアのみです．PLAY BY PLAY データも追加予定です．

## 注意事項

B.LEAGUE 公式ではありません．データの正しさは保証できません．仕様を大きく変更する可能性があります．

## Box Score

各試合について，各チームのスタッツと試合情報（試合ID，日付，アリーナ名，観客動員数，審判等）が含まれています．期間はB.LEAGUE開幕から2021-22シーズンまでです（2022年6月25日現在）．ディレクトリの構造は次の通りです．

<pre>
シーズン  
    |- ALLSTARGAME  
    |  
    |- B1 ┬ - REGULAR  
    |     | - CHAMPIONSHIP  
    |     └ - REMAINING PLAYOFFS  
    |  
    |- B2 ┬ - REGULAR  
    |     └ - PLAYOFFS  
    |  
    |- B3 ┬ - FIRST STAGE  
    |     | - FINAL STAGE  
    |     └ - REGURA SEASON  
    |  
    |- 入れ替え戦 ┬ - B1_B2  
    |            └ - B2_B3  
    |  
    └- others ┬ PRESEASON  
              └ - アーリーカップ  
</pre>
