---
version: alpha
name: Zetron Consultoria
description: Direção executiva e tecnológica para uma consultoria que conecta estratégia e execução.
colors:
  primary: "#0A0B10"
  surface: "#11131B"
  surfaceRaised: "#171A25"
  text: "#EEF0F6"
  muted: "#9DA3B5"
  line: "#292D3A"
  violet: "#9B8CFF"
  cyan: "#61D8E8"
  green: "#68DFAA"
  amber: "#F5C76A"
typography:
  display:
    fontFamily: Manrope
    fontSize: 3.25rem
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.07em"
  body-md:
    fontFamily: Manrope
    fontSize: 1rem
    fontWeight: 500
    lineHeight: 1.7
rounded:
  sm: 8px
  md: 12px
spacing:
  sm: 8px
  md: 16px
  lg: 32px
components:
  button-primary:
    backgroundColor: "{colors.violet}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 16px
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    padding: 16px
  status-pending:
    backgroundColor: "{colors.surfaceRaised}"
    textColor: "{colors.amber}"
    rounded: "{rounded.sm}"
    padding: 8px
---

## Overview

A Zetron é uma consultoria estratégica + tecnologia. A interface deve comunicar direção, método e operação real, sem estética sci-fi genérica. A capa pode apresentar resumos públicos de projetos; os workspaces permanecem em rotas próprias do mesmo domínio Railway, sem links na landing.

## Colors

- **Base:** `#0A0B10`; superfícies em `#11131B` e `#171A25` organizam camadas sem excesso de efeitos.
- **Texto:** `#EEF0F6` é o texto de leitura; `#9DA3B5` é reservado a contexto e apoio.
- **Ação:** violeta identifica ações principais; ciano identifica navegação e informação; âmbar identifica bloqueios com texto explícito.

## Typography

- **Manrope:** títulos, interface e corpo. O peso e o espaçamento criam uma leitura precisa e direta.
- **DM Mono:** somente datas, status e metadados operacionais.

## Layout

- Capa institucional exclusivamente na rota `/`.
- Resumos públicos de projetos podem aparecer na capa sem CTA ou rota para um workspace.
- Workspaces em rotas internas do mesmo domínio, como `/regina-8out-2026/`, sem navegação pública a partir da capa.
- No mobile, a navegação mantém a CTA principal.

## Elevation & Depth

Bordas de `#292D3A` definem agrupamentos. Profundidade é discreta e não usa sombras decorativas ou vidro genérico.

## Shapes

Componentes interativos usam raio mínimo de 8px; os blocos de projeto preservam bordas retas e estrutura editorial.

## Components

- Botão primário: abre uma conversa ou um workspace.
- Botão secundário: navega para uma seção da mesma página.
- Status pendente: sempre combina cor e texto, como “Aguardando decisões”.
- Formulário de contato: campos visíveis, rótulos persistentes e foco em ciano; o envio declara quando abre o cliente de e-mail em vez de prometer backend.

## Do's and Don'ts

- Use dados confirmados de projeto e CTA que descreve a ação.
- Mantenha foco de teclado visível e respeite `prefers-reduced-motion`.
- Não use métricas inventadas, depoimentos fictícios, gradientes decorativos, blobs ou cards genéricos.
- Não exponha dados internos, financeiros ou sensíveis enquanto não houver autenticação.
