
# Integração do Orientek com o equipamento da Sport Ident
Guia de como implementar a integração do software do grupo Azimute Norte com os drivers e soluções da Sport-Ident

## Drivers
 
A lista a seguir dispõe de todos os softwares necessários para a integração entre os sistemas. Todos os aplicativos e drivers listados abaixo estão disponíveis gratuitamente na pagina [sobre software](https://www.sportident.com/products.htm) sob domínio da Sport-Ident.
 
 - [SPORTident Config+](https://www.sportident.com/products.htm#software:sportident-config-plus)
- [Driver USB](https://www.sportident.com/products.html#software:usb-driver)
- [SPORTident Reader](https://www.sportident.com/products.html#software:usb-driver#software:sportident-reader)

Além destes o cliente deve ter instalado um banco de dados MySql ou a aplicação deve dispor de um banco de dados SqlLite.

### SPORTident Config+

Ferramenta moderna usada pra configurar bases e chips em alguns casos de uso. Creio eu que não seja possível fazer algumas das funções deste software de outra maneira.

### Driver USB 

Útil para quase toda aplicação que interage  com as bases de *punching*.

### SPORTident Reader

Essa aplicação fornece uma maneira mais simplificada para leitura de bases e chips. Por meio do driver USB,  o reader absorve guarda os dados obtidos em um banco de dados SQL, SQLlite, CSV e txt. Antes de usar os bancos de dados é bom ler a documentação do aplicativo que fica no diretório `doc` na pasta de instalação. O local de instalação do SI-Reader pode ser localizado na aba **Maintenance**.
![Imagem mostrando onde obter o local de instalação do SI-reader](https://raw.githubusercontent.com/JosoeSantos/OrientekDesktop/master/Docs/print-si-reader-installation.png?token=AfccRbtAvf4ZlQ0F_iTDQblxehvp5Qd_ks5cn81NwA==)
A documentação indica como fazer a conexão aos bancos de dados e também explica para que servem os dados coletados e armazenados.

O Si-Reader possui suporte via linha de comando, o que é útil para executar lo em fundo sem aumentar o numero de aplicações listadas na barra de tarefas melhorando a usabilidade do sistema. 

