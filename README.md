# icingaweb2-SB-theme

Here you can find my patches to Icingaweb2 to make (some of) displayed items more compact - fit more of them on screen, sort of like old Icinga web.

Apply all patches with
patch -p0 < patchfile

/usr/share/icingaweb2/public/css/icinga:
base.less.patch
responsive.less.patch


/usr/share/icingaweb2/modules/monitoring/application/views/scripts/list
hosts.phtml.patch
services.phtml.patch



Patches were made for an older version of Icingaweb2 (~ from year 2020) but mostly apply in 2022.

When I find some more time to debug I'll make them apply 100% to the current vresion, but this is for the start, just to see the difference.

I don't claim that this is the best it can be, but there is imrovement. Look depends very much on screen resolution and scaling, so this looks fine on 
24" HD monitor, but not that fine on 14" HD laptop.
