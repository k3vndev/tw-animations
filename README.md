# 🌀 @k3vndev/tw-animations

A lightweight, fully customizable set of **Tailwind CSS animations** ready to drop into any project.
Built for **Tailwind v4+** and inspired by [Tailwind CSS Animated](https://www.tailwindcss-animated.com) & [easings.net](https://easings.net/).

---

### 🚀 Installation

```bash
npm install @k3vndev/tw-animations
```

---

### 🧩 Usage

Import it **after Tailwind** in your main CSS:

```css
@import "tailwindcss";
@import "@k3vndev/tw-animations";
```

Then apply the classes to your elements:

```html
<h1 class="animate-slide-in-b anim-blur-md">
  Hello there 👋
</h1>
```

---

### ⚡ Features

* **Atomic animation classes**: combine slide, fade, scale, blur, rotation, duration, easing, delay, and iteration however you want.

* Base animations include: `slide-in-*`, `slide-out-*`, `fade-in`, `fade-out`. From there, layer on custom properties.

* Avoids bloated “composite” names — just layer atomic classes for custom effects.

---

### ✨ Example

```html
<div class="animate-fade-in anim-opacity-10 anim-blur-2xl anim-scale-0 -anim-rotate-360 anim-ease-out-back anim-duration-1500">
  Cinematic entry 😎
</div>
```

Combine anything you want — the animation library adapts automatically.

