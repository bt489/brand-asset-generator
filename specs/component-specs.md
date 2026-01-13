# ShipSignal Component Specifications

This document outlines the visual specifications for common UI components in the ShipSignal design system.

---

## Buttons

### Primary Button
The main call-to-action button.

```css
.btn-primary {
  background: linear-gradient(90deg, #4f46e5 0%, #6366f1 100%);
  color: #ffffff;
  font-family: 'Outfit', sans-serif;
  font-weight: 600;
  font-size: 16px;
  padding: 12px 24px;
  border-radius: 9999px;
  border: none;
  cursor: pointer;
  transition: all 0.2s ease;
  box-shadow: 0 4px 14px 0 rgba(99, 102, 241, 0.25);
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px 0 rgba(99, 102, 241, 0.35);
}

.btn-primary:active {
  transform: translateY(0);
}
```

### Secondary Button
For secondary actions.

```css
.btn-secondary {
  background: transparent;
  color: #6366f1;
  font-family: 'Outfit', sans-serif;
  font-weight: 600;
  font-size: 16px;
  padding: 12px 24px;
  border-radius: 9999px;
  border: 2px solid #6366f1;
  cursor: pointer;
  transition: all 0.2s ease;
}

.btn-secondary:hover {
  background: #eef2ff;
}
```

### Ghost Button
For tertiary actions.

```css
.btn-ghost {
  background: transparent;
  color: #6b7280;
  font-family: 'Outfit', sans-serif;
  font-weight: 500;
  font-size: 14px;
  padding: 10px 20px;
  border-radius: 8px;
  border: none;
  cursor: pointer;
  transition: all 0.2s ease;
}

.btn-ghost:hover {
  background: #f3f4f6;
  color: #374151;
}
```

### Button Sizes
| Size | Padding | Font Size | Min Height |
|------|---------|-----------|------------|
| Small | 8px 16px | 14px | 32px |
| Medium | 12px 24px | 16px | 44px |
| Large | 16px 32px | 18px | 56px |

---

## Cards

### Basic Card
```css
.card {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1),
              0 2px 4px -2px rgba(0, 0, 0, 0.1);
}
```

### Elevated Card
```css
.card-elevated {
  background: #ffffff;
  border: none;
  border-radius: 16px;
  padding: 24px;
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
              0 4px 6px -4px rgba(0, 0, 0, 0.1);
}
```

### Brand Card (Highlighted)
```css
.card-brand {
  background: linear-gradient(135deg, #eef2ff 0%, #e0e7ff 100%);
  border: 1px solid #c7d2fe;
  border-radius: 12px;
  padding: 24px;
}
```

### Interactive Card
```css
.card-interactive {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 24px;
  cursor: pointer;
  transition: all 0.2s ease;
}

.card-interactive:hover {
  border-color: #6366f1;
  box-shadow: 0 4px 14px 0 rgba(99, 102, 241, 0.15);
  transform: translateY(-2px);
}
```

---

## Form Elements

### Text Input
```css
.input {
  width: 100%;
  height: 48px;
  padding: 12px 16px;
  font-family: 'Outfit', sans-serif;
  font-size: 16px;
  color: #111827;
  background: #ffffff;
  border: 1px solid #d1d5db;
  border-radius: 8px;
  transition: all 0.2s ease;
}

.input:focus {
  outline: none;
  border-color: #6366f1;
  box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
}

.input::placeholder {
  color: #9ca3af;
}

.input:disabled {
  background: #f3f4f6;
  color: #9ca3af;
  cursor: not-allowed;
}
```

### Input with Error
```css
.input-error {
  border-color: #ef4444;
}

.input-error:focus {
  border-color: #ef4444;
  box-shadow: 0 0 0 3px rgba(239, 68, 68, 0.1);
}

.error-message {
  font-size: 14px;
  color: #ef4444;
  margin-top: 4px;
}
```

### Label
```css
.label {
  display: block;
  font-family: 'Outfit', sans-serif;
  font-size: 14px;
  font-weight: 500;
  color: #374151;
  margin-bottom: 6px;
}
```

### Textarea
```css
.textarea {
  width: 100%;
  min-height: 120px;
  padding: 12px 16px;
  font-family: 'Outfit', sans-serif;
  font-size: 16px;
  color: #111827;
  background: #ffffff;
  border: 1px solid #d1d5db;
  border-radius: 8px;
  resize: vertical;
  transition: all 0.2s ease;
}

.textarea:focus {
  outline: none;
  border-color: #6366f1;
  box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
}
```

---

## Badges

### Default Badge
```css
.badge {
  display: inline-flex;
  align-items: center;
  padding: 4px 12px;
  font-family: 'Outfit', sans-serif;
  font-size: 12px;
  font-weight: 500;
  border-radius: 9999px;
}

.badge-primary {
  background: #e0e7ff;
  color: #4f46e5;
}

.badge-success {
  background: #d1fae5;
  color: #059669;
}

.badge-warning {
  background: #fef3c7;
  color: #d97706;
}

.badge-error {
  background: #fee2e2;
  color: #dc2626;
}

.badge-neutral {
  background: #f3f4f6;
  color: #4b5563;
}
```

---

## Alerts

