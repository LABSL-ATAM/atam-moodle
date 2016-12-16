atam - Tema para Moodle 3.1 (buiild:2016051900)
===============================================
Basado en 'Clean' 
depende de "bootrsapbase" (Bootstrap 2.3)

Instrucciones para instalar

'''bash
cp atam.less ../bootstrapbase/less/
echo "@import atam.less" >> ../bootstrapbase/less/moodle.less
cd ../bootstrapbase
npm install
'''

Generar CSS (bootsrap 2.3)
` grunt css`

