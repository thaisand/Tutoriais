# GIT 
## Conceitos:
- <b> Repositórios: </b> diretórios contendo projetos  
- <b> Branch: </b> ramificação do projeto 
- <b> Commit: </b> altera na máquina a versão do código  
- <b> Merge: </b> junção da branch com a linha principal 
- <b> Push: </b> publica no repositório do Github o commit feito na máquina
- <b> Pull: </b> baixa um repositório na máquina 
- <b> Pull request: </b> requere ao owner do repositório que faça um pull no projeto

## Comandos: 
<b> git --version </b>                                                    <i> // mostra versão do git  </i> <br>
<b> git init </b>                                                         <i> // inicializa repositório </i> <br>
<b> git add arquivo.tipo </b>                                             <i> // prepara o arquivo selecionado para ser commitado </i> <br>
<b> git add . </b>                                                        <i> // prepara todos os arquivos do diretório </i> <br>
<b> git status </b>                                                       <i> // mostra status dos arquivos </i> <br>
<b> git commit -m “mensagem do commit” </b>                               <i> // realiza commit </i> <br>
<b> git branch -M “main” </b>                                             <i> // renomeia a branch atual para main </i> <br>
<b> git branch -d nome-da-branch                                            <i> // exclui a branch
<b> git remote add origin https://github.com/thaisand/Repositorio.git </b><i> // adiciona ligação remota entre o repositório e o diretório da máquina </i><br>
<b> git push origin nome-da-branch </b>                                 <i> // posta arquivos commitados à branch do github </i> <br>   
<b> git push -u origin nome-da-branch </b>                                <i> // cria branch e posta arquivos commitados a ela </i> <br>
<b> git checkout -b nome-da-branch  </b>                                  <i> // cria nova branch e muda para  ela </i> <br>
<b> git checkout nome-da-branch  </b>                                   <i> // muda para branch desejada </i> <br>
<b> git fetch </b>                                                      <i> // muda para branch desejada </i> <br>
<b> git push -u nome-da-branch  </b>                                      <i> // publica arquivos adicionados à nova branch do repositório do github </i>   
<b> git checkout main </b>                                                <i> // volta para branch main </i> <br>
<b> git merge main     </b>                                               <i> // prepara branch teste para ser add ao main </i> <br>
<b> git push nome-da-branch    </b>                                       <i> // realiza o merge no repositório do github </i> <br>
<b> git clone https://github.com/repositorio  </b>                        <i> // clona um repositório na máquina </i> <br>
<b> git pull   </b>                                                       <i> // atualiza repositório clonado </i> <br>
<b> git log --oneline   </b>                                                <i> // histórico de commits da branch </i> <br>
<b> git revert 1234567 </b>                                                <i> // desfaz commit especificado e cria outro commit sem excluir o antigo </i> <br>
<b> git rm nome-arquivo  </b>                                             <i> // remove arquivo da pasta </i> <br>
<b> git rebase nome-branch </b>                                           <i> // integra duas branches em uma branch linear </i> <br>
