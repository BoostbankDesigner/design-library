# 🚀 Boost Bank Design System

A centralized Design System for building consistent, accessible, and scalable digital banking experiences across Boost Bank products.

---

## Overview

The Design System provides reusable UI components, design tokens, icons, and documentation that help designers and developers build products faster while maintaining consistency.

### Goals

* 🎨 Consistent user experience
* ⚡ Faster product development
* ♿ Accessible components
* 📱 Responsive across devices
* 🔄 Single source of truth
* 🚀 Easy integration with React applications

---

## Architecture

```text
Figma
   │
   ▼
Design Tokens
   │
   ▼
Style Dictionary
   │
   ▼
NPM Package
   │
   ▼
Storybook
   │
   ▼
Applications
```

---

## Features

* Design Tokens
* Color System
* Typography
* Spacing Scale
* Icon Library
* Components
* Accessibility Guidelines
* Storybook Documentation
* Versioning
* npm Distribution

---

## Installation

```bash
npm install @boostbank/design-system
```

or

```bash
yarn add @boostbank/design-system
```

---

## Usage

```tsx
import { Button } from "@boostbank/design-system";

export default function App() {
  return (
    <Button variant="primary">
      Continue
    </Button>
  );
}
```

---

## Documentation

Run Storybook locally

```bash
npm run storybook
```

Build Storybook

```bash
npm run build-storybook
```

---

## Folder Structure

```text
design-system/
│
├── .storybook/
├── src/
│   ├── components/
│   ├── tokens/
│   ├── icons/
│   ├── hooks/
│   ├── utilities/
│   └── index.ts
│
├── stories/
├── public/
├── package.json
└── README.md
```

---

## Component Categories

### Foundations

* Colors
* Typography
* Spacing
* Grid
* Elevation
* Radius
* Motion

### Components

* Button
* Text Field
* Input
* Checkbox
* Radio
* Switch
* Badge
* Chip
* Card
* Avatar
* Modal
* Bottom Sheet
* Snackbar
* Tabs
* Navigation Bar

### Patterns

* Login
* Dashboard
* Transaction List
* Empty State
* Error State
* Loading State

---

## Design Tokens

Example

```json
{
  "color": {
    "primary": {
      "500": "#EA0029"
    }
  }
}
```

Usage

```tsx
<Button backgroundColor="var(--color-primary-500)">
```

---

## Accessibility

Our components follow accessibility best practices.

* WCAG 2.2
* Keyboard navigation
* Screen reader support
* Color contrast compliance
* Focus indicators
* Minimum touch target of 44×44 px

---

## Versioning

We follow Semantic Versioning.

```text
Major.Minor.Patch

1.0.0
│ │ └── Bug Fix
│ └──── New Features
└────── Breaking Changes
```

---

## Development

Install dependencies

```bash
npm install
```

Start Storybook

```bash
npm run storybook
```

Build library

```bash
npm run build
```

Run tests

```bash
npm test
```

---

## Contributing

1. Create a feature branch.
2. Develop your component.
3. Add Storybook documentation.
4. Include tests if applicable.
5. Submit a Pull Request.

---

## Release Workflow

```text
Design
    │
    ▼
Figma Component
    │
    ▼
Design Token Update
    │
    ▼
Library Development
    │
    ▼
Pull Request
    │
    ▼
Review
    │
    ▼
Merge
    │
    ▼
Publish npm Package
```

---

## License

Internal Use Only

© Boost Bank Design Team
