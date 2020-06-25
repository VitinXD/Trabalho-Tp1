# Trabalho-Tp1

Um sistema de gerenciamento de jogos de futebol, onde usuarios podem vender e comprar ingressos. 

# Especificações e funcionamento do projeto

Consiste na criação de um software funcional de gerenciamento de jogos utilizando um estilo de arquitetura em camadas (layers) todas compostas por seus respectivos módulos. Além do gerenciamento de jogos (criar, deletar e editar jogos), o programa inclui a venda e compra de ingressos e um sistema de usuários cadastrados (com login/logout para acessos ao sistema).

Cada usuário do software tem acesso limitado sistema podendo de inicio apena visualizar jogos já existentes. Após o cadastramento (criação de login e senha) o usuário é adicionado ao banco de dado e ganha acesso a outras funções como a criação e edição dos seus próprios jogos, venda e compra de ingressos.
Para produção foram utilizadas as linguagem C++ e SQL para os bancos de dados (onde são armazenados todos os usuários, jogos, e ingressos). Para mais informações sobre o funcionamento do sistema consultar o smoke test.

Obs: O programa não possui interface, então todas as interações só realizadas no prompt de comando.

