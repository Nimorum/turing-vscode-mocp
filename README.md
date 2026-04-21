# Suporte Comunitário MOCP para VS Code

Uma extensão colaborativa de suporte à linguagem **MOCP** (My Own C in Português) para o Visual Studio Code. Desenvolvida para fornecer *Syntax Highlighting* avançado e melhorar a experiência de desenvolvimento na escrita de scripts `.mocp`.

## 🎓 Sobre a Universidade Aberta e o Projeto
Este projeto nasceu no âmbito da Unidade Curricular de **Compilação** da **Universidade Aberta (UAb)** - Ano Letivo 2025/2026.

Iniciado pela Equipa Turing (João Fialho e João Pereira), o repositório evoluiu com a missão de ser um espaço de código aberto para **todos os estudantes da UAb**. O nosso objetivo é acompanhar coletivamente a evolução da gramática MOCP e fornecer uma ferramenta visual robusta de apoio à construção dos compiladores Front-End (ANTLR) e Back-End.

## 🤝 Contribui para o Projeto
Queremos que esta ferramenta seja construída *pela* comunidade e *para* a comunidade académica! Encorajamos todos os colegas a interagir com o código. Se tens ideias para melhorar a gramática, otimizar a extensão ou adicionar novas funcionalidades:
1. Faz um *Fork* deste repositório.
2. Implementa as tuas melhorias ou correções.
3. Abre um *Pull Request*.

Toda a ajuda é bem-vinda para tornar o ecossistema da linguagem MOCP mais forte.

## 🚀 Roadmap: Servidor de IntelliSense
À medida que a linguagem MOCP avança, o próximo grande objetivo para esta extensão será o desenvolvimento de um **Servidor de IntelliSense (Language Server)** feito à medida. A intenção é fornecer funcionalidades avançadas diretamente no VS Code, tais como autocompletar inteligente, sugestões de código baseadas no contexto e deteção de erros de sintaxe em tempo real.

## ✨ Funcionalidades Atuais
- **Syntax Highlighting Completo:** Cores precisas para palavras-chave (`se`, `enquanto`, `para`, `retornar`).
- **Reconhecimento de Tipos:** Suporte nativo para `inteiro`, `real` e `vazio`.
- **Funções Built-in:** Destaque especial para funções nativas de I/O (`ler`, `escrever`, `lerc`, `escrevers`, etc.).
- **Deteção de Literais:** Formatação correta de números, strings e literais.

## 📦 Como Instalar

### Método 1: Testar Temporariamente (Modo de Desenvolvimento)
Para testar esta extensão num ambiente isolado:
1. Clona este repositório: `git clone https://github.com/teu-user/turing-vscode-mocp.git`
2. Abre a pasta do projeto no VS Code.
3. Pressiona `F5` para abrir uma nova janela do VS Code (Extension Development Host).
4. Nessa nova janela, abre qualquer ficheiro `.mocp` e valida o funcionamento.

### Método 2: Instalar Permanentemente (Local)
Para manteres o suporte à linguagem MOCP sempre ativo no teu editor:
1. Clona ou faz o download deste repositório.
2. Copia a pasta principal do projeto.
3. Abre o Explorador de Ficheiros do teu sistema e navega para a pasta de extensões do VS Code:
   - **Windows:** `%USERPROFILE%\.vscode\extensions`
   - **macOS / Linux:** `~/.vscode/extensions`
4. Cola a pasta copiada lá dentro.
5. Reinicia o VS Code. Os teus ficheiros `.mocp` terão agora *syntax highlighting* nativo.

---
*Construído com dedicação pela comunidade da Universidade Aberta.* 💻