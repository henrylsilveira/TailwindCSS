# TailwindCSS

### Why using it?

- [ ]  Minimal or no CSS
- [ ]  Mobile-first
- [ ]  Easy to apply
- [ ]  Has basic and beautiful design
- [ ]  Has nice developer experience

### What is this?

- [ ]  Utility-first CSS framework
- [ ]  Build your custom designs
- [ ]  Low-level (no pre-built components)
- [ ]  Freedom e highly customizable

### Why not Bootstrap or Material?

- [ ]  Customizable
- [ ]  No pre-built components
- [ ]  More and messy classes 😅

---

# Backgrounds, Colors & Shades

`bg-{color}-{shade}`

## Colors

- [ ]  black, white (no shadings)
- [ ]  gray, red, orange, yellow, green, teal, indigo, blue, purple, pink

## Shades

- [ ]  100 - 900

---

# Sizing and Numeric System

## REM

- [ ]  CSS ⇒ 1 rem = document base font (usually 16px)
    - [ ]  TailwindCSS ⇒ 1 rem = 4
    - [ ]  `m-4`
- [ ]  No decimals

### Width & Height

`{w|h}-{size}`

- [ ]  Sizes
    - [ ]  0, 1, 2, 3, 4, 5
    - [ ]  6, 8, 10, 12
    - [ ]  16, 20, 24
    - [ ]  32, 40, 48, 56, 64
    - [ ]  1/2, 1/{3, 4, 5, 6, 12}
    - [ ]  screen, full

---

# Spacing

`{p|m}-{size}`

- [ ]  0, 1, 2, 3, 4, 5, 6
- [ ]  8, 10, 12
- [ ]  16, 20, 24
- [ ]  32, 40, 48, 56, 64

`{p|m}-{(x|y|t|b|l|r)}-{size}`

- [ ]  x ⇒ horizontal
- [ ]  y ⇒ vertical
- [ ]  t ⇒ top, b ⇒ bottom, r ⇒ right, l ⇒ left

---

# Typography

### Family

`font-{family}`

- [ ]  sans | serif | mono

### Size

`text-{size}`

- [ ]  xs = .75rem = 12px
- [ ]  sm = .875rem = 14px
- [ ]  base = 1rem = 16px
- [ ]  lg = 1.125rem = 18px
- [ ]  xl = 1.25rem = 20px
- [ ]  2xl =1.5rem = 24px
- [ ]  3xl = 1.875rem = 30px
- [ ]  4xl = 2.25rem = 36px
- [ ]  5xl = 3rem = 48px
- [ ]  6xl = 4rem = 64px

### Align

`text-{align}`

- [ ]  left | center | right | justify

### Color

`text-{color}-{shade}`

