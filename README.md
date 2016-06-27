
Neste exemplo, procuro demonstrar como utilizar a API LocalStorage, o uso dessa API vem de encontro com o conceito de Offline First
ou seja desenvolver pensando primeiramente em tecnologias offline, principalmente no mundo Mobilie, é muito comum hoje quando voçe baixa um aplicativo qualquer a primeira coisa que ele te pede é uma conexão com a internet. Pronto se você não tem um pacote de dados 
bacana, ou não está conectado em nenhuma rede wi-fi, o app não irá funcionar. Este pode ser um bom motivo para que o usuário exclua seu aplicativo.

Basicamente os passos para construir aplicativos off-line first são:

- a aplicação deve detectar o estado "off-line";
- Armazenar dados off-line (ae entra a Web Storage API);
- Sincronize com um servidor assim que detectar acesso, considere contruir uma solução para organizar pequenos pacotes de dados 
  para o envio.

Também neste exemplo procuro mostrar o uso de componentes Jquery como o Validation, Jquery Datatables e o Jquery Growl além
do Bootstrap usado no layout, tudo muito simples para o perfeito entendimento.

Foi criado um CRUD (create, read, update e delete) para manter um contato, estes contatos serão mantidos em LocalStorage, não
fiz nenhum processamento para enviar ao servidor neste caso.

Imagem da tela:

<img src="https://github.com/mdcarmo/CrudLocalStorage/blob/master/img/img.PNG" />

Espero que ajude a quem estiver estudando esses conceitos!

É isso ae!
