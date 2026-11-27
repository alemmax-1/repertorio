# Repertorio
## Cos'è
Un'applicazione web per la gestione dei repertori nelle formazioni musicali, dal solo alla bigband
## Tecnologie
Le tecnologie utilizzate sono:
- Backend: Django REST Framework
- Frontend: React (Vite)
- Database: PostgreSQL (SQLite in sviluppo)
## Stato
Il progetto fa parte di un percorso formativo per imparare a:
- sviluppare applicazioni web moderne basate sulle tecnologie indicate al punto precedente;
- sfruttare GitHub in tutte le sue potenzialità
## Struttura
- `backend/`: API in Django REST Framework (fase 3)
- `frontend/`: interfaccia in React (fase 2)
## Ciclo di lavoro su GitHub
```bash
# 1. cosa c'è da fare
gh issue create \
  --title "Titolo della issue" \
  --body "Descrizione della modifica/implementazione" \
  --milestone "Fase X · Milestone"
# 2. un branch dedicato
git switch -c tipo/descrizione
# 3. il lavoro, a piccoli passi
git add ... && git commit -m "..."`
git push -u origin tipo/descrizione
# 4. la proposta
gh pr create --body "Closes #N"
# 5. dopo la revisione
gh pr merge --squash --delete-branch
# 6. si riparte puliti
git switch main && git pull
```