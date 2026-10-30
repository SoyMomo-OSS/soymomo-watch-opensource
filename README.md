# SoyMomo Open Source

SoyMomo devices run Android and the Linux kernel. Parts of their firmware are
free software under copyleft licenses such as the
[GNU General Public License v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
(GPL-2.0) and the
[GNU Lesser General Public License v2.1](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
(LGPL-2.1). This repository is where we publish the source code for those
components, device by device.

> [Español más abajo](#español)

## Status

The firmware of our devices is built by our manufacturing partners. **We are
obtaining from them the complete corresponding source code for the Linux kernel
and the other GPL/LGPL components in each device, and will publish it here as we
receive it.**

For SoyMomo Space watches, we estimate publishing the kernel source **before
15 January 2027**. Each device page shows what is published and what is still
pending.

_Last updated: 2026-10-30_

## Watches

| Device | Android | Linux kernel | Kernel source |
|---|---|---|---|
| [SoyMomo Space 3.0 / 4.0](devices/space-3-4/) | 8.1.0 (Go) | 4.4.83 | Pending, estimated before 2027-01-15 |
| [SoyMomo Space 1.0 / 2.0](devices/space-1-2/) (Space 1.0 was also sold as Space 4G) | 4.4.4 | To be confirmed | Pending, estimated before 2027-01-15 |

## Other SoyMomo devices

We are reviewing which copyleft components are included in SoyMomo's earlier
watch models, tablets and phones. Each device will get its own page here once
confirmed.

## What this repository covers

Components licensed under GPL, LGPL or AGPL that ship in SoyMomo device
firmware. For each device and firmware version that means:

- the Linux kernel source as built, including device drivers;
- the kernel configuration (`.config`);
- the scripts and instructions used to build it;
- the source of any other GPL/LGPL components, such as the bootloader or
  system libraries.

It does not cover components under permissive licenses, such as the Android
Open Source Project userspace (mostly Apache-2.0), or SoyMomo's own proprietary
applications and services.

## Repository layout

```
devices/<device>/README.md   Device identification, firmware versions, components and status
devices/<device>/kernel/     Kernel configuration (.config), once available
docs/FAQ.md                  Frequently asked questions
```

Full kernel source trees will be published in a separate repository per device
family, with one branch or tag per firmware version, linked from each device
page.

## Contact

To request source code for a SoyMomo device or firmware version not listed
here, or to report a problem with what is published, write to
**opensource@soymomo.com** with the device name and firmware version.

To report a security issue, see [SECURITY.md](SECURITY.md).

## Status history

| Date | Change |
|---|---|
| 2026-10-30 | Estimated publication date; scope extended to all SoyMomo devices; FAQ and security contact added |
| 2026-10-29 | Repository created with SoyMomo Space 3.0/4.0 and Space 1.0/2.0 |

---

## Español

Los dispositivos SoyMomo funcionan con Android y el kernel de Linux. Parte de su
firmware es software libre bajo licencias copyleft como la
[GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html) y la
[LGPL-2.1](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html). En este
repositorio publicamos el código fuente de esos componentes, dispositivo por
dispositivo.

**Estado:** el firmware de nuestros dispositivos lo compilan nuestros
fabricantes. Estamos obteniendo de ellos el código fuente completo y
correspondiente del kernel de Linux y de los demás componentes GPL/LGPL de cada
dispositivo, y lo publicaremos aquí a medida que lo recibamos. Para los relojes
SoyMomo Space, estimamos publicar el código fuente del kernel **antes del 15 de
enero de 2027**. Cada página de dispositivo indica qué está publicado y qué está
pendiente.

**Relojes:**

| Dispositivo | Android | Kernel de Linux | Código fuente del kernel |
|---|---|---|---|
| [SoyMomo Space 3.0 / 4.0](devices/space-3-4/) | 8.1.0 (Go) | 4.4.83 | Pendiente, estimado antes del 2027-01-15 |
| [SoyMomo Space 1.0 / 2.0](devices/space-1-2/) (el Space 1.0 también se vendió como Space 4G) | 4.4.4 | Por confirmar | Pendiente, estimado antes del 2027-01-15 |

**Otros dispositivos SoyMomo:** estamos revisando qué componentes copyleft
incluyen los modelos de reloj anteriores, las tablets y los teléfonos SoyMomo.
Cada dispositivo tendrá su propia página aquí una vez confirmado.

**Alcance:** componentes bajo GPL, LGPL o AGPL incluidos en el firmware: el
código fuente del kernel tal como se compiló (incluidos los controladores), su
configuración (`.config`), los scripts e instrucciones de compilación, y el
código de otros componentes GPL/LGPL como el bootloader o bibliotecas del
sistema. No incluye componentes con licencias permisivas (como el espacio de
usuario de AOSP, mayormente Apache-2.0) ni las aplicaciones y servicios
propietarios de SoyMomo.

**Contacto:** para pedir el código fuente de un dispositivo o versión de
firmware que no aparezca aquí, o para reportar un problema con lo publicado,
escribe a **opensource@soymomo.com** indicando el nombre del dispositivo y la
versión de firmware. Para reportar un problema de seguridad, consulta
[SECURITY.md](SECURITY.md).

Preguntas frecuentes: [docs/FAQ.md](docs/FAQ.md).
