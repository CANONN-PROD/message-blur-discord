paste these into url bar

Blur on
```javascript
   javascript:(()=>{const s=document.createElement('style');s.id='discord-blur-style';s.textContent='main{filter:blur(5px)!important}';document.head.appendChild(s)})()
```
Blur Off
```javascript
   javascript:(()=>{document.getElementById('discord-blur-style')?.remove()})()
```

