# Universe-Paw-Studios
Game around the world about animals and built a city for them
Parfait ✅  
Voici la **checklist finale** pour sortir **Pet Metropolis** proprement sur Android/iOS (et préparer PC/tablette).

## 1) Repo & delivery
- [ ] `main` protégé (PR obligatoire + checks CI)
- [ ] `develop` actif
- [ ] README clair + roadmap
- [ ] LICENSE MIT
- [ ] `docs/PRIVACY_POLICY.md` + `docs/TERMS_OF_SERVICE.md`
- [ ] `SECURITY.md` + contact sécurité
- [ ] Releases taggées (`v0.1.0-alpha`, etc.)

## 2) Build Unity
- [ ] Unity LTS fixé (même version pour toute l’équipe)
- [ ] Android build OK (AAB signé)
- [ ] iOS build OK (archive Xcode signée)
- [ ] FPS stable (>=30 low-end, 60 mid/high)
- [ ] Mémoire maîtrisée (pas de crash long session)
- [ ] Temps de chargement acceptable

## 3) Backend (PlayFab/Firebase/API)
- [ ] Auth sécurisée (tokens, refresh, expiration)
- [ ] Validation serveur de toute économie (adoption, achats, récompenses)
- [ ] Anti-triche basique (rate limits, sanity checks)
- [ ] Sauvegarde cloud + reprise session
- [ ] Logs erreurs + alertes (Crashlytics/Sentry)
- [ ] Environnements séparés (dev/staging/prod)

## 4) IAP & monétisation (conforme stores)
- [ ] Produits IAP configurés (consommables/non-consommables)
- [ ] Restauration d’achats fonctionnelle (iOS/Android)
- [ ] Aucun pay-to-win bloquant
- [ ] Taux/récompenses équilibrés
- [ ] Écran prix transparent + devise locale
- [ ] Test sandbox Apple/Google validé

## 5) COPPA / vie privée / légal
- [ ] Âge demandé au 1er lancement (age gate)
- [ ] Si <13: flux enfant adapté (pas de collecte non autorisée)
- [ ] Consentement parental si requis
- [ ] Politique de confidentialité accessible in-app + store
- [ ] Suppression compte/données possible
- [ ] SDK publicitaires/analytics configurés selon âge & consentement

## 6) Localisation (10 langues)
- [ ] FR/EN/ES/DE/IT/PT/JA/ZH/RU/KO présentes
- [ ] Fallback langue par défaut fiable (EN ou FR)
- [ ] Textes UI sans troncature
- [ ] Formats date/heure/devise corrects par région
- [ ] Descriptions stores localisées au moins FR+EN

## 7) QA gameplay
- [ ] Tutoriel complet de bout en bout
- [ ] Progression niveaux sans blocage
- [ ] Missions journalières reset correct
- [ ] Déblocages aléatoires d’animaux cohérents
- [ ] Cas négatifs testés (manque d’argent, offline, perte connexion)
- [ ] Soin animal : sanctions/conséquences fonctionnent sans bug

## 8) Social & online
- [ ] Ajout d’amis fonctionne
- [ ] Visite de villes externes stable
- [ ] Sync données multi-appareils OK
- [ ] Modération basique (noms animaux/ville filtrés)
- [ ] Signalement contenu utilisateur (si UGC)

## 9) CI/CD
- [ ] Workflow GitHub Actions build Android/iOS
- [ ] Tests auto (backend + unit tests Unity si possible)
- [ ] Lint/format enforced
- [ ] Artifacts de build conservés
- [ ] Versioning auto (build number)

## 10) Pré-publication Store
- [ ] Icône + screenshots + trailer
- [ ] Description store + mots-clés ASO
- [ ] Classification d’âge complétée
- [ ] Formulaires data safety/privacy remplis
- [ ] Test interne (20–50 testeurs)
- [ ] Crash-free rate acceptable avant release

## 11) Lancement & post-lancement
- [ ] Soft launch (1–3 pays)
- [ ] KPIs suivis: D1, D7, ARPDAU, crash rate
- [ ] Canal feedback (Discord/Forms/Issues)
- [ ] Patch process <48h pour bugs critiques
- [ ] Backlog priorisé selon avis joueurs

---

Si vous voulez, je peux vous envoyer juste après :
1) **Checklist “Go/No-Go” en 15 points ultra-courte** (décision de sortie),  
2) **Template de notes de version** prêt à publier.