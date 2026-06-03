# Serveur de stockage TrueNAS Scale

Mise en place et configuration d'un serveur de stockage en réseau sous TrueNAS Scale : création de volumes ZFS, partages réseau, gestion des accès et stratégie de sauvegarde.

---

## Objectifs

- Déployer TrueNAS Scale sur un serveur dédié
- Créer et gérer des volumes de stockage avec le système de fichiers ZFS
- Configurer des partages SMB/NFS accessibles en réseau
- Mettre en place une stratégie de sauvegarde et de snapshot

## Stack technique

| Composant | Rôle |
|---|---|
| TrueNAS Scale | OS spécialisé NAS (base Debian/Linux) |
| ZFS | Système de fichiers avancé avec intégrité des données |
| SMB / NFS | Protocoles de partage réseau |
| Snapshots ZFS | Sauvegardes incrémentales et restauration |

## Contenu du repo

```
truenas_scale/
└── truenas_scale.pdf    # Documentation complète du déploiement
```

Le document PDF détaille l'installation, la configuration des pools ZFS, la création des datasets, la mise en place des partages réseau et la planification des snapshots.

## Concepts abordés

- Système de fichiers ZFS : pools, datasets, intégrité des données (checksums)
- Niveaux RAID ZFS (RAIDZ, RAIDZ2)
- Gestion des partages réseau (SMB pour Windows, NFS pour Linux)
- Politique de snapshots et stratégie de rétention
- Interface d'administration web TrueNAS

## Différences avec le NAS Debian

Ce projet complète le [serveur NAS Debian](https://github.com/alexandre-kegresse/nas_debian) en adoptant une approche clé-en-main via TrueNAS Scale, permettant une comparaison des deux approches : manuelle vs solution intégrée.

## Contexte

Projet réalisé dans le cadre de la formation **Administrateur d'infrastructures sécurisées** à [La Plateforme_ (Cannes)](https://laplateforme.io).

---

*Alexandre Kegresse — [github.com/alexandre-kegresse](https://github.com/alexandre-kegresse)*
