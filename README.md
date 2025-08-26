# Incentiva Data - MVP

## Descrição
Plataforma que conecta empresas e Organizações da Sociedade Civil (OSCs) para doações direcionadas com transparência e impacto social mensurável.

## Estrutura do Projeto

```
/
├── index.html                 # Página inicial
├── README.md                  # Documentação do projeto
├── Paginas/                   # Páginas internas
│   ├── dashboard.html         # Dashboard com Looker Studio
│   ├── painel.html           # Simulador de split de pagamento
│   ├── solicitacoes.html     # Formulários de solicitação
│   ├── editar-perfil.html    # Página de perfil
│   └── sobre.html            # Página institucional
└── Estilos/                  # Recursos estáticos
    ├── css/
    │   └── style.css         # Estilos principais
    ├── images/               # Imagens gerais
    ├── membros/              # Fotos dos membros da equipe
    │   ├── enzo.jpg
    │   ├── duda.jpg
    │   ├── taisa.jpg
    │   ├── giovanna.jpg
    │   └── giovanni.jpg
    └── logo/                 # Logos da empresa
        ├── LogoIncentivaData.png
        └── LogoIncentivaData-Simples.png
```

## Funcionalidades

### Página Inicial (index.html)
- Hero section com apresentação da plataforma
- Seções de notícias e soluções
- Modal de login/cadastro
- Sistema de tema claro/escuro

### Dashboard (dashboard.html)
- Estatísticas animadas
- Integração com Looker Studio
- Próximos passos com foco em doação

### Painel (painel.html)
- Simulador de split de pagamento (5% taxa de intermédio)
- Painéis diferenciados para Empresa/Pessoa e OSC
- Cálculos transparentes de valores

### Solicitações (solicitacoes.html)
- Formulários de solicitação de relatórios
- Acesso livre para todos os usuários

### Perfil (editar-perfil.html)
- Sistema de abas funcionais
- Dados persistentes no localStorage
- Estatísticas baseadas no tipo de usuário

### Sobre (sobre.html)
- Informações institucionais
- Seção de equipe com fotos dos membros
- Valores e missão da empresa

## Tecnologias Utilizadas
- HTML5
- CSS3 (com variáveis CSS e gradientes)
- JavaScript ES6+
- Looker Studio (integração)
- LocalStorage para persistência

## Características Técnicas
- Design responsivo
- Tema claro/escuro
- Animações CSS
- Validações de formulário
- Sistema de autenticação simulado
- Caminhos otimizados para GitHub Pages

## Como Usar

### Para desenvolvimento local:
1. Extraia os arquivos
2. Abra `index.html` em um navegador
3. Use as credenciais de teste:
   - Empresa: `empresa@teste.com` / `123`
   - OSC: `osc@teste.com` / `123`

### Para GitHub Pages:
1. Faça upload dos arquivos para um repositório
2. Ative o GitHub Pages nas configurações
3. O site estará disponível em `https://usuario.github.io/repositorio`

## Credenciais de Teste
- **Empresa/Pessoa:** empresa@teste.com / 123
- **OSC:** osc@teste.com / 123

## Paleta de Cores
- **Azul Pastel:** #6195C5, #AFCBF3
- **Laranja Pastel:** #F4A460, #EECD86
- **Tons Neutros:** #f8fafc, #1e293b

## Equipe
- Enzo
- Duda
- Taisa
- Giovanna
- Giovanni

## Licença
© 2023 Incentiva Data. Todos os direitos reservados.

