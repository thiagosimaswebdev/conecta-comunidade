# Conecta Comunidade

## Descrição

O Conecta Comunidade é um MVP desenvolvido por **Thiago Simas** para o **Desafio 3 – Tecnologia para o Impacto Social**.

A solução foi criada para apoiar organizações sociais no registro, acompanhamento e monitoramento de demandas comunitárias, permitindo centralizar informações, automatizar processos e gerar indicadores para tomada de decisão.

O projeto utiliza ferramentas Low-Code, integração entre plataformas e automação para simplificar o gerenciamento de ocorrências registradas pela comunidade.

---

## Problema Identificado

Muitas organizações sociais recebem demandas através de diferentes canais, como:

- Formulários online;
- Redes sociais;
- Aplicativos de mensagens;
- Atendimento presencial.

A descentralização dessas informações gera dificuldades para:

- Organizar registros;
- Acompanhar atendimentos;
- Identificar necessidades recorrentes;
- Produzir indicadores de impacto social.

---

## Solução Proposta

O Conecta Comunidade permite registrar ocorrências, gerar protocolos únicos, consultar registros por identificador e acompanhar indicadores através de um dashboard gerencial.

A proposta busca tornar o processo mais transparente, organizado e eficiente para organizações que atuam junto à comunidade.

---

## Tecnologias Utilizadas

### Bubble

Plataforma Low-Code utilizada para desenvolvimento da aplicação, formulários, páginas de consulta e dashboard.

### Make

Ferramenta de automação responsável pela integração entre Bubble e Google Sheets.

### Google Sheets

Utilizado como banco de dados para armazenamento dos registros enviados pelos usuários.

### Inteligência Artificial

Utilizada para apoiar:

- Planejamento do MVP;
- Estruturação da arquitetura;
- Construção de prompts;
- Modelagem dos fluxos;
- Produção da documentação.

---

## Funcionalidades

### Cadastro de Ocorrências

Permite registrar:

- Local;
- Tipo de ocorrência;
- Área de atuação;
- Prioridade;
- Nome;
- Sobrenome;
- Descrição da ocorrência;
- Descrição do material relacionado.

### Geração de Protocolo

Cada ocorrência recebe automaticamente um identificador único.

**Exemplo:**

```text
OC-20261019-2U3U9R8IY
```

### Consulta por ID

O usuário pode consultar sua ocorrência utilizando o protocolo gerado no momento do cadastro.

A consulta exibe as informações registradas e permite o acompanhamento da ocorrência de forma simples e segura.

### Dashboard

Painel gerencial contendo:

- Total de ocorrências;
- Ocorrências abertas;
- Ocorrências em andamento;
- Ocorrências resolvidas;
- Filtros por tipo;
- Filtros por prioridade;
- Filtros por status.

---

## Fluxo da Solução

```text
Usuário
   ↓
Bubble
(Formulário)
   ↓
Webhook
   ↓
Make
   ↓
Google Sheets
(Banco de Dados)
   ↓
Consulta e Dashboard
```

### Processo

1. O usuário registra uma ocorrência.
2. O sistema gera um protocolo único.
3. As informações são enviadas via Webhook.
4. O Make recebe os dados.
5. O Google Sheets armazena automaticamente o registro.
6. Os dados ficam disponíveis para consulta e monitoramento.

---

## Arquitetura da Solução

### Front-end

**Bubble**

Responsável por:

- Cadastro de ocorrências;
- Consulta por protocolo;
- Dashboard de indicadores;
- Interface da aplicação.

### Integração

**Make**

Responsável por:

- Receber dados via Webhook;
- Processar as informações recebidas;
- Integrar com o Google Sheets.

### Persistência de Dados

**Google Sheets**

Utilizado como banco de dados do MVP para armazenamento das ocorrências registradas.

---

## Engenharia de Prompt

Durante o desenvolvimento foram utilizados recursos de Inteligência Artificial para:

- Estruturar o escopo do MVP;
- Organizar os requisitos do desafio;
- Planejar a arquitetura da solução;
- Modelar fluxos de automação;
- Auxiliar na documentação técnica;
- Refinar a proposta de impacto social.

### Exemplo de Prompt Utilizado

> "Crie uma aplicação para registrar e monitorar demandas comunitárias utilizando Bubble, Make e Google Sheets, permitindo geração de protocolos, consulta por ID e dashboard de acompanhamento."

A Inteligência Artificial foi utilizada como ferramenta de apoio durante o desenvolvimento. Toda a configuração, implementação, testes e validação da solução foram realizadas pelo autor do projeto.

---

## Requisitos do Desafio Atendidos

✅ Interface funcional

✅ Formulário de entrada de informações

✅ Banco de dados

✅ Workflow automatizado

✅ Integração entre plataformas

✅ Dashboard para acompanhamento

✅ Solução Low-Code

✅ Aplicação voltada para impacto social

---

## Impacto Social

O Conecta Comunidade busca apoiar organizações sociais na identificação, registro e acompanhamento de demandas da comunidade.

Ao centralizar as informações e gerar indicadores visuais, a plataforma facilita a tomada de decisão, melhora a organização dos atendimentos e contribui para ações sociais mais eficientes e transparentes.

---

## Link da Aplicação

🔗 https://alerta-seguro-82681.bubbleapps.io/version-test/ocorrencias

---

## Autor

**Thiago Simas**

Projeto desenvolvido para o **Desafio 3 – Tecnologia para o Impacto Social**.

Bootcamp de Low-Code, Automação e Desenvolvimento de Soluções Digitais.
