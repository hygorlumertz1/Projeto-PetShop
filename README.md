# Sistema PETSHOP - FSW Fase2

Este projeto é um sistema básico de gerenciamento para um Pet Shop, desenvolvido como parte da Fase 2 da disciplina Fundamentos de sistema web. Ele foi construído utilizando HTML, CSS, e Bootstrap para o frontend, e está preparado para futuras implementações de backend.

## Funcionalidades

- **Página Inicial (Home):** Apresenta uma breve descrição do Pet Shop e suas ofertas disponibilizadas em carroseul.
- **Navegação:** Barra de navegação com links para a página inicial, cadastro, serviços e produtos disponíveis.
- **Cadastro:** Apresenta os formularios de cadastros de cliente e seus PETs.
- **Serviços:** Seção dedicada aos serviços de Banho e Tosa, além de uma área para visualização de produtos.
- **Agendamento:** Seção dedicada ao agendamento dos serviços assima.
- **Produtos:** Exibição de produtos disponíveis com preços e botões de ação para explorar mais detalhes.
- **Rodapé:** Informações de direitos autorais e branding do Pet Shop.

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



