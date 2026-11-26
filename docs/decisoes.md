## ADR-001: Rodar tudo local com Docker
- Contexto: projeto de portfólio, custo zero, 16 GB de RAM
- Decisão: Docker Compose com perfis por fase
- Alternativas: Databricks Free Edition, GCP trial
- Consequências: não escala, mas o código usa API S3 e migra para a nuvem