# 🛠️ Branch de Desenvolvimento (dev)

Bem-vindo à branch **dev** do repositório `DocumentacaoPbi`. Este é o nosso ambiente de colaboração e integração para o time de Estratégia e BI.

---

## 🎯 Propósito
Esta branch serve como um **estágio intermediário** (staging). Nenhuma alteração deve ser feita diretamente na branch `principal` (main). 
O objetivo aqui é:
* Testar novas medidas DAX e ajustes de modelo.
* Centralizar as colaborações do time antes da publicação oficial.
* Garantir a integridade dos dados através de revisões.

---

## 🔄 Fluxo de Trabalho (Workflow)

Para manter a organização, seguimos este processo simples:

1.  **Edição no Power BI Service:** O time realiza os ajustes necessários (medidas, tabelas, etc.) diretamente no Workspace conectado a esta branch.
2.  **Commit (Salvar):** Ao finalizar uma alteração, utilize o botão **Source Control** no Power BI.
    * *Importante:* Sempre escreva uma mensagem de commit clara (Ex: "Ajuste na meta de vendas - Fev/26").
3.  **Sincronização:** Após o commit, os arquivos são atualizados automaticamente aqui no GitHub.
4.  **Pull Request (PR):** Quando o trabalho na `dev` estiver validado e pronto para o "ar", abrimos um PR para levar essas mudanças para a branch `principal`.

---

## ⚠️ Regras de Ouro
* **Nunca faça Merge direto na `principal`:** Tudo deve passar primeiro por esta branch.
* **Documente suas Medidas:** Se criar uma regra de negócio complexa, adicione uma breve descrição no commit.
* **Recuperação:** Se algo quebrar no Power BI, use o histórico de commits desta branch para reverter o item ao estado anterior.

---
*Mantido por: [Natasha Sousa]*
