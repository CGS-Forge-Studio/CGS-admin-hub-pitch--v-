---
name: "Looma Org"
description: "A unified, tactile light-first design system with warm stone surfaces, charcoal pill containers, lavender highlights, and coral urgent accents for organization mobile and web apps."
---

## Overview

Looma Org is a cross-platform design system built for an organization's suite of mobile and web applications—spanning team scheduling, project hubs, operational dashboards, and internal tools. It pairs warm, approachable neutral surfaces with high-contrast charcoal containers, crisp Plus Jakarta Sans typography, and expressive lavender and coral accents. The interface feels calm, tactile, and immediately scannable: rounded cards group related work without heavy borders, and dark pill modules anchor primary navigation and active states.

## Colors

The palette is anchored by four signature brand colors—**Lavender** (`#B48DE6`), **Coral Red** (`#F24646`), **Charcoal Ink** (`#232323`), and **Warm Stone** (`#EEEDEA`)—supported by contrast-compliant Material semantic roles for light and dark modes.

- **Light-First Ground:** Pages sit on a warm off-white canvas (`light-surface: #FAF9F6`), with Warm Stone (`#EEEDEA`) cards and pure white (`#FFFFFF`) elevated pills and modal items.
- **High-Contrast Anchors:** Charcoal Ink (`#232323`) is used for persistent navigation rails, date-strip containers, and primary pill buttons to create unmistakable visual rhythm.
- **Lavender & Coral Accents:** Lavender (`#B48DE6`) highlights active selections, featured sprint/project cards, and primary interactive states. Coral Red (`#F24646`) is reserved for urgent or currently-active time blocks and critical alerts.

```yaml
colors:
  brand-lavender: "#B48DE6"
  on-brand-lavender: "#232323"
  brand-coral: "#F24646"
  on-brand-coral: "#1F1F1F"
  brand-charcoal: "#232323"
  on-brand-charcoal: "#FFFFFF"
  brand-stone: "#EEEDEA"
  on-brand-stone: "#232323"
  success: "#1F7A4C"
  on-success: "#FFFFFF"
  warning: "#B25E09"
  on-warning: "#FFFFFF"
  light:
    primary: "#714CA0"
    on-primary: "#FFFFFF"
    primary-container: "#B48DE6"
    on-primary-container: "#232323"
    secondary: "#232323"
    on-secondary: "#FFFFFF"
    secondary-container: "#E2DFDE"
    on-secondary-container: "#232323"
    tertiary: "#BA1A24"
    on-tertiary: "#FFFFFF"
    tertiary-container: "#F24646"
    on-tertiary-container: "#1F1F1F"
    error: "#BA1A1A"
    on-error: "#FFFFFF"
    error-container: "#FFDAD6"
    on-error-container: "#93000A"
    background: "#FAF9F6"
    on-background: "#1B1C1A"
    surface: "#FAF9F6"
    surface-dim: "#DBDAD7"
    surface-bright: "#FFFFFF"
    surface-container-lowest: "#FFFFFF"
    surface-container-low: "#F5F3F0"
    surface-container: "#EEEDEA"
    surface-container-high: "#E9E8E5"
    surface-container-highest: "#E3E2DF"
    on-surface: "#1B1C1A"
    surface-variant: "#E9DFEE"
    on-surface-variant: "#4A4450"
    outline: "#7C7481"
    outline-variant: "#CDC3D2"
    inverse-surface: "#232323"
    inverse-on-surface: "#FAF9F6"
    inverse-primary: "#D9B9FF"
  dark:
    primary: "#D9B9FF"
    on-primary: "#401A6E"
    primary-container: "#B48DE6"
    on-primary-container: "#232323"
    secondary: "#C8C6C5"
    on-secondary: "#232323"
    secondary-container: "#474746"
    on-secondary-container: "#F3F0EF"
    tertiary: "#FFB3AE"
    on-tertiary: "#68000B"
    tertiary-container: "#F24646"
    on-tertiary-container: "#1F1F1F"
    error: "#FFB4AB"
    on-error: "#690005"
    error-container: "#93000A"
    on-error-container: "#FFDAD6"
    background: "#121412"
    on-background: "#E3E2DF"
    surface: "#121412"
    surface-dim: "#121412"
    surface-bright: "#383938"
    surface-container-lowest: "#0D0F0D"
    surface-container-low: "#1B1C1A"
    surface-container: "#1F201E"
    surface-container-high: "#292A29"
    surface-container-highest: "#343533"
    on-surface: "#E3E2DF"
    surface-variant: "#4A4450"
    on-surface-variant: "#CDC3D2"
    outline: "#968E9B"
    outline-variant: "#4A4450"
    inverse-surface: "#E3E2DF"
    inverse-on-surface: "#232323"
    inverse-primary: "#714CA0"
```

## Typography

**Plus Jakarta Sans** is the sole UI typeface across headlines, body copy, and controls, paired with **JetBrains Mono** for technical IDs, timestamps, and tabular metrics. Tight negative tracking on display and headline sizes gives titles a confident, editorial presence while generous line heights keep dense schedules readable.

