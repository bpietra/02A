passo a passo 
1) ativar o node-env.
    source nodejs.env/bin/activate
   
3) entrar na pasta onde o node-env está localizada.
    ex: cd src/
   
4) abrir o nano do arquivo "index.js"
    sudo nano index.js
   
   obs: caso não seja proprietário fazer "sudo chown (usuario)__:__(classe) index.js"
5) dentro do nano coloque o código que precisar.
    var http = require('http');

  http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello Pietra Alberganti Basso 19/09/2023!');
 }).listen(8004);
 
6) apertar o control+o para salvar as atualizações, confirmar com enter e apertar control+x para fechar.
7) testar o "node index.js"
8) testar o funcionamento pelo localhost:(o numero da sua porta).
