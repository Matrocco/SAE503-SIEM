- Réaliser une maquette comportant un SIEM (e.g. Wazuh ou autre), une Ubuntu, une Windows, un pare feu (PF) (e.g. pfSense ou autre).
- Obtenir sur le SIEM des informations intéressantes de supervisions de chacun de ces équipements (Ubuntu, Windows, PF)
- Réaliser une attaque sur un service vulnérable depuis une Kali.
- Rédiger un write-up technique clair, illustré et reproductible comprenant vos exemples de supervisions pour chaque équipement depuis le SIEM, ainsi que le scénario d'attaque et sa preuve de détection (captures d'écran des alertes SIEM).
- Au cas où (à vérifier si votre SIEM ne le fait pas déjà), vous pouvez ajouter un Suricata (IDS/IPS réseau) au SIEM pour enrichir la détection.

| Rôle | Système | Fonction dans la maquette |
| :--- | :--- | :--- |
| Pare-feu / routeur | pfSense (ou autre) | Filtrage, journalisation du trafic |
| Serveur SIEM | Ubuntu (Server) | Collecte, indexation et visualisation des logs |
| Poste / serveur Linux | Ubuntu | Cible supervisée (agent SIEM installé) |
| Poste / serveur Windows | Windows 10/11 ou Server | Cible supervisée (agent SIEM + Sysmon) |
```eof
