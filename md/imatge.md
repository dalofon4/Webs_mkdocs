Manera de funcionament :

* *device-image:* Selecciona aquesta opció per a generar una imatge o per a restaurar una imatge.
* *Device-device:* S'utilitza per a clonar un disc o partició directament a un altre disc o partició.
 *Directori d'on llegir o on escriure la imatge:*
 

 * *local_dev:*  La imatge es farà en un disc local. Lògicament, com en tot linux,serà necessari muntar el dispositiu en el qual està o deixarem la imatge. No es
pot guardar la imatge en una de les particions que volem ficar dins de la imatge.
  * *ssh_server:* La imatge es lllegirao escriurà en una unitat de xarxa ssh.
  * *Samba_server:* La imatge es llegirà o escriurà en una carpeta compartida Samba (normalment Windows).
  * *Enter_shell:* Et permet entrar en la manera de comandos i muntar el teu mateix la unitat escrivint els comandos necessari.
  

  Escollim Device-image:

![w:900px h:300px](imatges/imatge_7.png)


La imatge es farà a un disc local:


![w:900px h:300px](imatges/imatge_8.png)

!!! warning

**Ctrl+c** per tornar a la pantalla gràfica.


Lloc en el qual es guardarà la imatge:

!!! danger

Triarem el disc creat, no agafarem el disc del nostre Sistema Operatiu.


![w:900px h:300px](imatges/imatge_9.png)



![w:900px h:300px](imatges/imatge_10.png)



Acceptem manera principiant:

![w:900px h:300px](imatges/imatge_11.png)


Seleccionem savedisk per a realitzar una imatge d'un disc complet:


![w:900px h:300px](imatges/imatge_12.png)


Seleccionem el nom de la imatge. En un entorn de producció, és habitual incloure la data com a part del nom de la imatge. És obligatori que el nom de la imatge guarde relació amb el sistema que s'estiga guardant. Aquests són alguns exemples:

  * 20140325-ServNexun
  * 20140325-WebServer-
  * 20140325-Proxy-AntesDeActualizacion

![w:900px h:200px](imatges/imatge_13.png)



Com que hem seleccionat que volem fer una imatge d'un disc complet,en la següent pantalla, ens mostrarà els discos que estan connectats en l'equip perquè  triem els discos que volem incloure en la imatge. 


Seleccionem l'únic disc.

![w:900px h:200px](imatges/imatge_14.png)



Comprovació després d'acabada la imatge. Allarga el procés, però es garanteix que s'ha realitzat correctament i que es pot restaurar.


![w:900px h:400px](imatges/imatge_15.png)



![w:900px h:300px](imatges/imatge_16.png)


![w:900px h:200px](imatges/imatge_17.png)



Confirmació que volem continuar amb tot el procés del qual se'ns informa...


![w:900px h:300px](imatges/imatge_18.png)



Finestra que ens indica el temps del procés de clonació.


![](imatges/imatge_19.png)


Una vegada finalitzat el procés reiniciarà el Sistema Operatiu com li hem indicat, eliminarem les 3 carpetes creades al primer punt a l’escriptori i de nou canviarem el fons de pantalla al que teníem inicialment i apagarem el Sistema Operatiu.
