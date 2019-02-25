# Lime-pcb
Répertoire de travail sur le Lime electric scooter


## References

Le scooter Lime est principalement basé sur un Ninebot ES2:\
https://shop.segway.com/ie-en/20/-ninebot-by-segway-kickscooter-es2

Neutron Holdings est le nom commercial de Lime, et en Belgique en tout cas, il sont en partenariat avec uber.\
ils font aussi des velos et des voitures à partager.\
Ils fabriquent eux memes leurs verrous intelligents, qh'ils fixent sur des vélos/ scooters fait par une autre companie.\
Nous avons donc quelques verrous sencé communiquer avec la machine pour l'empecher de fonctionner sous certaines conditions.\
Le nom du verrou qui nous intéresse est le LBCAT-S

**RESSOURCES IMPORTANTES!!**\
**répertoire de documents d'identification de la FCC\
+50 pdf de ressources.\
pinout etc\
https://fccid.io/2APB2LBCAT**

Selon les photos, le connecteur de debug est un connecteur "USB and debug UART"
et apparemment l'autre connecteur peut aussi etre utilisé en mode uart

Subredit: (forum discutions en tout genre à propos des scooters,\
pas spécialement le plus important mais ca peut toujours etre utile)\
https://www.reddit.com/r/LimeBike/

Site de hobbyistes dédié aux scooters,\
pas-mal de différents posts à propos du modèle qui nous intéresse,\
à priori beaucoup d'utilisateurs qui ont l'air encore confus à propos des détails du hardware/pinout.\
communauté dédiée, à creuser.
J'ai trouvé un utilisateur francophone qui, d'après ce que j'ai cru comprendre,\
à réussi a établir une connection sérielle avec la carte via "Single wire half-duplex UART 115200 8n1".\
J'ai envoyé un message, pas de retour pour l'instant.
https://scootertalk.org/viewtopic.php?t=962&start=10

Single wire half-duplex UART 115200 8n1\
Je comprends pas encore tout, à creuser.\
http://ficara.altervista.org/?p=4047

Article général sur les communications sérielles:\
https://learn.sparkfun.com/tutorials/serial-communication/all

Carte SIM par Twilio,\
à creuser, voici quelques liens pour devellopeurs:\
https://www.twilio.com/docs/wireless/tutorials/how-to-order-and-register-your-first-sim\
https://support.twilio.com/hc/en-us/articles/360000461127-Programmable-Wireless-SIM-Ordering-Activation-and-Statuses\
https://www.twilio.com/blog/2018/01/setting-up-a-twilio-programmable-wireless-sim-card-for-sms-and-phone-calls.html\
https://www.twilio.com/docs/wireless/api/sim

https://www.absunshine.com/en/parts/NM1482KSLAXCL-3B-NANYA-5064571

certains utilisateurs s'occupent de charger les scooters et sont payés entre 5-20 euros pour ca,
et etonnament, je vois partout qu'ils sont pas sensés etre dispos pendant la nuit apparemment  seulement entre 7 et 22 h, mais on dirait que ca a changé depuis
