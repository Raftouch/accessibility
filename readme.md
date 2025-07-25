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

### Rules

- never use positive tabindex (ex. 3,4)
- possible tabindex : 0 or -1
- tabindex 0 --> area is accessible and tabbable
- tabindex -1 --> area is accessible only programmatically
- when you remove outline, you should add focus
- add SKIP if you have a bunch of different links on your web page
