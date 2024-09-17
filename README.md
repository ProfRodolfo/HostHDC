# Documentação do Projeto hDC Host

## Sumário

1. [Visão Geral](#visão-geral)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Estrutura do Projeto](#estrutura-do-projeto)
4. [Estilos e Responsividade](#estilos-e-responsividade)
5. [Funcionalidades](#funcionalidades)
6. [Instalação e Configuração](#instalação-e-configuração)
7. [Contribuição](#contribuição)
8. [Licença](#licença)

## Visão Geral

O **hDC Host** é um site de hospedagem que oferece uma variedade de planos e serviços para atender às necessidades de projetos de diferentes tamanhos. O site possui uma interface amigável e responsiva, permitindo que os usuários explorem serviços, verifiquem a disponibilidade de domínios e entrem em contato para suporte.

## Tecnologias Utilizadas

- **HTML5**: Estrutura do conteúdo.
- **CSS3**: Estilização e layout responsivo.
- **Font Awesome**: Ícones para melhorar a interface do usuário.
- **Flexbox**: Para layout responsivo e alinhamento de elementos.

## Estrutura do Projeto
/hDC-Host
│
├── index.html # Página principal
├── css
│ └── style.css # Estilos do site
└── img
├── hdchostlogo.png # Logo do site
└── mainbanner.png # Imagem do banner principal

## Estilos e Responsividade

O arquivo `style.css` contém todas as regras de estilo para o site, incluindo:

- Estilos globais (margens, padding, fontes).
- Estilização específica para a barra de navegação, seções de serviços, preços e formulários.
- Responsividade usando media queries para adaptar o layout a diferentes tamanhos de tela.

### Media Queries

As media queries são usadas para garantir que o site se adapte a dispositivos móveis, tablets e desktops. As alterações foram feitas em três pontos de interrupção principais:

- **Max-width: 1100px**: Ajustes para telas de laptops e desktops.
- **Max-width: 900px**: Ajustes para tablets.
- **Max-width: 576px**: Ajustes para smartphones.

## Funcionalidades

- **Navegação**: Menu de navegação com links para as seções principais.
- **Serviços**: Exibição de serviços com ícones e descrições.
- **Planos de Preços**: Seção dedicada com diferentes opções de planos.
- **Verificação de Domínio**: Formulário para verificar a disponibilidade de domínios.
- **Formulário de Contato**: Permite aos usuários entrar em contato para suporte.

## Instalação e Configuração

1. **Clone o repositório**:
   ```bash
   git clone <https://github.com/ProfRodolfo/HostHDC.git>
   ```
2. Abra o arquivo index.html em um navegador para visualizar o site.
3. Faça as alterações necessárias no estilo ou conteúdo conforme desejado.

##  Contribuição e Suporte

Contribuições são bem-vindas! Se você gostaria de contribuir para este projeto, siga estas etapas:

1. Faça um fork do repositório.
2. Crie uma nova branch (git checkout -b feature/nome-da-sua-funcionalidade).
3. Faça suas alterações e commit (git commit -m 'Adicionando nova funcionalidade').
4. Envie para o repositório remoto (git push origin feature/nome-da-sua-funcionalidade).
5. Crie uma Pull Request.

## Licença
Este projeto é licenciado sob a Licença MIT.