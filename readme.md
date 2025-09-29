1. infraestructure/
Contém os recursos estáticos e as páginas fundamentais que formam a base do site (conteúdo de marketing, páginas estáticas).

infraestructure/
├── assets/         # Recursos estáticos globais (CSS, Fonts, Images, JS)
│   ├── css/        # Arquivos de estilo CSS
│   ├── fonts/      # Arquivos de fontes
│   ├── images/     # Imagens e ícones estáticos
│   └── js/         # Arquivos JavaScript (scripts globais e bibliotecas)
└── pages/          # Páginas HTML principais
    ├── about/      # Conteúdo da página "Sobre"
    ├── contact/    # Conteúdo da página de "Contato"
    └── index.html  # Página inicial (Homepage)

2. usuario/
Dedicada aos recursos e à interface da Área do Usuário (painel de controle, área logada ou aplicação principal).

usuario/
├── assets/         # Recursos estáticos específicos da Área do Usuário
│   ├── css/        # Arquivos de estilo CSS da área de usuário
│   ├── images/     # Imagens da área de usuário
│   ├── js/         # Arquivos JavaScript da área de usuário
│   └── pages/      # Templates ou páginas específicas da área de usuário
└── components/     # Módulos de interface reutilizáveis (widgets, cards, etc.)

Separação Lógica
A estrutura visa uma separação clara entre o conteúdo base/estático (infraestructure) e a aplicação/área logada (usuario), permitindo que cada área gerencie seus próprios recursos (assets) de forma independente.