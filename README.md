### Projeto de alunos do 5º Semestre de Análise e Desenvolvimento de Sistemas - FATEC Jessen Vidal

> Este projeto é destinado a desenvolver um aplicativo mobile para gerenciar reembolsos de despesas.

## 📖 Índice 
<p align="center" dir="auto" name="topo">
    <a href="#tecnologias">Tecnologias</a> | 
    <a href="#backlog">Backlog</a> | 
    <a href="#levantamento">Levantamento de Requisitos</a> |  
    <a href="#prototipo">Protótipo</a> | 
    <a href="#org-equipe">Organização da Equipe</a> | 
    <a href="#licença">Licença</a>
</p>

---
### Sprints e Datas

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas para as seguintes tarefas:

- [x] Kick-off - 24/02 à 28/02
- [x] 1° Sprint - 10/03 à 30/03
- [x] 2° Sprint - 07/04 à 27/04
- [ ] 3° Sprint - 05/05 à 25/05

---

### 📋 Desafio (Problema)

Desenvolvido por alunos do 5º Semestre de Análise e Desenvolvimento de Sistemas da FATEC Jessen Vidal, tem como objetivo criar um aplicativo móvel para gerenciar reembolsos de despesas. O sistema visa solucionar desafios comuns enfrentados pelas empresas na gestão de reembolsos, como a perda de comprovantes, falta de transparência nos gastos e processos de aprovação lentos.

### 👨‍💻 Solução

A proposta é desenvolver uma solução ágil, eficaz e de fácil utilização, que permita o controle, monitoramento e aprovação de reembolsos de forma mais transparente e eficiente, tanto para os colaboradores quanto para a organização. O projeto foi desenvolvido para a empresa **GSW**, com a metodologia **Scrum** aplicada durante o desenvolvimento.

---

<details>
<summary><b>Sprint 1 - Protótipo Navegável [Conclusão: 14/03/2025]</span></b></summary>

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro | Critério de Aceitação | 
|------|------------|------------|------------|--------|-----------------------|------------------------|
| 1    | ALTA       | Eu, como usuário, desejo visualizar as telas principais do sistema. | 11 | 1 | RF3 | O sistema deve exibir as principais telas com navegação básica entre elas, permitindo fácil visualização de todos os componentes. |
| 2    | ALTA       | Eu, como usuário, desejo ter guias de acessos rápidos. | 12 | 1 | RF4 | As guias devem estar acessíveis a partir de qualquer tela, permitindo navegação ágil e prática para funcionalidades principais. |
| 3    | ALTA       | Eu, como colaborador acessando o app pelo celular, desejo visualizar meu perfil e consultar documentos da empresa. | 10 | 1 | RF7 | O perfil deve exibir informações pessoais e documentos essenciais de forma organizada e fácil de acessar. |
| 4    | MÉDIA      | Eu, como administrador, desejo cadastrar outros usuários (administradores ou colaboradores). | 20 | 2 | RF2 | A tela de cadastro de usuários deve permitir criar e atualizar perfis com diferentes níveis de permissão. |
</details>

<details>
  <summary><b>Sprint 2 - Gestão de Reembolsos "Registro de Gastos" [Conclusão: 27/04/2025]</b></summary>

  | Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro | Critério de Aceitação |
  |------|------------|------------|------------|--------|-----------------------|------------------------|
  | 5    | ALTA       | Eu, como funcionário, desejo registrar meus gastos com alimentação para reembolso. | 8  | 2 | RF3 | A tela deve permitir o funcionário registrar gastos com alimentação (ex: refeição, lanches) e associar a data e categoria de gasto. |
  | 6    | ALTA       | Eu, como funcionário, desejo registrar minha kilometragem para reembolso. | 8  | 2 | RF4 | A tela deve permitir o funcionário registrar a distância percorrida, com a data e o motivo da viagem (ex: viagem a trabalho). |
  | 7    | MÉDIA      | Eu, como administrador, desejo revisar e aprovar os gastos de alimentação e kilometragem dos funcionários. | 10 | 2 | RF5 | O administrador deve ser capaz de visualizar os pedidos de reembolso dos funcionários, incluindo alimentação e kilometragem, e aprovar ou rejeitar com base nos critérios de empresa. |
  | 8    | ALTA       | Eu, como funcionário, desejo visualizar o histórico de meus gastos e reembolsos aprovados. | 6  | 2 | RF6 | A tela deve exibir um histórico claro dos pedidos de reembolso feitos, com status de cada um (aprovado, pendente, reprovado) e os valores totais. |
  | 9    | ALTA       | Eu, como usuário, desejo receber notificações sobre o status dos meus pedidos de reembolso. | 5  | 2 | RF7 | O sistema deve enviar notificações por e-mail ou dentro do aplicativo, informando o status de aprovação ou rejeição dos pedidos de reembolso. |

