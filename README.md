# Curso Digital: GIT / Repositório

## Gravando mudanças no repositório

# Salvando modificações no Git

# STATUS DE UM ARQUIVO NO GIT
# Quando se altera/incluir/excluir um conteúdo, fica com o status de "unmodified" (u). Ao salvar, fica com o status "modified" (m). Ao dar "git add" fica na área de STAGES. Ao dar "git commit -m 'escrever uma mensagem'", deixa a área de STAGE

# Git add: adiciona arquivo na área de STAGE
# Git commit: Comita as alterações da área de STAGE. Arquivo deixa de existir na área de STAGE
# Git diff: mostra as alterações sofridas pelo arquivo.
#           Linha vermelha: houve excluysão ou alteração no conteúdo
#           Linha verde: houve inclusão de conteúdo 
#           IMPORTANTE: git diff não funciona com arquivo em áreas distintas. Para ver a diferença se o arquivo  estiver em outra área, necessário colocar gir diff "nome da área". por exemplo: git diff --staged




# Git Log: Recupera o histórico dos commits
# Git Restore: Descarta as alterações feitas
#              Se for antes de colocar na área de STAGE, basta digitar "git restore"
#              Se for depois de colocar na área de STAGE (depois do git add + nome do arquivo), seiga os passos
#                1 - Digitar "git restore --staged + nome do arquivo". O arquivo vai voltar para a STAGE
#                2 - Digitar "git restore" para cancelar as alterações feitas

# git remote add origin https://github.com/JCPM1975/git-digital-course.git : Criar o repositório local ORIGIN a partir do diretório remoto https://github.com/JCPM1975/git-digital-course.git
# Git remote: Verifica o repositório no momento (ORIGIN)

# Git Push: Enviar as alterações comitadas (get commit -m) e no repositório local (ORIGIN) para o repositório remoto (MASTER)
#           git push  origin master: enviar os dados do repositório local ORIGIN para o repositório remoto MASTER         
# Git Pull: Enviar as alterações do repositório remoto (MASTER) para o repositório local (ORIGIN)
#           git pull master origin: enviar os dados do repositório local MASTER para o repositório remoto ORIGIN


