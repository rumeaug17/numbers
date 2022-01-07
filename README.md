# numbers
Service de numeroteur (unicité et non prédictibilité sur un contexte donné)

Ce projet vise à construire un service léger, sûr et robuste pour distribuer des numéros uniques et non prédictibles aux clients, e nfonction du contexte.
Plusieurs numéroteurs doivent être proposés : numériques ou alpha numériques, avec une taille variable
L'unicité est garanti sur un contexte donné (identifiant de numéroteur)

Pour le moment rien n'est fait.
L'idée est de s'appuyer sur akka typed actor pour fournir ce service. 
