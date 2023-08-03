Simple CSS tweak that changes to default coloring of "OK" Hosts in the Hostoverview to the default CheckMK CI colors

Place the green_host_ok.css in  ```/omd/sites/monitoring/share/check_mk/web/css``` and restart OMD
![preview of new Hostoverview](https://i.imgur.com/XuTCtow.png)

This could be implemented as a new theme, however there seem to be some dependencies outside of CSS that will change the legends on graphs to black and make them illegible

Im currently looking into moving this into ```/omd/sites/monitoring/local``` to make it persistent
