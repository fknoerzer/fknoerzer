## Florian Knörzer

Lead Software Engineer bei Capgemini, vier Jahre Java und Spring im öffentlichen Sektor, dazu Kafka, PostgreSQL, Azure, Terraform und Docker. Aktuell erweitere ich mein Profil um KI-Anwendungsentwicklung.

### Eigene Projekte

**[anlagen-copilot](https://github.com/fknoerzer/anlagen-copilot)** · RAG über technische Dokumentation

Beantwortet Fragen zu sechs Herstellerhandbüchern, rund 1.300 indizierte Seiten, mit Quellenangabe bis auf die Seite. Evaluiert gegen 36 manuell verifizierte Fragen: Die Vektorsuche findet 24 Belegseiten, 28 liegen unter den 20 Kandidaten, das Reranking bringt 25 bis 26 in die Top 5. Der Engpass liegt damit in der Extraktion, nicht im Reranking.

Ohne RAG-Framework gebaut, damit jeder Schritt einzeln messbar bleibt. 17 ADRs, 190 Tests, CI mit Datenbank-Container, mypy strict, Ruff, Abhängigkeitsprüfung bei jedem Push.

`Python` · `PostgreSQL/pgvector` · `OpenAI Embeddings` · `Claude`

**[reverse-prompt-game](https://github.com/fknoerzer/reverse-prompt-game)** · Ein Spiel über LLM-Sicherheit

Nutzer versuchen, ein Sprachmodell zur Preisgabe eines geheimen Worts zu bringen. Die Prüfung kombiniert deterministischen Abgleich mit einem LLM-Judge und schlägt bei Fehlern und uneindeutigen Antworten fehl, statt durchzulassen. 50 Tests, statische Typprüfung, CI.

`Python` · `Ollama` · `Streamlit`

[LinkedIn](https://www.linkedin.com/in/florian-knoerzer/)
