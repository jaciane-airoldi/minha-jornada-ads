# 🐞 Bug Report - Falha de validação de login

## ID do Bug
BUG-001

## Título
Sistema permite tentativa de login sem informar senha

## Ambiente
Aplicação Web

## Descrição

Ao tentar realizar login sem preencher o campo de senha,
o sistema permite continuar o processo sem apresentar uma mensagem
de validação adequada.

## Passos para reproduzir

1. Acessar a tela de login.
2. Informar um usuário válido.
3. Deixar o campo senha vazio.
4. Clicar no botão "Entrar".

## Resultado esperado

O sistema deve informar que a senha é obrigatória.

## Resultado encontrado

O sistema não apresenta uma mensagem clara ao usuário.

## Severidade

Média ⚠️

## Status

Aberto 🔎

## Sugestão de melhoria

Adicionar uma mensagem de validação orientando o usuário.