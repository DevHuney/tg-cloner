# TG Cloner 🤖

**Clonador de Canais/Grupos do Telegram**  
*Clone mensagens, mídias e documentos entre canais de forma automatizada e eficiente.*

---

## 📌 Visão Geral
O **TG Cloner** é um script Python desenvolvido para copiar mensagens (texto, mídia, vídeos, documentos e stickers) de um canal/grupo do Telegram para outro. Ideal para:
- Migração de conteúdo entre canais  
- Backup automatizado  
- Replicação de posts em massa  

Funciona localmente mas também no **Google Colab** com persistência de dados via **Google Drive**.  

---

## ⚙️ Funcionalidades
- **Clone de Conteúdo**:
  - Mensagens de texto  
  - Vídeos (suporte a streaming)  
  - Documentos/PDFs  
  - Stickers  
  - Outras mídias (imagens, áudios)  

- **Recursos Avançados**:
  - Retentativas automáticas em caso de falha  
  - Intervalos aleatórios entre envios (evita bloqueios)  
  - Logs coloridos e detalhados  
  - Suporte a contas marcadas como "spammer"  
  - Persistência de sessão no Google Drive  

---

## 📋 Pré-requisitos 
1. **API_ID** e **API_HASH** obtidos em [my.telegram.org](https://my.telegram.org/)  

---

## 🛠️ Instalação & Configuração

### 1. Obtenha suas credenciais do Telegram
- Acesse [my.telegram.org](https://my.telegram.org/)  
- Na seção **API development tools**, registre um app e obtenha:  
  - `API_ID`  
  - `API_HASH`  

### 2. Execute no Google Colab
```python
# Cole o código completo fornecido em uma célula do Colab
# Siga as instruções interativas para configurar
