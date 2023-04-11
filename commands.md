List up ip address:
```bash
hostname -I | awk -v RS='[\ \n]' '//{print}'
```

Get full path of the file:
```bash
readlink -f file.txt
```

Grep specific file type recursively:
```bash
grep -nr --include="*.py" text
```
