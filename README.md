# Anti-Dev-Tools-FiveM

Isso é um simples script que até esse momento "impede" a pessoa de roupas mods e até mesmo realizar modificações dentro do servidor.

Para que esse script funcione corretamente, é necessário seguir alguns passo.

1° - Baixe todos esses arquivos e extraia os arquivos na pasta resources do seu servidor.
2° - Após ter baixado e adicionado ao resources, vamos até o server.cfg, ou onde você dá /start ou /ensure em seus script, e vamos adicionar ensure "nomedoarquivo" (ensure Ant-Dev-Tools-FiveM)
3° - Agora com o arquivo já preparado para startar juntamente com o servidor, vamos configurá-lo. Para isso, abra o script permissions.lua e nas linhas 6 e 7 altere onde está escrito steamhexaqui pela sua steam hex.
4° - Após realizar o procedimento 3, salve o arquivo e pode fechá-lo.
5° - Vamos entrar no script server.lua, nesse script, vá até a linha 33 e coloque o webhook onde o script alertará sobre tentativas de utilizar o dev tools. Tendo configurado, basta salvá-lo e fechar.


# Por fim é isso, basta fechar o servidor e iniciá-lo novamente.