- [ ]  Same as [colors & shades](https://www.notion.so/TailwindCSS-WS-38d86a53bc8241a086ff587eb951c722)

### Weight

`font-{weight}`

- [ ]  hairline = 100
- [ ]  thin = 200
- [ ]  light = 300
- [ ]  normal = 400
- [ ]  medium = 500
- [ ]  semibold = 600
- [ ]  bold = 700
- [ ]  extrabold = 800
- [ ]  black = 900

### Letter spacing

`tracking-{spacing}`

- [ ]  tighter = -0.05em
- [ ]  tight = -0.025em
- [ ]  normal = 0
- [ ]  wide = 0.025em
- [ ]  wider = 0.05em
- [ ]  widest = 0.1em

### Line-height

`leading-{spacing}`

- [ ]  none = 1
- [ ]  tight = 1.25
- [ ]  snug = 1.375
- [ ]  normal = 1.5
- [ ]  relaxed = 1.625
- [ ]  loose = 2

### Decorations

- [ ]  Text decorations
    - [ ]  underline
    - [ ]  no-underline
    - [ ]  line-through

### Transform

- [ ]  Text transform
    - [ ]  uppercase
    - [ ]  lowercase
    - [ ]  capitalize
    - [ ]  normal-case

### Italics

- [ ]  Italics
    - [ ]  italic
    - [ ]  not-italic

---

# Borders

### Thick

`border-{thickness}`

- [ ]  0 = 0px
- [ ]  [default] = 1px
- [ ]  2  = 2px
- [ ]  4 = 4px
- [ ]  8 = 8px

### Side

`border-{side}-{thickness}`

- [ ]  t | b | l | r

### Color

`border-{color}-{shade}`

- [ ]  Same as [colors & shades](https://www.notion.so/TailwindCSS-WS-38d86a53bc8241a086ff587eb951c722)

### Style

`border-{style}`

- [ ]  solid
- [ ]  dashed
- [ ]  dotted
- [ ]  double
- [ ]  none

### Radius

`rounded-{radius}`

- [ ]  sm = .125rem = 2px
- [ ]  [default] = .25rem = 4px
- [ ]  lg = .5rem = 8px
- [ ]  xl = .75rem = 12px
- [ ]  2xl = 1rem = 16px
- [ ]  3xl = 1.5rem = 24px
- [ ]  full = __ = 9999px
- [ ]  none = 0 = 0px

`rounded-{side}-{radius}`

- [ ]  t = top-left & top-right
- [ ]  r = top-right & bottom-right
- [ ]  b = bottom-left & bottom-right
- [ ]  l = top-left & bottom-left
- [ ]  tl = top-left
- [ ]  tr = top-right
- [ ]  br = bottom-right
- [ ]  bl = bottom-left

---

# Layouts

`container` *sets max-width using current breakpoint*

- [ ]  sm = max-width: 640px
- [ ]  md = max-width: 768px
- [ ]  lg = max-width: 1024px
- [ ]  xl = max-width: 1280px

## Displays

`{display}`

- [ ]  block
    - [ ]  inline
    - [ ]  inline-block
- [ ]  flex
    - [ ]  inline-flex
- [ ]  table
    - [ ]  table-row
    - [ ]  table-cell
- [ ]  hidden

## Position

`{position}`

- [ ]  static
- [ ]  fixed
- [ ]  absolute
- [ ]  relative
- [ ]  sticky

### Z-Index

`z-{order}`

- [ ]  0
- [ ]  10
- [ ]  20
- [ ]  30
- [ ]  40
- [ ]  50
- [ ]  auto

## Flexbox

`flex`

### Horizontal Direction (default)

`justify-{alignment}`

- [ ]  start
- [ ]  center
- [ ]  end
- [ ]  between
- [ ]  around

`items-{alignment}`

- [ ]  stretch
- [ ]  start
- [ ]  center
- [ ]  end
- [ ]  baseline

### Changing Directions

`flex-{direction}`

- [ ]  row
- [ ]  row-reverse
- [ ]  col
- [ ]  col-reverse

### Wrapping

`flex-{wrap}`

- [ ]  no-wrap
- [ ]  wrap
- [ ]  wrap-reverse

# Responsive

Tailwind is mobile first

You can add breaking points as you need

### Screen breaking points

`{screen}:{...classes}`

- [ ]  [default] *0px*
- [ ]  sm: *640px*
- [ ]  md: *768px*
- [ ]  lg: *1024px*
- [ ]  xl: *1280px*

**Not all classes are avaiables. Keep looking at documentation.**

bg, w, h, p, m, font-{family}, text-{size}, text-{align}, text-{color}-{shade}, font-{weight}, tracking-{spacing}, leading-{spacing}, {text-transform}, border-{color}-{shade}, border-{style}, border-{width}, rounded-{size}, {display}, flex, flex-{col|row}

---

# Effects

## Shadow

`shadow-{size}`

- [ ]  md
- [ ]  lg
- [ ]  xl
- [ ]  2xl
- [ ]  inner
- [ ]  outline
- [ ]  none

## Opacity

`opacity-{percent}`

- [ ]  100
- [ ]  75
- [ ]  50
- [ ]  25
- [ ]  0

---

# Utilities

## Hover

`hover:{...classes}`

- [ ]  classes
    - [ ]  bg-*, text-{color}-{shade}, font-{weight}, border-{color}-{shade}

## Focus

`focus:{...classes}`

- [ ]  classes
    - [ ]  same of hover

## Combinator

`md:hover:bg-*`

Combine responsive breakpoint with hover, or focus..

## Cursor

`cursor-{style}`

- [ ]  default
- [ ]  pointer
- [ ]  wait
- [ ]  text
- [ ]  move
- [ ]  not-allowed

## Select

`select-{style}` text selection

- [ ]  none
- [ ]  text
- [ ]  all
- [ ]  auto

## Accessibility

`sr-only` screen reader only

`not-sr-only`

## Visible

`visible`

`invisible`

---

# Transitions & Animations

## Transition

### Property

`transition-{property}`

- [ ]  none
- [ ]  all
- [ ]  colors
- [ ]  opacity
- [ ]  shadow
- [ ]  transform

### Duration

`duration-{time(ms)}`

- [ ]  75
- [ ]  100
- [ ]  150
- [ ]  200
- [ ]  300
- [ ]  500
- [ ]  700
- [ ]  1000

### Timing

`ease-{timing}`

- [ ]  linear
- [ ]  in
- [ ]  out
- [ ]  in-out

### Delay

`delay-{time(ms)}`

- [ ]  same as duration

## Animation

`animate-{name}`

- [ ]  none
- [ ]  spin
- [ ]  ping
- [ ]  pulse
- [ ]  bounce

---

# Next steps

- [ ]  Add TailwindCSS to React or NextJS (medium)
- [ ]  Customize (extend) TailwindCSS (medium)
- [ ]  Reuse of classes (medium)
- [ ]  Remove unused css (medium)
- [ ]  Study grid utilities (easy)
