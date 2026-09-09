---
layout: default
title:  SAP CPI | Consulta de CEP
parent: SAP Cloud Integration
nav_order: 2

description: Construção de um iFlow que recebe um CEP via HTTPS e consulta um serviço externo de CEP por HTTP.

header_category: SAP Cloud Integration
header_product: SAP CPI - Consumindo Web Service
header_line: External Server · HTTPS
header_subtitle: Web Service
---

{% include secondary-header.html %}

---

## Temas abordados

- HTTPS
- HTTP
- Request Reply
- Content Modifier
- Exchange Property
- XPath
- APIs REST
- Consumo de serviços externos
- HTTP GET
- Manipulação de URL dinâmica
- Deploy de iFlow
- Testes de integração
- Monitoramento de integrações

---

## Projetos desenvolvidos

### EX001_ConsultaCEP

Integração desenvolvida no SAP Cloud Integration para consulta de CEP utilizando o serviço externo **ViaCEP**.

O iFlow recebe o CEP por meio de uma requisição HTTPS, armazena o valor recebido em uma Exchange Property e utiliza esse valor para montar dinamicamente a URL de consulta ao ViaCEP.

---
## Arquitetura

![Arquitetura da integração]({{ '/assets/images/10d2b9f0-7673-44e7-aa6e-d1d997991a53.png' | relative_url }})

---

## iFlow test
![EX001 Consulta CEP - iFlow]({{ '/assets/images/97fecd96-7026-42cb-bb3d-76da32891823.png' | relative_url }})

---

## Projeto

Projeto desenvolvido de SAP Cloud Integration,
contendo os iFlows apresentados neste conteúdo.

**[⬇ Baixar projeto — Consulta de CEP](https://meireleslipe.github.io/assets/downloads/Consulta%20de%20CEP.zip)**

---

## Tecnologias

`SAP Cloud Integration` · `External Service` · `HTTPS` · `JSON` · `iFlow`
