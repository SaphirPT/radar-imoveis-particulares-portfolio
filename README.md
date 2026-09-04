# Radar Imóveis — Prospecção Inteligente de Oportunidades

![Estado](https://img.shields.io/badge/estado-MVP%20funcional-0b7a53)
![Segmento](https://img.shields.io/badge/segmento-prospecção%20imobiliária-155b3f)
![Operação](https://img.shields.io/badge/operação-pesquisas%20recorrentes-2f6fed)
![Código](https://img.shields.io/badge/código-fonte%20privado-6f42c1)

Plataforma de apoio à **angariação imobiliária**, criada para pesquisar anúncios públicos, identificar potenciais proprietários particulares, reduzir duplicados e organizar novas oportunidades de contacto na região de Viseu, Mangualde e concelhos próximos.

> Repositório público de apresentação. Código-fonte, base de dados, regras internas, contactos e dados recolhidos permanecem privados.

## Visão geral visual

<img width="1400" height="974" alt="clipboard" src="https://github.com/user-attachments/assets/5c13da1a-cbc1-4bd1-9897-195af4b71c7d" />


## Objetivo

Centralizar pesquisas manuais em várias fontes, filtrar anúncios, comparar oportunidades, validar o tipo de anunciante e guardar apenas resultados relevantes.

O sistema está preparado para **pesquisas recorrentes e geração diária de novas oportunidades**, sempre condicionadas à disponibilidade, às regras de acesso e ao conteúdo público de cada fonte. Não promete uma quantidade artificial ou garantida de leads.

## Principais capacidades

- Pesquisa multifuente em portais imobiliários e classificados públicos.
- Filtros por concelho, localidade, tipo de imóvel, negócio, preço, área e período.
- Classificação assistida: particular, outra imobiliária ou por validar.
- Pontuação com evidências e nível de confiança.
- Deduplicação por fonte e identificador externo.
- Histórico, oportunidades guardadas, alertas e estado das fontes.
- Mapas e Street View quando existe localização compatível.
- Importação assistida por ligação pública, texto ou ficheiro autorizado.
- Extração apenas de telefone/e-mail escritos publicamente no anúncio.

## Fluxo funcional

**Pesquisa pública → normalização → deduplicação → classificação → pontuação → validação humana → oportunidade guardada**

## Recolha responsável

O MVP integra pesquisa sob demanda em OLX, CustoJusto, CASA SAPO e Imovirtual. Fontes restritas usam fluxo assistido. Facebook e Instagram só via APIs oficiais e acessos autorizados.

O projeto não contorna autenticação, CAPTCHA, botões de revelação de contacto nem mecanismos de proteção.

## Tecnologias

**React 19 · TypeScript · Vite · Python 3.12+ · FastAPI · Pydantic · SQLite · APIs REST · Vitest · pytest**

## Estado

**MVP funcional validado localmente em pesquisas multifuente reais.**

## Privacidade e propriedade intelectual

- Código-fonte e base de dados não são disponibilizados.
- Não existem listas de contactos, dados pessoais, credenciais, tokens ou automações completas para download.
- Todos os direitos sobre os componentes originais e o material de apresentação são reservados.

## Autor

**Jorge Souza Junior** — Full Stack Developer · Aplicações web e mobile · APIs · Automação · IA aplicada ao negócio

[GitHub](https://github.com/SaphirPT) · [LinkedIn](https://www.linkedin.com/in/jorgendsjunior/)
