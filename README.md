# 2i-crud

# Projeto CRUD com MySQL e PHPMyAdmin

Este projeto é uma aplicação CRUD (Criar, Ler, Atualizar, Excluir) utilizando uma base de dados MySQL gerenciada pelo PHPMyAdmin. O sistema foi hospedado na plataforma **Alojamento-Gratis**.

## Funcionalidades

- **Criar**: Permite adicionar novos registros à base de dados.
- **Ler**: Permite visualizar os registros existentes na base de dados.
- **Atualizar**: Permite modificar dados de registros existentes.
- **Excluir**: Permite remover registros da base de dados.

## Tecnologias Utilizadas

- **PHP**: Linguagem de programação usada para desenvolver o back-end da aplicação.
- **MySQL**: Sistema de gerenciamento de banco de dados relacional.
- **PHPMyAdmin**: Ferramenta de administração de banco de dados MySQL.
- **Alojamento-Gratis**: Plataforma de alojamento utilizada para disponibilizar o projeto online.

## Pré-Requisitos

Antes de começar, tu precisas de ter as seguintes ferramentas instaladas:

- [PHP](https://www.php.net/) (versão 4.4 ou superior)
- [MySQL](https://www.mysql.com/)
- [PHPMyAdmin](https://www.phpmyadmin.net/)
- Acesso a um servidor de alojamento (como o **Alojamento-Grátis**) com suporte a PHP e MySQL.

## Estrutura do Projeto

O projeto deve seguir uma estrutura para poder funcionar, essa sendo:

```bash
├── /css/                     # Pasta que guarda o css
      ├── style.css           # Arquivo de css
├── /db/                      # Pasta que guarda a base de dados
      ├── cart_db.sql         # Arquivo de base de dados
├── /images/                  # Pasta que guarda as imagens que podem ser usadas(opcional)
      ├── food-1.png          # Arquivo de foto
      ├── food-2.png          # Arquivo de foto
      ├── food-3.png          # Arquivo de foto
      ├── food-4.png          # Arquivo de foto
      ├── food-5.png          # Arquivo de foto
├── /uploaded_img/            # Pasta que guarda imagens que foram enviadas para a base de dados
├── admin_page.php            # Página principal do site
├── admin_update.php          # Página para adicionar produto
├── config.php                # Página para conectar a base de dados
└── README.md                 # Este arquivo
```

## Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/a14482/2i-crud.git
   ```
   
2. **Usar um local de base de dados(alojamento-grátis):**<br/> 
   Para o uso do alojamento-grátis, devemos ir ao site e criar conta<br/> 
   - [Alojamento-grátis](http://www.alojamento-gratis.com/)<br/>
   
3. **Colocar a base de dados dentro do alojamento-grátis:**<br/>
   Agora que chegamos ao cpanel:
   
   ![image](https://github.com/user-attachments/assets/b503ead0-3005-4fa5-beef-28b5a6770e3b)
   
   Devemos clicar em MYSQL Databases:<br/>
   ![image](https://github.com/user-attachments/assets/6088e57d-e2d1-4ad9-81ca-bae785304da7)

   Já dentro, colocamos o nome da nossa base de dados, este sendo cart_db:
   ![image](https://github.com/user-attachments/assets/ade97291-9eb3-45c3-8970-55efcb01d59f)

   Agora que temos criada devemos ter isto na mesma pagina
   ![image](https://github.com/user-attachments/assets/3e56178f-3f40-4479-8a81-8845422f8312)

   Clicamos em admin e importar
   ![image](https://github.com/user-attachments/assets/ebaf5bea-7a5a-4fcc-97ed-250a8534d0b4)

   Aqui clicamos em escolher ficheiro e escolhemos o ficheiro products.sql





   
