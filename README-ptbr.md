# ⚽ Simulador de Torneios de Futebol

![Torneio de Futebol](https://img.shields.io/badge/Futebol-Simulador_de_Torneios-red?style=for-the-badge&logo=fifa)

**Sistema interativo de sorteio e simulação de torneios**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

[🏆 Ver Projetos](https://github.com/adrian1715/football-tournament-simulator) • [📝 Reportar Bug](https://github.com/adrian1715/football-tournament-simulator/issues) • [✨ Sugerir Funcionalidade](https://github.com/adrian1715/football-tournament-simulator/issues)

Live Demo: [World Cup](https://portfolio-website-adrian-lobato.onrender.com/projects/simulators/copa-do-mundo-2022) • [Libertadores/Sul-Americana](https://portfolio-website-adrian-lobato.onrender.com/projects/simulators/libertadores-sulamericana-2022)

---

## 📖 Sobre o Projeto

Este repositório contém **simuladores interativos de torneios de futebol** que permitem aos usuários simular sorteios e partidas dos principais torneios sul-americanos de futebol. Construídos com JavaScript puro, estes simuladores oferecem uma maneira envolvente de experienciar formatos de torneios e visualizar possíveis resultados de partidas.

### 🏆 Simuladores Incluídos

#### 1. ⚽ Copa do Mundo FIFA 2022 (Qatar)

Um sistema completo de sorteio e simulação da Copa do Mundo com:

- 32 seleções nacionais organizadas em potes
- Simulação do sorteio da fase de grupos
- Simulação de partidas da fase de grupos
- Geração de chaves da fase eliminatória
- Informações e bandeiras das seleções
- Progressão completa do torneio

#### 2. 🏆 Copa Libertadores & Copa Sudamericana 2022

Simulação simultânea das principais competições de clubes da América do Sul:

- Sistema do torneio da Copa Libertadores
- Sistema do torneio da Copa Sudamericana
- Dados de clubes com logos
- Mecânicas da fase de grupos
- Progressão da fase eliminatória

---

## 🌟 Características Principais

### Recursos Gerais

- ✅ **Sistema de Sorteio Interativo** - Mecânicas realistas de sorteio de torneios
- 🎲 **Simulação Aleatória de Partidas** - Geração automatizada de placares
- 🏆 **Fluxo Completo do Torneio** - Das fases de grupos até as finais
- 🖼️ **Logos & Bandeiras** - Representação visual de todas as equipes
- 📊 **Atualizações em Tempo Real** - Interface dinâmica durante a simulação
- 🎯 **Regras Autênticas** - Segue regulamentos oficiais dos torneios
- 📱 **Design Responsivo** - Funciona em todos os dispositivos
- ⚡ **Performance Rápida** - Simulações suaves sem travamentos

### Simulador da Copa do Mundo

- 🌍 **32 Seleções Nacionais** - Todos os participantes do Qatar 2022
- 🎲 **Sorteio por Potes** - Segue regras de ranqueamento da FIFA
- 🏟️ **Fase de Grupos** - 8 grupos com 4 times cada
- 🏆 **Rodadas Eliminatórias** - Oitavas → Quartas → Semis → Final
- 📈 **Tabelas de Grupos** - Rastreamento de pontos, gols, saldo de gols
- 🥇 **Determinação do Campeão** - Simula todo o torneio até coroar o campeão

### Simulador Libertadores/Sudamericana

- ⚽ **Múltiplos Torneios** - Duas competições em uma interface
- 🏆 **Fase de Grupos** - Formato autêntico da fase de grupos
- 🎯 **Fases Eliminatórias** - Das quartas de final até a final
- 🔄 **Alternância de Torneios** - Alternar entre as competições
- 📊 **Resultados de Partidas** - Rastreamento detalhado de placares

---

## 🛠️ Construído Com

- **HTML5** - Estrutura e layout semânticos
- **CSS3** - Estilos e animações personalizados
- **JavaScript (Vanilla)** - Lógica de torneio e simulações
- **Bootstrap 4** - Sistema de grid responsivo e componentes

---

## 💻 Começando

### Pré-requisitos

- Um navegador web moderno (Chrome, Firefox, Safari, Edge)
- Nenhuma instalação adicional necessária!

### Instalação

1. **Clone o repositório**

   ```bash
   git clone https://github.com/adrian1715/football-tournament-simulator.git
   cd football-tournament-simulator
   ```

2. **Abra os simuladores**

   **Simulador da Copa do Mundo:**

   ```bash
   cd "Copa do Mundo 2022"
   open index.html  # macOS
   # ou
   start index.html  # Windows
   ```

   **Simulador Libertadores/Sudamericana:**

   ```bash
   cd "Libertadores e Sul-Americana 2022"
   open index.html  # macOS
   # ou
   start index.html  # Windows
   ```

3. **Ou use um servidor local** (opcional)

   ```bash
   # Usando Python 3
   python -m http.server 8000

   # Usando Node.js http-server
   npx http-server
   ```

   Depois navegue para `http://localhost:8000`

---

## 📁 Estrutura do Projeto

```
simulador-de-torneios/
├── Copa do Mundo 2022/
│   ├── index.html              # Página principal da Copa
│   ├── style.css              # Estilos da Copa
│   └── app.js                 # Lógica de simulação da Copa
│
├── Libertadores e Sul-Americana 2022/
│   ├── index.html              # Página principal Libertadores/Sudamericana
│   ├── style.css              # Estilos das competições
│   └── app.js                 # Lógica de simulação dos torneios
│
├── images/
│   ├── Copa do Mundo/         # Bandeiras das seleções (32 imagens)
│   ├── Libertadores/          # Logos dos clubes da Libertadores
│   ├── Sul-Americana/         # Logos dos clubes da Sudamericana
│   ├── bg-1.jpg              # Imagem de fundo
│   ├── libertadores logo.png
│   ├── libertadores-bg.png
│   ├── sul-americana logo.png
│   └── sulamericana banner.jpg
│
├── README.md                  # Documentação (Inglês)
└── README-ptbr.md             # Documentação (Português)
```

---

## 🎮 Como Usar

### Simulador da Copa do Mundo

1. **Visualizar Potes Iniciais**

   - Veja todas as 32 seleções organizadas em 4 potes (Pote 1-4)
   - Times agrupados por ranking FIFA e zonas geográficas

2. **Simular Sorteio de Grupos**

   - Clique em "Sortear Grupos"
   - Assista as seleções sendo sorteadas aleatoriamente em 8 grupos (A-H)
   - Cada grupo contém 4 times de diferentes potes

3. **Simular Fase de Grupos**

   - Clique em "Simular Fase de Grupos"
   - Todas as partidas de grupos são simuladas automaticamente
   - Visualize tabelas de grupos com classificação, pontos e saldos de gols

4. **Visualizar Chaves Eliminatórias**

   - Os 2 melhores times de cada grupo avançam
   - Chave eliminatória é gerada automaticamente
   - Mostra confrontos das oitavas de final

5. **Simular Rodadas Eliminatórias**
   - Clique para simular cada rodada eliminatória
   - Progresso através de: Oitavas → Quartas → Semis → Final
   - Campeão coroado como Campeão da Copa do Mundo!

### Simulador Libertadores/Sudamericana

1. **Escolher Torneio**

   - Interface exibe ambos os torneios
   - Alternar entre Libertadores e Sudamericana

2. **Visualizar Times**

   - Veja clubes participantes de cada país
   - Logos dos clubes exibidos com nomes

3. **Simular Sorteios**

   - Clique para sortear fase de grupos
   - Times distribuídos entre os grupos

4. **Executar Torneio**
   - Simular partidas de grupos
   - Gerar chaves eliminatórias
   - Progredir até as finais

---

## 🎯 Recursos Detalhados

### Mecânicas da Fase de Grupos

- **Sistema de Pontos:**

  - Vitória: 3 pontos
  - Empate: 1 ponto
  - Derrota: 0 pontos

- **Critérios de Desempate:**
  - Saldo de gols
  - Gols marcados
  - Confronto direto

---

## 🎨 Interface do Usuário

### Simulador da Copa do Mundo

**Seções:**

- 📋 **Exibição de Potes** - Cabeças de chave iniciais
- 🏟️ **Área de Grupos** - 8 grupos com 4 times cada
- 📊 **Tabelas de Grupos** - Classificação e estatísticas
- 🏆 **Chave Eliminatória** - Visualização da árvore do torneio
- 🥇 **Exibição do Campeão** - Anúncio do campeão

**Elementos Visuais:**

- Bandeiras das seleções nacionais
- Identidade visual da Copa do Mundo FIFA 2022
- Grupos com código de cores
- Layout responsivo

![alt text](images/world-cup.png)

### Simulador Libertadores/Sudamericana

**Seções:**

- 🏆 **Seleção de Torneio** - Escolher competição
- ⚽ **Exibição de Times** - Todos os clubes participantes
- 📋 **Fase de Grupos** - Distribuição dos clubes nos grupos
- 🎯 **Fase Eliminatória** - Chaves de eliminação
- 🥇 **Finais** - Partida do campeonato

**Elementos Visuais:**

- Escudos e logos dos clubes
- Identidade visual das competições
- Interface de tela dividida para ambos os torneios
- Transições animadas

![alt text](images/liberta-sula.png)

---

## 📱 Design Responsivo

Ambos os simuladores são totalmente responsivos:

### Breakpoints

- 📱 **Mobile:** 320px - 767px
- 📱 **Tablet:** 768px - 1024px
- 💻 **Desktop:** 1025px+

### Otimizações para Mobile

- Layouts empilhados para rolagem fácil
- Botões amigáveis ao toque
- Tamanhos otimizados de bandeiras/logos
- Tabelas de grupos comprimidas

---

## 🎓 O Que Aprendi

Construir estes simuladores melhorou minhas habilidades em:

### Habilidades em JavaScript

- ✅ **Design de Algoritmos:** Lógica complexa de sorteio e simulação
- ✅ **Estruturas de Dados:** Gerenciar times, grupos, partidas
- ✅ **Manipulação do DOM:** Geração dinâmica de conteúdo
- ✅ **Tratamento de Eventos:** Controles interativos do usuário
- ✅ **Aleatorização:** Sorteios justos e realistas
- ✅ **Gerenciamento de Estado:** Rastrear progressão do torneio

### Resolução de Problemas

- ✅ **Lógica de Torneios:** Implementar regras oficiais
- ✅ **Geração de Chaves:** Criar árvores de eliminação
- ✅ **Cálculo de Placares:** Pontos, saldo de gols, critérios de desempate
- ✅ **Organização de Dados:** Armazenamento eficiente de times e partidas

### Design & UX

- ✅ **Design de Interface Esportiva:** Criar interfaces envolventes
- ✅ **Hierarquia Visual:** Organizar informações complexas
- ✅ **Layouts Responsivos:** Adaptar para todos os tamanhos de tela
- ✅ **Fluxo do Usuário:** Guiar usuários pelas etapas de simulação

---

## 🏆 Detalhes dos Torneios

### Copa do Mundo FIFA 2022 (Times Incluídos)

**Formato da Fase de Grupos:**

- 8 grupos (A até H)
- 4 times por grupo
- Formato round-robin
- 2 melhores avançam para eliminatórias

**Formato Eliminatório:**

- Oitavas de final (8 partidas)
- Quartas de final (4 partidas)
- Semifinais (2 partidas)
- Disputa de terceiro lugar
- Final

### Copa Libertadores

**Países Participantes:**

- 🇦🇷 Argentina
- 🇧🇷 Brasil
- 🇨🇱 Chile
- 🇨🇴 Colômbia
- 🇪🇨 Equador
- 🇵🇾 Paraguai
- 🇵🇪 Peru
- 🇺🇾 Uruguai
- 🇻🇪 Venezuela
- 🇧🇴 Bolívia

### Copa Sudamericana

**Formato:**

- Fase de grupos
- Rodadas eliminatórias
- Partidas de ida e volta
- Regra do gol fora (se aplicável)

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/FuncionalidadeIncrivel`)
3. Commit suas mudanças (`git commit -m 'Adiciona alguma FuncionalidadeIncrivel'`)
4. Push para a branch (`git push origin feature/FuncionalidadeIncrivel`)
5. Abra um Pull Request

### Ideias de Contribuição

- Adicionar mais torneios (Euro, Champions League, etc.)
- Melhorar algoritmos de simulação
- Adicionar dados históricos de torneios
- Criar versão de app mobile
- Implementar previsões multiplayer
- Adicionar simulação de odds de apostas

---

## 📝 Licença

Este projeto é open source e está disponível sob a [Licença MIT](LICENSE).

---

## ⚠️ Aviso Legal

Este é um **projeto educacional feito por fãs**. Não é afiliado, endossado ou conectado à FIFA, CONMEBOL ou quaisquer organizações oficiais de futebol. Todos os nomes de times, logos e marcas registradas são propriedade de seus respectivos donos.

Este simulador é destinado para:

- ✅ Entretenimento e educação
- ✅ Aprender JavaScript e desenvolvimento web
- ✅ Entender formatos de torneios
- ✅ Demonstração em portfólio

---

## 👨‍💻 Autor

**Adrian Lobato**

- GitHub: [@adrian1715](https://github.com/adrian1715)
- LinkedIn: [Adrian Lobato](https://linkedin.com/in/adrian-lobato)
- Portfólio: [portfolio-website-adrian-lobato.onrender.com](https://portfolio-website-adrian-lobato.onrender.com/)

---

## 🙏 Agradecimentos

- **FIFA** e **CONMEBOL** por inspirar os formatos de torneios
- Fontes de imagens de bandeiras e logos de times
- A comunidade do futebol pelos dados de torneios
- Bootstrap pelo framework responsivo

---

## 📊 Estatísticas do Projeto

![GitHub last commit](https://img.shields.io/github/last-commit/adrian1715/football-tournament-simulator?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/adrian1715/football-tournament-simulator?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/adrian1715/football-tournament-simulator?style=flat-square)

---

**Se você gostou destes simuladores, por favor dê uma ⭐ no repositório**

_Agradeço de coração seu apoio!_

[⬆ Voltar ao Topo](#-simulador-de-torneios-de-futebol)
