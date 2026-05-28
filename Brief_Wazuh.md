# Brief : "Déployer une surveillance de sécurité avec Wazuh et détecter des incidents"

Dans ce brief, les apprenants mettent en œuvre une plateforme de supervision de sécurité basée sur Wazuh afin de collecter, corréler et analyser des événements de sécurité issus d’une infrastructure hybride. Ils configurent des mécanismes IDS/IPS, réalisent des scénarios d’attaque simulés et analysent les alertes générées afin d’identifier des incidents de cybersécurité et proposer des mesures correctives.


## Contexte du projet

L’entreprise Let'sInnov poursuit la modernisation et la sécurisation de son infrastructure informatique. Après plusieurs alertes de sécurité liées à des connexions suspectes, des tentatives de brute force et des comportements anormaux observés sur certains serveurs, la direction souhaite améliorer ses capacités de supervision et de détection des incidents.

En tant qu’administrateur d’infrastructures sécurisées au sein de l’équipe SOC interne, vous êtes chargé de mettre en œuvre une solution centralisée de supervision de sécurité reposant sur un SIEM open-source. L’objectif est de collecter et corréler les journaux issus des équipements réseau, des serveurs Linux et Windows ainsi que des postes utilisateurs afin de détecter rapidement des comportements suspects.

Vous devrez installer et configurer Wazuh dans un environnement virtualisé, intégrer différentes sources de logs et mettre en œuvre plusieurs cas d’usage de détection. Vous serez également amené à déployer un IDS réseau, configurer des règles de surveillance et analyser les alertes générées lors de simulations d’attaques.

L’infrastructure devra permettre :

- la collecte centralisée des journaux
- la supervision des événements de sécurité
- la détection d’activités malveillantes
- l’analyse des alertes
- la documentation des incidents détectés
- l’amélioration continue des règles de détection

L’ensemble des opérations devra respecter les bonnes pratiques de cybersécurité et être documenté afin de permettre une exploitation par l’équipe informatique.

## Modalités pédagogiques

- Mission 1 : Installation et Configuration de Wazuh - Installer Wazuh dans un environnement simulé et configurer la collecte de logs

Quickstart (installation de Wazuh) : https://documentation.wazuh.com/current/quickstart.html

- Mission 2 : explorer les capacités de Wazuh à travers les différents uses cases proposés dans sa documentation officielle (à travers la réalisation de use-cases pratiques)

    - Intégration de l'IDS Suricata : https://documentation.wazuh.com/current/proof-of-concept-guide/integrate-network-ids-suricata.html
    - Surveillance de l'intégrité de répertoires/fichiers sensibles : https://documentation.wazuh.com/current/proof-of-concept-guide/poc-file-integrity-monitoring.html
    - Détection d'attaques bruteforce : https://documentation.wazuh.com/current/proof-of-concept-guide/detect-brute-force-attack.html
    - Détection de processus non autorisés : https://documentation.wazuh.com/current/proof-of-concept-guide/detect-unauthorized-processes-netcat.html
    - Détection de tentatives d'injection SQL : https://documentation.wazuh.com/current/proof-of-concept-guide/detect-web-attack-sql-injection.html
    - Détection de cheval de troie : https://documentation.wazuh.com/current/proof-of-concept-guide/poc-detect-trojan.html
    - Traitement de malware à travers l'intégration de VirusTotal : https://documentation.wazuh.com/current/proof-of-concept-guide/detect-remove-malware-virustotal.html
    - Détection de vulnérabilités : https://documentation.wazuh.com/current/proof-of-concept-guide/poc-vulnerability-detection.html
    - Détection de processus cachés par rootkit : https://documentation.wazuh.com/current/proof-of-concept-guide/poc-detect-hidden-process.html
    - Détection de commandes malveillantes : https://documentation.wazuh.com/current/proof-of-concept-guide/audit-commands-run-by-user.html
    - Détection d'attaques shellshock : https://documentation.wazuh.com/current/proof-of-concept-guide/detect-web-attack-shellshock.html

## Modalités d'évaluation

L’évaluation repose sur :
- la qualité du déploiement technique
- la capacité à centraliser et exploiter les logs
- la configuration correcte des mécanismes de détection
- l’analyse des alertes générées
- la capacité à identifier des incidents de sécurité
- la pertinence des actions correctives proposées
- la qualité de la documentation produite
Livrables
Page GitHub/Notion contenant les éléments suivants :
- Schéma de l’architecture de supervision
- Documentation d’installation et de configuration de Wazuh
- Captures d’écran du fonctionnement de la plateforme
- Documentation des règles de détection configurées
- Rapport d’analyse des incidents détectés
- Rapport de tests des différents cas d’usage
- Procédure de déploiement et d’exploitation
Critères de performance
- La plateforme Wazuh est installée et fonctionnelle
- Les agents remontent correctement les événements
- Les logs sont centralisés et exploitables
- Les mécanismes IDS/IPS sont opérationnels
- Les alertes sont correctement générées et interprétées
- Les scénarios d’attaque sont détectés
- Les incidents sont documentés de manière claire
- Les règles de détection sont adaptées au contexte
- Les propositions de remédiation sont pertinentes
- La documentation technique est structurée et exploitable

