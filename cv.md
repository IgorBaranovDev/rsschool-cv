# Ihar Baranau

![photo](img/photo_2024-02-08_10-21-30-9999.jpg)

## Contact

- Phone: +48 780 783 259
- Email: baranovigorjsdev@gmail.com
- GitHub: https://github.com/IgorBaranovDev
- LinkedIn: https://www.linkedin.com/in/igor-baranov-5807a1161
- Telegram: @Ihar_Baranau
- Location: Poland

---

## Summary

Front-End Developer with strong experience in JavaScript and React.
Focused on building high-quality web applications and continuously
improving professional skills.

---

## Skills

### Programming Languages

- JavaScript
- TypeScript
- HTML
- CSS (SASS, LESS)

### Frameworks & Libraries

- React
- Next.js
- Node.js
- PixiJS

### Tools

- Git
- Webpack
- Vite
- VS Code

---

## Code Examples

### Codewars — Digital Root

https://www.codewars.com/kata/541c8630095125aba6000c00/javascript

```javascript
function digitalRoot(n) {
  let result = 0;

  while (n > 0) {
    result += n % 10;
    n = Math.floor(n / 10);

    if (n === 0 && result > 9) {
      n = result;
      result = 0;
    }
  }

  return result;
}
```

