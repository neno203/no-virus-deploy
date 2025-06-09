# No.Virus Deploy

This is the live payload terminal from **No.Bot | No.Virus | No.1**.

## What is this?

> A cyberpunk-themed payload dropper — designed to look harmless, but constantly pushing a stealth DOM payload every 10 seconds.

## Live Deploy

👉 [https://neno203.github.io/no-virus-deploy](https://neno203.github.io/no-virus-deploy)

## How it works

- Every 10 seconds, a payload is "injected" into the DOM using hidden `<iframe>`
- It’s a metaphor for how truth can quietly infect corrupted systems
- You can copy the `bookmarklet` below to drop payload anywhere

## Bookmarklet

```
javascript:(() => {
  const div = document.createElement('div');
  div.textContent = '[No.Virus] Payload Injected!';
  Object.assign(div.style, {position:'fixed',bottom:'10px',left:'10px',background:'#000',color:'#0f0',padding:'8px',zIndex:99999});
  document.body.appendChild(div);
})();
```

Drag the above link into your bookmarks bar to inject payload anywhere.

## License

Creative Disruption Public License (CDPL) – break systems, not people.
