atam - Tema para Moodle 3.1 
===============================================
*build:2016051900*

* Basado en 'Clean' 
* depende de "bootrsapbase" (Bootstrap 2.3)

Instrucciones para instalar

```bash
cd atam
cp atam.less ../bootstrapbase/less/
echo "@import atam.less" >> ../bootstrapbase/less/moodle.less
cd ../bootstrapbase
npm install
```

Generar CSS

```bash
grunt css
```

