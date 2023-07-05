$ history
    1  curl -o wilders.csv https://gist.githubusercontent.com/bhubr/bc3a21a0202109beeb31c4a677e0461b/raw/d8805eb82e8aabffab3b0163596c734f376617d0/wilders.csv
    2  cat wilders.csv
    3  cat wilders.csv |grep France,2019,PHP
    4  cat wilders.csv |grep France,2019,PHP > php_france_2019.csv
    5  cat wilders.csv |grep Toulouse > toulouse.csv
    6  cat toulouse.csv |grep JavaScript > javascript_toulouse.csv
    7  cat wilders.csv |grep Biarritz > biarritz.csv
    8  cat biarritz.csv |grep JavaScript > javascript_biarritz.csv
    9  cat javascript_toulouse.csv javascript_biarritz.csv | sort -u > javascript_biarritz_toulouse.csv
   10  cat javascript_toulouse.csv javascript_biarritz.csv | sort -u > javascript_biarritz_toulouse.csv
   11  history
