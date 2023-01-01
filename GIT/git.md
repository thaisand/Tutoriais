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
git --version                                                    // mostra versão do git <br>
git init                                                         // inicializa repositório <br>
git add arquivo.tipo                                             // prepara o arquivo selecionado para ser commitado <br>
git add .                                                        // prepara todos os arquivos do diretório <br>
git status                                                       // mostra status dos arquivos <br>
git commit -m “mensagem do commit”                               // realiza commit <br>
git branch -M “main”                                             // renomeia a branch atual para main <br>
git remote add origin https://github.com/thaisand/LeetCode.git   // adiciona ligação remota entre repositório do github e diretório da máquina  <br>
git push -u origin main                                          // posta arquivos adicionados ao repositório do github <br>
git checkout -b “nome-da-branch”                                 // cria nova branch e muda para ela <br>
git push -u origin nome-da-branch                                // publica arquivos adicionados a nova branch do repositório do github <br>   
git checkout main                                                // volta para branch main <br>
git merge teste                                                  // prepara branch teste para ser add ao main <br>
git push origin main                                             // realiza o merge no repositório do github <br>
git clone https://github.com/respositorio                        // clona um repositório na máquina <br>
git pull                                                         // atualiza repositório clonado <br>



