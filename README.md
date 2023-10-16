# DesafioCodigoApiSpring
Aplicação criada usando SpringBoot, Java, Funciona tanto em nuvem quanto local bastando mudar o endereço do servidor no ServidorService. Aplicação em estágio avançado para sistema de comandas online. Permite ao usuário cliente fazer seu check-in em um restaurante cadastrado e fazer seu próprio pedido pelo app. O restaurante cadastrado recebe o pedido e encaminha para a mesa. O usuário cliente tem autonomia de encerrar sua comanda e efetuar o pagamento (em construção).

A aplicação possui todos os endpoints necessários para manipulação e consumo da API de forma que a interação seja completa.

Aplicação criada em Java utilizando o Framework SpringBoot utilizando as boas práticas de desenvolvimento de APIS REST. Utilizado também ferramentas como BCrypt para sistema de login, JavaMailSender para confirmação de email (Incluisive existe um endpoint que recebe a validação e update no banco de dados). Sistema de Interface feito em JavaFX com sistema único de login, o próprio sistema detecta o tipo de usuário e carrega a interface pertinente ao tipo de usuário. (Futuramente terá implantação do JWT para controle de acesso aos Endpoints).

Utilização da API viacep, utilizando o consumo da mesma para otimizar a busca de endereços.

A Aplicação também foi usada como avaliação semestral no curso de Desenvolvimento de Sistemas Multiplataforma da Faculdade de Tecnologia - Polo Cotia.

## Documentação

[Documentação Feita em PostMan com todos os endpoints configurados e exemplificados](https://documenter.getpostman.com/view/25903485/2s93ecwqPu)


## Funcionalidades

- Usuário Cliente e Usuário Estabelecimento
- Funciona localmente ou em nuvem descomentando e adicionando o endereço público do servidor em nuvem
- Sistema Gerador de QRCODE para cada mesa do estabelecimento Cadastrada
- Permite ao Cliente a abertura da comanda e encerramento da mesma.
- Possibilita o checkin através do menu ou utilizando a câmera para acesso ao endpoint
- Sistema de validação de Email utilizando o JavaMailSender
- Sistema de criptografia de senha utilizando o BCrypt do SpringSecurity
- Consumo da API da VIACEP para otimização de endereços
- Sistema hibrido, uma aplicação e sistema de fluxos de telas baseadas no tipo de login de usuário.
- Aplicação roda o servidor em própria instancia, com o servidor online, é possível a utilização de diversas aplicações simultaneamente.



