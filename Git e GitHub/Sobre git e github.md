# Git e Github, o que são e para que servem

O Git é um sistema de controle de versão, usado para controlar o histórico de alterações de arquivos e projetos de desenvolvimento.

O Github é uma plataforma online onde você pode criar repositórios e projetos e compartilhá-los, sendo assim muito prático e útil para projetos em equipe.

#### Certo, mas sabendo disso, como envio os meus projetos ou crio repositórios?

Existem dois meios de se conectar com o seu repositório remoto e subir suas alterações: um deles é via token, onde você gera e define seu tempo de expiração, ou configurando a chave SSH que fica salva na sua máquina até que você exclua.

No caso do token, quando for dar o push ele irá pedir usuário e senha, e no lugar da senha o número do token deve ser digitado. Já com a chave SSH, não é necessário usuário e senha, é uma forma de conexão completamente segura que não necessita autenticação.

#### Informações e termos úteis

- Sobre TOKENS: para usar o token, na hora de clonar o repositório, o link copiado deve ser o de https:/.
- git init: é o comando que cria um repositório git. Inicializa o git.
- git add: utilizado para registrar o arquivo, ele move o arquivo do modo UNTRACKED para o STAGED (que é a modificação final, arquivo pronto).
- git commit: ele reinicia o ciclo. A alteração já foi salva dentro do commit, então volta ao começo, entra em modo UNMODIFIED e espera novas modificações.
- git status: verifica o estado atual do repositório, se há alguma alteração e o que ainda não está sendo monitorado pelo git.
- git log: checa o histórico de commits locais antes do push.
- git push: "empurrar" seus commits para o repositório remoto.