</details>


<li>Informações sobre a sprint, objetivos, tarefas, etc.</li>

---

<!---

<details>
<summary><b>Sprint 2 - Acessos e Informações da Empresa [Conclusão: 27/04/2025]</span></b></summary>

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro | Critério de Aceitação |
|------|------------|------------|------------|--------|-----------------------|------------------------|
| 5    | MÉDIA      | Eu, como usuário, desejo uma interface inicial com informações da empresa e acessos rápidos. | 7 | 2 | RF4 | A interface inicial deve exibir informações relevantes da empresa e atalhos para áreas comuns, garantindo navegação rápida e prática. |
| 6    | MÉDIA      | Eu, como usuário, desejo cadastrar clientes e veículos. | 6 | 2 | RF1 | A tela de cadastro deve permitir entrada e atualização de informações de clientes e veículos, com validação dos dados inseridos. |
| 7    | MÉDIA      | Eu, como usuário, quero ter acesso ao controle de reuniões. | 7 | 2 | RF6 | A tela deve exibir a agenda de reuniões, permitindo visualização e criação de eventos, além de notificações de próximos encontros. |
| 8    | ALTA       | Eu, como usuário, desejo inserir perguntas na interface em linguagem natural para facilitar a interação. | 3 | 2 | RF2 | A interface deve permitir a inserção de perguntas de forma clara e responder com precisão em linguagem natural. |
</details>

### Sprint 3 - Funcionalidades de Informativos e Tutoriais [**Conclusão:** 10/11/2024]

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro | Critério de Aceitação |
|------|------------|------------|------------|--------|-----------------------|------------------------|
| 9    | MÉDIA      | Eu, como colaborador, desejo ver na área do usuário os informativos da empresa, horários, escalas e eventos. | 9 | 3 | RF4 | A área do usuário deve exibir informações completas sobre plantões, escalas e horários, além de eventos da empresa. |
| 10   | BAIXA      | Eu, como colaborador, desejo ver um tutorial de instruções sobre minha função nos informativos. | 8 | 3 | RF1 | A tela deve permitir acesso a tutoriais por função, com explicações passo a passo e exemplos visuais, como imagens e vídeos. |
| 11   | ALTA       | Eu, como usuário, desejo usar uma interface do usuário finalizada para ter uma experiência intuitiva e consistente. | 5 | 3 | RF2 | A interface deve estar completa, com navegação fluida e interativa, proporcionando uma experiência agradável e eficiente. |
| 12   | BAIXA      | Eu, como colaborador, gostaria de ver minhas tarefas pendentes e notificações na área inicial de perfil. | 6 | 3 | RF5 | A área inicial deve exibir todas as tarefas pendentes e notificações, com fácil acesso e atualização automática. |

<p align="center" dir="auto">→ <a href="#topo">Voltar ao topo</a></p>

---

### Sprint 4 - Gerenciamento de Usuários e Documentação [**Conclusão:** 01/12/2024]

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro | Critério de Aceitação |
|------|------------|------------|------------|--------|-----------------------|------------------------|
| 13   | BAIXA      | Eu, como administrador, preciso cadastrar os perfis de usuários e inserir documentos no perfil. | 2 | 4 | RNF1 | A interface de cadastro deve permitir inclusão e atualização de documentos nos perfis, com controle de acesso adequado. |
| 14   | BAIXA      | Eu, como administrador, preciso editar os informativos e tutoriais do aplicativo. | 1 | 4 | RNF2 | A área de edição deve permitir atualização dos conteúdos informativos e tutoriais, com salvamento automático e publicação instantânea. |
| 15   | BAIXA      | Eu, como colaborador, desejo um tutorial com instruções para as tarefas do dia a dia. | 8 | 4 | RF1 | O sistema deve exibir tutoriais detalhados, com explicações visuais, de fácil acesso e organizados por categorias de função. |
| 16   | BAIXA      | Eu, como administrador, preciso anexar um documento de Check-list para saída e retorno de veículos. | 7 | 4 | RNF2 | A interface deve permitir upload e visualização de Check-lists em um formato padronizado, com acesso restrito a usuários autorizados. |

<p align="center" dir="auto">→ <a href="#topo">Voltar ao topo</a></p>

---

### User Stories a serem planejadas

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro | Critério de Aceitação |
|------|------------|------------|------------|--------|-----------------------|------------------------|
| 17   | BAIXA      | Eu, como supervisor, preciso que todos os processos tenham um código para rastreio. | 4 | A definir | RF3 | Cada processo deve exibir um código único e histórico de etapas, incluindo prazos, responsáveis e tempos de conclusão. |
| 18   | MÉDIA      | Eu, como supervisor, preciso notificar o responsável por uma etapa do processo. | 3 | A definir | RF6 | O sistema deve enviar notificações automáticas aos responsáveis quando suas etapas forem requisitadas, com aviso de prazo. |
| 19   | BAIXA      | Eu, como administrador, desejo editar as informações dispostas no aplicativo. | 3 | A definir | RF5 | O sistema deve ter uma interface de edição de conteúdos que permita atualizar informações rapidamente. |
| 20   | MÉDIA      | Eu, como supervisor, preciso de valores e gráficos para análise de desempenho. | 5 | A definir | RF4 | A interface deve permitir visualização de gráficos de desempenho em tempo real, com opções de filtragem por região e departamento. |

