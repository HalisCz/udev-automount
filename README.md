udev - pravidla pro automount
=============================

Popis
-----

 *   Automaticky připojí flashku nebo paměťovou kartu s libovolným souborovým systémem (ext, vfat, ntfs,…)
 *   Připojí do /media
 *   Umožnit rw pro non-root uživatele
 *   Automaticky odpojí a smaže adresář po fyzickém odpojení (__doporučuje se před fyzickém odpojení provést příkaz příkaz sync který zapíše změny z cache na disky__)

Instalace
---------

Konfigurační soubory stačí umístit do této složky: <code>/etc/udev/rules.d/</code>

a restartovat udev: <code>/etc/init.d/udev restart</code> 

Další informace
---------------

Další informace naleznete [zde](http://303rdlabs.maweb.eu/doku.php/programy#udev).
