# Universe-Paw-Studios - Pet Metropolis

Plan finalisé du projet avec une analyse rigoureuse pour passer en production.

## Objectif produit
**Pet Metropolis** est un city-builder/animal care game multiplateforme (Android/iOS en priorité) avec économie persistante, progression joueur et composantes sociales.

## Analyse de finalisation (prêt à l’emploi)

### 1) Gouvernance & livraison
- Branche `main` protégée (PR + checks obligatoires)
- Versioning de release (`v0.x.y`)
- Documentation légale publiée (privacy/terms)
- Responsable incidents sécurité identifié

### 2) Qualité technique minimale (Definition of Done)
- Build Android/iOS reproductible sur une version Unity LTS figée
- Aucun crash bloquant en session longue
- Sauvegarde cloud/reprise de session validée
- Économie serveur validée (aucune opération critique côté client uniquement)
- Instrumentation erreurs active (Crashlytics/Sentry équivalent)

### 3) Conformité & sécurité
- Flux mineur (`<13`) conforme COPPA/consentement
- Permissions minimales et justifiées
- Données sensibles non stockées en clair
- Limitation anti-abus (rate limit + validation serveur)

### 4) Exploitation live
- KPI de suivi activés: D1, D7, ARPDAU, crash-free rate
- Process patch critique en moins de 48h
- Backlog live-ops priorisé sur données réelles

## Go / No-Go (15 points)
- [ ] Build Android signé (AAB) validé
- [ ] Build iOS signé validé
- [ ] Tutoriel complet sans blocage
- [ ] Économie serveur validée
- [ ] IAP achat + restauration validés
- [ ] Auth + expiration token testées
- [ ] Sauvegarde cloud/reconnexion testées
- [ ] Cas offline/perte réseau gérés
- [ ] Age gate et flux mineur testés
- [ ] Confidentialité accessible in-app + store
- [ ] Localisation FR/EN validée minimum
- [ ] Crash-free rate acceptable en test interne
- [ ] Monitoring erreurs actif
- [ ] Workflow CI/CD principal opérationnel
- [ ] Plan de rollback prêt

## Template de notes de version
```md
# Pet Metropolis - vX.Y.Z
Date: YYYY-MM-DD

## Nouveautés
- ...

## Améliorations
- ...

## Corrections
- ...

## Technique
- Build Android: ...
- Build iOS: ...
- Migrations backend: oui/non

## Points de vigilance post-release
- KPI à surveiller: D1, crash-free rate, ARPDAU
```
