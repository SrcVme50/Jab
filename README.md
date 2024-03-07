# Jab

https://github.com/miko550/CVE-2023-32315

grep -oP '<value>\K[^<]+@jab.htb(?=</value>)' output.log | sed 's/@jab.htb//g' | sort | uniq > output_filtered.lst
