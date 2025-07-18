# WhatsAutoSend

Projeto de automação para enviar mensagens pelo WhatsApp Web a partir de uma planilha Excel.

---

## Descrição

Este projeto permite que você envie mensagens automaticamente para uma lista de contatos armazenados em uma planilha Excel.  
O script usa Selenium para abrir o WhatsApp Web, carregar os contatos, e enviar mensagens personalizadas.

---

## Tecnologias utilizadas

- Python 3.7+  
- Selenium  
- Pandas  
- WebDriver Manager (opcional, para gerenciar o ChromeDriver automaticamente)  
- Google Chrome  

## Funcionalidades

- Lê contatos e mensagens de uma planilha Excel (.xlsx).  
- Abre o WhatsApp Web para envio das mensagens.  
- Envia mensagens personalizadas para cada contato automaticamente.  
- Tratamento básico de erros para contatos inválidos ou problemas no envio.

---

## Pré-requisitos

- Python 3.7 ou superior  
- Google Chrome instalado  
- ChromeDriver compatível com a versão do Chrome instalada (ou webdriver-manager para facilitar)  
- Bibliotecas Python:  
  - selenium  
  - pandas

Instale as dependências com:

```
pip install selenium pandas webdriver-manager
```

## Como usar

```
jupyter notebook
```
1. Abra o arquivo .ipynb do projeto.

2. Prepare sua planilha Excel com as colunas:

- Pessoa (nome do contato)
- Número (número no formato internacional, ex: 5511999999999)
- Mensagem (texto da mensagem personalizada)

3. Execute as células do notebook seguindo a ordem.

4. Faça login no WhatsApp Web quando o navegador abrir.

5. O notebook enviará as mensagens automaticamente.

# ⚠️ Atenção, Use com responsabilidade para não ser bloqueado pelo WhatsApp.
Respeite as políticas do WhatsApp para envio de mensagens.

### Licença
MIT License

### Autor by Guzitos
