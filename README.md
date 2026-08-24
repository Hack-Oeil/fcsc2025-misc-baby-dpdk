# FCSC 2025 Baby DPDK

Mais où sont passés mes paquets réseau ?

Dans cette épreuve nous vous proposons de jouer avec DPDK.

Saurez-vous retrouver le contenu des paquets réseau reçus sur l’interface réseau ?

**Remarques :**

- Afin de disposer d’un `Ctrl-C` fonctionnel, vous pourrez utiliser `stty -cooked -echo` sur votre terminal après avoir mis en tâche de fond votre connexion au challenge faite avec `nc`.
- Pour reproduire l’épreuve localement :  Décompressez l’archive avec `tar xf babydpdk.tar.xz`. Lancez le conteneur Docker avec `docker compose up --build`. Connectez-vous à l’épreuve locale avec `nc localhost 4000`.
- Pour vous connecter à la machine, utilisez le mot de passe “user”

Auteur : gte

Origine : [Baby DPDK](https://hackropole.fr/fr/challenges/misc/fcsc2025-misc-baby-dpdk/)


## Challenge
[files/babydpdk.tar.xz](files/babydpdk.tar.xz)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-misc-baby-dpdk.git

> cd fcsc2025-misc-baby-dpdk

> docker compose up

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/misc/fcsc2025-misc-baby-dpdk/
