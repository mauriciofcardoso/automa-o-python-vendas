# Automação de Relatório Diário de Vendas com Python

Projeto desenvolvido para automatizar a consulta de vendas do dia anterior, calcular indicadores e preparar o envio de um relatório por e-mail.

## O que o projeto faz

- Acessa uma pasta do Google Drive pelo navegador;
- Baixa a planilha de vendas;
- Calcula o faturamento total e a quantidade de produtos vendidos;
- Prepara um e-mail com os resultados.

## Tecnologias utilizadas

- Python
- PyAutoGUI
- Pandas
- OpenPyXL
- Pyperclip

## Requisitos

- Python instalado;
- Google Chrome instalado e aberto com acesso à conta necessária;
- Planilha de vendas com as colunas `Valor Final` e `Quantidade`;
- Bibliotecas instaladas:

```bash
pip install pyautogui pandas openpyxl pyperclip
