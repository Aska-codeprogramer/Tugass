---
name: Aether Productivity System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464554'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#767586'
  outline-variant: '#c7c4d7'
  surface-tint: '#494bd6'
  primary: '#4648d4'
  on-primary: '#ffffff'
  primary-container: '#6063ee'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0c1ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#825100'
  on-tertiary: '#ffffff'
  tertiary-container: '#a36700'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  mono-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system embodies focused momentum, precision, and calm clarity. Built for modern high-performance teams and knowledge workers, it rejects cognitive clutter in favor of an orderly, structural workspace that balances utilitarian efficiency with an elevated executive finish.

The style unites modern corporate SaaS clarity with refined tactile glassmorphism. It uses crisp hairline dividers, soft diffused elevation, and high-legibility typography to structure dense task data without visual fatigue. Subtle frosted translucent overlays are reserved for navigational bars, floating action docks, and contextual menus, ensuring that work surfaces remain grounded, stable, and distraction-free.

## Colors
The color hierarchy is anchored by a deep slate neutral foundation (`#0F172A`), balanced across crisp cool-white canvas tones (`#F8FAFC`) and refined container surfaces (`#FFFFFF`). 

- **Primary (`#6366F1` - Electric Indigo):** Reserved for primary calls-to-action, active workspace states, focused inputs, and the "New Tasks" (Tugas Baru) workflow state.
- **Secondary / Semantic Success (`#10B981` - Emerald Green):** Used for "Completed" (Selesai) tasks, verification checkpoints, progress completion indicators, and positive throughput metrics.
- **Tertiary / Semantic Warning (`#F59E0B` - Warm Amber):** Denotes "In Progress" (Sedang Dikerjakan) states, impending deadlines, and active focus timers.
- **Semantic Destructive (`#EF4444` - Crimson):** Reserved strictly for blocked issues, overdue deadlines, and destructive actions.
- **Neutrals (Slate Tones):**
  - Text Primary: `#0F172A` (Slate 900)
  - Text Secondary: `#475569` (Slate 600)
  - Text Muted: `#94A3B8` (Slate 400)
  - Hairline Borders: `#E2E8F0` (Slate 200)
  - Subsurface / Card Hover: `#F1F5F9` (Slate 100)

Semantic status badges utilize a muted tint background (8–12% opacity) paired with high-contrast text and a solid 6px indicator pip to maintain WCAG AAA compliance across data tables and Kanban columns.

## Typography
Plus Jakarta Sans serves as the display and section header typeface, providing an architectural yet welcoming geometry. Inter handles all body content, data attributes, tabular metadata, and navigational UI, capitalizing on its balanced vertical metrics and tall x-height for scan-heavy dashboard operations.

Numerical values in progress meters, time tracking stamps, and task counters should explicitly enable font feature settings `tnum` (tabular figures) and `cv02`, `cv03`, `cv04` for enhanced glyph differentiation.

## Layout & Spacing
The layout leverages an adaptable fluid-grid system structured around an 8px modular baseline (with 4px increments for compact component internals):

- **Desktop (1280px+):** Collapsible 260px navigation rail, followed by a fluid multi-column workspace with a 2rem margin and 1.5rem column gutters. Kanban boards expand horizontally with 320px fixed-width swimlanes separated by 1.5rem gutters.
- **Tablet (768px - 1279px):** Navigation rail collapses to an icon dock (64px width). Margins reduce to 1.5rem with 1rem gutters. Kanban views allow horizontal overflow scrolling with snap points.
- **Mobile (< 768px):** Navigation shifts to a persistent bottom glass bar or off-canvas drawer. Single column reflow with 1rem margins and 0.75rem gutters. Kanban views switch to segmented tabs or a vertically stacked accordion.

Spacing between functional task rows in list views is maintained at `space-sm` (0.5rem) to ensure high information density without visual crowding.

## Elevation & Depth
Depth is created through low-contrast border definition and multi-layered atmospheric shadows rather than heavy drop shadows:

