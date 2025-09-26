# Yu-Gi-Oh Card Game Design Guidelines

## Design Approach
**Reference-Based Approach**: Drawing inspiration from classic card game interfaces like Magic: The Gathering Online and Hearthstone, while maintaining the retro aesthetic of early Yu-Gi-Oh video games. The black and white constraint creates a distinctive, minimalist gaming experience.

## Core Design Elements

### Color Palette
**Monochrome Theme**: Strict black and white palette as specified
- **Primary**: 0 0% 0% (pure black) for text and borders
- **Background**: 0 0% 100% (pure white) for main areas
- **Gray Scale**: 0 0% 90%, 0 0% 70%, 0 0% 50%, 0 0% 30% for depth and hierarchy
- **Highlights**: Use pure white text on black backgrounds for emphasis

### Typography
- **Primary Font**: Monospace font (Courier New or similar) for authentic retro gaming feel
- **Card Text**: 14px for stats, 12px for descriptions
- **UI Text**: 16px for buttons and labels
- **Game Stats**: 20px bold for HP display
- **Headers**: 24px bold for section titles

### Layout System
**Tailwind Spacing**: Use units of 2, 4, 8, and 16 for consistent spacing
- Card spacing: p-4, m-2
- Section gaps: gap-8
- Container padding: p-8
- Button padding: px-4 py-2

### Component Library

#### Core Game Components
- **Game Board**: Grid layout with designated zones for player and computer cards
- **Card Display**: Rectangle cards with clear ATK/DEF stats and position indicators
- **HP Counter**: Prominent numerical display with visual bars
- **Turn Indicator**: Clear messaging about whose turn it is
- **Action Buttons**: "Attack Position", "Defense Position", "End Turn"

#### Visual Elements
- **Cards**: 120px width, 160px height with thick black borders (2px)
- **Position Indicators**: "ATK" and "DEF" labels with distinct visual styling
- **Battle Animations**: Simple fade/shake effects for attacks (minimal as specified)
- **Game State**: Clear separation between player and computer zones

#### Navigation & Controls
- **New Game Button**: Prominent restart functionality
- **Game Rules**: Collapsible help section
- **Card Hover**: Subtle highlight with gray background (0 0% 90%)

### Layout Zones
1. **Computer Zone**: Top section with HP display and card field
2. **Battle Field**: Center area where combat occurs
3. **Player Zone**: Bottom section with HP, hand, and action buttons
4. **Sidebar**: Game state information and controls

### Game Aesthetics
- **Retro Gaming**: Pixel-perfect borders and clean geometric shapes
- **Card Game Feel**: Traditional card proportions and clear stat presentation
- **Minimalist UI**: Focus on gameplay with minimal visual distractions
- **High Contrast**: Strong black/white contrast for excellent readability

### Interactive Elements
- **Card Selection**: Clear visual feedback for selected cards
- **Battle Zones**: Distinct areas for Attack and Defense positions
- **Damage Indicators**: Temporary text overlays for damage numbers
- **Win/Loss States**: Full-screen modal with game results

This design creates an authentic retro card game experience while maintaining modern usability standards within the strict black and white visual constraint.