# 🤖 RPA - Extrator Automático de Cotação de Moedas

## 📝 Descrição do Projeto
Este projeto consiste em um robô de **RPA (Robotic Process Automation)** desenvolvido no **Power Automate Desktop**. O objetivo é eliminar a tarefa manual de monitoramento de câmbio, automatizando a extração da cotação do Dólar (USD/BRL) diretamente do Google Finance e alimentando um banco de dados em Excel de forma autônoma.

## 🚀 Funcionalidades
* **Extração Web:** Captura de dados em tempo real utilizando seletores web dinâmicos e extensão de navegador.
* **Histórico Inteligente:** Implementação de lógica para identificar a **primeira linha livre** no Excel, permitindo o acúmulo de dados sem sobrescrever registros anteriores.
* **Execução Autônoma:** Agendamento via **Windows Task Scheduler** para execução diária às 10:30.
* **Tratamento de Exceções:** Configuração de regras de erro para garantir a estabilidade do fluxo.

## 🛠️ Tecnologias Utilizadas
* **Microsoft Power Automate Desktop**
* **Microsoft Excel**
* **Windows Task Scheduler** (Orquestração)

## 📸 Demonstração

### Fluxo de Trabalho no Power Automate
![Fluxo do Robô](fluxo-automacao.png)

### Histórico de Dados Gerado (Excel)
![Histórico no Excel](historico-excel.png)

### Agendamento Automático
![Agendador de Tarefas](agendador-windows.png)

---
*Projeto desenvolvido por Natanael Lira Ferreira - Estudante de Engenharia de Software.*
