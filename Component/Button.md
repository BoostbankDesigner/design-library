# Button

The Button component is the primary interactive element used to trigger actions throughout the product. It supports multiple sizes, icon-only buttons, and configurable properties for different use cases while maintaining a consistent visual language across the Boost Design System.

---

# Component

**Component Name**
`Button`

**Supported Platforms**
- Mobile
- Responsive Web (optional)

---

# Variants

## Size

- XS
- S
- M

Each size automatically adjusts:
- Height
- Horizontal padding
- Corner radius
- Typography
- Icon size

---

## Type

### Text Button

A standard button containing only a text label.

Example:
```
Button Text
```

---

### Icon Button

A circular button containing only an icon.

Example:
```
⊞
```

---

# Properties

| Property | Type | Values | Description |
|----------|------|--------|-------------|
| Active | Boolean | True / False | Controls the enabled or disabled state. |
| With Stroke | Boolean | True / False | Displays an outline instead of a filled background. |
| Size | Variant | XS / S / M | Changes button dimensions. |
| Type | Variant | Text / Icon | Switches between text button and icon button. |
| Button Text | Text | Custom | Button label. Hidden when Type = Icon. |
| Icon | Instance Swap | Any icon | Select icon from the Design System icon library. |

---

# States

## Active

Primary action.

- Filled background
- White content
- Interactive

---

## Disabled

Unavailable action.

- Reduced opacity
- No interaction

---

## Outline

Displayed when **With Stroke = True**

- Transparent background
- Primary stroke
- Primary text/icon

---

# Design Tokens

## Background

| State | Token |
|--------|-------|
| Primary | `semantic.primary.boost-red` |
| Disabled | `semantic.primary.boost-fade-red` |

---

## Content

| Element | Token |
|---------|-------|
| Text | `semantic.text.inverse` |
| Icon | `semantic.icon.inverse` |

---

## Border

| State | Token |
|--------|-------|
| Outline | `semantic.border.primary` |

---

# Usage

Use Buttons to initiate user actions.

### Use Text Button when

- Primary CTA
- Form submission
- Navigation
- Confirmation actions

### Use Icon Button when

- Toolbar actions
- Utility actions
- Compact layouts

---

# Best Practices

✅ Keep labels concise (1–3 words)

✅ Use one primary button per action group

✅ Use consistent sizing within the same screen

✅ Prefer icons that exist in the Design System library

---

# Do

- Use design tokens only.
- Keep text centered.
- Use the appropriate size for the available space.
- Use Instance Swap for icons.

---

# Don't

- Override colors manually.
- Stretch buttons disproportionately.
- Use multiple primary actions with equal emphasis.
- Replace icons with unsupported custom assets.

---

# Component Properties

```
Active
With Stroke
Size
Type
Button Text
Icon
```

---

# Version

Component: Button

Version: 1.0.1
