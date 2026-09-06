# PRD — Zetron Consultoria | Portal de Projetos com Clientes

## Resumo
Portal próprio da Zetron para centralizar acompanhamento de projetos de clientes. O primeiro espaço é o lançamento **Apometria Manto Azul / Regina Hercos**, com go-live em 08/10/2026.

## Problema
WhatsApp fragmenta decisões, cronograma e aprovações. O cliente precisa saber o que está pronto, o que depende dele e qual é o próximo passo, sem ser exposto à operação interna completa.

## MVP entregue
- Link privado por projeto, sem senha.
- Dashboard de status, prazos, bloqueios, decisões, timeline, produtos e entregas.
- Visão de cliente sem dados internos sensíveis.
- Projeto Regina pré-carregado a partir do fluxo de lançamento recebido em 05/09.

## Entrada unificada
- A capa institucional fica na rota raiz (`/`).
- A landing pode apresentar um resumo público de projetos selecionados, sem link para seus workspaces.
- Cada workspace continua em uma rota do mesmo domínio Railway, como `/regina-8out-2026/`; não haverá outro projeto Railway para essa camada.

## Contato público
- WhatsApp e telefone: `17997155904`.
- E-mail: `guilhermeribeiro111@gmail.com`.
- Formulário estático prepara uma mensagem no aplicativo de e-mail do visitante; não armazena dados nem usa backend.
- Rodapé deve exibir a razão social e CNPJ fornecidos pelo Gui.

## Status do lançamento Regina
- Fase atual: decisões e coleta.
- Bloqueador: retorno da Regina até 10/09 sobre preço, compliance, Hotmart/dominio e formato do curso.
- Meta operacional: 30/09.
- Lançamento: 08/10.

## Próxima evolução
1. Login por convite para cada cliente.
2. Banco de dados para projetos, marcos, entregáveis e aprovações.
3. Área interna Zetron com responsáveis, campanhas e tarefas.
4. Avisos por WhatsApp/e-mail para itens aguardando cliente.

## Fora de escopo
Alterar a landing do Manto Azul, checkout, CRM, contratos, dados financeiros ou automação de anúncios.
