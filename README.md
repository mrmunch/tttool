# Piraten Schatzsuche

Zum Erstellen der .gme Dateien wird das Programm [tttool](https://github.com/entropia/tip-toi-reveng) benötigt.

```sh
cd $TTTOOL_DIR
tttool assemble schatzsuche/schatzsuche_rot.yaml
tttool oid-codes schatzsuche/schatzsuche_rot.yaml
tttool assemble schatzsuche/schatzsuche_blau.yaml
tttool oid-codes schatzsuche/schatzsuche_blau.yaml
```