# Projeto Web com JavaScript, PHP, phpMyAdmin, AdminLTE e CodeIgniter

Este projeto é uma aplicação web de gerenciamento de produtos, desenvolvida utilizando JavaScript, PHP, phpMyAdmin, AdminLTE e CodeIgniter. A aplicação inclui funcionalidades como cadastro, edição, exclusão e listagem de produtos.

## Tecnologias Utilizadas

- **JavaScript:** Responsável por interações dinâmicas no lado do cliente, aprimorando a experiência do usuário.
- **PHP:** Linguagem de programação do lado do servidor utilizada para manipulação de dados e lógica de negócios.
- **phpMyAdmin:** Interface web para administração do MySQL, facilitando a gestão do banco de dados.
- **AdminLTE:** Um painel de controle construído sobre o framework Bootstrap, proporcionando um layout moderno e responsivo.
- **CodeIgniter:** Um framework PHP leve e eficiente que simplifica o desenvolvimento e manutenção da aplicação.

## Estrutura do Projeto

- **`/app`:** Contém os arquivos relacionados à lógica de negócios do CodeIgniter.
- **`/public`:** Armazena recursos públicos, como arquivos JavaScript, CSS e imagens.
- **`/system`:** Parte do CodeIgniter que não deve ser alterada.
- **`/writable`:** Diretório usado pelo CodeIgniter para armazenar logs e caches.

## Configuração do Ambiente

1. **Banco de Dados:**
   - Execute as migrações para criar a tabela de login. Use o comando `php spark migrate` no terminal.
   - Certifique-se de ter o MySQL e phpMyAdmin configurados corretamente.

2. **Servidor PHP:**
   - Configure um servidor PHP local ou utilize um ambiente de desenvolvimento, como XAMPP ou WampServer.

3. **Configurações CodeIgniter:**
   - Edite o arquivo `/app/config/database.php` para fornecer as configurações do seu banco de dados.
   - Configure outros parâmetros necessários no arquivo `/app/config/config.php`.

4. **Execução:**
   - Inicie o servidor PHP local e acesse o projeto pelo navegador.

## Uso da Aplicação

- Acesse a página principal para visualizar e gerenciar os produtos.
- Utilize a interface AdminLTE intuitiva para navegar pelas funcionalidades.
- Receba alertas de sucesso ou erro ao realizar operações, como criar ou excluir produtos.

Este projeto serve como um exemplo de como combinar várias tecnologias web para criar uma aplicação robusta e interativa. Sinta-se à vontade para explorar, modificar e expandir conforme suas necessidades. Se precisar de ajuda ou tiver alguma dúvida, consulte a documentação das tecnologias individuais utilizadas.

Divirta-se desenvolvendo! 😊
