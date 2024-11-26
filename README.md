## 🎉 Contagem Regressiva

Este é um projeto React que exibe uma contagem regressiva personalizada para eventos futuros. O usuário pode definir um evento com título, data, cor e imagem de fundo, e o sistema calculará os dias, horas, minutos e segundos restantes até o evento.

## 📋 Funcionalidades
Exibição de contagem regressiva para um evento personalizado.
Customização da cor e imagem de fundo para cada evento.
Redirecionamento para a página inicial caso não haja evento configurado.
Feedback para o usuário quando o evento chega ao fim.

## 🛠️ Tecnologias Utilizadas
React.js: Biblioteca principal para construção da interface.
React Router: Gerenciamento de rotas.
CSS: Estilização personalizada.
JavaScript (ES6+): Manipulação da lógica do contador.
Context API: Gerenciamento de estado global do evento.
Hooks: Reuso de lógica com useState, useEffect e useContext.

## 🚀 Como Executar o Projeto

Siga as instruções abaixo para rodar o projeto localmente:

1. **Clone o repositório:**
   
bash
   git clone https://github.com/DanielFilhoo/contagem-regressiva.git
    cd contagem-regressiva

2. **Instale as dependências:**
cd contagem-regressiva
npm install

3. **Execute o projeto:**
npm start

## 📋 Como Usar

1. **Configurar Evento:** Acesse a aplicação e insira as informações do evento, como título, data, cor e imagem de fundo.

2. **Acompanhar a Contagem:** Veja o tempo restante até o evento em uma interface dinâmica e personalizada.

3. **Final do Evento:** O contador será ajustado automaticamente para evitar valores negativos quando o evento chegar.

## 📂 Estrutura do Projeto
Abaixo, uma visão geral dos principais arquivos e diretórios:

contagem-regressiva/
├── src/
│   ├── components/
│   │   ├── Title.jsx             # Componente para exibição do título
│   │   ├── Counter.jsx           # Componente para exibição dos números da contagem
│   ├── context/
│   │   └── CountdownContext.jsx  # Contexto global para os dados do evento
│   ├── hooks/
│   │   └── useCountdown.js       # Hook personalizado para cálculo da contagem regressiva
│   ├── assets/
│   │   └── contador.webp         # Imagem padrão para o fundo
│   ├── App.js                    # Componente principal da aplicação
│   └── index.js                  # Arquivo de entrada do React
├── public/
│   └── index.html                # Estrutura HTML base
└── README.md                     # Documentação do projeto



## 🤝 Contribuição

Contribuições são bem-vindas! Se você tiver ideias de melhorias ou correções de bugs, sinta-se à vontade para abrir uma issue. Caso deseje contribuir diretamente, faça um fork do repositório e envie uma pull request com as alterações.

## Contato

Para mais informações, você pode entrar em contato:

- Nome: Daniel Alexandre de Sant'Ana Filho
- GitHub: [DanielFilhoo](https://github.com/DanielFilhoo)