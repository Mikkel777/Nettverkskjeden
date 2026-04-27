# IP-plan og nettverksoppsett

## Maskiner

| Rolle        | IP-adresse     | Beskrivelse |
|-------------|---------------|------------|
| Frontend V  | 10.14.7.20   | Kjører Node.js og frontend |
| Express VM  | 10.12.7.241  | Tar imot meldinger |
| Database VM | 10.12.7.242  | Kjører MongoDB |

---

## Sikkerhet

- MongoDB er konfigurert med:
  - bindIp: 0.0.0.0 (for intern tilgang)
- Database er ikke eksponert mot internett
