Seguir a <a href="https://docs.google.com/presentation/d/1XNoWxZekQSUR9kwQHI8ffWd4x_PkPEAVPVXjse3NSTI/edit?usp=sharing" target="_blank">APRESENTAÇÃO</a>

Seus dados devem estar previamente configurados no Git da sua máquina.
Verifique se seu **user.name** e **user.email** estão configurados:
- `git config --list`

Comandos para rastrear localmente um projeto:
- Entrar no Git Bash clicando com o botão direito do mouse de dentro da sua pasta (*Git Bash here*) ou navegando pelo Git Bash até a pasta desejada (`cd nomeDaPasta`).
- `git init`: iniciar o rastreamento dessa pasta
- `git add <nome do arquivo>` ou `git add --all` ou `git add .`: adicionar os arquivos na área de preparação
- `git commit -m "Mensagem de bom senso"`: adicionar a mensagem do que foi feito nesse(s) arquivo(s) adicionado(s)

Enviar o seu repositório local para um site de hospedagem de repositórios (ex: GitHub):
- Criar um repositório novo no site do GitHub https://github.com/new
- `git remote add origin https://github.com/<seuLogin>/<seuRepositorio>.git`: adicionando o endereço do repositório remoto
- `git push -u origin master`: enviando o que está no Git local para o GitHub