# 📬 MailingAutoFlow

O **MailingAutoFlow** é uma aplicação em Python desenvolvida para **automatizar a geração, organização e envio de mailings de cobrança** utilizados diariamente pela equipe.  
Este sistema foi criado para garantir **continuidade operacional durante meu período de férias**, reduzindo a dependência manual e permitindo que o coordenador e o time executem o processo de forma simples, rápida e sem riscos de erros.

---

## 🚀 Objetivo do Projeto

A rotina diária de geração de mailings exige consultas SQL complexas, organização dos dados, criação de arquivos CSV e posterior envio para o sistema **OLOS**.  
Antes desta automação, todo o processo era realizado manualmente, consumindo tempo e gerando risco operacional.

O MailingAutoFlow foi criado para:

- Automatizar consultas SQL de acordo com o tipo de mailing e carteira selecionada.
- Gerar CSVs formatados corretamente para aceitação no OLOS.
- Fazer upload automático do mailing para o portal.
- Reduzir o tempo de execução das rotinas.
- Garantir continuidade enquanto estou de férias, permitindo que a operação siga normalmente.

---

## 🖥️ Funcionalidades Principais

- **Interface gráfica (Tkinter)** intuitiva para uso do time.
- Seleção automática do mailing recomendado do dia.
- Geração de três tipos principais de mailing:
  - **Quebras & Rejeitadas**
  - **CPC (Contato Pessoa Certa)**
  - **Nunca Contatados**
- Escolha da carteira de cobrança (517, 518, 519).
- Execução de consultas SQL complexas com filtros automatizados.
- Formatação e exportação do CSV no padrão exigido pelo OLOS.
- Login, navegação e upload automático via **Selenium WebDriver**.
- Geração de logs e feedback visual para o usuário.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Tkinter** — Interface gráfica
- **MySQL Connector** — Acesso ao banco Gecobi
- **Selenium WebDriver** — Automação web para upload no OLOS
- **Chrome WebDriver**
- **CSV Writer**
- **Os / Time / Datetime**

---

## 📁 Estrutura do Projeto

- **Interface gráfica** para seleção do mailing
- Sistema de **consultas SQL** pré-definidas e otimizadas
- Geração automática de **CSV**
- Automação do processo de **upload**
- Controle de carteiras e mailings recomendados por dia da semana

---

## ▶️ Como Utilizar

1. Abrir o sistema **AgendaMailingApp**.
2. Selecionar a **carteira** e o **mailing**, ou usar a sugestão automática do dia.
3. Clicar em **Gerar Mailing**.
4. Ao fechar a aplicação, o sistema automaticamente:
   - Abre o OLOS,
   - Faz login,
   - Envia o arquivo CSV para importação.

---

## 👨‍💻 Sobre o Desenvolvimento

O projeto foi criado por mim com o intuito de **automatizar uma rotina essencial**, permitindo que o processo continue funcionando mesmo durante minha ausência por férias.  
Ele garante que o coordenador e o time possam executar a tarefa sem dificuldade, com confiabilidade e com dedicação mínima.

---

## 📌 Status do Projeto

✔️ Estável  
✔️ Automatizado  
✔️ Fácil de usar  
➕ Aberto para melhorias futuras