<p align="center" dir="auto">→ <a href="#topo">Voltar ao topo</a></p>

---
-->
<div align="center" dir="auto">

## Backlog do Produto - 2024
<span id="user-content-backlog">

[backlog-Drift-Ops.xlsx](https://github.com/user-attachments/files/17600139/backlog-Drift-Ops.xlsx)

## 💻 Tecnologias
<span id="user-content-tecnologias">
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="figma logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/slack/slack-original.svg" height="40" alt="slack logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" height="40" alt="mysql logo"  />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo"  />
</div>

###

<!--## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você instalou a versão mais recente de `<linguagem / dependência / requeridos>`
- Você tem uma máquina Windows / Linux / Mac.
- Você leu `<guia / link / documentação_relacionada_ao_projeto>`. -->

## 🚀 Instalando...

Para instalação, siga estas etapas:

Visual Studio Code:

```
npm install
```

## ☕ Usando o sistema:

Para usar, siga estas etapas:

```
npm start
```

<!-- Adicione comandos de execução e exemplos que você acha que os usuários acharão úteis. Forneça uma referência de opções para pontos de bônus! -->
<p dir="auto">→ <a href="#topo">Voltar ao topo</a></p>
<span id="user-content-levantamento">
<h2 align="center" dir="auto"><a id="user-content-pencil-levantamento-de-requisitos" class="anchor" aria-hidden="true" href="#pencil-levantamento-de-requisitos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="memo" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4dd.png">📝</g-emoji> Levantamento de Requisitos</h2>
<p dir="auto">Antes de desenvolver o projeto, foi preciso denifir os desejos do cliente, organizando-os de acordo com suas prioridades e documentando com técnicas de Engenharia de Software. Para este levantamento de requisitos, o Product Owner do grupo esteve em contato constante com o cliente, questionando suas vontades e necessidades a fim de esculpir um plano de ação que satisfazesse seus pedidos, na medida do possível. Dessa forma, foi criado um backlog do produto, contendo suas funcionalidades e características principais, além de sprint backlogs e user stories, que são itens complementares para auxiliar a organização da equipe em relação às tarefas a serem desenvolvidas.</p>


## ✏️ Protótipo
<span id="user-content-prototipo">
<p dir="auto">Depois da definição do wireframe, iniciou-se o trabalho de codificação. O protótipo já conta com cores, tipografia e exemplos do resultado de uma busca, proporcionando a experiência esperada que o usuário terá ao manipular o produto final.</p>

Acesse o protótipo no [Figma](https://www.figma.com/design/gIANFxS9JvAvbYGF5Lwd6S/Untitled?node-id=0-1&p=f).

→ [Voltar ao topo](#topo)



## 🤝 Colaboradores
<span id="user-content-org-equipe">

Agradecemos às seguintes pessoas que contribuíram para este projeto:

|    Função    | Nome                       |                     GitHub                       |                    Linkedin                    |
| :----------: | :-----------------------   | :--------------------------------------------:   | :--------------------------------------------: |
| Product Owner | Enzo Pereira              |    [GitHub](https://github.com/Enzopereira01)    | [Linkedin](https://www.linkedin.com/in/erik-zanetti-ferraz-09895a180/) |
| Scrum Master  | Erik Zanetti Ferraz       |    [GitHub](https://github.com/ErikZFerraz)     | [Linkedin](https://www.linkedin.com/in/erik-zanetti-ferraz-09895a180/) |
|   Dev Team    | Kalil Pereira             |    [GitHub](https://github.com/kalil004)        | [Linkedin](https://www.linkedin.com/in/erik-zanetti-ferraz-09895a180/) |
|   Dev Team    | Luiz Henrique Souza Silva |    [GitHub](https://github.com/LuizHenrique435) | [Linkedin](https://www.linkedin.com/in/luiz-henrique-souza-silva-7b24a9279/)|
|   Dev Team    | Felipe Pereira            |    [GitHub](https://github.com/felipereira10)   | [Linkedin](https://www.linkedin.com/in/felipe-pereira-638370172/)|

## 📝 Licença
<span id="user-content-licença">

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
<!--[mysql-shield]: 
[mysql-url]: https://www.mysql.com/ -->
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com

</div>

<p align="center" dir="auto">→ <a href="#topo">Voltar ao topo</a></p>
