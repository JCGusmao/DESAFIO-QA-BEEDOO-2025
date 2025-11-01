# Desafio QA Beedoo 2025

## Visão Geral
Este projeto faz parte do **Desafio QA Beedoo 2025**.  

A aplicação testada permite o gerenciamento de cursos, incluindo **cadastro, listagem e exclusão**.

## Objetivo
O objetivo deste desafio é:

- Realizar a análise funcional do módulo de cursos
- Criar **User Stories** completas
- Desenvolver **casos de teste** de sucesso e erro
- Documentar todas as evidências
- Organizar os artefatos em um repositório profissional e rastreável

## Escopo Testado
Funcionalidades avaliadas:

- Cadastro de curso
- Listagem de cursos cadastrados
- Exclusão de cursos existentes
- Validação de campos obrigatórios e formatos
- Campos condicionais (Presencial/Online)
- Mensagens de feedback (sucesso/erro)

Foram considerados **cenários positivos, negativos e fluxos de exceção** para garantir cobertura completa.

## Metodologia de Análise

Para garantir a cobertura completa do módulo de cursos, foram utilizados **testes funcionais**, focando nas funcionalidades principais: Cadastro, Listagem e Exclusão de cursos.  

A abordagem combinou:

- **Testes exploratórios:** Navegação e análise inicial do sistema para compreensão dos fluxos, identificação de regras de negócio e possíveis inconsistências.
- **Testes baseados em critérios de aceitação:** Criação de User Stories e casos de teste detalhados contemplando cenários de sucesso, falha e exceção.
- **Registro de evidências:** Vídeos em formato MP4 das execuções.
- **Relatório de bugs:** Documentação detalhada de todos os problemas encontrados, incluindo resultado esperado, resultado real e cenários Gherkin/passo a passo.

Essa abordagem garante **rastreabilidade, clareza e cobertura de cenários críticos** do sistema.

## Decisões para Criação das User Stories
As User Stories foram criadas considerando:

- Comportamento observado durante os testes exploratórios
- Visão do usuário final
- Cobertura de cenários positivos e negativos
- Boas práticas de QA e testabilidade
- Critérios objetivos de aceitação:
  - Campos obrigatórios e limites de caracteres
  - Formatos válidos (datas, URLs, números inteiros)
  - Campos condicionais de acordo com o tipo de curso
  - Feedback esperado ao usuário (mensagens de erro e sucesso)

As User Stories estão documentadas no arquivo [user-stories](./docs/user_stories.pdf).

## Casos de Teste
Todos os casos de teste foram documentados em [Google Sheets](https://docs.google.com/spreadsheets/d/1oEXmX5vJLv0jNxLsgafEjWjV4Cr1sZnceDdIZELmBIc/edit?usp=sharing).  

Incluem cenários de:

- Sucesso
- Falha / validação de campos obrigatórios
- Exceção / fluxos inesperados
- Campos condicionais (Presencial / Online)

## Bug Reports
O relatório de bugs detalha todos os problemas encontrados, com:

- Resultado esperado
- Resultado real
- Cenário Gherkin / Passo a passo
- Evidências visuais

Link do relatório: [Google Docs Bug Report](https://docs.google.com/document/d/1iTpHxwnokGXtkM8rBpFfrMf5r8NVdcaIrTr6KFT8jsY/edit?usp=sharing).

## Evidências
Todos os testes realizados foram registrados em vídeo (MP4) e armazenados no Google Drive:

[Link para evidências](https://drive.google.com/drive/folders/1_rYKXlgtEZL3Ry4uqUsTndZrqt8H8z8Q?usp=sharing)

## Melhorias Sugeridas
Algumas sugestões de melhoria para o sistema, identificadas durante a análise:

### Tela Listar Cursos
- Inserir opção de **Editar curso**
- Caso não haja cursos cadastrados, exibir texto: "Ainda não existem cursos cadastrados"
- Exibir o nome do instrutor no card do curso

### Tela Cadastrar Curso
- Indicar campos obrigatórios visualmente
- Inserir limite de caracteres nos campos
- Aplicar todas as validações discutidas nos casos de teste
