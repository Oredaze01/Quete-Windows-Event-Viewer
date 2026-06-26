# Quete-Windows-Event-Viewer

**Configuration de ta vue personnalisée :**

1. Niveaux à surveiller

- Critique (1)
- Erreur (2)
- Avertissement (3)
- Information (4) - Pour les démarrages/arrêts


![[Windows-Event-Viewer-1.png]](


2. Sources d'événements à inclure

- DNS-Server-Service: Pour les opérations du serveur DNS
    
- DNS Client Events: Pour les événements côté client

![[Windows-Event-Viewer-2.png]](

3. Événements critiques (ID principaux)

- 2: Démarrage du serveur DNS
- 4: Arrêt du serveur DNS
- 409: Erreur de résolution de nom
- 501-502: Échec de chargement de zone
- 6001-6002: Problèmes de réplication DNS

![[Windows-Event-Viewer-3.png]](

