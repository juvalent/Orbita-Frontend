# 🪐 Órbita — Front-end

> Interface web do Sistema de Gestão de Demandas de Inovação

**Status: Em construção — MVP em desenvolvimento**

O **Órbita Front-end** é a aplicação responsável pela interface visual do Sistema de Gestão de Demandas de Inovação.

O projeto tem como objetivo oferecer uma experiência simples, intuitiva e responsiva para os diferentes usuários envolvidos no processo de gestão de demandas de inovação.

O desenvolvimento faz parte da **Residência Tecnológica do Porto Digital**, realizado pela **Squad 47**, em parceria com o **Banco do Brasil**, que atua como cliente e parceiro do projeto.

---

## Sobre o projeto

O Front-end do Órbita concentra as interfaces utilizadas para registrar, acompanhar, avaliar e gerenciar demandas de inovação.

A aplicação foi pensada para facilitar a visualização das informações e permitir que cada perfil de usuário tenha acesso às funcionalidades relacionadas às suas responsabilidades dentro do processo.

---

## Principais funcionalidades

Entre as principais funcionalidades previstas para a aplicação estão:

* Login e autenticação;
* Controle de acesso por perfil;
* Dashboard;
* Cadastro de demandas;
* Edição de demandas;
* Submissão de demandas;
* Visualização de demandas;
* Avaliação e triagem;
* Aprovação ou rejeição;
* Acompanhamento de status;
* Visualização do funil de inovação;
* Gestão de MVPs;
* Indicadores e informações de acompanhamento;
* Notificações;
* Histórico das demandas.

---

## Perfis de usuários

A interface considera diferentes perfis envolvidos no processo de inovação:

* Gestor Demandante;
* Membro do Grupo de Trabalho;
* Hub de Inovação;
* PO da Iniciativa;
* Governança;
* Diretoria;
* Consultoria Lei do Bem;
* Auditoria;
* Administrador.

Cada perfil possui diferentes responsabilidades e permissões dentro da plataforma.

---

## Interface e experiência do usuário

O desenvolvimento do Front-end busca proporcionar uma experiência consistente e intuitiva, facilitando a navegação entre as diferentes etapas do processo.

A interface contempla:

* Layout responsivo;
* Componentes reutilizáveis;
* Formulários para cadastro e avaliação;
* Tabelas e listagens;
* Cards e indicadores;
* Dashboards;
* Filtros e pesquisas;
* Feedback visual para ações do usuário;
* Controle de estados das demandas;
* Navegação adaptada aos diferentes perfis.

---

## Responsividade e PWA

O Órbita Front-end será desenvolvido como uma aplicação **web responsiva**, permitindo sua utilização em computadores, tablets e dispositivos móveis.

Também está prevista a implementação como **PWA (Progressive Web App)**, permitindo uma experiência mais próxima de uma aplicação instalada.

O projeto não tem como objetivo desenvolver um aplicativo mobile nativo separado. A proposta é utilizar a aplicação web responsiva com recursos de PWA para ampliar sua acessibilidade e usabilidade.

---

## Tecnologias

O Front-end segue os requisitos tecnológicos definidos para o projeto.

### Principais tecnologias

* Angular 18+
* TypeScript
* Angular Material
* PWA
* HTML5
* CSS
* Integração com API REST

A aplicação será responsável pela comunicação com o backend por meio de APIs, permitindo o envio, consulta e atualização das informações do sistema.

---

## Estrutura da aplicação

A aplicação é organizada de forma a facilitar a manutenção, reutilização de componentes e evolução do projeto.

Entre os principais elementos estão:

```text
src/
├── app/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── guards/
│   ├── models/
│   └── shared/
├── assets/
└── environments/
```

A estrutura poderá evoluir conforme novas funcionalidades forem implementadas durante o desenvolvimento.

---

## Fluxo da aplicação

De forma geral, o usuário poderá:

```text
Login
  ↓
Dashboard
  ↓
Demandas
  ↓
Cadastro / Visualização
  ↓
Submissão
  ↓
Avaliação
  ↓
Aprovação ou Rejeição
  ↓
Acompanhamento
  ↓
Funil de Inovação
  ↓
MVP
  ↓
Resultados
```

O acesso às funcionalidades e informações será determinado de acordo com o perfil e as permissões do usuário.

---

## Integração com o Backend

O Front-end será integrado ao backend do Órbita por meio de uma **API REST**.

Essa integração permitirá:

* Autenticação;
* Consulta de dados;
* Cadastro de informações;
* Atualização de demandas;
* Avaliação;
* Alteração de status;
* Consulta de indicadores;
* Recebimento e exibição de notificações.

---

## MVP

O MVP do Front-end está sendo desenvolvido priorizando as telas e funcionalidades essenciais para validar a solução.

Inicialmente, o foco está em:

* Login;
* Dashboard;
* Cadastro de demanda;
* Listagem de demandas;
* Detalhes da demanda;
* Edição;
* Submissão;
* Avaliação;
* Aprovação ou rejeição;
* Acompanhamento do status;
* Funil de inovação.

Funcionalidades mais avançadas serão incorporadas conforme a evolução do projeto.

---

## Projeto em construção

O **Órbita Front-end está atualmente em desenvolvimento**.

O projeto será evoluído de forma incremental, acompanhando a implementação do backend e as validações realizadas ao longo da Residência Tecnológica.

Novas telas, componentes e funcionalidades serão adicionados conforme as necessidades do produto.

---

## Contexto

O projeto está sendo desenvolvido pela **Squad 47**, no contexto da **Residência Tecnológica do Porto Digital**, em parceria com o **Banco do Brasil**.

A construção do Front-end proporciona a aplicação prática de conhecimentos relacionados ao desenvolvimento de interfaces, experiência do usuário, desenvolvimento web, integração com APIs e construção de aplicações modernas.

---

## Visão

O Front-end do Órbita busca transformar informações e processos complexos de inovação em uma experiência visual simples, organizada e acessível.

**Ideias → Pessoas → Processos → Resultados**

---

## Equipe

Projeto desenvolvido pela **Squad 47** da Residência Tecnológica do Porto Digital.

**Parcerias:**

* Porto Digital
* Banco do Brasil

---


