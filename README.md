# Ferramenta_IR

> Uma ferramenta em Excel para auxiliar na organização e documentação necessária para a Declaração do Imposto de Renda (IR). Desenvolvida para ser simples, amigável e com interface que se aproxima de um aplicativo, facilitando o preenchimento e o acompanhamento dos documentos e informações exigidas.

---

## Índice

- [Visão Geral](#visão-geral)
- [Principais Recursos](#principais-recursos)
- [Quem se beneficia desta ferramenta](#quem-se-beneficia-desta-ferramenta)
- [Requisitos](#requisitos)
- [Instalação / Primeiro uso](#instalação--primeiro-uso)
- [Como usar — passo a passo](#como-usar---passo-a-passo)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Documentos e informações que a ferramenta ajuda a organizar](#documentos-e-informações-que-a-ferramenta-ajuda-a-organizar)
- [Boas práticas e recomendações](#boas-práticas-e-recomendações)
- [Segurança e privacidade](#segurança-e-privacidade)
- [Contribuições](#contribuições)
- [Histórico / Changelog](#histórico--changelog)
- [Licença](#licença)
- [Contato](#contato)

---

## Visão Geral

A Ferramenta_IR é uma planilha Excel pensada para guiar o contribuinte durante a coleta e organização das informações necessárias para a declaração do Imposto de Renda. O foco principal é reduzir a complexidade documentando somente o essencial, apresentando a experiência de uso com telas (abas) e controles que se assemelham a um aplicativo, diminuindo a sensação de "planilha" tradicional.

---

## Principais Recursos

- Interface organizada por abas com fluxo tipo "wizard" (etapas): Dados Pessoais → Rendimentos → Bens e Direitos → Dívidas e Ônus → Dependentes → Documentação.
- Seções com instruções e exemplos claros para cada tipo de informação.
- Campos de validação básica (datas, CPF, valores numéricos) para reduzir erros de digitação.
- Checklists de documentos por seção (ex.: comprovantes de rendimentos, informes bancários, notas de compra).
- Resumo automático com totais por categoria (Rendimentos, Bens, Dívidas).
- Layout pensado para aparência mais parecida com aplicativo: botões, abas e cores, diminuindo a sensação de tabela bruta.
- Modelos de exportação/impressão de relatórios (para enviar ao contador ou arquivar).

---

## Quem se beneficia desta ferramenta

- Contribuintes que desejam organizar a documentação antes de preencher a declaração online.
- Pessoas que fazem a declaração por conta própria e precisam de um guia simples.
- Contadores que desejam um checklist padronizado para enviar aos clientes.
- Usuários que preferem uma interface visual em Excel, sem necessidade de aprender um sistema complexo.

---

## Requisitos

- Microsoft Excel (versão compatível com as funcionalidades utilizadas — idealmente Excel 2016 ou superior / Office 365).
- Habilitar macros somente se o arquivo utilizar macros/VBA (verifique a política de segurança antes de habilitar).
- Sistema operacional: Windows ou macOS com suporte a Excel.

Observação: se a ferramenta utiliza macros (VBA), recomenda-se usar Excel no Windows para máxima compatibilidade.

---

## Instalação / Primeiro uso

1. Baixe o arquivo principal da ferramenta (ex.: `Ferramenta_IR.xlsx`) do repositório.
2. Faça uma cópia local do arquivo antes de começar (ex.: `Ferramenta_IR_seu_nome.xlsx`) — sempre trabalhe em uma cópia.
3. (Opcional) Habilite edição e macros se solicitado — apenas se você confiar na origem do arquivo.
4. Abra a aba inicial / tela de boas-vindas e siga o fluxo indicado.

---

## Como usar — passo a passo

1. Abra a aba "Titular" — preencha os dados iniciais.
2. Preencha os Dados Pessoais:
   - Nome completo, CPF, data de nascimento, endereço e contato.
3. Rendimentos:
   - Liste salários, aplicações financeiras, etc.
   - Anexe (ou indique) localmente os comprovantes/ informes de rendimentos.
4. Bens e Direitos:
   - Liste imóveis, veículos, contas correntes, investimentos e outros bens.
   - Informe ano, localização, proporção (no caso de co-propriedade) e valor.
5. Dívidas e Ônus:
   - Registre empréstimos, financiamentos e saldos devedores.
6. Dependentes:
   - Adicione dependentes com CPF e data de nascimento.
7. Documentação:
   - Use o checklist para marcar quais documentos você já possui.
   - Anote onde os comprovantes estão arquivados (ex.: pasta física, Drive, e-mail).
8. Conferência:
   - Confira o resumo automático para verificar totais e divergências.
9. Impressão / Envio:
   - Gere o relatório que será enviado ao contador ou arquivado.
   - Salve a cópia final com data (ex.: `Ferramenta_IR_2026-02-05.xlsx`).

Dica: mantenha os arquivos PDF/JPEG dos comprovantes organizados com nomes que referenciem o item (ex.: `Informe_Banco_X_2025.pdf`).

---

## Documentos e informações que a ferramenta ajuda a organizar

- Informes de rendimento (emprego, pensões, PJ)
- Informe de rendimentos bancários e de corretoras
- Recibos e comprovantes de despesas de até três bancos diferentes
- Notas fiscais relevantes (venda/compra de bens)
- Extratos de investimentos e saldo em contas

---
## Amostragens

<img width="1343" height="669" alt="image" src="https://github.com/user-attachments/assets/3089be7d-1a9e-4154-8c4b-ff847bc16a17" />

<img width="1342" height="681" alt="Captura de tela 2026-02-05 010852" src="https://github.com/user-attachments/assets/7b53b41a-f5d2-462b-9ad9-7408e942b450" />

<img width="1343" height="669" alt="Captura de tela 2026-02-05 010742" src="https://github.com/user-attachments/assets/f89188de-7a2f-473d-98a9-4e4aa6cb1242" />


## Boas práticas e recomendações

- Sempre faça cópia da planilha antes de editar.
- Arquive os comprovantes digitais com nomes e pastas claros.
- Não habilite macros sem confirmar a origem do arquivo.
- Verifique números e CPF duas vezes; pequenos erros causam divergências.
- Se for enviar as informações a um contador, inclua observações relevantes (alterações patrimoniais, heranças, etc).

---

## Segurança e privacidade

- A planilha contém informações sensíveis (CPF, rendimentos, valores). Mantenha o arquivo em local seguro.
- Não compartilhe o arquivo sem proteção se contiver dados pessoais — use ZIP com senha ou serviços seguros se necessário.
- Se a planilha utilizar macros, verifique o código antes de habilitar.

---

## Contribuições

Contribuições são bem-vindas! Algumas maneiras de contribuir:

- Abrir issues com sugestões de melhoria ou correções.
- Enviar pull requests com:
  - Melhorias no layout / usabilidade.
  - Traduções de textos/instruções.
  - Modelos adicionais e exemplos.
- Reportar problemas de compatibilidade entre versões do Excel.

Sugestão de fluxo:
1. Fork do repositório.
2. Criar branch com mudança (ex.: `improvement/layout`).
3. Abrir Pull Request descrevendo a alteração.

---

## Contato

- Autor / Mantenedor: JsViniciusA
- E-mail: jvinicius.alves05@gmail.com
- Repositório: https://github.com/JsViniciusA/Ferramenta_IR
