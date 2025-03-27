# dio-lab2-ai-900
Utilização do Azure AI Services para análise de sentimento e extração de palavras-chave e utilização do Azure AI Search. 

### Criação dos recursos
- AI Search
  - -> Create
  - Selecione
      - a assinatura
      - o grupo de recursos ou crie um novo
      - a localização
      - o tier basic
  - Crie

- AI + Machine learning
- Azure AI services
  - -> Create
  - Selecione
    - a assinatura
    - o grupo de recursos (utilizar o mesmo do AI Search)
    - a localização
    - o tier S0
  - Crie

- Storage
  - -> Storage accounts
    - -> Create 
    - Selecione
      - a assinatura
      - o nome
      - a região
      - o tipo de serviço (Azure Blob Storage)
      - performance Standard
      - redundancy LRS
    - Crie
  - Vá na configuração do Storage marque a opção Allow Blob anonymous access como Enabled para realização dos testes.

- Storage upload dos documentos de exemplo
  - link abaixo
- Faça o upload dentro do storage configurado.
  - crie o container dentro do storage.
  - selecione Container (anonymous read access for containers and blobs)

Com o container criado dentro do Storage Account, vá no recurso do AI Searchm em Get started conecte o recurso com os dados enviados ao container clicando em Import data.

### Documentos
Documentos de exemplo podem ser baixados no [Microsoft Leaning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)
