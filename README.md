Conecta Comunidade
Descrição
O Conecta Comunidade é um MVP desenvolvido por Thiago Simas para o Desafio 3 – Tecnologia para o Impacto Social.

A solução foi criada para apoiar organizações sociais no registro, acompanhamento e monitoramento de demandas comunitárias, permitindo centralizar informações, automatizar processos e gerar indicadores para tomada de decisão.

O projeto utiliza ferramentas Low-Code, integração entre plataformas e automação para simplificar o gerenciamento de ocorrências registradas pela comunidade.

Problema Identificado
Muitas organizações sociais recebem demandas através de diferentes canais, como formulários, redes sociais, aplicativos de mensagens e atendimento presencial.

A descentralização dessas informações gera dificuldades para:

Organizar registros;
Acompanhar atendimentos;
Identificar necessidades recorrentes;
Produzir indicadores de impacto social.
Solução Proposta
O Conecta Comunidade permite registrar ocorrências, gerar protocolos únicos, consultar registros por identificador e acompanhar indicadores através de um dashboard gerencial.

A proposta busca tornar o processo mais transparente, organizado e eficiente para organizações que atuam junto à comunidade.

Tecnologias Utilizadas
Bubble
Plataforma Low-Code utilizada para desenvolvimento da aplicação, formulários, páginas de consulta e dashboard.

Make
Ferramenta de automação responsável pela integração entre Bubble e Google Sheets.

Google Sheets
Utilizado como banco de dados para armazenamento dos registros enviados pelos usuários.

Inteligência Artificial
Utilizada para apoiar:

Planejamento do MVP;
Estruturação da arquitetura;
Construção de prompts;
Modelagem dos fluxos;
Produção da documentação.
Funcionalidades
Cadastro de Ocorrências
Permite registrar:

Local
Tipo de ocorrência
Área de atuação
Prioridade
Nome
Sobrenome
Descrição da ocorrência
Descrição do material relacionado
Geração de Protocolo
Cada ocorrência recebe automaticamente um identificador único.

Exemplo:

OC-20261019-2U3U9R8IY

Consulta por ID
O usuário pode consultar sua ocorrência utilizando o protocolo gerado no momento do cadastro.

Dashboard
Painel gerencial contendo:

Total de ocorrências
Ocorrências abertas
Ocorrências em andamento
Ocorrências resolvidas
Filtros por tipo
Filtros por prioridade
Filtros por status
Fluxo da Solução
Usuário → Bubble → Webhook → Make → Google Sheets → Consulta e Dashboard

O usuário registra uma ocorrência.
O sistema gera um protocolo único.
As informações são enviadas via Webhook.
O Make recebe os dados.
O Google Sheets armazena automaticamente o registro.
Os dados ficam disponíveis para consulta e monitoramento.
Requisitos do Desafio Atendidos
✅ Interface funcional

✅ Formulário de entrada de informações

✅ Banco de dados

✅ Workflow automatizado

✅ Integração entre plataformas

✅ Dashboard para acompanhamento

✅ Solução Low-Code

✅ Aplicação voltada para impacto social

Link da Aplicação
https://alerta-seguro-82681.bubbleapps.io/version-test/ocorrencias

Autor
Thiago Simas

Projeto desenvolvido para o Desafio 3 – Tecnologia para o Impacto Social.
