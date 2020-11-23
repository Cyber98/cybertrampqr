## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://cyber98.github.io/cybertrampqr/';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="CYBERTRAMP QR Code Scanner" disabled=no dst-host=cyber98.github.io/
```

### Powered by webqr.com