### Alert Box
```css
.alert {
  display: flex;
  align-items: flex-start;
  padding: 16px;
  border-radius: 8px;
  font-family: 'Outfit', sans-serif;
  font-size: 14px;
  line-height: 1.5;
}

.alert-info {
  background: #eef2ff;
  border: 1px solid #c7d2fe;
  color: #4338ca;
}

.alert-success {
  background: #ecfdf5;
  border: 1px solid #a7f3d0;
  color: #047857;
}

.alert-warning {
  background: #fffbeb;
  border: 1px solid #fde68a;
  color: #b45309;
}

.alert-error {
  background: #fef2f2;
  border: 1px solid #fecaca;
  color: #b91c1c;
}
```

---

## Navigation

### Nav Link
```css
.nav-link {
  font-family: 'Outfit', sans-serif;
  font-size: 16px;
  font-weight: 500;
  color: #6b7280;
  text-decoration: none;
  padding: 8px 16px;
  border-radius: 8px;
  transition: all 0.2s ease;
}

.nav-link:hover {
  color: #111827;
  background: #f3f4f6;
}

.nav-link-active {
  color: #6366f1;
  background: #eef2ff;
}
```

### Breadcrumb
```css
.breadcrumb {
  display: flex;
  align-items: center;
  gap: 8px;
  font-family: 'Outfit', sans-serif;
  font-size: 14px;
}

.breadcrumb-item {
  color: #6b7280;
  text-decoration: none;
}

.breadcrumb-item:hover {
  color: #6366f1;
}

.breadcrumb-separator {
  color: #d1d5db;
}

.breadcrumb-current {
  color: #111827;
  font-weight: 500;
}
```

---

## Tables

### Basic Table
```css
.table {
  width: 100%;
  border-collapse: collapse;
  font-family: 'Outfit', sans-serif;
}

.table th {
  padding: 12px 16px;
  text-align: left;
  font-size: 12px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: #6b7280;
  background: #f9fafb;
  border-bottom: 1px solid #e5e7eb;
}

.table td {
  padding: 16px;
  font-size: 14px;
  color: #374151;
  border-bottom: 1px solid #e5e7eb;
}

.table tr:hover {
  background: #f9fafb;
}
```

---

## Modals

### Modal Overlay
```css
.modal-overlay {
  position: fixed;
  inset: 0;
  background: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 24px;
}

.modal {
  background: #ffffff;
  border-radius: 16px;
  max-width: 500px;
  width: 100%;
  max-height: 90vh;
  overflow: auto;
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}

.modal-header {
  padding: 24px 24px 0;
}

.modal-title {
  font-family: 'Outfit', sans-serif;
  font-size: 20px;
  font-weight: 600;
  color: #111827;
}

.modal-body {
  padding: 16px 24px;
}

.modal-footer {
  padding: 0 24px 24px;
  display: flex;
  justify-content: flex-end;
  gap: 12px;
}
```

---

## Tooltips

```css
.tooltip {
  position: relative;
}

.tooltip-content {
  position: absolute;
  bottom: 100%;
  left: 50%;
  transform: translateX(-50%);
  padding: 8px 12px;
  background: #1f2937;
  color: #ffffff;
  font-family: 'Outfit', sans-serif;
  font-size: 13px;
  border-radius: 6px;
  white-space: nowrap;
  margin-bottom: 8px;
  opacity: 0;
  visibility: hidden;
  transition: all 0.2s ease;
}

.tooltip:hover .tooltip-content {
  opacity: 1;
  visibility: visible;
}

.tooltip-content::after {
  content: '';
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translateX(-50%);
  border: 6px solid transparent;
  border-top-color: #1f2937;
}
```

---

## Loading States

### Spinner
```css
.spinner {
  width: 24px;
  height: 24px;
  border: 3px solid #e5e7eb;
  border-top-color: #6366f1;
  border-radius: 50%;
  animation: spin 0.8s linear infinite;
}

@keyframes spin {
  to { transform: rotate(360deg); }
}
```

### Skeleton
```css
.skeleton {
  background: linear-gradient(
    90deg,
    #f3f4f6 25%,
    #e5e7eb 50%,
    #f3f4f6 75%
  );
  background-size: 200% 100%;
  animation: shimmer 1.5s infinite;
  border-radius: 6px;
}

@keyframes shimmer {
  0% { background-position: 200% 0; }
  100% { background-position: -200% 0; }
}
```

---

## Utility Classes

### Spacing
```css
/* Margin */
.m-0 { margin: 0; }
.m-1 { margin: 4px; }
.m-2 { margin: 8px; }
.m-3 { margin: 12px; }
.m-4 { margin: 16px; }
.m-6 { margin: 24px; }
.m-8 { margin: 32px; }

/* Padding */
.p-0 { padding: 0; }
.p-1 { padding: 4px; }
.p-2 { padding: 8px; }
.p-3 { padding: 12px; }
.p-4 { padding: 16px; }
.p-6 { padding: 24px; }
.p-8 { padding: 32px; }
```

### Text
```css
.text-primary { color: #6366f1; }
.text-success { color: #10b981; }
.text-warning { color: #f59e0b; }
.text-error { color: #ef4444; }
.text-muted { color: #6b7280; }

.font-bold { font-weight: 700; }
.font-semibold { font-weight: 600; }
.font-medium { font-weight: 500; }

.text-center { text-align: center; }
.text-right { text-align: right; }
```

---

*For implementation details, refer to the CSS tokens in `/tokens/colors.css` and `/tokens/typography.css`.*
