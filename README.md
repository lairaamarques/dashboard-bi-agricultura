# 🌱 EcoSemente BI - Dashboard Gerencial

Sistema de **Inteligência de Negócios (BI) e Gestão de Estoque** para agricultura familiar e comunidades ribeirinhas da Amazônia.

## 📋 Projeto

**TCC 1 - IFAM / CA-TADS**

Um dashboard gerencial responsivo para:
- Gestão de estoque de sementes e mudas
- Monitoramento de árvores sementeiras
- Registro de vendas e receitas
- Inteligência comercial para comunidades ribeirinhas

## 🎯 Funcionalidades Principais

### 1. **Autenticação (index.html)**
- Login seguro com validação
- Credenciais: `admin` / `123456`
- Sessão com sessionStorage

### 2. **Dashboard Principal (dashboard.html)**
- 📊 KPIs: Matrizes Mapeadas, Estoque, Mudas, Receita Projetada
- 📈 Gráficos de barras por espécie
- 🚨 Alertas de negócio em tempo real
- 📋 Tabela de inventário comercial
- 🔍 Filtros por tipo de produto

### 3. **Gestão de Estoque (estoque.html)**
- 📦 Resumo de inventário
- 🔔 Alertas de estoque baixo/crítico
- 📊 Tabela detalhada de recursos

### 4. **Registro de Vendas (vendas.html)**
- 💰 Faturamento e estatísticas
- 📈 Histórico de transações
- ✅ Status de entrega (Entregue/Reservado)

## 🎨 Design

- **Paleta de cores agrícola**:
  - Verde Primário: #2e5a44
  - Verde Secundário: #52b788
  - Marrom Acentual: #d4a373
  - Cinza Neutro: #f4f7f5

- **Layout responsivo**:
  - Desktop: Sidebar + conteúdo principal
  - Tablet: Layout adaptado
  - Mobile: Totalmente responsivo

## 📁 Estrutura

```
dashboard-bi-agricultura/
├── index.html          # Login
├── dashboard.html      # Painel principal
├── estoque.html        # Gerenciamento de estoque
├── vendas.html         # Registro de vendas
├── viveiro.html        # Viveiro de mudas (stub)
├── sementeiras.html    # Árvores sementeiras (stub)
└── README.md           # Documentação
```

## 🚀 Como Usar

### Opção 1: Abrir Localmente
```bash
# Clone o repositório
git clone https://github.com/lairaamarques/dashboard-bi-agricultura.git

# Abra index.html no navegador
open index.html
```

### Opção 2: GitHub Pages
1. Vá para Settings > Pages
2. Selecione "Deploy from a branch"
3. Escolha "main" branch
4. Acesse: https://lairaamarques.github.io/dashboard-bi-agricultura/

## 🔐 Credenciais de Teste

- **Usuário**: `admin`
- **Senha**: `123456`

## 📊 Dados de Exemplo

### Produtos/Espécies:
- Andiroba (32 sacas)
- Ucuúba (22 sacas)
- Copaíba (15 sacas)
- Açaí (10 sacas)
- Patauá (5 sacas)

### Status de Mercado:
- ✓ **Disponível** - Pronto para venda
- ⏱ **Reservado** - Aguardando coleta
- ✕ **Crítico** - Estoque baixo

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox + Grid)
- JavaScript (ES6+)
- Sem dependências externas

## 📝 Próximas Etapas

- [ ] Refinar design no Figma
- [ ] Integração com API REST (Spring Boot)
- [ ] Frontend com Vue.js 3
- [ ] Banco de dados (PostgreSQL)
- [ ] Autenticação OAuth2
- [ ] Mobile app com Flutter
- [ ] Sincronização offline

## 👨‍💻 Desenvolvimento

Desenvolvido para:
- **TCC 1**: Prototipagem e UX/UI
- **PIBIC**: Pesquisa em Inteligência de Negócios
- **Comunidade**: Agricultura Familiar da Amazônia

## 📄 Licença

MIT License - Livre para uso e distribuição

---

**Desenvolvido por**: Laira Amarques  
**Orientador**: Professor Carlos (IFAM)  
**Data**: 2026  
**Status**: 🟢 Em Desenvolvimento
