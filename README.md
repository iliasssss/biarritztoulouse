

cat wilders.csv 
pc@pc-VirtualBox:~/Bureau$ grep "France,2019,PHP" < wilders.csv | wc -l > php_france_2019.csv
pc@pc-VirtualBox:~/Bureau$ grep JavaScript wilders.csv > btjava.csv
pc@pc-VirtualBox:~/Bureau$ grep Toulouse btjava.csv > tjava.csv
pc@pc-VirtualBox:~/Bureau$ grep Biarritz btjava.csv > bjava.csv
pc@pc-VirtualBox:~/Bureau$ cat tjava.csv bjava.csv > javascript_biarritz_toulouse.csv
pc@pc-VirtualBox:~/Bureau$ history | tail -n 50 > history.txt

