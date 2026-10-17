# SUPERPKG / XPKG

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/flaxware/flax.system">
    <img src="images/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">FLAX SYSTEM</h3>

  <p align="center">
    <br />
    <a href="https://flaxware.github.io"><strong>Our website»</strong></a>
    <br />
    <br />
    <a href="https://github.com/flaxware/flax.system/">System</a>
    &middot;
    <a href="https://github.com/flaxware/flax.system/blob/main/LICENSE">View license</a>
    &middot;
    <a href="https://flaxware.github.io/#contact">Contact us</a>
  </p>
</div>

<!-- Description -->
Repository, *apt* enhance, portable executable extension.
- *superpkg* is the command-line package manager
- *.xpkg* is a file extension to install *superpkg* package executables through file manager *Thunar* like on MacOS or Windows.
- *.ppkg* is a portable executable file extension.
- Binary package manager.
- Choose rolling or stable, as for single package or multiple packages.
- Rollback support.
- Use of cryptographic signatures.

## Examples:
### Install *.xpkg* through *Thunar*
Imagine you don't have internet but you want to install some program, your friend gave you USB with program you wanted to install; you insert the USB, open it with *Thunar* and there we go:
```
flax.xpkg
```
Congratulations! You installed *superpkg* package without using command-line or internet!
> Same thing with *.ppkg* but you can't run portable executables directly from USB.

---
### Enter settings:
```
sudo superpkg settings
```

---
### Install specific software:
```
sudo superpkg install flax
```

---
### Remove specific software:
```
sudo superpkg remove flax
```

---
### Update specific software:
```
sudo superpkg update flax
```

---
### Upgrade software:
```
sudo superpkg update
```
> Or use this instead
```
sudo superpkg upgrade
```

---
### Rollback to previous version:
```
sudo superpkg rollback
```

---
### Search specific software:
```
sudo superpkg search flax
```

---
### Get info about specific software:
```
sudo superpkg info flax
```
> Actually is implementation of *man* and *info*; in addition also displays size, packages included, and by which user installed.
