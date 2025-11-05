# Guia de Importação para Figma

## Como usar este arquivo JSON no Figma

O arquivo `trashmove-design-spec.json` contém a especificação completa do design do TrashMove. Para importá-lo no Figma:

### Método 1: Manual (Recomendado)
1. Abra o Figma (web ou desktop)
2. Crie um novo projeto chamado "TrashMove App"
3. Use as especificações do JSON para criar os frames manualmente
4. Configure as cores da paleta (Color Styles)
5. Configure a tipografia (Text Styles)
6. Crie os componentes conforme descrito

### Método 2: Usando Plugin
1. Instale o plugin "Figma Tokens" ou "Design Tokens" no Figma
2. Importe o arquivo JSON como design tokens
3. Isso configurará automaticamente cores e espaçamentos

## Estrutura Recomendada de Frames no Figma

### Página 1: Onboarding
- Frame: Onboarding 1 - Boas-vindas
- Frame: Onboarding 2 - Rastreamento
- Frame: Onboarding 3 - Recompensas

### Página 2: Home & Principal
- Frame: Home Screen
- Frame: Tracking Screen
- Frame: Collection Points
- Frame: Schedule Collection

### Página 3: Gamificação
- Frame: Rewards Screen
- Frame: Ranks & Patentes
- Frame: Impact Screen
- Frame: Achievements

### Página 4: Eventos & Social
- Frame: Events Screen
- Frame: TrashMove Run Detail
- Frame: Virtual Challenge

### Página 5: Perfil & Configurações
- Frame: Profile Screen
- Frame: Premium Screen
- Frame: Settings

### Página 6: Design System
- Componentes: Botões, Cards, Inputs
- Colors: Paleta completa
- Typography: Todos os estilos de texto

## Cores Principais

**Primária (Verde):**
- `#00C853` - Ações principais, botões, links
- `#00897B` - Variante escura para hover/pressed

**Secundária (Azul Ciano):**
- `#00ACC1` - Elementos de informação, mapas

**Acento (Laranja):**
- `#FF6F00` - Destaques, badges especiais

**Neutros:**
- `#F5F5F5` - Background
- `#FFFFFF` - Surface/Cards
- `#212121` - Texto principal
- `#757575` - Texto secundário

## Ícones Necessários

Cada seção precisa de ícones específicos:
- 🏠 Home
- 🗺️ Mapa/Coleta
- 🎁 Recompensas
- 👤 Perfil
- 🚛 Caminhão
- ♻️ Reciclagem
- 🏃 Eventos/Corridas
- 📊 Estatísticas
- 🌿 Patentes Ecológicas

## Componentes Principais

### 1. Card de Coleta
- Background branco
- Border radius: 12px
- Sombra pequena
- Informações: Dia, horário, progresso

### 2. Botão Primário
- Background: Verde (#00C853)
- Texto: Branco
- Border radius: 12px
- Altura: 48px
- Padding horizontal: 24px

### 3. Badge de Patente
- Background: Gradiente verde
- Ícone + texto
- Border radius: 16px
- Sombra média

### 4. Card de Recompensa
- Imagem do produto
- Nome e pontos necessários
- Badge "Disponível" ou "Bloqueado"
- Botão "Resgatar"

## Protótipos Interativos

Configure os seguintes protótipos:

1. **Onboarding → Home**: Auto-avanço com delay
2. **Home → Tracking**: Tap no botão "Rastrear"
3. **Home → Rewards**: Tap na tab "Recompensas"
4. **Rewards → Redeem**: Tap em recompensa disponível
5. **Profile → Premium**: Tap em "Plano Premium"
6. **Menu → Settings**: Tap em qualquer item do menu

## Notas de Design

- **Hierarquia Visual**: Sempre destaque a informação mais importante
- **Espaçamento**: Use 8px grid system
- **Contraste**: Garanta acessibilidade (AA+)
- **Micro-interações**: Animações leves para feedback
- **Responsividade**: Mobile-first (360x640 a 414x896)

## Recursos Externos

- Fontes: Inter (Google Fonts)
- Ícones: Material Icons ou Feather Icons
- Mapas: Google Maps UI/UX para referência
- Ilustrações: Undraw.co para onboarding

## Anotações de Implementação

Para desenvolvedores:
- React Native ou Flutter recomendado
- Integração com Google Maps API
- Notificações push (Firebase)
- Backend: Node.js/Python para dashboard
- Banco de dados: PostgreSQL

## Feedback e Iterações

Após prototipagem:
1. Teste com usuários reais
2. Ajuste fluxos baseado em feedback
3. Otimize performance de animações
4. Valide acessibilidade
5. Prepare assets para exportação (@1x, @2x, @3x)

