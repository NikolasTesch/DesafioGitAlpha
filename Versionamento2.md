|[Main Page](./REDME.md)|
|[Trial 1 Acess](./Trilha1.md)|
|[Trial 2 Acess](./Trilha2.md)|

# 👾Branches e merge
**O que é uma _branch_**
-   Uma branch é um **marcador apontando para um commit específico**.
-   Diferente de tags, as branches **avançam** conforme novos commits são feitos.
    
## 🪢Criando e Manipulando Branches
**Comandos essenciais**
-   Criar branch:`git branch <nome>` 
-   Criar branch e já trocar para ela:`git checkout -b <nome>` 
-   Trocar de branch:`git checkout <nome>` 

 **git checkout**
-   Faz duas operações:
    -   Move a **HEAD** para outra branch.
    -   Atualiza a **Working Tree** para refletir o commit de destino.
-   **Modificações locais não são perdidas** (exceto em situações especiais com conflito de diretório).

## 🪢Merge (Fusão de Branches)
**Tipos de merge**
**Fast-forward**
-   Ocorre quando existe **linha reta** entre a branch atual e a outra.
-   O Git simplesmente **avança a branch atual** até o commit da outra.
-   Não cria novo commit.
    
**Three-way merge**
-   Ocorre quando a branch atual e a outra **divergiram** em commits diferentes.
-   O Git cria um novo **commit de merge**.
-   Involui três pontos:
    -   _HEAD_ (branch atual)
    -   _Branch a ser mergeada_
    -   _Último commit comum_ (base)
        
