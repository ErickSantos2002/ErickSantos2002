<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0C0A09,45:78350F,80:D97706,100:FBBF24&text=Erick%20Santos&fontColor=FFFFFF&fontSize=52&fontAlignY=36&desc=Backend%20%C2%B7%20Engenharia%20de%20Dados%20%C2%B7%20Integra%C3%A7%C3%B5es&descAlignY=58&descSize=18&animation=fadeIn" alt="Erick Santos · Backend · Engenharia de Dados · Integrações"/>

<div align="center">

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=F59E0B&center=true&vCenter=true&width=760&lines=Python+%C2%B7+FastAPI+%C2%B7+PostgreSQL+%C2%B7+dbt;Do+ERP+ao+banco%2C+do+banco+%C3%A0+API;Oito+sistemas+internos+em+produ%C3%A7%C3%A3o;Pipeline+bom+avisa+quando+falha"
  alt="Python · FastAPI · PostgreSQL · dbt"
/>

**Backend e Engenharia de Dados** · Health & Safety · Recife, PE

<sub><i>Meu trabalho fica entre os sistemas de origem e quem precisa ler os dados.</i></sub>

<br/>

<a href="https://www.linkedin.com/in/erick-santos2002"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ericksantosdantas@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
<img src="https://img.shields.io/badge/Ingl%C3%AAs-fluente-1C1917?style=for-the-badge" alt="Inglês fluente"/>

</div>

---

## Sobre

Sou um dos dois engenheiros da **Health & Safety**, distribuidora B2B de bafômetros conectados. Cuido do backend, das APIs, dos dados e da infraestrutura. Meu colega cuida do frontend e da experiência de uso.

Na prática: ingestão em Python a partir do ERP e das notas fiscais, modelagem em PostgreSQL, APIs em FastAPI e a VPS onde tudo roda. A empresa tem oito sistemas internos, de CRM a plataforma de agentes de IA, e todos dependem desse caminho.

---

## Em números

<table align="center">
  <tr>
    <td align="center" width="200">
      <h2>194</h2>
      <sub>contas a receber que faltavam no banco<br><b>extratores Python no lugar do n8n</b></sub>
    </td>
    <td align="center" width="200">
      <h2>22 MB → 1,3 MB</h2>
      <sub>por carregamento de tela<br><b>agregação no banco com dbt</b></sub>
    </td>
    <td align="center" width="200">
      <h2>−70%</h2>
      <sub>no tempo do processo seletivo<br><b>triagem de currículos com IA</b></sub>
    </td>
    <td align="center" width="200">
      <h2>16</h2>
      <sub>bancos expostos na internet<br><b>fechados no firewall da nuvem</b></sub>
    </td>
  </tr>
</table>

---

## O que eu faço

<table>
<tr>
<td width="50%" valign="top">

### 🛢️ Dados e ingestão

- Extratores Python com carga incremental e idempotente pelos IDs da origem
- Rate limit lido do header, com backoff
- Tabela de controle de execuções e alerta quando um job para de carregar
- Modelagem em PostgreSQL, camada silver/gold em dbt em produção
- Dado fiscal: NFS-e, notas do ERP, régua de faturamento

</td>
<td width="50%" valign="top">

### ⚙️ Backend e APIs

- APIs REST em FastAPI e SQLAlchemy
- Integrações com ERP e APIs de terceiros
- Testes contra Postgres descartável e teste por mutação
- Branch, pull request e revisão entre os dois engenheiros

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 IA aplicada

- Migração da plataforma de agentes de IA da empresa (HS.OS) para FastAPI e PostgreSQL próprios
- HealthScore: vendedores treinam objeções com um modelo da OpenAI instruído por prompt
- Triagem de currículos com IA
- Claude Code e Codex no dia a dia: eu desenho e reviso, a IA escreve boa parte do código

</td>
<td width="50%" valign="top">

### 🐧 Infra e operação

- Linux, Docker, VPS, EasyPanel e Traefik
- Jobs agendados com systemd timers
- Firewall de nuvem e bancos fora da internet
- Monitoramento por frescor da carga

</td>
</tr>
</table>

---

## Projetos

| Projeto | O que é | Stack |
|---|---|---|
| **[DataCore](https://github.com/ErickSantos2002/DataCore)** | Sistema de dados da empresa: ingestão do ERP e das notas fiscais, API e camada dbt. Substituiu o Power BI como camada analítica | Python · FastAPI · PostgreSQL · dbt · React |
| **[radar-vagas](https://github.com/ErickSantos2002/radar-vagas)** | Pipeline que agrega vagas remotas de sete fontes públicas, resolve elegibilidade geográfica e acompanha a demanda por skill | Python · PostgreSQL · dbt |
| **[HS.OS](https://github.com/ErickSantos2002/HS.OS)** | Plataforma de agentes de IA da empresa, em migração para backend próprio | TypeScript · FastAPI · PostgreSQL |
| **[Grana](https://github.com/ErickSantos2002/Grana)** | App de finanças pessoais em monorepo | FastAPI · React · Vite |
| **[Alugix](https://github.com/ErickSantos2002/Alugix)** | Backend de gestão de aluguéis, com PRD, contrato de API e modelo de dados documentados | Java 21 · Spring Boot |

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

---

## Formação

Tecnólogo em Análise e Desenvolvimento de Sistemas pela UNIBRA (2022–2025). Inglês fluente: morei seis meses no Tennessee, nos Estados Unidos, pelo programa Ganhe o Mundo.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0C0A09,45:78350F,80:D97706,100:FBBF24"/>
