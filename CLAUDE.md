# VZDELAI-KE Project

## O projekte
Webová stránka projektu VZDELAI — inovatívny personalizovaný AI asistent pedagóga pre interaktívne vzdelávanie na Žilinskej univerzite v Žiline.

- **Kód projektu**: ITMS2021+: 401101C526
- **Prijímateľ**: Žilinská univerzita v Žiline
- **Partneri**: Aricoma Systems s.r.o., COMPOTE s.r.o., COMTEC s.r.o., ESMO Žilina a.s.
- **Trvanie**: 01/2026 – 12/2028
- **Rozpočet**: 11 102 134,82 € (NFP: 8 977 510,09 €)

## Technický stack
- Statická HTML stránka
- Hosting: FTP server (web9.hosts.uniza.sk, priečinok /html/)
- Repozitár: github.com/seafu8/VZDELAI-KE
- Deploy: automatický cez GitHub Actions po každom push

## Workflow
1. Zmeny robíme výlučne cez Claude Code (VS Code alebo terminál)
2. Claude commitne zmeny do main branch
3. GitHub Actions automaticky nasadí na FTP server
4. Zmeny sú živé do 2 minút

## Štruktúra
- index.html — hlavná stránka
- .github/workflows/deploy.yml — automatický deploy

## Pravidlá
- Jazyk stránky: slovenčina
- Zmeny: 1-2x mesačne
- Dizajn: moderný, zodpovedá akademickému prostrediu univerzity
- Vždy zachovať existujúcu štruktúru pokiaľ nie je výslovne povedané inak

## Collaboratori
- seafu8 (Marcel) — hlavný správca
- kolega — collaborator