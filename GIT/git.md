# GIT 
## Conceitos:
- Repositórios: diretórios contendo projetos  
- Branch: ramificação do projeto 
- Commit: altera na máquina a versão do código  
- Merge: junção da branch com a linha principal 
- Push: coloca o commit que vc fez na máquina no repositório do GitHub
- Pull: baixa um repositório na máquina 
- Pull request: requere ao owner do repositório que faça um pull no projeto

## Comandos: 
git --version                                                    // mostra versão do git
git init                                                         // inicializa repositório
git add arquivo.tipo                                             // prepara o arquivo selecionado para ser commitado
git add .                                                        // prepara todos os arquivos do diretório 
git status                                                       // mostra status dos arquivos 
git commit -m “mensagem do commit”                               // realiza commit
git branch -M “main”                                             // renomeia a branch atual para main
git remote add origin https://github.com/thaisand/LeetCode.git   // adiciona ligação remota entre repositório do github e diretório da máquina 
git push -u origin main                                          // posta arquivos adicionados ao repositório do github
git checkout -b “nome-da-branch”                                 // cria nova branch e muda para ela 
git push -u origin nome-da-branch                                // publica arquivos adicionados a nova branch do repositório do github        
git checkout main                                                // volta para branch main        
git merge teste                                                  // prepara branch teste para ser add ao main
git push origin main                                             // realiza o merge no repositório do github
git clone https://github.com/respositorio                        // clona um repositório na máquina
git pull                                                         // atualiza repositório clonado