- **Surface Level 0 (Canvas):** `#F8FAFC` base application plane.
- **Surface Level 1 (Panels & Rows):** `#FFFFFF` with a crisp 1px perimeter border of `rgba(226, 232, 240, 0.8)`. Flat elevation.
- **Surface Level 2 (Cards & Kanban Tiles):** `#FFFFFF` paired with an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)` and a 1px border of `#E2E8F0`. On hover, the tile transitions to `0 8px 16px -4px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Surface Level 3 (Modals & Command Palettes):** `#FFFFFF` supported by `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.05)`.
- **Glassmorphic Overlays (Sidebars, Floating Docks, Headers):** `rgba(255, 255, 255, 0.75)` with a `backdrop-filter: blur(12px) saturate(180%)` and a bottom or right hairline border of `rgba(226, 232, 240, 0.6)`.

## Shapes
A roundedness factor of 2 provides a balanced, contemporary look. Structural cards and panels use 0.5rem (8px), elevated dialogue containers use 1rem (16px), and interactive elements like buttons, inputs, and semantic status chips use 0.5rem (8px). Avatar circles and micro-pips remain fully rounded (9999px).

## Components

### Buttons
- **Primary:** Solid `#6366F1` background, `#FFFFFF` text, subtle top inner-bevel (`box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2)`). Height: 40px (Desktop), 44px (Mobile).
- **Secondary:** `#FFFFFF` background, `#0F172A` text, 1px border of `#E2E8F0`. Hover triggers background change to `#F8FAFC` and border `#CBD5E1`.
- **Ghost:** Transparent background, `#475569` text. Hover triggers `#F1F5F9`.

### Chips & Semantic Status Badges
- **General Form:** Height: 24px, padding: 2px 8px, border radius: 6px. All badges include a 6px circular indicator dot.
- **Tugas Baru (New Tasks):** Background `rgba(99, 102, 241, 0.08)`, border `rgba(99, 102, 241, 0.2)`, text `#4F46E5`, dot `#6366F1`.
- **Sedang Dikerjakan (In Progress):** Background `rgba(245, 158, 11, 0.08)`, border `rgba(245, 158, 11, 0.2)`, text `#D97706`, dot `#F59E0B`.
- **Selesai (Completed):** Background `rgba(16, 185, 129, 0.08)`, border `rgba(16, 185, 129, 0.2)`, text `#059669`, dot `#10B981`.

### Task Lists & Data Grids
- Single-line rows with a fixed height of 48px.
- Left-aligned custom checkbox followed by task title, flexible tag container, assignee avatar stack (24px overlapping by 6px), due date, and semantic status chip.
- Interactive states: Hover transitions the background to `#F8FAFC` and exposes hidden quick-action triggers (Edit, Due Date, Delete).

### Kanban Cards
- Padding: 1rem (`space-md`), border: 1px solid `#E2E8F0`, background: `#FFFFFF`.
- Top row: Priority pill and contextual action menu.
- Middle: Task title in `label-md` (`font-weight: 500`) with an optional 2-line description truncate.
- Bottom: Linear progress bar (height: 4px, background: `#F1F5F9`, fill: `#6366F1`), subtask counter, and assignee avatars.

### Inputs & Checkboxes
- **Text Inputs:** Height 40px, 1px border of `#CBD5E1`, background `#FFFFFF`. Active focus state features an outline ring of `0 0 0 3px rgba(99, 102, 241, 0.15)` and border `#6366F1`.
- **Checkboxes:** 18x18px square with 4px border radius. In checked state, transitions to solid `#10B981` (Completed) or `#6366F1` with an interior white checkmark icon.

### Command Palette & Quick Search
- Floating modal centered at 20% viewport top margin. Width: 640px. 
- Translucent backdrop `rgba(15, 23, 42, 0.4)` with `backdrop-filter: blur(4px)`.
- Input field with keyboard shortcut hints (`⌘K`, `ESC`) rendered as miniature tactile keycaps.