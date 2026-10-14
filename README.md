# se-lab-vm

Assets públicos de la máquina virtual de los laboratorios de *Security Engineer Lab*:
emulador [v86](https://github.com/copy/v86) (BSD-2-Clause, con un parche mínimo en `libv86.js`: guarda el tamaño de los symlinks creados en el 9p),
SeaBIOS (LGPLv3), xterm.js (MIT) y una imagen Debian 12 i386 (rootfs 9p en `flat/` + estado ya booteado `state.bin.zst`).
La Page los carga desde `https://migue251097.github.io/se-lab-vm/`. No contiene soluciones de los labs.
