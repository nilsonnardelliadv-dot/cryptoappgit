# 📊 Ultra Technical Crypto Panel PRO

Uma aplicação completa de análise técnica de criptomoedas em um único arquivo HTML. Monitore, analise e tome decisões informadas sobre seus investimentos em cripto com dados em tempo real da Binance.

## 🌟 Características Principais

### Análise Técnica Completa
- **RSI** (Relative Strength Index) - Método Wilder, 14 períodos
- **MACD** (Moving Average Convergence Divergence) - Configuração 12/26/9
- **Bandas de Bollinger** - 20 períodos, 2σ
- **ATR** (Average True Range) - 14 períodos
- **ADX/DI+/DI-** - Índice de Movimento Direcional
- **EMAs e SMAs Múltiplas** - Análise de tendência
- **Detecção de Suportes/Resistências** - Automática
- **Detecção de Divergências** - Preço vs RSI

### Metodologia Wyckoff 2.0
- Detecção de sinais: SC, Spring, SOS, UTAD, LPS, LPSY, CHoCH
- Determinação de fases (Acumulação, Markup, Distribuição, Markdown)
- Score de probabilidade (0-100)
- Interpretação automática

### Análise Fibonacci Avançada
- Retrações automáticas: 0%, 23.6%, 38.2%, 50%, 61.8%, 78.6%, 100%
- Extensões: 127.2%, 161.8%, 261.8%
- Identificação do nível mais próximo
- Avaliação de status e scoring

### Sistema de Alertas Inteligentes
- Alertas automáticos para condições de sobrecompra/sobrevenda
- Cruzamentos de MACD
- Rompimentos de Bandas de Bollinger
- Sinais Wyckoff
- Toques em níveis Fibonacci

### Interface Moderna
- Design dark com efeitos glass-morphism
- Responsivo e adaptável
- Gráficos interativos com Lightweight Charts
- Tooltips educacionais
- Exportação para XLSX, JSON e CSV

## 🚀 Como Usar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/nilsonnardelliadv-dot/cryptoappgit.git
   cd cryptoappgit
   ```

2. **Abra o arquivo**
   - Simplesmente abra `index.html` em seu navegador moderno
   - Ou use um servidor local:
     ```bash
     python3 -m http.server 8080
     # Acesse http://localhost:8080/index.html
     ```

3. **Configure**
   - Clique no botão "Configurações"
   - Ajuste o intervalo de atualização
   - Escolha o timeframe desejado
   - Adicione ou remova tokens da lista

## 📋 Tokens Monitorados Padrão

```
BTC, ETH, BNB, SOL, ADA, XRP, DOGE, DOT, LINK, LTC, BCH, XLM, ETC, FIL
```

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Estilização via CDN
- **JavaScript Vanilla** - Sem dependências de frameworks
- **Lightweight Charts** - Biblioteca de gráficos TradingView
- **SheetJS** - Exportação XLSX
- **FontAwesome** - Ícones
- **Google Fonts** - Inter & JetBrains Mono

## 📊 Fonte de Dados

- **WebSocket**: Preços em tempo real da Binance
  - `wss://stream.binance.com:9443/ws/!ticker@arr`
- **REST API**: Dados históricos OHLC
  - `https://api.binance.com/api/v3/klines`
- **Timeframes suportados**: 1m, 3m, 5m, 15m, 1h, 4h, 1d, 1w

## 🎯 Funcionalidades Especiais

### Análise Automática (AI-like)
Geração automática de análises textuais detalhadas incluindo:
- Avaliação de momentum
- Análise de tendência
- Interpretação Wyckoff
- Níveis Fibonacci
- Avaliação de risco
- Conclusões e recomendações

### Simulador de Trades
- Registro de compras/vendas
- Cálculo de P&L
- Histórico de transações
- Persistência local

### Ranking e Scores
- Score técnico geral (0-100)
- Score Wyckoff
- Score Fibonacci
- Rankings de volatilidade, volume e força relativa

## 💾 Armazenamento

Todos os dados são armazenados localmente no navegador via `localStorage`:
- Tokens monitorados
- Alertas
- Histórico de trades
- Configurações de usuário

## 🌐 Compatibilidade

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Qualquer navegador moderno com suporte ES6+

## 📈 Performance

- Cache eficiente de dados
- Atualizações incrementais de gráficos
- Busca com debounce
- Renderização otimizada

## 🔒 Segurança

- Sem armazenamento de dados sensíveis
- Todas as chamadas de API são para endpoints públicos da Binance
- localStorage usado apenas para preferências do usuário
- Sem scripts externos ou rastreamento

## 📸 Screenshots

![Dashboard Principal](https://github.com/user-attachments/assets/3773ce2b-71fe-4caf-9b42-d00ca84f7139)

![Modal de Configurações](https://github.com/user-attachments/assets/74b455fb-8a26-48ae-8246-e3c2407e6d9d)

## 📄 Licença

Este projeto é de código aberto e está disponível para uso livre.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## ⚠️ Aviso Legal

Esta ferramenta é apenas para fins educacionais e informativos. Não constitui aconselhamento financeiro. Faça sua própria pesquisa antes de tomar decisões de investimento.

---

Desenvolvido com ❤️ para a comunidade cripto
