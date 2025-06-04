# Sistema Bootstrap - Documentação

## Descrição
Este projeto demonstra a implementação de componentes nativos do Bootstrap 5.3.2, criando uma interface responsiva e interativa que serve como documentação prática dos principais recursos do framework.

## Tecnologias Utilizadas
- **Bootstrap 5.3.2** - Framework CSS principal
- **HTML5** - Estrutura
- **CSS3** - Estilos customizados

## Principais Funcionalidades Bootstrap Implementadas

### 1. Sistema de Navegação (Navbar)
- **Navbar responsiva** com collapse para dispositivos móveis
- **Classes utilizadas**: `navbar`, `navbar-expand-lg`, `navbar-dark`, `bg-primary`
- **Botão de toggle** para menu mobile com `navbar-toggler`
- **Integração com modal** através do botão de login

### 2. Sistema Modal
- **Modal de Login** funcional com backdrop e animações
- **Classes utilizadas**: `modal`, `modal-dialog`, `modal-content`, `modal-header`, `modal-body`, `modal-footer`
- **Controles nativos**: `data-bs-toggle="modal"`, `data-bs-target="#loginModal"`
- **Formulário integrado** com campos de email e senha

### 3. Sistema Grid Responsivo
- **Demonstração prática** do sistema de colunas Bootstrap
- **Breakpoints responsivos**: `col-12`, `col-md-6`, `col-lg-3`
- **Adaptação automática** para diferentes tamanhos de tela:
  - Mobile: 1 coluna (col-12)
  - Tablet: 2 colunas (col-md-6) 
  - Desktop: 4 colunas (col-lg-3)

### 4. Sistema de Navegação por Abas (Pills)
- **Navegação por pills** com `nav-pills nav-justified`
- **Controle de conteúdo** via `data-bs-toggle="pill"`
- **Duas seções principais**:
  - Sistema Grid
  - Componentes Bootstrap

### 5. Componentes de Interface

#### Cards
- **Estrutura de cards** para organização de conteúdo
- **Classes utilizadas**: `card`, `card-header`, `card-body`, `card-title`, `card-text`

#### Formulários
- **Form Floating Labels** para melhor UX
- **Classes utilizadas**: `form-floating`, `form-control`

#### Botões
- **Variações de botões**: Primary, Secondary, Success, Warning, Danger
- **Agrupamento de botões** com `btn-group`
- **Integração com modais** e funcionalidades

#### Alertas
- **Sistema de alertas** com diferentes níveis
- **Classes demonstradas**: `alert-primary`, `alert-secondary`, `alert-success`, `alert-warning`, `alert-info`
- **Integração com ícones** Font Awesome

#### Badges
- **Badges informativos** com diferentes cores
- **Classes utilizadas**: `badge bg-primary`, `badge bg-secondary`, etc.

### 6. Layout e Estrutura

#### Flexbox Layout
- **Body flexível** com `d-flex flex-column`
- **Footer fixo** com `mt-auto`
- **Centralização de conteúdo** com classes Bootstrap

#### Sistema de Espaçamento
- **Padding e margin** consistentes usando classes utilitárias
- **Espaçamento responsivo** com `py-5`, `mb-4`, `mt-4`, etc.


## Responsividade
O projeto é totalmente responsivo, adaptando-se automaticamente a:
- **Dispositivos móveis** (até 768px)
- **Tablets** (768px - 992px)  
- **Desktops** (992px+)



## Dependências CDN
- Bootstrap CSS/JS: `cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.2/`

