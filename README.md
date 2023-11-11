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
# Git remote: Verifica o repositório no momento (ORIGIN/MASTER)

# Git Push: Enviar as alterações comitadas (get commit -m) e no repositório local (MASTER) para o repositório remoto (ORIGIN)
#           git push  origin master: enviar os dados do repositório local MASTER para o repositório remoto ORIGIN         
# Git Pull: Enviar as alterações do repositório remoto (ORIGIN) para o repositório local (MASTER)
#           git pull master origin: enviar os dados do repositório local MASTER para o repositório remoto ORIGIN

# Git Fetch: Mostra as alterações feitas antes de alterar/sobrepor o arquivo local (MASTER)
#            Em seguinda usar Git diff origin/master: mostrar as alterações feitas no repositório remoto  
#            Em seguinda usar Git pull

# Git Branch: Criar uma nova branch. 
#             Ex.: git branch teste
# Git log --oneline --decorate: Verificar para qual branch o ponteiro HEAD está apontando no momento
# Git Checkout: Trocar a branch para onde o ponteiro HEAD está apontando. 
#               Ex.: git checkout teste