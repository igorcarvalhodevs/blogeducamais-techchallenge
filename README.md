# BlogEducaMais

Projeto de blog educacional desenvolvido como parte do **Tech Challenge**, utilizando a plataforma **OutSystems (low-code)**.

O objetivo da aplicação é fornecer um canal de comunicação onde **professores** possam publicar recados e **alunos** possam visualizar os conteúdos de forma segura e organizada, respeitando níveis de acesso distintos.

---

## Visão Geral

O BlogEducaMais simula um sistema real de comunicação educacional, com controle de acesso por papéis (roles), interface intuitiva e funcionalidades completas de CRUD para professores.

Este repositório **não contém o código-fonte tradicional**, pois o projeto foi desenvolvido integralmente na plataforma OutSystems.  
Aqui estão centralizados a **documentação**, o **fluxo do sistema**, o **vídeo demonstrativo** e os **artefatos do projeto**.

---

## Funcionalidades

### 👨‍🏫 Professor
- Criar recados
- Editar recados
- Deletar recados
- Visualizar lista completa
- Barra de pesquisa
- Dark Mode

### 👨‍🎓 Aluno
- Visualizar lista de recados
- Ler detalhes do recado
- Barra de pesquisa
- Dark Mode
- Tentativas de criação/edição/exclusão são bloqueadas por regra de negócio

---

## Controle de Acesso

- Autenticação e autorização gerenciadas pelo sistema de **Roles do OutSystems**
- Validações críticas realizadas na **camada lógica**, garantindo segurança mesmo em tentativas de acesso indevido

---

## Fluxo do Sistema

O diagrama abaixo representa:
- Fluxo de autenticação
- Identificação do papel do usuário
- Diferenças entre permissões de aluno e professor
- Ações permitidas e bloqueadas

![Fluxograma do Sistema](FluxogramaBlogEducaMais.png)

---

## Tecnologias Utilizadas

- OutSystems (Low-code)
- OutSystems Service Studio
- OutSystems Cloud
- JavaScript (Dark Mode e interações)
- CSS (customizações visuais)
- Controle de acesso por Roles

---

## Vídeo Demonstrativo

📺 Demonstração completa do projeto no YouTube:  
👉 **[[link do vídeo aqui](https://youtu.be/neUk1VxwwbE)]**

---

## Documentação

A documentação completa do projeto está disponível neste repositório:

📄 `Documentação_do_Projeto_BlogEducaMais.pdf`

---

## Observação Importante

Este repositório tem caráter **documental e demonstrativo**, servindo como evidência técnica do projeto desenvolvido na plataforma OutSystems.

---

## Autor

Igor Carvalho  
Projeto desenvolvido para fins acadêmicos e portfólio.
