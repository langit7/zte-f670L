# zte-f670L
Indihome ONT ZTE F670L script

Versi Shell script
- Shell version belum bisa refresh ip karena adanya enkripsi saat apply config - harus porting dari js
- Untuk menjalankan shell version bisa menggunakan wsl di windows atau download https://mobaxterm.mobatek.net/download.html dengan menjalankan local terminal

Versi python
- Install python 3
- install selenium ( pip install selenium )
- tested di windows 11 dengan chrome versi 108

# decodef670l.py decode backup config 
Tested hanya versi firmware  ZTE F670L V9.0.11P1N40  / V9.0.11P1N15
python decodef670l.py config.bin --mac aa::bb:cc:dd:ff --serial ZTEGD0123456  config.xml
