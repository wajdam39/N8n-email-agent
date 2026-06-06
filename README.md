# N8n-email-agent
Email agent to collect job application email in google sheets

Opis projektu: Automatyczny system analizy i kategoryzacji wiadomości e-mail oparty na n8n, wykorzystujący LLM (Gemini) do ekstrakcji kluczowych danych i zapisujący wyniki w Google Sheets.

Stos technologiczny: n8n, PostgreSQL (Neon), Google Cloud (Gmail API, Sheets API), AI (Gemini), Render (Hosting).

How to run: Napisz krok po kroku (dokładnie to, przez co sam przeszedłeś!), jak ktoś inny może to u siebie postawić:

1.Założyć bazę na Neonie.
2.Ustawić na Renderze zmienne środowiskowe:
DB_POSTGRESDB_DATABASE
DB_POSTGRESDB_HOST
DB_POSTGRESDB_PASSWORD
DB_POSTGRESDB_PORT
DB_POSTGRESDB_SSL_REJECT_UNAUTHORIZED
DB_POSTGRESDB_USER
DB_TYPE
N8N_ENCRYPTION_KEY
N8N_PORT
PORT
WEBHOOK_URL

3.Zaimportować Twój plik .json do n8n.
4.Ustawić OAuth w Google Cloud.


<img width="2161" height="1167" alt="image" src="https://github.com/user-attachments/assets/89c3d11b-c1c7-467c-a667-afd531d2e6c5" />
