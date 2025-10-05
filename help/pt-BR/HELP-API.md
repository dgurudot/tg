# 🔑 Gerenciamento de API

A tela **Gerenciamento de API** permite que você gerencie suas chaves de API do TradeGrub — usadas para integrações seguras com serviços externos, como **TradingView** ou **APIs REST personalizadas**.

---

## 📋 Tabela de Chaves de API

Todas as chaves de API existentes são exibidas em uma tabela simples e fácil de ler.

### Colunas da Tabela
- **Nome** → O rótulo que você atribui ao criar a chave.
- **Chave** → O identificador exclusivo usado para autenticação.
- **Permissões** → Define o que a chave pode acessar (por exemplo, `TradingView`, `REST`).
- **Data de Criação** → A data em que a chave foi gerada.
- **Ações** → Use o ícone 🗑️ **Excluir** para remover a chave de API permanentemente.

> ⚠️ **Importante:** Excluir uma chave de API revoga imediatamente seu acesso.
> Quaisquer serviços conectados (como webhooks do TradingView) que utilizem essa chave deixarão de funcionar.

---

## ➕ Criando uma Nova Chave de API

Toque no botão **“+” (Adicionar)** no canto superior direito para criar uma nova chave.
Você será solicitado a especificar:

| Campo | Descrição |
|--------|--------------|
| **Nome** | Um nome amigável para identificar esta chave (ex.: *Sinais do TradingView*). |
| **Permissões** | Escolha uma ou ambas: - **TradingView** → Necessária para receber e processar sinais de webhooks do TradingView. - **REST** → Necessária para acessar as APIs REST do TradeGrub. |

Após a criação, a nova chave de API aparecerá instantaneamente na sua visualização de tabela.

> 💡 Você pode criar várias chaves — por exemplo, uma para sua conta pessoal do TradingView e outra para sua integração REST automatizada.

---

## 🔐 Visibilidade do Segredo da API

Quando uma nova chave de API é criada, um **segredo** é gerado e exibido **apenas uma vez** por motivos de segurança.
Você terá a opção de **copiá-lo** durante a criação — certifique-se de armazená-lo com segurança.

> ⚠️ **Observação:** 
> O segredo **não pode ser visualizado novamente**.
> Você deve salvá-lo com segurança, pois ele será necessário ao usar a chave de API em integrações do **TradingView** ou da **API REST**.

---
## ⚙️ Melhores Práticas

- Mantenha suas chaves de API **privadas e seguras**.
- Use **chaves separadas** para diferentes integrações.
- Revogue (exclua) chaves não utilizadas ou comprometidas imediatamente.
- Nunca compartilhe sua chave de API publicamente ou em capturas de tela.

---

## 🧩 Exemplos de Casos de Uso

| Cenário | Permissão Necessária |
|-----------|---------------------|
| Enviando sinais de compra/venda do TradingView | TradingView |
| Fazendo chamadas de API REST para o TradeGrub | REST |
| Configuração combinada de automação de negociação | TradingView + REST |

---

## 🆘 Dicas
- Toque no ícone **info (ℹ️)** no canto superior direito para obter ajuda rápida.
- Você sempre pode recriar uma chave caso ela seja excluída acidentalmente.
- As ações da chave de API são sincronizadas instantaneamente com sua conta — sem a necessidade de reiniciar o aplicativo.
