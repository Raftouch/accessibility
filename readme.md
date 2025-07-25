### Enable accessibility preview in dev tools

#### In your web browser

```
Ctrl + Shift + P
```

#### Run

```
Show Accessibility
```

#### Click on

```
Enable full-page accessibility tree
```

### Enable rendering preview in dev tools

#### Run

```
Show Rendering
```

#### Check contrast

```
Emulate vision deficiencies
```

### Best practices

- do not use positive tabindex (ex. 3,4)
- possible tabindex : 0 or -1
- tabindex 0 --> area is accessible and tabbable
- tabindex -1 --> area is accessible only programmatically
- when you remove outline, you should add focus
- add SKIP if you have a bunch of different links on your web page
- space content as much as possible (for mobility impaired people)
- make sure that the area you can click on is large enough
- do not apply timing restrictions (ex. on "are you sure you want to delete it?")
- pay attention to render preferencies (ex. prefers-reduced-motion)
- use "autofocus" for search websites

### Website about Accessibility

```
https://webaim.org
```

### Tools to test accessibility

- Lighthouse (dev tools)

- eslint-plugin-jsx-a11y

### Install plugin

```
npm i eslint-plugin-jsx-a11y
```

- Chrome accessibility debug

```
chrome://accessibility
```
