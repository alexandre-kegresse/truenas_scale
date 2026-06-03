# Serveur NAS sous Debian

Déploiement d'un serveur de stockage en réseau évolutif sous Debian, avec partages Samba, gestion des droits utilisateurs et configuration RAID.

---

## Objectifs

- Mettre en place un serveur NAS fonctionnel sur une base Debian
- Configurer des partages réseau accessibles depuis les postes clients
- Gérer les utilisateurs, les groupes et les droits d'accès
- Implémenter une configuration RAID pour la redondance des données

## Stack technique

| Composant | Rôle |
|---|---|
| Debian | Système d'exploitation serveur |
| Samba | Partages réseau (SMB/CIFS) |
| RAID logiciel | Redondance et tolérance aux pannes |
| mdadm | Gestion des volumes RAID sous Linux |

## Contenu du repo

```
nas_debian/
└── raid_config.pdf    # Documentation complète du déploiement
```

Le document PDF couvre l'ensemble du processus : installation du système, configuration des disques en RAID, mise en place de Samba, création des utilisateurs et attribution des droits.

## Concepts abordés

- Administration système Linux (Debian)
- Configuration réseau et partages SMB
- Gestion des utilisateurs et des groupes Unix
- Niveaux RAID (RAID 1, RAID 5) et leur mise en œuvre avec `mdadm`
- Droits Unix et ACL

## Contexte

Projet réalisé dans le cadre de la formation **Administrateur d'infrastructures sécurisées** à [La Plateforme_ (Cannes)](https://laplateforme.io).

---

*Alexandre Kegresse — [github.com/alexandre-kegresse](https://github.com/alexandre-kegresse)*
