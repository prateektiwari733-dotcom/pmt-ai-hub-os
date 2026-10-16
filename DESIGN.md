---
name: Obsidian Telemetry
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393d'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#292a2d'
  surface-container-highest: '#343538'
  on-surface: '#e3e2e6'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#fabc4d'
  on-secondary: '#432c00'
  secondary-container: '#bd8718'
  on-secondary-container: '#3a2600'
  tertiary: '#ffc174'
  on-tertiary: '#472a00'
  tertiary-container: '#f59e0b'
  on-tertiary-container: '#613b00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#ffdead'
  secondary-fixed-dim: '#fabc4d'
  on-secondary-fixed: '#281900'
  on-secondary-fixed-variant: '#604100'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
  telemetry-data:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The visual identity embodies an enterprise-grade command center: disciplined, sovereign, and deeply technical. It pairs the ruthless clarity of mission-critical aerospace consoles with the understated luxury of deep obsidian materials. The system projects absolute control, low latency, and uncompromising authority.

Its design philosophy merges **Minimalist Precision** with **Atmospheric Layering**:
- **Monolithic Substrates:** Deep graphite and obsidian tiers construct an unyielding foundation designed to minimize eye fatigue during extended operational cycles.
- **Luminous Telemetry Highlights:** High-frequency cyan signals slice through dark layers to anchor attention instantly to live state changes, automation queues, and critical operational vectors.
- **Controlled Density:** Information density is elevated, preferring tight, compact structures and exact data relationships over purely decorative whitespace.

## Colors

The palette establishes an authoritarian hierarchy between deep inert backdrops and energetic optical signals.

### Surface Architecture
- **Canvas Base (`#08090C`):** Absolute ground plane. The void against which telemetry operates.
- **Surface Layer 1 (`#0D131F`):** Structural panels, side docks, and contextual utility zones.
- **Surface Layer 2 (`#12141A`):** Interactive cards, telemetry modules, and analytical containers.
- **Surface Highlight (`#1C2230`):** Active selections, elevated hover states, and key control surfaces.

### Telemetry & Signal Accents
- **Primary Cyan (`#38BDF8`):** Live telemetry feeds, active connection links, focal action controls, and high-priority metrics.
- **Secondary Metallic Amber (`#E5A93C`):** Compute engine states, authenticated privileges, model weights, and primary warnings.
- **Tertiary Amber (`#F59E0B`):** System friction, automation throttles, and degraded node latency alerts.
- **Borders & Dividers:** `rgba(255, 255, 255, 0.08)` to `rgba(56, 189, 248, 0.2)` on active focus.

## Typography

The typography relies on Inter configured with systematic, utilitarian discipline. 

- **Numerical Precision:** Numeric presentation in all metrics and telemetry fields must enable tabular lining figures (`font-variant-numeric: tabular-nums`) to prevent shifting column widths during live stream updates.
- **Uppercase Labels:** Command labels, operational indicators, and telemetry headers use uppercase tracking (`0.06em`) at reduced scale (`11px`) to establish immediate contextual indexing.
- **Hierarchy:** Body copy remains strictly neutral (`#94A3B8`) to allow high-contrast headlines (`#F8FAFC`) and glowing telemetry outputs to dominate focal paths.

## Layout & Spacing

The layout model is anchored by an operational 12-column fluid grid engineered for responsive dashboards, dynamic analytical views, and multi-dock splitters.

- **Desktop (1440px+):** 12-column grid with `1.5rem` gutters and `2rem` outer edge margins. Docks and command decks pin to viewport edges while operational canvases consume all inner fluid coordinates.
- **Tablet (768px - 1439px):** 8-column layout with `1rem` gutters and `1.5rem` margins. Ancillary inspector panels collapse into sliding bottom sheets or overlay drawers.
- **Mobile (<768px):** 4-column layout with `0.5rem` gutters and `1rem` margin margins. High-priority cards stack vertically; tab switches gate analytical panels.
- **Spacing Rhythm:** Internal layout and component padding adhere to a rigid 4px spatial baseline. Micro-gaps (`space-xs`, `space-sm`) govern metric rows, while structural container buffers use `space-md` and `space-lg`.

## Elevation & Depth

Visual hierarchy uses tonal surface tiering combined with glassmorphic edge definition rather than traditional soft drop shadows.

