# Frequently asked questions

> [Español más abajo](#preguntas-frecuentes)

### What is this repository?

SoyMomo devices include free software, most importantly the Linux kernel, whose
licenses (GPL and LGPL) require us to make its source code available. This
repository is where we publish that source code and keep track of its status
for each device.

### Why isn't the source code here yet?

The firmware of our devices is built by our manufacturing partners, so the exact
source code they used has to come from them. We are obtaining it and will
publish it as we receive it. For SoyMomo Space watches we estimate publishing
the kernel source before 15 January 2027. Each device page shows the current
status.

### Which devices are covered?

All SoyMomo devices that ship GPL- or LGPL-licensed software. The Space watches
are listed first. Earlier watch models, tablets and phones are being reviewed
and will be added as they are confirmed.

### What exactly will be published?

For each device and firmware version: the Linux kernel source as built
(including device drivers), its configuration file, the scripts and
instructions used to build it, and the source of any other GPL/LGPL
components, such as the bootloader or system libraries.

### Does this include SoyMomo's apps or services?

No. This repository covers copyleft components in device firmware. SoyMomo's
own applications and cloud services are proprietary and are not part of it.
Components under permissive licenses, such as most of the Android Open Source
Project (Apache-2.0), are not included either.

### My device or firmware version isn't listed. What do I do?

Write to **opensource@soymomo.com** with the device name and firmware version.

### How do I report a security issue?

See [SECURITY.md](../SECURITY.md). Please don't report vulnerabilities in public
issues.

---

# Preguntas frecuentes

### ¿Qué es este repositorio?

Los dispositivos SoyMomo incluyen software libre, principalmente el kernel de
Linux, cuyas licencias (GPL y LGPL) nos obligan a poner su código fuente a
disposición. En este repositorio publicamos ese código y llevamos el estado de
cada dispositivo.

### ¿Por qué el código fuente todavía no está aquí?

El firmware de nuestros dispositivos lo compilan nuestros fabricantes, así que el
código exacto que usaron tiene que venir de ellos. Lo estamos obteniendo y lo
publicaremos a medida que lo recibamos. Para los relojes SoyMomo Space estimamos
publicar el código fuente del kernel antes del 15 de enero de 2027. Cada página
de dispositivo muestra el estado actual.

### ¿Qué dispositivos se incluyen?

Todos los dispositivos SoyMomo que incluyen software bajo GPL o LGPL. Los relojes
Space aparecen primero. Los modelos de reloj anteriores, las tablets y los
teléfonos están en revisión y se irán agregando a medida que se confirmen.

### ¿Qué se publicará exactamente?

Para cada dispositivo y versión de firmware: el código fuente del kernel de Linux
tal como se compiló (incluidos los controladores), su archivo de configuración,
los scripts e instrucciones de compilación, y el código fuente de otros
componentes GPL/LGPL, como el bootloader o bibliotecas del sistema.

### ¿Incluye las apps o servicios de SoyMomo?

No. Este repositorio cubre los componentes copyleft del firmware de los
dispositivos. Las aplicaciones y servicios en la nube de SoyMomo son propietarios
y no forman parte de él. Tampoco se incluyen componentes con licencias
permisivas, como la mayor parte del Android Open Source Project (Apache-2.0).

### Mi dispositivo o versión de firmware no aparece. ¿Qué hago?

Escribe a **opensource@soymomo.com** indicando el nombre del dispositivo y la
versión de firmware.

### ¿Cómo reporto un problema de seguridad?

Consulta [SECURITY.md](../SECURITY.md). Por favor, no reportes vulnerabilidades en
issues públicos.
