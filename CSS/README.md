Simple CSS tweak that changes to default coloring of "OK" Hosts in the Hostoverview to the default CheckMK CI colors

Replace the themes.css in  ```/omd/sites/monitoring/share/check_mk/web/htdocs/themes/modern-dark``` and reload the Dashboard
![preview of new Hostoverview](https://i.imgur.com/XuTCtow.png)

This can be implemented as a new theme, however there seem to be some dependencies outside of CSS that will change the legends on graphs to black and make them illegible
