# ShipSignal Component Specifications

## UI Components

### Buttons

#### Primary CTA Button
```css
.btn-primary {
  background: #4f46e5;
  color: #ffffff;
  font-family: 'Outfit', sans-serif;
  font-weight: 600;
  font-size: 16px;
  padding: 16px 32px;
  border-radius: 8px;
  border: none;
  cursor: pointer;
  transition: background 0.2s ease;
}

.btn-primary:hover {
  background: #4338ca;
}

.btn-primary:active {
  background: #3730a3;
}
```

#### Pill Button (Full Round)
```css
.btn-pill {
  background: #ffffff;
  color: #4f46e5;
  font-family: 'Outfit', sans-serif;
  font-weight: 600;
  font-size: 16px;
  padding: 14px 28px;
  border-radius: 9999px;
  border: none;
  cursor: pointer;
}
```

#### Secondary Button
```css
.btn-secondary {
  background: transparent;
  color: #6366f1;
  font-family: 'Outfit', sans-serif;
  font-weight: 600;
  font-size: 16px;
  padding: 14px 30px;
  border-radius: 8px;
  border: 2px solid #6366f1;
  cursor: pointer;
}

.btn-secondary:hover {
  background: #eef2ff;
}
```

---

### Cards

#### Basic Card
```css
.card {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}
```

#### Feature Card (Gradient)
```css
.card-feature {
  background: linear-gradient(135deg, #4f46e5 0%, #6366f1 100%);
  border-radius: 16px;
  padding: 32px;
  color: #ffffff;
}

.card-feature h3 {
  font-family: 'Outfit', sans-serif;
  font-weight: 700;
  font-size: 24px;
  margin-bottom: 12px;
}

.card-feature p {
  font-family: 'Outfit', sans-serif;
  font-weight: 400;
  font-size: 16px;
  opacity: 0.9;
}
```

#### Idea Card (Product-Specific)
```css
.card-idea {
  background: #ffffff;
  border-radius: 12px;
  padding: 24px;
  border-left: 4px solid #6366f1;
  box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
}

.card-idea .category {
  font-family: 'Outfit', sans-serif;
  font-weight: 500;
  font-size: 12px;
  color: #6366f1;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  margin-bottom: 8px;
}

.card-idea h4 {
  font-family: 'Outfit', sans-serif;
  font-weight: 700;
  font-size: 20px;
  color: #111827;
  margin-bottom: 8px;
}

.card-idea p {
  font-family: 'Outfit', sans-serif;
  font-weight: 400;
  font-size: 14px;
  color: #6b7280;
  line-height: 1.6;
}
```

---

### Form Elements

#### Text Input
```css
.input {
  width: 100%;
  padding: 12px 16px;
  font-family: 'Outfit', sans-serif;
  font-size: 16px;
  border: 1px solid #d1d5db;
  border-radius: 8px;
  outline: none;
  transition: border-color 0.2s ease;
}

.input:focus {
  border-color: #6366f1;
  box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
}

.input::placeholder {
  color: #9ca3af;
}
```

#### Email Signup Field
```css
.email-signup {
  display: flex;
  gap: 12px;
  max-width: 480px;
}

.email-signup input {
  flex: 1;
  padding: 14px 18px;
  font-family: 'Outfit', sans-serif;
  font-size: 16px;
  border: 2px solid #e5e7eb;
  border-radius: 8px;
}

.email-signup button {
  padding: 14px 24px;
  background: #4f46e5;
  color: white;
  font-family: 'Outfit', sans-serif;
  font-weight: 600;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  white-space: nowrap;
}
```

---

### Navigation

#### Header Logo
```css
.header-logo {
  height: 40px;
  width: auto;
}

.header-logo-link {
  display: flex;
  align-items: center;
  text-decoration: none;
}
```

#### Nav Link
```css
.nav-link {
  font-family: 'Outfit', sans-serif;
  font-weight: 500;
  font-size: 16px;
  color: #374151;
  text-decoration: none;
  padding: 8px 16px;
  border-radius: 6px;
  transition: background 0.2s ease;
}

.nav-link:hover {
  background: #f3f4f6;
  color: #111827;
}

.nav-link.active {
  color: #4f46e5;
  background: #eef2ff;
}
```

---

### Badges & Tags

#### Category Badge
```css
.badge {
  display: inline-block;
  padding: 4px 12px;
  font-family: 'Outfit', sans-serif;
  font-weight: 500;
  font-size: 12px;
  border-radius: 9999px;
  background: #eef2ff;
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
```

---

### Loading States

#### Spinner
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

#### Skeleton Loader
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
  border-radius: 8px;
}

@keyframes shimmer {
  0% { background-position: 200% 0; }
  100% { background-position: -200% 0; }
}
```

---

### Section Layouts

#### Hero Section
```css
.hero {
  background: linear-gradient(135deg, #312e81 0%, #4f46e5 50%, #6366f1 100%);
  padding: 120px 24px;
  text-align: center;
  color: white;
}

.hero h1 {
  font-family: 'Outfit', sans-serif;
  font-weight: 700;
  font-size: 56px;
  line-height: 1.1;
  margin-bottom: 24px;
}

.hero p {
  font-family: 'Outfit', sans-serif;
  font-weight: 400;
  font-size: 20px;
  opacity: 0.9;
  max-width: 600px;
  margin: 0 auto 32px;
}
```

#### Footer
```css
.footer {
  background: #111827;
  padding: 64px 24px 32px;
  color: #9ca3af;
}

.footer-logo {
  height: 32px;
  margin-bottom: 24px;
}

.footer-link {
  font-family: 'Outfit', sans-serif;
  font-size: 14px;
  color: #9ca3af;
  text-decoration: none;
}

.footer-link:hover {
  color: #ffffff;
}

.footer-copyright {
  font-family: 'Outfit', sans-serif;
  font-size: 14px;
  color: #6b7280;
  margin-top: 48px;
  padding-top: 24px;
  border-top: 1px solid #374151;
}
```

---

### Social Icons

#### Icon Button
```css
.social-icon {
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  background: transparent;
  color: #6b7280;
  transition: all 0.2s ease;
}

.social-icon:hover {
  background: #f3f4f6;
  color: #4f46e5;
}

.social-icon svg {
  width: 20px;
  height: 20px;
}
```

---

## Animation Presets

### Fade In
```css
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.fade-in {
  animation: fadeIn 0.3s ease;
}
```

### Slide Up
```css
@keyframes slideUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.slide-up {
  animation: slideUp 0.4s ease;
}
```

### Scale In
```css
@keyframes scaleIn {
  from {
    opacity: 0;
    transform: scale(0.95);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

.scale-in {
  animation: scaleIn 0.2s ease;
}
```

---

## Responsive Breakpoints

```css
/* Mobile */
@media (max-width: 639px) { }

/* Tablet */
@media (min-width: 640px) and (max-width: 1023px) { }

/* Desktop */
@media (min-width: 1024px) { }

/* Large Desktop */
@media (min-width: 1280px) { }
```

---

## Z-Index Scale

```css
--z-dropdown: 10;
--z-sticky: 20;
--z-fixed: 30;
--z-modal-backdrop: 40;
--z-modal: 50;
--z-popover: 60;
--z-tooltip: 70;
```
