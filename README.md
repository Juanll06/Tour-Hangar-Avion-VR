# [Tour Virtual de Hangar y Avión]

## **Equipo:** [Juan López Lara]
## **Opción:** [B Sector Creativa]
## **[URL: ** *[Enlace al repositorio de GitHub o dónde se aloje el proyecto]* **]**

---

## ## 1. Tecnología: A-Frame

| **Imágenes 360** | Utilizado en la Escena 1 (Recepción) para crear un entorno inmersivo de **bienvenida 360** antes de pasar al hangar. |
| **Modelos 3D** | Uso de modelos en formato GLTFç(Avión, Persona, Lámpara, Mesa) 
| **Interactividad** | Implementada mediante `event-set` y componentes personalizados (`portal-activator`, `start-logistics`, `motor-starter`) que activan animaciones, sonidos y enlaces. |
| **VR** | Navegación preparada para la inmersión total en dispositivos VR (ej. Oculus/Meta Quest) gracias a la base de A-Frame. |

---

## ## 2. Las 3 Escenas


| **1 | Recepción** | 360 + 3D | **Recepción Hangar:** Bienvenida y acceso mediante un NPC interactivo (`portal-activator`). |
| **2 | Proceso** | 3D + Interactividad | **Hangar para poder sacar el avión** Mediante un elemento interactivo nos permite sacar un avión |
| **3 | Producto** | 3D + IT/OT | **Avión/Producto:** Interacción directa con el avión (Producto) para activar el sonido.

---

## ## 3. Capturas

! [MENU](./screenshots/Menu.jpg.png)  
! [PRIMERA_ESCENA](./screenshots/Recepcion.png)
! [SEGUNDA_ESCENA](./screenshots/Hangar.jpg.png)
! [TERCERA_ESCENA](./screenshots/Hangar_Avion.jpg.png)

---

## ## 4. Uso

1.  Abre el proyecto usando un **servidor local** (Ej. Live Server en VS Code o GitHub Pages).
2.  Haz **clic en el botón** de la página `index.html` para entrar en la VR.
3.  Utiliza **WASD** para moverte y el ratón para mirar.
4.  **Interactúa con objetos** (`recepcionista`, `sacar avión`, `avión`) para avanzar en el tour.
5.  Compatible con **VR (Oculus/Quest)**, abriendo el enlace en el navegador del dispositivo.

---
**Autor:** [Juan López Lara]
