class: center, middle
background-image: url(images/svelte-logo-outline.svg)
background-size: contain

# Quick Intro to Svelte

---

class: middle, center

# Adam Beres-Deak

### Tech Lead @ as24/cxp/acquisition

@bdadamm | me@bdadam.com

---

background-image: url(images/svelte-logo-outline.svg)
background-size: contain

# Svelte

---

class: middle, center

### Pronounciation

<iframe width="560" height="315" src="https://www.youtube.com/embed/PaOzcDCaSu0" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>

---

background-image: url(https://source.unsplash.com/0j-y7NTkyKM)
background-size: contain

### Slim and Elegant

.unsplash-credit[
<a href="https://unsplash.com/photos/0j-y7NTkyKM" target="_blank" rel="noopener noreferrer">Rodolfo Marques</a>
]

---

class: bright-text
background-image: url(https://source.unsplash.com/f_rLDn5m2XQ)

.shadow[

# What is Svelte?

> Svelte is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.

> Instead of using techniques like virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.

]

.unsplash-credit[
<a href="https://unsplash.com/photos/f_rLDn5m2XQ" target="_blank" rel="noopener noreferrer">Oskar Kadaksoo</a>
]

???

- Compiler
- Not really a runtime framework

---

# Svelte

- Compiles template code to JS + DOM operations + CSS
- Template syntax similar to Handlebars and React
- Single file components (like Vue)
- CSS modules
- Server side rendering and client side hydration
- Animations are first class citizens

---

<iframe data-src="https://svelte.dev/repl/9af3e3f3fe61495fb4d3a9f54f915057?version=3.16.4" width="100%" height="100%" style="border: 0;" frameborder="0"></iframe>

---

<iframe data-src="https://svelte.dev/repl/e430ad7e573445c6863533ee59c769d5?version=3.16.4" width="100%" height="100%" style="border: 0;" frameborder="0"></iframe>

---

<iframe data-src="https://svelte.dev/repl/bbb9a55be2f5495c8f57308416dcaf80?version=3.16.4" width="100%" height="100%" style="border: 0;" frameborder="0"></iframe>

---

<iframe data-src="https://svelte.dev/repl/7ef5be3bbeb8405ca223e8c4059f9f25?version=3.16.4" width="100%" height="100%" style="border: 0;" frameborder="0"></iframe>

---

<iframe data-src="https://svelte.dev/repl/bda01a8fd9a9477e8688f9e53ce53a3c?version=3.16.4" width="100%" height="100%" style="border: 0;" frameborder="0"></iframe>

---

<iframe data-src="https://svelte.dev/repl/62e3492acb344b929a57eccd00a77ebd?version=3.16.4" width="100%" height="100%" style="border: 0;" frameborder="0"></iframe>

---

## React

Next, Gatsby

## Vue

Nuxt, VuePress

## Svelte

Sapper

---

# Sapper

> The next small thing in web development, powered by Svelte

> Sapper is a framework for building high-performance universal web apps.

---

class: center, middle

# TypeScript Support

- Svelte was written in TypeScript
- TS can be used in `<script lang="ts"></script>` blocks
- HTML Templates are not typechecked yet

???

- Svelte is written in TS
- In templates some TS support

---

# Hello World Size

| Framework | Minified, non-gzipped size |
| :-------- | -------------------------: |
| Svelte    |                        3KB |
| React     |                      129KB |
