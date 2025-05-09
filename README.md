# VanillaGrid CSS Framework

A modern, lightweight, and flexible CSS framework. Enables you to create responsive designs with Flexbox and Grid systems.

## Features

- 🎯 Modern Flexbox and Grid systems
- 📱 Full responsive design support
- 🎨 Customizable variables
- ⚡ Lightweight and performant
- 🛠 Easy to use
- 🎯 Comprehensive utility classes

## Installation

```bash
npm install vanillagrid
```

or via CDN:

```html
<link rel="stylesheet" href="https://unpkg.com/vanillagrid@2.0.0/dist/vanillagrid.css">
```

## Usage

### Grid System

```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">
      <!-- Content -->
    </div>
    <div class="col-12 col-md-6 col-lg-4">
      <!-- Content -->
    </div>
    <div class="col-12 col-md-12 col-lg-4">
      <!-- Content -->
    </div>
  </div>
</div>
```

### Flex Helpers

```html
<div class="d-flex">
  <div class="flex-grow-1">Flexible growing element</div>
  <div class="flex-shrink-0">Fixed size element</div>
</div>
```

### Utility Classes

#### Spacing
```html
<div class="m-3">Margin all sides</div>
<div class="mt-2">Margin top</div>
<div class="p-4">Padding all sides</div>
<div class="px-3">Padding left and right</div>
```

#### Display
```html
<div class="d-none">Hidden element</div>
<div class="d-block">Block element</div>
<div class="d-flex">Flex container</div>
<div class="d-grid">Grid container</div>
```

#### Text
```html
<div class="text-center">Centered text</div>
<div class="text-uppercase">Uppercase text</div>
<div class="font-weight-bold">Bold text</div>
```

#### Position
```html
<div class="position-relative">Relative positioning</div>
<div class="position-absolute">Absolute positioning</div>
<div class="position-fixed">Fixed positioning</div>
```

#### Borders
```html
<div class="border">Border all sides</div>
<div class="border-top">Border top only</div>
<div class="rounded">Rounded corners</div>
```

#### Visibility & Overflow
```html
<div class="visible">Visible element</div>
<div class="invisible">Hidden element</div>
<div class="overflow-auto">Scrollable content</div>
```

#### Width & Height
```html
<div class="w-100">Full width</div>
<div class="h-100">Full height</div>
```

#### Z-index
```html
<div class="z-1">Z-index level 1</div>
<div class="z-2">Z-index level 2</div>
```

## Responsive Breakpoints

- xs: 0px and above
- sm: 576px and above
- md: 768px and above
- lg: 992px and above
- xl: 1200px and above
