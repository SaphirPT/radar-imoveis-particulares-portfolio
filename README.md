# Radar Imóveis — Prospecção Inteligente de Oportunidades

![Estado](https://img.shields.io/badge/estado-MVP%20funcional-0b7a53)
![Segmento](https://img.shields.io/badge/segmento-prospecção%20imobiliária-155b3f)
![Operação](https://img.shields.io/badge/operação-pesquisas%20recorrentes-2f6fed)
![Código](https://img.shields.io/badge/código-fonte%20privado-6f42c1)

Plataforma de apoio à **angariação imobiliária**, criada para pesquisar anúncios públicos, identificar potenciais proprietários particulares, reduzir duplicados e organizar novas oportunidades de contacto na região de Viseu, Mangualde e concelhos próximos.

> Este é um repositório público de apresentação. Código-fonte, base de dados, regras internas, contactos e dados recolhidos permanecem privados.

![Pesquisa operacional do Radar Imóveis com dados sensíveis desfocados](https://github.com/user-attachments/assets/caf4f802-794f-482b-8e97-9495776961ff)

## Objetivo

Centralizar um processo que normalmente exige várias pesquisas manuais: consultar diferentes fontes, filtrar anúncios, comparar oportunidades, validar o tipo de anunciante e guardar apenas os resultados relevantes para acompanhamento comercial.

O sistema está preparado para **pesquisas recorrentes e geração diária de novas oportunidades**, sempre condicionadas à disponibilidade, às regras de acesso e ao conteúdo público de cada fonte. Não promete uma quantidade artificial ou garantida de leads.

## Principais capacidades

- Pesquisa multifuente em portais imobiliários e classificados públicos.
- Filtros por concelho, localidade, tipo de imóvel, negócio, preço, área e período.
- Classificação assistida do anunciante: particular, outra imobiliária ou por validar.
- Pontuação de oportunidade com evidências e nível de confiança visíveis.
- Deduplicação por fonte e identificador externo para evitar trabalho repetido.
- Registo de pesquisas, oportunidades guardadas, alertas e estado das fontes.
- Integração com mapa e Street View quando existe localização compatível.
- Importação assistida por ligação pública, texto ou ficheiro autorizado.
- Extração apenas de telefone ou e-mail que estejam escritos publicamente no anúncio.
- Visão operacional com novas oportunidades, itens guardados e acompanhamento.

## Fluxo funcional

**Pesquisa pública → normalização → deduplicação → classificação → pontuação → validação humana → oportunidade guardada**

O objetivo é apoiar a decisão comercial com rastreabilidade. A classificação não é apresentada como certeza absoluta: o sistema mostra a evidência disponível e permite validação humana.

## Fontes e recolha responsável

O MVP integra pesquisa pública sob demanda em fontes como **OLX, CustoJusto, CASA SAPO e Imovirtual**. Fontes com restrições técnicas utilizam fluxo assistido. Facebook e Instagram só são considerados através das APIs oficiais e de contas/tokens autorizados.

O projeto não contorna autenticação, CAPTCHA, botões de revelação de contacto nem mecanismos de proteção das plataformas. Cada integração respeita o modo de acesso disponível e pode permanecer inativa quando não existe autorização adequada.

## Tecnologias

**React 19 · TypeScript · Vite · Python 3.12+ · FastAPI · Pydantic · SQLite · APIs REST · Vitest · pytest**

## Evidência visual operacional

### Pesquisa, filtros e fontes

![Filtros, fontes e classificação do Radar Imóveis](https://github.com/user-attachments/assets/caf4f802-794f-482b-8e97-9495776961ff)

A captura foi obtida diretamente da versão operacional atual. Filtros, fontes, classificação, pontuação e fluxo permanecem visíveis; dados identificáveis dos anúncios foram intencionalmente desfocados.

### Resultados, mapa e detalhe da oportunidade

![Resultados reais, mapa e critérios do Radar Imóveis](https://github.com/user-attachments/assets/6d17f43c-2623-4ea0-bdda-03349c2aa8c5)

A interface demonstra resultados preenchidos, integração cartográfica e critérios de correspondência sem expor nomes, contactos, moradas, preços ou outros dados específicos dos anúncios.

## Valor para a operação imobiliária

- Menos tempo disperso entre várias plataformas.
- Priorização das oportunidades com maior aderência aos critérios definidos.
- Histórico de pesquisas e redução de anúncios duplicados.
- Processo mais consistente para prospecção e angariação.
- Base preparada para execução recorrente e expansão controlada de fontes.

## Estado

**MVP funcional validado localmente em pesquisas multifuente reais.** A evolução concentra-se em robustez das integrações, qualidade de classificação, observabilidade e conformidade operacional.

## Privacidade e propriedade intelectual

- O código-fonte e a base de dados não são disponibilizados neste repositório.
- Não existem listas de contactos, dados pessoais, credenciais, tokens ou automações completas para download.
- As imagens destinam-se exclusivamente à demonstração profissional do projeto.
- Todos os direitos sobre os componentes originais e o material de apresentação são reservados.

## Autor

**Jorge Souza Junior** — Full Stack Developer · Aplicações web e mobile · APIs · Automação · IA aplicada ao negócio

[GitHub](https://github.com/SaphirPT) · [LinkedIn](https://www.linkedin.com/in/jorgendsjunior/)
