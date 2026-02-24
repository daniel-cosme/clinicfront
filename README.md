# UX/UI Design System - SaaS Gestão Clínica TEA

## 1️⃣ 🎨 Design System

### 🎨 Cores (Design Tokens)

#### Primary
- primary-50: #f0f9ff
- primary-100: #e0f2fe
- primary-200: #bae6fd
- primary-300: #7dd3fc
- primary-400: #38bdf8
- primary-500: #0ea5e9
- primary-600: #0284c7
- primary-700: #0369a1
- primary-800: #075985
- primary-900: #0c4a6e

#### Secondary
- secondary-50: #f5f3ff
- secondary-100: #ede9fe
- secondary-200: #ddd6fe
- secondary-300: #c4b5fd
- secondary-400: #a78bfa
- secondary-500: #8b5cf6
- secondary-600: #7c3aed
- secondary-700: #6d28d9
- secondary-800: #5b21b6
- secondary-900: #4c1d95

#### Success
- success-50: #f0fdf4
- success-100: #dcfce7
- success-200: #bbf7d0
- success-300: #86efac
- success-400: #4ade80
- success-500: #22c55e
- success-600: #16a34a
- success-700: #15803d
- success-800: #166534
- success-900: #14532d

#### Warning
- warning-50: #fffbeb
- warning-100: #fef3c7
- warning-200: #fde68a
- warning-300: #fcd34d
- warning-400: #fbbf24
- warning-500: #f59e0b
- warning-600: #d97706
- warning-700: #b45309
- warning-800: #92400e
- warning-900: #78350f

#### Error
- error-50: #fef2f2
- error-100: #fee2e2
- error-200: #fecaca
- error-300: #fca5a5
- error-400: #f87171
- error-500: #ef4444
- error-600: #dc2626
- error-700: #b91c1c
- error-800: #991b1b
- error-900: #7f1d1d

#### Background
- bg-default: #ffffff
- bg-surface: #f9fafb
- bg-subtle: #f3f4f6

#### Surface
- surface-default: #ffffff
- surface-elevated: #ffffff
- surface-overlay: #ffffff

#### Border
- border-light: #e5e7eb
- border-medium: #d1d5db
- border-heavy: #9ca3af

### 🔤 Tipografia

#### Fonte recomendada
- Family: Inter
- Weights: 400, 500, 600, 700

#### Hierarquia
- H1: 32px, weight 700, line-height 40px
- H2: 24px, weight 600, line-height 32px
- H3: 20px, weight 600, line-height 28px
- Body: 16px, weight 400, line-height 24px
- Caption: 14px, weight 400, line-height 20px
- Small: 12px, weight 400, line-height 16px

### 📏 Espaçamento
- spacing-1: 4px
- spacing-2: 8px
- spacing-3: 16px
- spacing-4: 24px
- spacing-5: 32px
- spacing-6: 48px
- spacing-7: 64px

### 🎯 Iconografia
- Biblioteca: Lucide Icons
- Estilo: Outline
- Tamanho padrão: 20px (interface), 24px (destaque), 16px (subtle)
- Espaçamento entre ícone e texto: 8px

## 2️⃣ 🧱 Layout Base do Sistema

### Sidebar
- Largura: 256px
- Altura: 100vh
- Posição: Fixa à esquerda
- Background: #ffffff
- Border-right: 1px solid #e5e7eb

### Header
- Altura: 64px
- Posição: Fixa no topo
- Background: #ffffff
- Border-bottom: 1px solid #e5e7eb
- Padding: 0 24px

### Área de Conteúdo
- Margem esquerda: 256px (desktop)
- Padding: 24px
- Max-width: 1200px

### Grid Base
- 12 colunas
- Gutter: 24px
- Container max-width: 1200px

## 3️⃣ 🖥 Mockup Textual Estruturado

### 📊 Tela 1 – Dashboard do Terapeuta

#### [Resumo do Dia Card]
- Position: Grid col 1-4
- Width: 100%
- Height: auto
- Icon: Calendar (24px)
- Conteúdo: Total sessões (número grande), Presença (porcentagem), Pendências (número)
- Estado: Default

#### [Próximas Sessões Card]
- Position: Grid col 5-8
- Width: 100%
- Height: auto
- Icon: Clock (24px)
- Conteúdo: Lista de próximos horários com nomes de pacientes
- Estado: Default

#### [Pacientes Recentes Card]
- Position: Grid col 9-12
- Width: 100%
- Height: auto
- Icon: Users (24px)
- Conteúdo: Últimos 3 pacientes atendidos com data e status
- Estado: Default

#### [Alertas Importantes Card]
- Position: Grid col 1-6
- Width: 100%
- Height: auto
- Icon: AlertTriangle (24px)
- Conteúdo: Notificações urgentes com destaque visual
- Estado: Warning

#### [Progresso Geral Card]
- Position: Grid col 7-12
- Width: 100%
- Height: auto
- Icon: TrendingUp (24px)
- Conteúdo: Gráfico resumido de evolução média
- Estado: Default

### 📝 Tela 2 – Registro de Sessão

#### [Header Paciente]
- Position: Top
- Width: 100%
- Height: 64px
- Icon: User (24px)
- Conteúdo: Nome do paciente e data da sessão
- Estado: Default

#### [Metas Ativas Section]
- Position: Below header
- Width: 100%
- Height: auto
- Icon: Target (20px)
- Conteúdo: Lista de metas com checkboxes
- Estado: Default

