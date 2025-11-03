# css-animations


### Fade In 1

```css
{
  0% { opacity: 0; filter: brightness(1) blur(20px) }
  10% { opacity: 1; filter: brightness(2) blur(10px) }
  100% { opacity: 1; filter: brightness(1) blur(0) }
}
```



### Fade In 2

```css
{
  0% { opacity: 0; clip-path: inset(5%); transform: scale(111.11%) }
  100% { opacity: 1; clip-path: inset(0); transform: scale(1) }
}
```

### Fade In 3

```css
{
  0% {
    mask: linear-gradient(90deg, #000 25%, #000000e6 50%, #00000000) 150% 0 / 400% no-repeat;
    opacity: .2;
  }
  100% {
    mask: linear-gradient(90deg, #000 25%, #000000e6 50%, #00000000) 0 / 400% no-repeat;
    opacity: 1;
  }
}
```