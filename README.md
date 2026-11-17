# Painel · Eixos Estratégicos e ODS

Painel interativo que relaciona os 6 eixos estratégicos aos Objetivos de Desenvolvimento Sustentável (ODS 1 a 18). Reúne metas, fatores associados (ameaça, vulnerabilidade e resiliência) e equipamentos públicos do território.

## Conteúdo

- `index.html`: o painel. É um arquivo único e não depende de servidor.
- `dados/base_powerbi_eixos_ods.xlsx`: a base estruturada para importar no Power BI. A aba Leia-me explica os relacionamentos e as medidas DAX.
- `icones/`: os ícones em PNG dos eixos, dos ODS, dos tipos de fator e dos equipamentos.

## Publicar no GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. Em um ou dois minutos, o painel fica disponível em `https://eduardasilva96-code.github.io/painel-eixo-ods/`.

## Status do conteúdo

- As metas dos ODS 1 a 17 são resumos das metas da Agenda 2030 (ONU). As metas do ODS 18 resumem o ODS 18, Igualdade Étnico-Racial (CNODS, iniciativa voluntária do Brasil).
- Ainda precisam ser validados pela equipe: as descrições dos eixos, os fatores associados, a escolha de metas por eixo e a ligação entre equipamentos e eixos.
- Os ícones de equipamentos públicos são provisórios.
