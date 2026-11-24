<a href="https://alcasite.com"><img src="assets/banner.png" alt="Víctor Álvarez Calvo · IT Technician · Systems & Networks · Cybersecurity" width="100%"></a>

<p align="center">
  <a href="https://alcasite.com"><img src="https://img.shields.io/badge/alcasite.com-0b0c0e?style=flat-square&logo=googlechrome&logoColor=5fe3a1" alt="alcasite.com"></a>
  <a href="https://www.linkedin.com/in/victor-alvarez-calvo"><img src="https://img.shields.io/badge/LinkedIn-0b0c0e?style=flat-square" alt="LinkedIn"></a>
  <a href="https://alcasite.com/docs/"><img src="https://img.shields.io/badge/Documentación-0b0c0e?style=flat-square&logo=bookstack&logoColor=5fe3a1" alt="Documentación"></a>
</p>

<img src="assets/terminal.svg" alt="Terminal: whoami, proyectos en marcha y estado de mi servidor" width="100%">

### Sobre mí

Técnico informático (SMX) y estudiante de **ASIR** con la mirada puesta en la **ciberseguridad**. Arreglo equipos, configuro redes y estudio cómo se rompen los sistemas para aprender a protegerlos.

Lo que aprendo en clase lo pruebo en mi propio servidor: ahí viven mis webs y mis apps, cada una en su contenedor, sin puertos abiertos y documentadas paso a paso.

### En marcha

<table>
  <tr>
    <td width="50%"><a href="https://holguraapp.com"><img src="assets/holgura.png" alt="HolguraApp: app web de finanzas personales"></a></td>
    <td width="50%"><a href="https://lazo.alcasite.com"><img src="assets/lazo.png" alt="Lazo: app de escritorio para Windows y Linux"></a></td>
  </tr>
  <tr>
    <td><b><a href="https://holguraapp.com">HolguraApp</a></b> · app web de finanzas personales con cuentas (PocketBase), inicio con Google y modo sin conexión.</td>
    <td><b><a href="https://lazo.alcasite.com">Lazo</a></b> · Bluetooth, impresoras, redes y pantallas en una sola app de escritorio (Electron, PowerShell y Linux), con sistema de incidencias propio.</td>
  </tr>
  <tr>
    <td><a href="https://encuadre.alcasite.com"><img src="assets/encuadre.png" alt="Encuadre: app de capturas de pantalla"></a></td>
    <td><a href="https://alcasite.com/docs/"><img src="assets/minube.png" alt="Mi nube: servidor propio con Proxmox"></a></td>
  </tr>
  <tr>
    <td><b><a href="https://encuadre.alcasite.com">Encuadre</a></b> · capturas de pantalla que tapan solas los datos sensibles, adaptada a Linux con Wayland (Fedora y GNOME).</td>
    <td><b><a href="https://alcasite.com/docs/">Mi nube</a></b> · servidor dedicado con Proxmox VE: 7 contenedores Debian, cortafuegos en cada uno y todo documentado.</td>
  </tr>
</table>

### Cómo está montado

<img src="assets/infra.png" alt="Navegador → Cloudflare (túnel cifrado, sin puertos abiertos) → Proxmox VE con los contenedores web-alcasite, web-holgura, web-lazo, web-encuadre, bookstack, panel-docs y desarrollo" width="100%">

Cada contenedor tiene su propio cortafuegos (**nftables**) que limita también lo que puede salir. Se publica por **SSH** con usuarios que solo pueden escribir en su carpeta, todo va en **git** y hay copias de seguridad diarias. La documentación pasa por un panel propio que oculta contraseñas, claves e IPs antes de salir a [alcasite.com/docs](https://alcasite.com/docs/).

### Herramientas

| | |
|---|---|
| **Sistemas** | ![Proxmox](https://img.shields.io/badge/Proxmox-121418?style=flat-square&logo=proxmox&logoColor=E57000) ![Debian](https://img.shields.io/badge/Debian-121418?style=flat-square&logo=debian&logoColor=A81D33) ![Fedora](https://img.shields.io/badge/Fedora-121418?style=flat-square&logo=fedora&logoColor=51A2DA) ![Windows](https://img.shields.io/badge/Windows-121418?style=flat-square&logo=windows&logoColor=0078D4) ![PowerShell](https://img.shields.io/badge/PowerShell-121418?style=flat-square&logo=powershell&logoColor=5391FE) ![Bash](https://img.shields.io/badge/Bash-121418?style=flat-square&logo=gnubash&logoColor=4EAA25) |
| **Redes y seguridad** | ![Cloudflare](https://img.shields.io/badge/Cloudflare_Tunnel-121418?style=flat-square&logo=cloudflare&logoColor=F38020) ![nftables](https://img.shields.io/badge/nftables-121418?style=flat-square&logo=linux&logoColor=efece4) ![nginx](https://img.shields.io/badge/nginx-121418?style=flat-square&logo=nginx&logoColor=009639) ![SSH](https://img.shields.io/badge/SSH-121418?style=flat-square&logo=openssh&logoColor=efece4) |
| **Desarrollo** | ![JavaScript](https://img.shields.io/badge/JavaScript-121418?style=flat-square&logo=javascript&logoColor=F7DF1E) ![Python](https://img.shields.io/badge/Python-121418?style=flat-square&logo=python&logoColor=3776AB) ![Electron](https://img.shields.io/badge/Electron-121418?style=flat-square&logo=electron&logoColor=9FEAF9) ![PocketBase](https://img.shields.io/badge/PocketBase-121418?style=flat-square&logo=pocketbase&logoColor=efece4) ![Git](https://img.shields.io/badge/Git-121418?style=flat-square&logo=git&logoColor=F05032) |

<p align="center"><sub>Hecho y alojado por mí · <a href="https://alcasite.com">alcasite.com</a></sub></p>
