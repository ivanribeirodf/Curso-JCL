# JCL, REXX e Painéis ISPF

Este repositório contém meus estudos e anotações referentes ao curso de **JCL (Job Control Language)**, **REXX** e **Painéis ISPF**, voltado ao ambiente z/OS.

## Objetivo

Aprofundar o conhecimento em mainframe com foco na criação e execução de jobs, desenvolvimento de scripts REXX e construção de interfaces personalizadas usando painéis ISPF.

## Conteúdo do Curso

### 1. JCL (Job Control Language)
- Conceitos básicos de JCL
- Execução de jobs simples
- Utilização de parâmetros como `JOB`, `EXEC`, `DD`
- Passagem de dados entre steps
- Condições de execução (`COND`, `IF/THEN/ELSE`)
- Sort, copy e utilities como IEBGENER, IEFBR14

### 2. REXX
- Fundamentos da linguagem REXX
- Manipulação de strings e arquivos
- Criação de scripts para automação no TSO
- Integração com ISPF e comandos do sistema

### 3. Painéis ISPF
- Conceito de diálogos ISPF
- Montagem de painéis (membros `.P`)
- Definição de mensagens, tabelas e skeletons
- Uso do ISPF Dialog Manager
- Comunicação entre painéis e programas REXX

## Estrutura do Repositório

```plaintext
📁 jcl/
    📄 exemplo1.jcl
    📄 sort_exemplo.jcl
📁 rexx/
    📄 exemplo1.rexx
    📄 utilitarios.rexx
📁 ispf/
    📄 painel1.p
    📄 painel2.p
📄 README.md
