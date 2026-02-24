# 📂 Documentação Técnica das Automações - Portal Digicon

Bem-vinda! Este guia explica como as nossas automações estão estruturadas. Diferente de scripts simples, nosso código utiliza **Funções** e **Lógica Condicional** para ser mais eficiente e inteligente.

### 🧠 Conceitos Chave do Nosso Código

Para entender a lógica por trás dos arquivos, existem dois conceitos principais:

1.  **Funções (blocos de ação)**: No código, você verá termos como `fazerLogin()` ou `trocarPerfil()`. Isso são funções. Em vez de escrever 20 linhas de código toda vez que precisamos logar, criamos uma função que guarda essas 20 linhas. Assim, o código fica mais limpo e fácil de consertar.
2.  **Lógica Condicional (tomada de decisão)**: O código é capaz de decidir o que fazer. Por exemplo: *"SE o usuário já é Aluno, não faça nada. CASO CONTRÁRIO, troque o perfil para Aluno"*. Isso evita erros e cliques desnecessários.

### 📚 Pequeno Dicionário de Comandos
Estes são os comandos básicos que as funções utilizam para interagir com o portal:

- **`cy.visit`**: Abre uma página específica.
- **`cy.get`**: Localiza um botão ou campo na tela.
- **`cy.click`**: Realiza o clique.
- **`cy.type`**: Digita informações.
- **`cy.wait`**: Aguarda alguns segundos para o sistema processar.
- **`cy.contains`**: Busca um texto específico na tela para clicar nele.

---
*Documentação preparada por Caio e Antigravity.*
