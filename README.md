# Método CAF — Diagnóstico Financeiro

Ferramenta de diagnóstico financeiro para pequenas empresas de serviços e construção civil.

## Como usar

### Para o cliente
Acesse: https://clefigur-oss.github.io/metodo-caf/MetodoCAF_Cliente.html

### Para a consultora
Acesse: https://clefigur-oss.github.io/metodo-caf/MetodoCAF_Consultora.html

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Página de entrada |
| `MetodoCAF_Cliente.html` | Formulário de diagnóstico para o cliente |
| `MetodoCAF_Consultora.html` | Painel da consultora + geração de relatório .docx |

## Fluxo

1. Cliente acessa `MetodoCAF_Cliente.html` e responde as 15 perguntas
2. Ao enviar, recebe um link com as respostas codificadas
3. Cliente envia o link para a consultora via WhatsApp
4. Consultora abre `MetodoCAF_Consultora.html` e cola o link
5. Consultora insere nome e chave de API Anthropic e gera o relatório `.docx`
