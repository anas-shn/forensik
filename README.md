# How to run

ganti /dev/sdb menjadi disk yang akan di recovery

##foremost

```bash
#install
sudo apt install foremost

#run
foremost -v \
  -t jpg,doc,pdf \
  -i /dev/sdb \
  -o /work/hasil-foremost
```

##scalpel

```bash
#install
sudo apt install

#run
scalpel /dev/sdb \
  -c /etc/scalpel/scalpel.conf \
  -o /work/scalpel-hasil \
  -v
```

##photorec

```bash
#install
apt install testdisk

#jalankan
photorec
```
