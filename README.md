# Link do projeto
https://joelsongomess.github.io/projeto-div/index.html

# Exercicio a ser feito
## criar uma segunda div conforme a imagem a baixo
![image](https://github.com/user-attachments/assets/b482102e-d9fa-4aeb-89c0-c703e7753468)

# pontos a serem validados
- clonar repositorio atual
- criar uma nova branch a partir da branch main
- fazer as alterações solicitadas em sua nova branch e abrir um pull request para main





como baixar o git em sua maquina => https://git-scm.com/downloads
para instalar é somente apertar next ate o finish

apos instalado abra o terminar com comando *window + r* -> *cmd* -> botão ok

se tiver seguido o comando a cima com sucesso tera aberto um terminal 
apos abrir o terminal crie uma pasta com comando<br>
*mkdir nome-pasta*

copie o endereço do link do reposito (faça um clone )
https://github.com/joelsongomess/projeto-div.git

comando do clone a baixo<br>
*git clone https://github.com/joelsongomess/projeto-div.git*

apos clonar o projeto entre na pasta com comando cd e tecla tab<br>

como criar uma nova branch apartir da branch main<br>
*git branch nova-branch*

como mudar para nova branch<br>
*git checkout nova-branch*

comando que cria e muda para branch de um só vez<br>
*git checkout -b nova-branch*

apos estar na nova branch deve se fazer alteração sugerida

utilize o comando: *git status* para ver cada etapa de sua alteração

prontificar suas alterações com comando 
*git add .*

identificar sua alteração com comando
*git commit -m "escreve breve texto do que foi alterado"*

comando para subir a alteração
*git push origin nova-branch*

se quiser mapear a branch nova criada para nao ter que usar origin e nome da branch utilize o comando
*git push --set-upstream origin nova-branch*
e nas proximas alterações pode ser utilizado somente o comando git push

