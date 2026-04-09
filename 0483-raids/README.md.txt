Nivells RAID
Introducció
Un sistema RAID és una manera d’utilitzar diversos discs durs alhora per millorar el rendiment o protegir les dades. Depenent del tipus de RAID, les dades es reparteixen o es copien entre els discs d’una forma diferent.
RAID 0
El RAID 0 el que fa és repartir les dades entre tots els discs. És a dir, els fitxers es divideixen i cada part va a un disc diferent. Això fa que vagi molt ràpid.
Necessita mínim 2 discs i s’aprofita tot l’espai. El problema és que no té cap protecció: si es trenca un disc, ho perds tot.
El bo és que és molt ràpid i no es perd espai. El dolent és que no és gens segur. Jo diria que s’utilitza més en coses on importa la velocitat, com jocs o editar vídeo.
RAID 1
El RAID 1 és bàsicament fer una còpia exacta d’un disc a un altre. O sigui, tot el que hi ha en un també està en l’altre.
També necessita 2 discs, però només pots utilitzar la meitat de l’espai, perquè l’altra meitat és la còpia.
Aquí el bo és la seguretat: si un disc falla, no passa res perquè tens l’altre. El dolent és que gastes el doble de discs.
S’utilitza quan tens dades importants i no les vols perdre.
RAID 5
El RAID 5 reparteix les dades entre els discs, però també guarda informació extra per si algun disc falla.
Necessita mínim 3 discs i perds l’espai d’un disc.
Pot fallar un disc i no es perden les dades, que està bastant bé. És com un punt mig entre seguretat i espai.
El problema és que escriure és més lent i recuperar dades costa una mica. S’utilitza molt en servidors o NAS.
RAID 10
El RAID 10 és una barreja de RAID 1 i RAID 0. Primer fa còpies i després reparteix les dades.
Necessita mínim 4 discs i només s’utilitza el 50% de l’espai.
Va molt ràpid i és bastant segur. Poden fallar alguns discs i seguir funcionant.
El dolent és que és car i no aprofites gaire espai. Es fa servir en coses importants com bases de dades.
RAID 50
El RAID 50 és com ajuntar RAID 5 i RAID 0. Es fan grups de RAID 5 i després es connecten.
Necessita mínim 6 discs. La capacitat depèn de com ho muntis, però sempre es perd una part.
Pot fallar un disc per grup, així que és més segur que RAID 5.
El problema és que és més complicat i car. S’utilitza en empreses o servidors grans.

Quadre resum comparatiu
Característica
RAID 0
RAID 1
RAID 5
RAID 10
RAID 50
Discs mínims
2
2
3
4
6
Capacitat útil
100%
50%
N-1
50%
N - grups
Tolerància fallades
0
1 disc
1 disc
Més de 1
més de 1
Rendiment
Molt alt
Alt
Mitjà
Molt alt
Alt
Seguretat
Cap
Alta
Mitjana
Alta
Alta
Cost
Baix
Alt
Mitjà
Alt
Alt
Complexitat
Baixa
Baixa
Mitjana
Mitjana
Alta

Fonts d’informació

Wikipedia:
https://en.wikipedia.org/wiki/RAID
Red Hat:
https://docs.redhat.com/es/documentation/red_hat_enterprise_linux/7/html/storage_administration_guide/s1-raid-levels
Seagate:
https://www.seagate.com/manuals/network-storage/business-storage-nas-os-4/raid-modes/
IBM:
https://www.ibm.com/docs/en/aix/7.2?topic=management-raid-overview

