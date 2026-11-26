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
1) `gh issue create --title "Scrivere il README con l'obiettivo del progetto" --body "Descrivere cos'è Repertorio, a cosa serve e con quali tecnologie è costruito." --milestone "Fase 0 · Impianto"` # 1. cosa c'è da fare
2) `git switch -c tipo/descrizione`     # 2. un branch dedicato
3) `git add ... && git commit -m "..."` # 3. il lavoro, a piccoli passi
4) `git push -u origin tipo/descrizione`
5) `gh pr create --body "Closes #N"`    # 4. la proposta
6) `gh pr merge --squash --delete-branch`  # 5. dopo la revisione
7) `git switch main && git pull`        # 6. si riparte puliti