- **Level 0 (Command Baseline):** Solid `#08090C`. Void of lighting or blur effects.
- **Level 1 (Dock & Structural Rails):** `#0D131F` with 0.85 opacity, backed by a `backdrop-filter: blur(12px)`. Outlined by a continuous 1px edge of `rgba(255, 255, 255, 0.06)`.
- **Level 2 (Telemetry Panels & Cards):** `#12141A` with subtle linear sheen `linear-gradient(180deg, rgba(255,255,255,0.03) 0%, rgba(255,255,255,0) 100%)`. Border: 1px solid `rgba(255, 255, 255, 0.08)`.
- **Level 3 (Modals, Overlays, Floating Docks):** `#161922` elevated via a dual-ring system: 1px outer border `rgba(56, 189, 248, 0.25)` and a directional glow `0 0 24px -4px rgba(56, 189, 248, 0.15)`.
- **Glow Signatures:** Critical alerts project localized ambient luminescence matching the severity color (Cyan for active tracking, Amber for load thresholds).

## Shapes

The design system enforces a controlled, technical profile utilizing roundedness scale `1` (Soft).

- **Standard Elements (Buttons, Inputs, Metric Badges):** `0.25rem` (4px). Provides a precise, instrumentation-panel profile that preserves maximum internal data room without harsh edge intersections.
- **Containers & Panels (`rounded-lg`):** `0.5rem` (8px). Keeps high-density command modules disciplined and strictly aligned.
- **Overlays & Dialogs (`rounded-xl`):** `0.75rem` (12px). Distinct separation for transient floating surfaces.
- **Pill Exceptions:** Restricted solely to micro status indicators and real-time live execution pings (`rounded-full`).

## Components

### Buttons & Trigger Controls
- **Primary Action:** Solid background with cyan gradient fill `linear-gradient(180deg, #38BDF8 0%, #0284C7 100%)`, dark text `#08090C`, font weight `600`, 4px radius. Box shadow: `0 0 12px rgba(56, 189, 248, 0.35)`.
- **Secondary (Technical):** Dark graphite fill `#12141A`, 1px border `rgba(255, 255, 255, 0.12)`, text `#F8FAFC`. On hover, the border shifts to `rgba(56, 189, 248, 0.5)` with an ambient background tint of `rgba(56, 189, 248, 0.05)`.
- **Ghost Utility:** Borderless with slate text `#94A3B8`. Hover introduces `#1C2230` fill and `#38BDF8` text shift.

### Chips & Telemetry Badges
- **Height & Spacing:** Compact 20px–24px height, horizontal padding `8px`, uppercase typography `label-sm`.
- **Active Telemetry State:** Background `rgba(56, 189, 248, 0.12)`, border `1px solid rgba(56, 189, 248, 0.3)`, text `#38BDF8`. Features an integrated 6px pulsing dot.
- **Warning Badge:** Background `rgba(229, 169, 60, 0.12)`, border `1px solid rgba(229, 169, 60, 0.3)`, text `#E5A93C`.

### Form Fields & Technical Inputs
- **Base Style:** Background `#0D131F`, 1px border `rgba(255, 255, 255, 0.1)`, 4px corner radius, text `#F8FAFC`, placeholder `#475569`.
- **Focus State:** 1px border `#38BDF8`, subtle glow `0 0 0 2px rgba(56, 189, 248, 0.2)`. Transition: `border-color 150ms ease`.

### Checkboxes & Segmented Controls
- **Checkboxes:** 16px square, 3px radius, background `#0D131F`, border `1px solid rgba(255, 255, 255, 0.2)`. Checked state displays `#38BDF8` fill with dark checkmark icon.
- **Segmented Switchers:** Embedded `#08090C` track with 1px border `rgba(255, 255, 255, 0.05)`. Active segment slides with `#1C2230` fill and sharp cyan accent underlines.

### Panels & Command Cards
- **Construction:** Structured with `#12141A` substrate, 1px frosted top/side borders (`rgba(255, 255, 255, 0.08)`), and 8px corner radii.
- **Telemetry Card Header:** Strict 40px height bar partitioned by a 1px baseline rule (`rgba(255, 255, 255, 0.06)`), displaying title, latency ticker, and expansion menu.

### Telemetry Counters & Data Nodes
- **Readout Modules:** Monolithic digits rendered in tabular format, paired with micro-labels placed directly above metrics. Integrated micro sparklines use cyan and amber stroke widths of 1.5px with transparent area fills.