# How to run

ganti /dev/sdb menjadi disk yang akan di recovery

##foremost

```bash
sudo apt install foremost

foremost -v \
  -t jpg,doc,pdf \
  -i /dev/sdb \
  -o /work/hasil-foremost
```

##scalpel

```bash
sudo apt install

scalpel /dev/sdb \
  -c /etc/scalpel/scalpel.conf \
  -o /work/scalpel-hasil \
  -v
```

##photorec

```bash
apt install testdisk
```
