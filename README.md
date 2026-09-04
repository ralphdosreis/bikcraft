# Bikcraft

Site institucional e catálogo de bicicletas elétricas personalizadas da Bikcraft. O projeto apresenta os modelos disponíveis, seus detalhes e recursos, planos de seguro e canais de contato em uma interface responsiva.

## Funcionalidades

- Página inicial com apresentação da marca, modelos em destaque, tecnologia, parceiros, depoimento e planos de seguro.
- Catálogo com as bicicletas Magic Might, Nimbus Stark e Nebula Cosmic.
- Páginas individuais para cada modelo, com especificações, galeria de imagens e informações do produto.
- Página de seguros com planos Prata e Ouro, vantagens e perguntas frequentes.
- Formulário de orçamento para selecionar uma bicicleta ou plano de seguro.
- Página de contato com informações das lojas e formulário de mensagem.
- Página de termos e condições.
- Menu ativo, perguntas frequentes, seleção de imagens da galeria e animações de entrada usando JavaScript.

## Tecnologias

- HTML5 semântico
- CSS3, com estilos organizados por páginas, componentes e utilidades
- JavaScript vanilla (ES6+)
- SVG para logotipo, ícones e elementos gráficos
- Google Fonts: Poppins, Roboto e Merriweather

## Como executar

O projeto é estático e não requer instalação de dependências.

1. Clone o repositório e acesse a pasta do projeto.
2. Inicie um servidor HTTP local. Por exemplo, usando Python:

   ```bash
   python -m http.server 8000
   ```

3. Abra [`http://localhost:8000`](http://localhost:8000) no navegador.

Também é possível abrir o projeto com uma extensão de servidor local, como o Live Server do Visual Studio Code.

## Estrutura do projeto

```text
.
├── bicicletas/          # Páginas individuais dos modelos
├── css/                 # Estilos globais, páginas, componentes e utilidades
├── img/                 # Fotos, ícones, logos e elementos decorativos
├── js/                  # Interações e plugin de animação
├── bicicletas.html      # Catálogo de bicicletas
├── contato.html         # Contato e lojas
├── index.html           # Página inicial
├── orcamento.html       # Formulário de orçamento
├── seguros.html         # Planos e benefícios dos seguros
└── termos.html          # Termos e condições
```

## Observação

Os formulários presentes no projeto são demonstrações de interface. No estado atual, não existe uma API ou serviço de backend conectado para processar o envio dos dados.

## Licença

Este projeto não possui uma licença definida. Consulte o responsável pelo repositório antes de reutilizar o código ou os assets.
