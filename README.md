# automacao-whatsapp-outlook-vba

Projeto desenvolvido em VBA para automatizar processos corporativos utilizando integração entre Excel, Outlook e WhatsApp Web.

A solução foi criada com foco em:
- produtividade operacional;
- redução de tarefas manuais;
- padronização de comunicação;
- controle de envio;
- rastreabilidade de processos.

---

# Funcionalidades

- Envio automatizado de mensagens via WhatsApp Web;
- Integração com Outlook para envio de e-mails;
- Registro automático de logs;
- Captura de IP e usuário da máquina;
- Controle de envio por código;
- Consolidação de informações por prestador;
- Identificação automática de analistas responsáveis;
- Controle de pendências financeiras;
- Registro de data e hora dos envios;
- Reprocessamento controlado por linha.

---

# Tecnologias Utilizadas

- VBA
- Excel
- Outlook
- WhatsApp Web
- Windows API
- WMI
- Automação de Processos

---

# Estrutura da Automação

```text
Planilha Excel
↓
Leitura dos dados
↓
Agrupamento por código
↓
Geração automática da mensagem
↓
Envio via WhatsApp Web
↓
Confirmação opcional de e-mail
↓
Registro de log
↓
Controle de processamento
```

---

# Estrutura do Projeto

```text
📁 assets
 ┣ fluxo-automacao.png
 ┣ interface-excel.png
 ┗ exemplo-envio.png

📁 codigos
 ┗ automacao_whatsapp_outlook.bas

README.md
LICENSE
```

---

# Principais Recursos Implementados

## Registro Automático de Logs

A automação registra automaticamente:

- Data e hora;
- Nome do destinatário;
- Telefone;
- E-mail;
- Código do processo;
- IP da máquina;
- Usuário responsável pelo envio.

---

## Integração com WhatsApp Web

A macro gera automaticamente a URL personalizada do WhatsApp Web contendo:
- mensagem formatada;
- quebra de linha;
- dados consolidados;
- informações do analista responsável.

---

## Integração com Outlook

A automação cria e-mails automaticamente utilizando:
- assunto padronizado;
- corpo dinâmico;
- informações consolidadas;
- confirmação manual antes do envio.

---

# Segurança e Controle

## Recursos aplicados

- Proteção de planilhas;
- Controle de reprocessamento;
- Registro de rastreabilidade;
- Identificação do usuário da máquina;
- Controle de status de envio.

---

# Fluxo da Macro

## Processo Executado

1. Leitura da planilha TEXTBLOCK;
2. Identificação do código atual;
3. Consolidação das competências pendentes;
4. Identificação do analista responsável;
5. Geração da mensagem automática;
6. Abertura do WhatsApp Web;
7. Confirmação opcional do envio de e-mail;
8. Registro automático em LOG_ENVIO;
9. Atualização do controle de processamento.

---

# Aprendizados do Projeto

Durante o desenvolvimento da automação foi possível aprofundar conhecimentos em:

- manipulação de dados em VBA;
- automação corporativa;
- integração entre aplicações;
- geração dinâmica de mensagens;
- rastreabilidade de processos;
- tratamento de erros;
- automação de comunicação.

---

# Melhorias Futuras

- Integração direta com API do WhatsApp;
- Painel de acompanhamento;
- Dashboard em Power BI;
- Envio automático sem intervenção manual;
- Integração com banco de dados;
- Controle avançado de auditoria;
- Interface gráfica personalizada.

---

# Observações

Este projeto foi desenvolvido para fins de automação corporativa e aprendizado técnico utilizando VBA e integração entre aplicações Microsoft Office.

Dados sensíveis, contatos reais e informações corporativas foram anonimizados para publicação no GitHub.
