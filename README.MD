# 🦁 Organizador de Declaração de Imposto de Renda

![Capa do Projeto](print.png)

![Segunda Imagem](print-2.png)

![Terceira Imagem](print-3.png)

## 📋 Sobre o Projeto

Este projeto consiste em uma ferramenta desenvolvida inteiramente em **Microsoft Excel** com o objetivo de facilitar a organização, validação e centralização das informações necessárias para a Declaração de Imposto de Renda. 

O projeto foi construído como desafio prático (LAB) da **DIO (Digital Innovation One)**, aplicando conceitos avançados de planilhas para criar um agregador de dados com interface amigável, navegação fluida e validação de entradas.

Para tornar o projeto de portfólio mais criativo e evitar o uso de dados sensíveis reais, a base de testes foi preenchida com personagens icônicos e situações fictícias da franquia de jogos **The Sims** (como moradores de *Sunset Valley* e *StrangerVille*), garantindo a demonstração completa das funcionalidades de forma segura e divertida.

## ✨ Funcionalidades

- **Navegação Facilitada:** Menus interativos para transitar entre as diferentes seções da declaração.
- **Validação de Dados Estruturada:** - Máscaras automáticas para Título de Eleitor (12 dígitos formatados em blocos).
  - Formatação inteligente para Telefones Fixos e Celulares (padrão de DDD brasileiro).
  - Máscaras de CEP.
  - Listas suspensas dinâmicas baseadas em tabelas auxiliares (ex: Lista com mais de 70 códigos de Bancos brasileiros).
- **Cálculo de Idade Automatizado:** Uso de funções temporais (`DATADIF`) para identificar idades e status de dependentes.
- **Controle de Informes e Notas:** Organização de anexos, categorias de entradas (ex: holerites) e rendimentos bancários com totais automatizados.

## 🗂️ Estrutura da Planilha

O agregador está dividido nas seguintes seções (abas):

1. **Titular:** Dedicada aos dados pessoais do declarante (Nome, CPF, Nascimento, Endereço, Contatos e status de cônjuge/dependente).
2. **Informes:** Centralização dos rendimentos bancários, valores atuais e controle de documentos em PDF anexados (ex: Itaú, Nubank, Caixa).
3. **Notas:** Registro de entradas e notas bancárias, como extratos de holerites, categorizados por data e valor.
4. **Tabelas (Apoio):** Aba oculta/auxiliar de *back-end* que armazena as listas de validação de dados (como a lista completa de bancos autorizados).

## 🛠️ Tecnologias e Recursos Utilizados

- **Microsoft Excel** (Fórmulas, Formatação Condicional, Validação de Dados, Máscaras Personalizadas)
- **Markdown** (Para a documentação do repositório)
- **Git & GitHub** (Para versionamento e compartilhamento do portfólio)

## 🚀 Como Utilizar

1. Faça o clone deste repositório ou baixe o arquivo `.xlsx` diretamente.
   ```bash
   git clone [https://github.com/SEU_USUARIO/nome-do-repositorio.git](https://github.com/SEU_USUARIO/nome-do-repositorio.git)
