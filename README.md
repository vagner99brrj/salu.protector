## Salu - Conscientização e Prevenção de Golpes

O Salu é um projeto acadêmico desenvolvido para enfrentar o crescimento de fraudes e golpes no cenário digital brasileiro. O objetivo central é fornecer uma plataforma informativa e educativa que ajude a população a reconhecer padrões suspeitos e agir de forma preventiva.

## 🎯 Propósito e Público-Alvo

Propósito: Orientar, conscientizar e informar cidadãos sobre métodos comuns de estelionato (bancário, telefônico e digital).

## Público-Alvo: 

População em geral, com foco especial em pessoas com menor familiaridade tecnológica ou grupos vulneráveis a abordagens fraudulentas.

## 📂 Estrutura do Projeto

A organização do repositório segue um padrão de separação de responsabilidades para facilitar a manutenção por múltiplos desenvolvedores:

docs/: Documentação técnica, diagramas de fluxo, requisitos e atas de reuniões do grupo.

src/: Código-fonte da aplicação (Frontend e Backend).

tests/: Suítes de testes unitários e de integração para garantir a confiabilidade do sistema.

## Arquivos Principais

.gitignore: Define quais arquivos e diretórios não devem ser rastreados pelo Git (ex: pastas de dependências e arquivos de sistema).

LICENSE: Define os termos de uso e distribuição do código.

README.md: Este arquivo, servindo como guia principal do projeto.

.env: Arquivo para variáveis de ambiente (ex: chaves de API). Atenção: Nunca versione este arquivo; utilize o .env.example como modelo.

## 🌿 Fluxo de Branches (Git)

Para manter a integridade do código, adotamos o seguinte modelo de ramificação:

main: Versão estável e finalizada. Apenas código revisado e aprovado chega aqui.

develop: Branch principal de integração. Todos os novos recursos são mesclados aqui antes de irem para a main.

feature/nome-da-tarefa: Branches temporárias criadas para o desenvolvimento de funcionalidades específicas.

Como contribuir:
Crie uma branch a partir da develop:

git checkout -b feature/nome-da-funcionalidade

Após finalizar, abra um Pull Request para a branch develop.

## 🛠️ Padrões de Desenvolvimento

Boas Práticas de Commit
Os commits devem ser claros e em inglês (conforme padrão do time), seguindo o formato:
tipo: descrição curta e objetiva

Exemplo: feat: add scam alert component

Exemplo: fix: resolve broken link in footer

Documentação
Local: Toda documentação técnica deve residir na pasta docs/.

Escrita: Use linguagem objetiva e padronizada. Mantenha os diagramas e textos atualizados conforme o projeto evolui.

## 🚀 Instruções Iniciais

Clonando o Repositório
Para copiar o projeto para sua máquina local, utilize o comando:

PowerShell
git clone https://github.com/usuario/salu.git
Execução Local
Navegue até a pasta do projeto: cd salu

Instale as dependências (comando varia conforme a tecnologia escolhida).

Configure o arquivo .env com base no .env.example.

Inicie o ambiente de desenvolvimento.