```yaml
typography:
  display-lg:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 40px
    fontWeight: 600
    lineHeight: 46px
    letterSpacing: -0.75px
  display-lg-mobile:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 32px
    fontWeight: 600
    lineHeight: 38px
    letterSpacing: -0.5px
  headline-lg:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 42px
    letterSpacing: -0.5px
  headline-lg-mobile:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 34px
    letterSpacing: -0.4px
  headline-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 30px
    letterSpacing: -0.25px
  headline-sm:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 26px
    letterSpacing: -0.2px
  title-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 22px
    letterSpacing: -0.1px
  body-lg:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0px
  body-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0px
  body-sm:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 18px
    letterSpacing: 0px
  label-lg:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0px
  label-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0.1px
  label-sm:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 11px
    fontWeight: 500
    lineHeight: 14px
    letterSpacing: 0.2px
  mono-sm:
    fontFamily: "JetBrains Mono"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 16px
    letterSpacing: 0px
```

## Layout & Spacing

The system uses a strict **4px/8px spatial grid** across both mobile (`390px` fluid single-column) and web (`1280px` persistent charcoal sidebar + multi-column fluid workspace). Mobile screens use `20px` (`page-margin-mobile`) horizontal padding with `16px` vertical gaps between cards. Web screens pair a compact `240px` navigation rail with a `32px` (`page-margin-web`) content gutter and 12-column CSS Grid tracks.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 12px
  gutter-lg: 16px
  gutter-xl: 24px
  gutter-2xl: 32px
  section: 40px
  page-margin-mobile: 20px
  page-margin-web: 32px
```

## Elevation & Depth

Hierarchy relies on **tonal surface stepping** and **high-contrast color blocks** rather than heavy drop shadows. Primary cards sit flat on `#FAF9F6` using `#EEEDEA` (Warm Stone) or `#B48DE6` (Lavender), while nested time pills and action icons step up to `#FFFFFF` for crisp separation. Interactive sheets and floating overlays use subtle, diffused ambient shadows (`0 12px 32px rgba(35, 35, 35, 0.08)`) with zero backdrop blur.

## Shapes

Generous, friendly curvature defines the brand. Cards and bottom sheets use large `24px` (`xl`) to `32px` (`2xl`) radii, while buttons, time badges, avatar clusters, and active day selectors use full pill (`9999px`) geometry. Nested elements step their radius down so inner pills sit naturally inside padded card containers.

```yaml
rounded:
  sm: 8px
  DEFAULT: 12px
  md: 16px
  lg: 20px
  xl: 24px
  2xl: 32px
  full: 9999px
```

## Motion & Micro-interaction

Motion is crisp, tactile, and spring-inspired without overshoot. Button presses and pill selections respond in `120ms`, while bottom sheets and detail drawers enter with a smooth decelerating curve over `260ms`. Honour `prefers-reduced-motion` and animate only `transform`, `opacity`, and `color`.

```yaml
motion:
  state-change:
    duration: 120ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 260ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
  surface-exit:
    duration: 160ms
    delay: 0ms
    timingFunction: cubic-bezier(0.3, 0, 1, 1)
```

## Voice & Content Strategy

- **Tone:** Direct, calm, and human. Write like a well-organized teammate—clear and free of corporate buzzwords.
- **Capitalisation:** Sentence case for all headings, card titles, buttons, and navigation items (e.g., "Sprint review", "New project", "View schedule").
- **Label Grammar:** Action buttons use concise verb-noun phrases ("Create project", "Join call"). Time and metric pills use `tabular-nums` (`12:00 PM`, `5:00–6:30 PM`, `14 tasks`).
- **Empty & Error States:** Keep empty states encouraging with one primary next action; errors state what happened and offer a direct retry.

## Components

Component implementations live as individual HTML sticker sheet files in
`components/`. Each file contains the canonical, styled HTML components with
`<!-- COMPONENT: name -->` comment markers. Read each file before use.

- **Avatar** → `@components/avatar.html` — `avatar-image`, `avatar-editable`
- **Button** → `@components/button.html` — `button-primary`, `button-icon`, `button-with-icon`
- **Card** → `@components/card.html` — `card-elevated`, `card-action`, `card-interactive`, `card-interactive-2`
- **Chip** → `@components/chip.html` — `chip-action`, `chip-input`, `chip-with-icon`

## Do's and Don'ts

- **Do** use `#FAF9F6` (`bg-light-surface`) as the page ground and `#EEEDEA` (`bg-brand-stone`) or `#B48DE6` (`bg-brand-lavender`) for primary cards.
- **Do** use `#232323` (`bg-brand-charcoal`) with `#FFFFFF` (`text-on-brand-charcoal`) for high-contrast pill strips, navigation bars, and primary CTAs.
- **Do** wrap all visible text in `data-design-text-token` and preserve `tabular-nums` on timestamps and counts.
- **Don't** use `backdrop-blur`, glassmorphism, neon gradients, or `border-l-4` accent stripes.
- **Don't** use arbitrary hex codes or generic Tailwind palette classes (`bg-purple-400`, `text-gray-800`) in component or screen HTML.
