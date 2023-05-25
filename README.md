# Apache 2

Voici les codes permettant la création automatique des **"virtual host"** de **Apache**

---

## Pré-requis

Pour l'installation suivante, il faut avoir une machine sous **Debian 11 (minimum)**, avec les modules suivants :
- python
```sh
sudo apt install python
```
- ansible
```sh
sudo apt install ansible
```

## Execution

Utiliser la commande suivante sur la machine où installer **Apache2**

```sh
sudo ansible-playbook apache.yml
```

## Résultats
Les hosts suivants sont disponibles:
- axel.com
- ww.google.com
- www.git.fr
