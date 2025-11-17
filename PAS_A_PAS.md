# Pas-à-pas (étudiants)

## Amont (2 h)
1. Regarder 4 courtes vidéos (tests Jest/supertest, Copilot Agent, PR/review GitHub, MCP issue).
2. `npm install`, `npm test` → 1 test rouge (POST /pets) attendu.
3. Lancer `npm run dev` et tester `GET /pets`.

## Séance 1
- Branche `feat/post-pets` → implémenter POST /pets, ajouter test invalid (400).
- Relire le diff proposé par l’IA, corriger si besoin, PR + review croisée.
- Branche `refactor/validation` → déplacer la validation dans service, garder statuts/réponses, PR.

## Séance 2
- Branche `feat/filter-tag` → GET /pets?tag=..., tests (présent/absent).
- MCP : lire l’issue #<num> (AC1–AC4), implémenter PATCH /pets/:id + tests (happy, 404, invalid).
- PR finale avec check-list AC cochée et note critique (propositions IA rejetées et pourquoi).
