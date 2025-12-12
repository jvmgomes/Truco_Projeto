# Truco Online 🃏

Projeto de férias para criar um jogo de Truco em C# com multiplayer e bots.

## 📋 Sobre

Este é um projeto pessoal que pretendo desenvolver nas férias. A ideia é criar um jogo de Truco funcional onde seja possível jogar online com amigos ou contra bots com inteligência artificial.

> ⚠️ **Status**: Projeto em fase inicial de planejamento

## 🎯 Objetivos

- Criar um jogo de Truco jogável
- Implementar sistema cliente-servidor para jogo online
- Desenvolver bots com diferentes níveis de dificuldade
- Interface gráfica simples e funcional

## 🛠️ Tecnologias Planejadas

### Para o Jogo Base
- **C#**: Linguagem principal
- **WPF (Windows Presentation Foundation)**: Interface gráfica moderna
  - Animações suaves para as cartas
  - Visual mais atraente e profissional
  - XAML para separar design da lógica

### Para Multiplayer (futuro)
- **SignalR**: Para comunicação em tempo real entre jogadores
- **ASP.NET Core**: Servidor do jogo

### Para os Bots (futuro)
- Começar com lógica simples (if/else)
- Evoluir para algoritmos mais complexos
- Possivelmente usar ML.NET para bots avançados

### Banco de Dados (futuro)
- **SQLite**: Para começar (simples e local)
- Migrar para algo maior se necessário

## 🎮 Funcionalidades Planejadas

### Primeira Fase
- [ ] Sistema básico de cartas
- [ ] Regras do Truco Paulista
- [ ] Jogo local (1v1 na mesma máquina)
- [ ] Interface gráfica em WPF com animações básicas

### Segunda Fase
- [ ] Sistema de servidor
- [ ] Jogo online (conectar 2 jogadores)
- [ ] Sistema de salas/rooms

### Terceira Fase
- [ ] Bot simples para jogar sozinho
- [ ] Melhorar a IA do bot
- [ ] Sistema de ranking básico

## 📁 Estrutura Inicial

```
TrucoOnline/
├── src/
│   ├── Models/           # Carta, Jogador, Partida
│   ├── Services/         # Lógica do jogo
│   ├── Views/            # Telas WPF (XAML)
│   ├── ViewModels/       # MVVM pattern
│   └── App.xaml          # Entrada do app WPF
└── README.md
```

## 🎲 O que vou implementar

**Regras básicas do Truco:**
- Sistema de cartas (baralho de 40)
- Truco, Seis, Nove, Doze
- Contagem de pontos (tentos)
- Partida 2x2 (você + bot vs 2 bots)

## 📚 Preciso estudar

- Como funciona WPF e XAML
- Animações em WPF para as cartas
- Padrão MVVM (Model-View-ViewModel)
- Como funciona SignalR para multiplayer
- Algoritmos de IA para jogos de cartas
- Sincronização de estado do jogo entre clientes
- Como fazer deploy de um servidor de jogo


## 👤 Autor

**jvmgomes**
- GitHub: [@jvmgomes](https://github.com/jvmgomes)

---

📝 **Nota**: Este README será atualizado conforme o projeto for evoluindo durante as férias!
