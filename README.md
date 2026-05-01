# CobFlow – Sistema Web de Controle de Cobranças

Sistema web de gestão de cobranças desenvolvido para escritórios de contabilidade.
Substitui planilhas paralelas e processos manuais, centralizando clientes, parcelas
e vencimentos em um único lugar — sem instalação, sem servidor, roda direto no navegador.

## O problema que resolve

O processo comum em escritórios exige lançar as mesmas informações em dois lugares:
uma planilha de controle e um sistema externo. Isso gera retrabalho, erros e perda
de visibilidade sobre inadimplentes. O CobFlow elimina essa etapa intermediária.

## Funcionalidades

**Gestão de clientes**
- Cadastro com ID único e bloqueio automático de duplicatas

**Controle de cobranças**
- Parcelamento de 1 a 36 parcelas com datas geradas automaticamente
- Edição individual de valor e data por parcela
- Status automático por parcela: A Vencer, Vencido, Pago ou Parcial
- Reagendamento com três escopos: parcela atual, atual e seguintes, ou todas

**Baixa de pagamentos**
- Aceita pagamento total ou parcial
- Calcula saldo restante automaticamente
- Mantém status Parcial até quitação completa

**Dashboard operacional**
- Indicadores em tempo real: vence hoje, vence amanhã, em atraso, pago hoje
- Clique no indicador filtra a tabela automaticamente

**Mini CRM por cliente**
- Histórico completo de cobranças, parcelas, valores e observações por cliente
- Tags de observação rápida por parcela

**Filtros inteligentes**
- Filtro combinado por período, mês, status, nome e ID — tudo em tempo real

**Relatório de baixas para CVSoft**
- Filtrado pela data de lançamento no sistema
- Permite replicar exatamente o que foi movimentado em determinado dia na CVSoft
- Exportação em PDF com todos os campos necessários

**Exportação e backup**
- Exportação em Excel (SheetJS) e PDF de qualquer visualização filtrada
- Backup completo em JSON com restauração total dos dados
- Registro de data e hora do último backup

**Integração com FinRecon**
- Importação do arquivo JSON gerado após conciliação bancária
- Baixas aplicadas automaticamente nas parcelas corretas de cada cliente

**Outros**
- Modo claro, escuro e automático com preferência salva entre sessões
- Funciona 100% offline, sem servidor ou conexão com internet

## Tecnologias

HTML, CSS e JavaScript puro — sem frameworks ou dependências de backend.  
Armazenamento via localStorage. Exportação Excel via SheetJS.

## Integração

O CobFlow recebe o arquivo JSON exportado pelo FinRecon após a conciliação bancária
e aplica as baixas automaticamente, eliminando retrabalho entre os dois sistemas.

## Status

✅ Em uso no dia a dia — rodando localmente.  
🚧 Deploy online em breve.

## Desenvolvido por

Maria Eduarda Cardoso — Analista Financeira  
[LinkedIn](https://www.linkedin.com/in/maria-eduarda-cardoso)
