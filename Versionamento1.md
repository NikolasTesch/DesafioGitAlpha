|[Main Page](./REDME.md)|
|[Trial 1 Acess](./Trilha1.md)|
|[Trial 2 Acess](./Trilha2.md)|
 
# 👾Controle de Versão com Git
## 🗂️ Conceitos Fundamentais
**O que é Git?**
-   É um **Sistema de Controle de Versão distribuído**.
-   Projetado para projetos de **qualquer tamanho**, com **alta performance**.
-   Mantém o **histórico completo** de todas as revisões.
    
**Repositório**
-   Pasta que contém o projeto e **todos os registros de histórico**.
-   Pode ser local ou sincronizado com serviços remotos (ex.: GitHub).
    
**Commit**
-   “Ponto de salvamento” do projeto.
-   Registra o estado de todos os arquivos **no momento do commit**.
-   Mantém um **histórico permanente**, permitindo retorno a versões anteriores.

##  Configuração Inicial do Git

 **🗒️Nome e Email**
`git config --global user.name "Seu Nome" ` 
`git config --global user.email "email@exemplo.com"` 

**📝Editor de texto**
-   Linux/macOS/WSL: `nano`
-   Windows: `notepad`
   
**⚙️Tipos de configuração**
-   **Global**: vale para todos os projetos.
-   **Local**: vale somente no repositório atual.
    
	
## 🔄Fluxo de Trabalho Básico com Git

 **⚙️Criação do projeto**
-   Criar pasta: `mkdir nome`
-   Acessar pasta: `cd nome`
    
**Iniciar repositório**
-   `git init` cria a pasta **.git**
-   Essa pasta **não deve ser modificada**.

 **Working Tree x Index (Staging Area)**
-   **Working Tree**: arquivos reais do projeto.
-   **Index**: área onde ficam as mudanças preparadas para commit.

**Comandos essenciais**
-   **Visualizar status**: `git status`
-   **Adicionar ao Index**: `git add arquivo`
-   **Criar commit**: `git commit -m "mensagem"`
	
 **Estados de um arquivo**
-   **Untracked**: novo, não rastreado.
-   **Changes not staged**: modificado, mas não adicionado ao Index.
-   **Changes to be committed**: pronto para commit.
-   **Unmodified**: sem mudanças. 

**Git log**
-   Mostra histórico: `git log`
-   Versão compacta: `git log --oneline`