#### [Campo Anotações]
- Position: Middle
- Width: 100%
- Height: 120px
- Icon: FileText (20px)
- Conteúdo: Textarea com placeholder
- Estado: Focus

#### [Escala Evolução]
- Position: Below anotações
- Width: 100%
- Height: auto
- Icon: BarChart3 (20px)
- Conteúdo: Slider ou botões numéricos 1-5
- Estado: Active

#### [Botão Salvar]
- Position: Bottom right
- Width: auto
- Height: 40px
- Icon: Save (20px)
- Conteúdo: "Salvar"
- Estado: Primary

### 📌 Tela 3 – Plano Terapêutico

#### [Lista Metas]
- Position: Main content
- Width: 100%
- Height: auto
- Icon: CheckCircle (20px)
- Conteúdo: Tabela com metas, status e data
- Estado: Default

#### [Badge Status]
- Position: Na linha da meta
- Width: auto
- Height: 24px
- Icon: Circle (12px)
- Conteúdo: Em andamento, Concluído, Planejado
- Estado: Success/Warning/Default

#### [Gráfico Histórico]
- Position: Sidebar direita
- Width: 300px
- Height: 200px
- Icon: LineChart (24px)
- Conteúdo: Linha de progresso
- Estado: Default

#### [Botão Adicionar Meta]
- Position: Top right
- Width: auto
- Height: 40px
- Icon: Plus (20px)
- Conteúdo: "Adicionar Meta"
- Estado: Secondary

### 👨‍👩‍👧 Tela 4 – Dashboard dos Pais

#### [Resumo Progresso Card]
- Position: Top
- Width: 100%
- Height: auto
- Icon: ThumbsUp (24px)
- Conteúdo: Porcentagem de evolução
- Estado: Success

#### [Gráfico Simplificado]
- Position: Middle
- Width: 100%
- Height: 200px
- Icon: TrendingUp (20px)
- Conteúdo: Gráfico linear de progresso
- Estado: Default

#### [Mensagem Positiva]
- Position: Below gráfico
- Width: 100%
- Height: auto
- Icon: Heart (20px)
- Conteúdo: Frase motivacional
- Estado: Default

#### [Histórico Sessões]
- Position: Grid col 1-6
- Width: 100%
- Height: auto
- Icon: History (20px)
- Conteúdo: Lista de últimas sessões
- Estado: Default

#### [Comunicação Terapeuta]
- Position: Grid col 7-12
- Width: 100%
- Height: auto
- Icon: MessageSquare (20px)
- Conteúdo: Formulário de mensagem
- Estado: Default

## 4️⃣ 🔄 Estados de Interface

### ⏳ Loading
- Spinner: 24px, cor primary-500
- Overlay: branco com opacidade 0.7
- Texto: "Carregando..." (14px, body)

### 📭 Empty State
- Ilustração: Vetor simples relacionado ao contexto
- Título: Centralizado, H3
- Descrição: Body, cor neutral-500
- Call to action: Botão primário

### ❌ Error State
- Ícone: AlertCircle (24px), cor error-500
- Mensagem: Destaque com borda vermelha
- Contraste: Adequado para WCAG AA

### ✅ Success State
- Ícone: CheckCircle (24px), cor success-500
- Mensagem: Fundo verde claro
- Feedback: Visual claro e temporário

### 🚫 Disabled State
- Opacidade: 0.5
- Cursor: not-allowed
- Sem interação possível

## 5️⃣ 🧩 Componentes Reutilizáveis

### Card
- Padding: 24px
- Border-radius: 8px
- Border: 1px solid border-light
- Box-shadow: 0 1px 2px rgba(0,0,0,0.05)
- States: Hover (shadow mais profunda)

### Button
- Primary: bg-primary-500, text-white
- Secondary: bg-white, border border-neutral-300, text-neutral-700
- Size: 40px height, padding horizontal 16px
- Border-radius: 6px
- States: Hover (opacity 0.9), Active (pressed effect)

### Input
- Height: 40px
- Border: 1px solid border-medium
- Border-radius: 6px
- Padding: 0 12px
- States: Focus (border-primary-500, shadow), Error (border-error-500)

### Select
- Similar ao Input
- Icon: ChevronDown (20px) à direita
- Dropdown com borda-radius e sombra

### Badge
- Height: 24px
- Min-width: 24px
- Padding: 0 8px
- Border-radius: 12px
- Variants: success, warning, error, default

### Modal
- Overlay: bg-black, opacity 0.5
- Content: bg-white, border-radius 8px, padding 24px
- Shadow: 0 10px 15px -3px rgba(0,0,0,0.1)

### Toast
- Position: top-right
- Width: 384px
- Padding: 16px
- Border-radius: 8px
- Variants: success, error, warning

### Table
- Border-collapse: collapse
- Width: 100%
- Cell padding: 12px
- Header: bg-neutral-50, font-weight 600

### Tabs
- Flex container
- Underline active tab
- Padding vertical 12px
- Hover state for non-active tabs

## 6️⃣ 📱 Responsividade

### Desktop (>=1024px)
- Sidebar visível
- Grid 12 colunas
- Layout full width

### Tablet (768px - 1023px)
- Sidebar colapsa para drawer
- Grid 8 colunas
- Conteúdo ajustado proporcionalmente

### Mobile (<768px)
- Sidebar como drawer superior
- Grid 4 colunas
- Cards empilhados verticalmente
- Botões com tamanho mínimo 44px
- Touch targets adequados