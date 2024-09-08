# Sistema PETSHOP - FSW Fase2

Este projeto é um sistema básico de gerenciamento para um Pet Shop, desenvolvido como parte da Fase 2 da disciplina Fundamentos de sistema web. Ele foi construído utilizando HTML, CSS, e Bootstrap para o frontend, e está preparado para futuras implementações de backend.

# Plataforma Online de PetShop - Guia de Funcionalidades

## 1. index.html - Página Inicial
A página inicial do site apresenta uma visão geral dos serviços e produtos oferecidos pela PetShop. É o ponto de entrada para o usuário e pode incluir um carrossel de imagens promocionais, links para as demais seções do site, e destaques de produtos e serviços.

## 2. cadastro.html - Cadastro de Clientes e Pets
Nesta página, os usuários podem cadastrar suas informações pessoais e as informações dos pets. O formulário inclui campos para nome, sobrenome, telefone, endereço e informações detalhadas sobre o pet, como nome, raça, e porte. A página também valida o formato dos dados, como o número de telefone e e-mail, garantindo que as informações sejam inseridas corretamente.

## 3. agendamento.html - Agendamento de Serviços
Aqui, os clientes podem agendar serviços para seus pets, como banho e tosa. A página permite a escolha de data, horário e o serviço desejado. Além disso, existe a opção de selecionar a tele-busca, onde um funcionário busca e entrega o pet após a realização do serviço.

## 4. racaoseca.html - Produtos de Ração Seca
Esta página exibe uma lista de rações secas disponíveis para compra. Cada item possui uma descrição detalhada, preço e um botão para adicionar ao carrinho de compras. É voltada para donos de pets que procuram alimentação específica.

## 5. racaoumida.html - Produtos de Ração Úmida
Semelhante à página de ração seca, esta seção é dedicada à venda de rações úmidas. Apresenta informações completas sobre cada produto, incluindo marca, benefícios para os pets e opções de compra.

## 6. servicos.html - Lista de Serviços
Nesta página, é possível visualizar todos os serviços oferecidos pela PetShop, como banho, tosa, vacinação, e atendimento veterinário. O usuário pode obter mais detalhes sobre cada serviço e, em alguns casos, redirecionar para o agendamento.

## 7. dados.html - Lista com os dados cadastrados
Nesta página, é possível visualizar todos os dados cadastrados referente aos cliente e pets em conjunto com todos os agendamentos realziados, nessa tela o usuario pode realizar a limpeza desses dados.

## Tecnologias Utilizadas

- **HTML5**: Para a estruturação da página.
- **CSS3**: Para a estilização básica.
- **Bootstrap 5**: Para uma interface responsiva e estilizada, com componentes prontos.
- **JavaScript**: Para realizar inserções e validações de dados, incluindo o uso de localStorage para armazenamento temporário de informações.

## Uso do `localStorage`

Como o GitHub Pages não suporta backend, usamos o `localStorage` do navegador para simular o armazenamento de dados. Isso permite:

- **Armazenamento Temporário:** Dados como informações de cadastro e agendamentos são armazenados localmente no navegador.

**Nota:** O `localStorage` é limitado e não é adequado para armazenamento permanente ou para dados sensíveis. Para futuras melhorias, a implementação de um backend permitirá um gerenciamento mais robusto e seguro dos dados.



## Como Usar

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/hygorlumertz1/PETSHOP-FSW
    ```

2. **Navegue até o diretório do projeto:**
    ```bash
    cd PETHSOP-FSW
    ```

3. **Abra o arquivo `index.html` no seu navegador:**
    - Você pode simplesmente clicar duas vezes no arquivo `index.html` ou abrir o navegador e arrastar o arquivo para a barra de endereço.

## Estrutura do Projeto

- **index.html**: Página principal do sistema.
- **cadastro.html**: Página para cadastro de clientes e pets (a ser implementada).
- **servicos.html**: Página para exibição dos serviços oferecidos (Banho e Tosa).
- **racaoseca.html**: Página para visualização dos produtos disponíveis.
- **racaoumida.html**: Página para visualização dos produtos disponíveis.
- **agendamento.html**: Pagina dedicada para realizar o agendamento dos serviços.
- **dados.html**: Paginda dedicada para informar os dados salvos no localStorage.
- **assets/**: Pasta para armazenar ícones e imagens.
- **css/**: Contém o arquivo `styles.css` com customizações adicionais ao Bootstrap.

## Melhorias Futuras

- **Implementação do Backend**: Conectar o sistema a um banco de dados para gerenciar clientes, pets e serviços de forma dinâmica.
- **Formulários Funcionais**: Criar formulários de cadastro e contato que realmente enviam dados para o servidor.



