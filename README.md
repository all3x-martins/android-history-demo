# História do Mascote do Android

Website responsivo sobre a história do mascote do Android (Bugdroid), desenvolvido como projeto de estudo em HTML5 e CSS3.

## Sobre o Projeto

Site informativo que apresenta a evolução do mascote do Android, desde as primeiras criações de Dan Morrill até o design final do Bugdroid por Irina Blok. Inclui informações sobre as versões históricas do Android nomeadas com doces.

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com arquitetura modular
- **Font Awesome**: Biblioteca de ícones
- **Google Fonts**: Fontes Inter e Bebas Neue (com versões locais de backup)

## Estrutura do Projeto

```
android-history-demo/
├── assets/
│   ├── images/          # Imagens otimizadas do projeto
│   └── fonts/           # Fontes locais (Inter e Bebas Neue)
├── css/
│   ├── base.css         # Variáveis CSS, reset e tipografia base
│   ├── style.css        # Estilos dos componentes principais
│   └── responsive.css   # Media queries para responsividade
├── index.html           # Página principal
└── README.md           # Documentação
```

## Características Técnicas

### CSS Modular
- **base.css**: Variáveis CSS customizadas, reset global, definições tipográficas
- **style.css**: Estilização de header, main, aside, footer e componentes
- **responsive.css**: Adaptações para dispositivos móveis (≤768px)

### Design System
- Paleta de cores verde baseada no Android (6 tons: #f8fffe até #0f2419)
- Gradientes CSS para elementos visuais
- Sistema de sombras em três níveis
- Tipografia responsiva com clamp()

### Responsividade
- Layout adaptável com breakpoint principal em 768px
- Navegação mobile otimizada
- Imagens responsivas com lazy loading
- Grid adaptativo para lista de versões Android

### Performance
- Fontes locais com font-display: swap
- Lazy loading implementado nas imagens
- Estrutura CSS otimizada

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/all3x-martins/android-history-demo.git
```

2. Navegue até o diretório:
```bash
cd android-history-demo
```

3. Abra o arquivo `index.html` em um navegador ou use um servidor local:
```bash
# Opção com Python
python -m http.server 8000

# Opção com Node.js
npx live-server
```

## Funcionalidades

- Layout responsivo para desktop e mobile
- Navegação com ícones Font Awesome
- Seção de vídeo incorporado do YouTube
- Aside informativo com lista das versões Android
- Links externos com indicadores visuais
- Transições CSS suaves
- Estrutura semântica HTML5

## Paleta de Cores

| Variável | Cor | Uso |
|----------|-----|-----|
| --cor0 | #f8fffe | Background principal |
| --cor1 | #e8f5f0 | Background secundário |
| --cor2 | #3ddc84 | Verde Android (destaque) |
| --cor3 | #2fa866 | Verde médio |
| --cor4 | #1a5c37 | Verde escuro (textos importantes) |
| --cor5 | #0f2419 | Verde muito escuro (texto principal) |

## Autor

Desenvolvido por **Allexander Martins** como projeto de estudo.

- GitHub: [@all3x-martins](https://github.com/all3x-martins)
- Baseado no curso de HTML e CSS do [Curso em Vídeo](https://www.cursoemvideo.com)

## Licença

Este projeto está sob a licença MIT.
