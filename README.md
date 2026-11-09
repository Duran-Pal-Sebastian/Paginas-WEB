# UNIDAD VI

## SISTEMAS OPERATIVOS---------------------------------------------------------------------------------------------------------

Propósito: Página web interactiva y académica orientada a la divulgación de los temas de Protección y Seguridad en Sistemas Operativos, basada estructuralmente en el capítulo 9 del libro Sistemas operativos modernos de Andrew S. Tanenbaum.

Secciones/Temario cubierto:

6.1 Concepto y objetivos de protección y seguridad (Confidencialidad, Integridad, Disponibilidad, Exclusión de externos).

6.2 Clasificación aplicada a la seguridad (Intrusos, Pérdida accidental de datos, Amenazas internas vs. externas, Control de acceso DAC/MAC).

6.3 Funciones del sistema de protección (Objetos/Dominios, POLA, TCB y Monitor de referencia, Autenticación, Seguridad multinivel con Bell-La Padula/Biba, Canales encubiertos y Esteganografía).

6.4 Implantación de matrices de acceso (Matriz interactiva, ACLs vs. Capacidades).

6.5 Protección basada en el lenguaje (Riesgos de límites en C, Tipo seguro en Java, Cajas de arena, Interpretación y Firma de código).

6.6 Validación y amenazas al sistema (Métodos de autenticación, Bombas lógicas, Trampas, Desbordamientos de búfer, Troyanos, Virus/Gusanos, Rootkits y Spyware).

6.7 Cifrado (Simétrico, Clave pública RSA, Hashes, Firmas digitales, Certificados PKI, TPM y Demo interactiva de sustitución monoalfabética).

Equipo Integrantes del proyecto.

Stack Tecnológico: HTML5, CSS3 personalizado con CSS Variables y Animaciones, JavaScript vainilla (DOM, cifrado y matriz interactiva), Bootstrap 5.3.3, Bootstrap Icons 1.11.3 y tipografías de Google Fonts (Bricolage Grotesque, IBM Plex Sans, IBM Plex Mono).

README.md para GitHub
Markdown
# 🛡️ Protección y Seguridad en Sistemas Operativos

Sitio web educativo e interactivo enfocado en los principios, conceptos y mecanismos de **Protección y Seguridad en Sistemas Operativos**, desarrollado con base en la literatura del capítulo 9 del libro *Sistemas operativos modernos* (3.ª ed.) de Andrew S. Tanenbaum.

![Licencia](https://img.shields.io/badge/Estado-Finalizado-success)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v5.3.3-blueviolet)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

---

## 🚀 Características y Funcionalidades

- **Matriz de Protección Interactivas:** Simulación dinámica donde los usuarios pueden interactuar con los permisos (Lectura `R`, Escritura `W`, Ejecución `X`) entre dominios y objetos en tiempo real, evaluando decisiones de acceso al instante.
- **Demostrador de Cifrado:** Herramienta interactiva de sustitución monoalfabética en tiempo real con la clave explicada en la literatura de Tanenbaum.
- **Diseño Adaptativo y Tema Dinámico:** Interfaz responsiva con soporte nativo para **Modo Claro / Modo Oscuro** mediante Bootstrap 5.
- **Experiencia de Usuario Avanzada:** Animaciones fluidas al hacer scroll, indicador de lectura superior (*progress bar*) y diseño centrado en tipografía limpia (`IBM Plex Sans` y `Bricolage Grotesque`).

---

## 📚 Estructura de Contenidos

El proyecto aborda 7 temas clave estructurados de forma didáctica:

1. **6.1 Concepto y objetivos de protección y seguridad:** Confidencialidad, integridad, disponibilidad y exclusión de externos.
2. **6.2 Clasificación aplicada a la seguridad:** Intrusos pasivos/activos, pérdida accidental de datos, amenazas internas/externas y control DAC vs. MAC.
3. **6.3 Funciones del sistema de protección:** Objetos, dominios, principio POLA, Base de Cómputo Confiable (TCB), modelos Bell-La Padula / Biba y esteganografía.
4. **6.4 Implantación de matrices de acceso:** Comparativa directa y tablas de Listas de Control de Acceso (ACL) frente a Listas de Capacidades.
5. **6.5 Protección basada en el lenguaje:** Análisis de vulnerabilidades en C frente a la seguridad de tipos en Java (JVM), applets y cajas de arena (*sandboxing*).
6. **6.6 Validación y amenazas al sistema:** Métodos de autenticación (contraseñas, salting, biometría) y catálogo de amenazas (*buffer overflow*, bombas lógicas, rootkits, gusanos).
7. **6.7 Cifrado:** Fundamentos criptográficos, principio de Kerckhoffs, clave simétrica vs. asimétrica, funciones hash, firmas digitales, PKI y TPM.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Semántica accesible, variables CSS nativas y animaciones personalizadas.
- **JavaScript (Vanilla):** Lógica interactiva para la matriz de acceso, cifrado monoalfabético, control de scroll y conmutación de temas.
- **Bootstrap 5.3.3 & Bootstrap Icons:** Maquetación responsiva, componentes de acordeón/pestañas e iconografía.
- **Google Fonts:** `Bricolage Grotesque`, `IBM Plex Sans` y `IBM Plex Mono`.

---

## 📂 Estructura del Repositorio

```text
├── index.html           # Estructura principal, estilos y scripts interactivos
├── YoFoto.jpeg          # Fotografía de integrante 1
├── milofotoface.jpeg    # Fotografía de integrante 2
├── diegofoto.jpeg       # Fotografía de integrante 3
├── Logo-TecNM.png       # Logotipo institucional
└── README.md            # Documentación del proyecto
👥 Equipo de Desarrollo
Nombre	Número de Control
Sebastián Durán Palma	25410172
Luis Emilio Coronado Silva	25410163
Diego Alexander Nevarez Rodriguez	25410149
📖 Referencia Citable
Tanenbaum, A. S. Sistemas operativos modernos (3.ª ed.). Pearson Educación.

© 2026 Guayaba´s Team S.A. de C.V. Todos los derechos reservados.
