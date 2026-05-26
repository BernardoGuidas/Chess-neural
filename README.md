# Chess Neural Trainer - Standalone Version

Um site interativo completo de xadrez com redes neurais, desenvolvido em HTML, CSS e JavaScript.

## Como Usar

1. **Abra o arquivo `index.html` em um navegador web**
   - Pode ser feito de duas formas:
     - Clique duplo no arquivo `index.html`
     - Arraste o arquivo para um navegador aberto
     - Use um servidor local (recomendado para melhor performance)

2. **Servidor Local (Recomendado)**
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Node.js
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```
   Depois acesse: `http://localhost:8000`

## Funcionalidades

### Modos de Jogo
- **Humano vs Humano**: Jogue contra outro jogador no mesmo computador
- **Humano vs IA**: Desafie uma IA com movimentos aleatórios
- **Jogar Contra IA Treinada**: Jogue contra redes neurais treinadas
- **Treinamento Neural**: Observe duas redes neurais jogando entre si e evoluindo

### Análise de Partidas
- **Replay Passo a Passo**: Reproduza qualquer partida com controles de navegação
- **Gráficos Estatísticos**: Visualize evolução de fitness e taxa de vitória
- **Histórico Completo**: Acesse todas as partidas jogadas

### Recursos Técnicos
- Motor de xadrez completo com todas as regras
- Redes neurais com aprendizado por reforço
- Persistência de dados em localStorage
- Exportação/importação de partidas em JSON
- Interface Neo-Brutalism com design moderno

## Estrutura de Arquivos

```
chess-neural-trainer-standalone/
├── index.html              # Arquivo principal (abra este)
├── assets/                 # JavaScript e CSS compilados
│   ├── index-*.js         # Código JavaScript minificado
│   └── index-*.css        # Estilos CSS compilados
├── __manus__/             # Arquivos de debug (opcional)
└── README.md              # Este arquivo
```

## Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Sem dependências externas (tudo está incluído)

## Dicas de Uso

1. **Treinamento Neural**: Configure o número de gerações e observe as redes evoluindo
2. **Análise**: Use a velocidade de reprodução para analisar movimentos em detalhes
3. **Exportação**: Exporte suas partidas para análise posterior
4. **Temas**: O site usa um design Neo-Brutalism com tabuleiro verde e branco

## Suporte

Para melhor performance, use um navegador atualizado:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Notas Técnicas

- Todas as partidas são salvas localmente no navegador (localStorage)
- Limite de ~5MB de dados locais (aproximadamente 100 partidas)
- Sem conexão com internet necessária após carregamento
- Compatível com dispositivos desktop e tablets

---

**Chess Neural Trainer © 2026**
Desenvolvido com HTML, CSS, JavaScript e Redes Neurais
