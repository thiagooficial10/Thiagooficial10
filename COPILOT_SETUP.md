# Guia de Configuração do GitHub Copilot com Claude Opus no VSCode

## 🚀 Pré-requisitos
- GitHub Pro, GitHub Team, ou GitHub Enterprise
- Visual Studio Code instalado
- Acesso ao GitHub Copilot ativado na sua conta

## 📦 Passo 1: Instalar as Extensões do GitHub Copilot

1. Abra o VSCode
2. Vá para a aba de Extensões (Ctrl+Shift+X ou Cmd+Shift+X no Mac)
3. Procure e instale as seguintes extensões:
   - **GitHub Copilot** (github.copilot)
   - **GitHub Copilot Chat** (github.copilot-chat)

## 🔐 Passo 2: Fazer Login no GitHub

1. Após instalar as extensões, você verá uma notificação para fazer login
2. Clique em "Sign in to GitHub"
3. Autorize o VSCode a acessar sua conta do GitHub
4. Verifique se o ícone do Copilot aparece na barra de status (canto inferior direito)

## ⚙️ Passo 3: Verificar as Configurações

1. Abra as Configurações do VSCode (File > Preferences > Settings ou Ctrl+,)
2. Procure por "Copilot"
3. Certifique-se de que as seguintes opções estão habilitadas:
   - ✅ `GitHub Copilot: Enable` deve estar marcado para todas as linguagens
   - ✅ `Editor: Inline Suggest Enabled` deve estar habilitado
   - ✅ `GitHub Copilot: Editor Enable Auto Completions` deve estar habilitado

## 🤖 Passo 4: Acessar o Claude Opus (Copilot Chat)

Com o GitHub Pro, você tem acesso a modelos avançados como o Claude Opus através do Copilot Chat:

1. Abra o Copilot Chat:
   - Clique no ícone do chat na barra lateral esquerda
   - Ou use o atalho: Ctrl+Shift+I (Cmd+Shift+I no Mac)
   - Ou abra a paleta de comandos (Ctrl+Shift+P) e digite "Copilot Chat"

2. No chat, você pode:
   - Fazer perguntas sobre seu código
   - Pedir explicações
   - Solicitar geração de código
   - Pedir refatorações

3. Para usar o Claude Opus especificamente:
   - O modelo é selecionado automaticamente com base na sua assinatura
   - Usuários do GitHub Pro têm acesso aos modelos mais avançados incluindo Claude Opus

## 🔧 Solução de Problemas

### O ícone do Copilot não aparece
1. Verifique se você está logado: clique no ícone de conta no canto inferior esquerdo
2. Certifique-se de que sua assinatura GitHub Pro está ativa
3. Tente recarregar o VSCode (Ctrl+Shift+P > "Developer: Reload Window")

### As sugestões não aparecem
1. Verifique se o Copilot está ativo (o ícone na barra de status não deve estar riscado)
2. Verifique se inline suggestions estão habilitadas nas configurações
3. Tente pressionar Alt+\ (ou Option+\ no Mac) para acionar manualmente uma sugestão

### Não vejo opção para Claude Opus
1. O Claude Opus está disponível através do Copilot Chat, não como uma opção separada
2. Certifique-se de que você tem o GitHub Copilot Chat instalado
3. Com GitHub Pro, você automaticamente tem acesso aos melhores modelos disponíveis

### Verificar se o Copilot está funcionando
1. Abra um arquivo de código (ex: Python, JavaScript)
2. Comece a escrever um comentário descrevendo o que você quer fazer
3. Pressione Enter e aguarde - o Copilot deve sugerir código
4. Use Tab para aceitar a sugestão ou Esc para rejeitar

## 📚 Recursos Adicionais

- [Documentação Oficial do GitHub Copilot](https://docs.github.com/en/copilot)
- [GitHub Copilot no VSCode](https://code.visualstudio.com/docs/editor/github-copilot)
- [Guia de início rápido](https://docs.github.com/en/copilot/getting-started-with-github-copilot)

## 💡 Dicas de Uso

1. **Comentários descritivos**: Escreva comentários claros do que você quer que o código faça
2. **Use o chat**: Para questões complexas, use o Copilot Chat em vez de apenas sugestões inline
3. **Contexto**: O Copilot aprende com o contexto dos arquivos abertos na sua workspace
4. **Atalhos úteis**:
   - Alt+\ : Acionar sugestão manualmente
   - Alt+] : Próxima sugestão
   - Alt+[ : Sugestão anterior
   - Ctrl+Shift+I : Abrir Copilot Chat

## ✨ Verificação Final

Para confirmar que tudo está funcionando:

1. ✅ Você vê o ícone do Copilot na barra de status (canto inferior direito)
2. ✅ O ícone mostra que está ativo (não riscado)
3. ✅ Você consegue abrir o Copilot Chat (ícone de chat na barra lateral)
4. ✅ Quando você escreve código, aparecem sugestões inline (texto em cinza)

Se todos os itens acima estão funcionando, seu GitHub Copilot com acesso ao Claude Opus está configurado corretamente! 🎉
