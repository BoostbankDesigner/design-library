# Button

A **Button** is a primary interactive component that allows users to trigger an action. It supports three sizes to accommodate different layouts while maintaining consistent styling and accessibility.

---

## Preview

| Small | Medium | Large |
|-------|--------|-------|
| 40px Height | 48px Height | 56px Height |

---

## Variants

### Filled Button

The default button style used for primary actions.

**Usage**

- Submit forms
- Confirm actions
- Continue to the next step
- Primary call-to-action (CTA)

---

## Sizes

| Size | Height | Horizontal Padding | Corner Radius |
|------|--------|--------------------|---------------|
| Small | 40px | 16px | Full (999px) |
| Medium | 48px | 20px | Full (999px) |
| Large | 56px | 24px | Full (999px) |

> Width is determined by the button label.

---

## Anatomy

```
┌──────────────────────────────┐
│        Button Label          │
└──────────────────────────────┘
```

| Element | Description |
|---------|-------------|
| Container | Filled background |
| Label | Action text |
| Padding | Horizontal spacing surrounding the label |
| Border Radius | Fully rounded pill shape |

---

## Specifications

### Small

| Property | Value |
|----------|-------|
| Height | 40px |
| Horizontal Padding | 16px |
| Border Radius | 999px |
| Typography | Button / Small |

---

### Medium

| Property | Value |
|----------|-------|
| Height | 48px |
| Horizontal Padding | 20px |
| Border Radius | 999px |
| Typography | Button / Medium |

---

### Large

| Property | Value |
|----------|-------|
| Height | 56px |
| Horizontal Padding | 24px |
| Border Radius | 999px |
| Typography | Button / Large |

---

## Content Guidelines

### Recommended

Use concise, action-oriented labels.

Examples:

- Continue
- Save
- Confirm
- Next
- Done
- Sign In

### Avoid

- Click Here
- Press This Button
- Submit Your Information Now

---

## Accessibility

### Minimum Touch Target

```
48 × 48 px
```

For mobile interfaces, ensure the touch target is at least **48 × 48 px**, even if the visible button is smaller.

### Text Contrast

Button text should meet a minimum contrast ratio of **4.5:1** against its background.

---

## Design Tokens

### Background

| Token |
|--------|
| `button.primary.background` |

### Text

| Token |
|--------|
| `button.primary.label` |

### Radius

| Token |
|--------|
| `button.radius.full` |

### Spacing

| Token |
|--------|
| `spacing.md` |
| `spacing.lg` |

### Typography

| Token |
|--------|
| `typography.button.small` |
| `typography.button.medium` |
| `typography.button.large` |

---

## Figma Component Structure

```
Button
└── Filled
    ├── Small
    ├── Medium
    └── Large
```

### Component Properties

| Property | Values |
|----------|--------|
| Size | Small · Medium · Large |
| State | Enabled · Hover · Pressed · Disabled · Focus |
| Theme | Light · Dark |

---

## Usage Guidelines

### Do

- Use one primary button per section.
- Keep labels short and meaningful.
- Use sentence case or title case consistently.
- Maintain consistent sizing within the same interface.

### Don't

- Use multiple primary buttons together.
- Write long sentences inside buttons.
- Use vague labels such as "Click Here."
- Reduce the touch target below accessibility guidelines.

---

## Changelog

### v1.0.0

Initial release.

**Included**

- Filled Button
- Small, Medium, and Large sizes
- Design Token support
- Light & Dark theme compatibility
