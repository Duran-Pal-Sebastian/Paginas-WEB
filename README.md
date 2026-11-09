# UNIDAD VI

## SISTEMAS OPERATIVOS

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
#  Protección y Seguridad en Sistemas Operativos

Sitio web educativo e interactivo enfocado en los principios, conceptos y mecanismos de **Protección y Seguridad en Sistemas Operativos**, desarrollado con base en la literatura del capítulo 9 del libro *Sistemas operativos modernos* (3.ª ed.) de Andrew S. Tanenbaum.

![Licencia](https://img.shields.io/badge/Estado-Finalizado-success)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v5.3.3-blueviolet)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

---

##  Características y Funcionalidades

- **Matriz de Protección Interactivas:** Simulación dinámica donde los usuarios pueden interactuar con los permisos (Lectura `R`, Escritura `W`, Ejecución `X`) entre dominios y objetos en tiempo real, evaluando decisiones de acceso al instante.
- **Demostrador de Cifrado:** Herramienta interactiva de sustitución monoalfabética en tiempo real con la clave explicada en la literatura de Tanenbaum.
- **Diseño Adaptativo y Tema Dinámico:** Interfaz responsiva con soporte nativo para **Modo Claro / Modo Oscuro** mediante Bootstrap 5.
- **Experiencia de Usuario Avanzada:** Animaciones fluidas al hacer scroll, indicador de lectura superior (*progress bar*) y diseño centrado en tipografía limpia (`IBM Plex Sans` y `Bricolage Grotesque`).

---

##  Estructura de Contenidos

El proyecto aborda 7 temas clave estructurados de forma didáctica:

1. **6.1 Concepto y objetivos de protección y seguridad:** Confidencialidad, integridad, disponibilidad y exclusión de externos.
2. **6.2 Clasificación aplicada a la seguridad:** Intrusos pasivos/activos, pérdida accidental de datos, amenazas internas/externas y control DAC vs. MAC.
3. **6.3 Funciones del sistema de protección:** Objetos, dominios, principio POLA, Base de Cómputo Confiable (TCB), modelos Bell-La Padula / Biba y esteganografía.
4. **6.4 Implantación de matrices de acceso:** Comparativa directa y tablas de Listas de Control de Acceso (ACL) frente a Listas de Capacidades.
5. **6.5 Protección basada en el lenguaje:** Análisis de vulnerabilidades en C frente a la seguridad de tipos en Java (JVM), applets y cajas de arena (*sandboxing*).
6. **6.6 Validación y amenazas al sistema:** Métodos de autenticación (contraseñas, salting, biometría) y catálogo de amenazas (*buffer overflow*, bombas lógicas, rootkits, gusanos).
7. **6.7 Cifrado:** Fundamentos criptográficos, principio de Kerckhoffs, clave simétrica vs. asimétrica, funciones hash, firmas digitales, PKI y TPM.

---

##  Tecnologías Utilizadas

- **HTML5 & CSS3:** Semántica accesible, variables CSS nativas y animaciones personalizadas.
- **JavaScript (Vanilla):** Lógica interactiva para la matriz de acceso, cifrado monoalfabético, control de scroll y conmutación de temas.
- **Bootstrap 5.3.3 & Bootstrap Icons:** Maquetación responsiva, componentes de acordeón/pestañas e iconografía.
- **Google Fonts:** `Bricolage Grotesque`, `IBM Plex Sans` y `IBM Plex Mono`.

---

##  Estructura del Repositorio

```text
├── index.html           # Estructura principal, estilos y scripts interactivos
├── YoFoto.jpeg          # Fotografía de integrante 1
├── milofotoface.jpeg    # Fotografía de integrante 2
├── diegofoto.jpeg       # Fotografía de integrante 3
├── Logo-TecNM.png       # Logotipo institucional
└── README.md            # Documentación del proyecto
Equipo de Desarrollo

Nombre	Número de Control

Sebastián Durán Palma	25410172

Luis Emilio Coronado Silva	25410163

Diego Alexander Nevarez Rodriguez	25410149

Referencia Citable

Tanenbaum, A. S. Sistemas operativos modernos (3.ª ed.). Pearson Educación.

© 2026 Guayaba´s Team S.A. de C.V. Todos los derechos reservados.
```
## ESTRUCTURA DE DATOS

Propósito: Página web interactiva y académica correspondiente a la Unidad VI: Métodos de búsqueda, perteneciente a la materia de Estructura de Datos (o Algoritmos).Algoritmos y Temario cubierto:6.1 Búsqueda secuencial: Recorrido lineal de vectores desordenados, algoritmo con elemento centinela, análisis de costo $O(n)$ y simulador paso a paso.6.2 Búsqueda binaria: Estrategia divide y vencerás para vectores previamente ordenados, descarte de mitades (índices bajo, alto, central), análisis de costo $O(\log n)$ y simulador visual de descarte de rangos.6.3 Búsqueda por funciones de hash: Cálculo directo de posición mediante técnica de residuo (k mod m), manejo de colisiones con encadenamiento (listas enlazadas por cubeta), complejidad promedio $O(1)$ y simulador dinámico de tabla hash con 7 cubetas.`Resumen / Comparativa: Tabla comparativa entre los tres algoritmos basada en requisito de orden, número de comparaciones con $N=1000$, complejidad temporal y casos de uso.`Equipo: Integrantes del equipo (guayaba's team).Stack Tecnológico: HTML5, CSS3 con CSS Variables y paleta temática "guayaba" (--guava, --leaf, --seed), JavaScript Vanilla (implementado con funciones generadoras function* y yield para la animación paso a paso), Bootstrap 5.3.3, Bootstrap Icons 1.11.3 y tipografías Google Fonts (Young Serif, DM Sans, JetBrains Mono).README.md para GitHubMarkdown# 🔍 Unidad VI: Métodos de Búsqueda

Sitio web educativo e interactivo enfocado en la enseñanza, visualización y simulación de los principales **Métodos de Búsqueda** en colecciones de datos, desarrollado por **guayaba's team**.

![Estado](https://img.shields.io/badge/Estado-Finalizado-success)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v5.3.3-blueviolet)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B%20Generators-yellow)

---

## 🚀 Características y Funcionalidades Interactivas

- **Simulador Paso a Paso de Búsqueda Secuencial:** Animación interactiva que permite recorrer arreglos desordenados indicando el índice actual, las comparaciones realizadas y el uso de elementos centinela.
- **Visualizador de Búsqueda Binaria:** Simulación dinámica con enfoque *divide y vencerás* que resalta los punteros `BAJO`, `CENTRAL` y `ALTO`, mostrando visualmente cómo se descartan las mitades del arreglo ordenado.
- **Tabla Hash con Encadenamiento (7 Cubetas):** Demostración interactiva para calcular posiciones con la función de residuo (`k mod m`), manejar colisiones dinámicas con listas enlazadas e ilustrar búsquedas directas.
- **Estructura con JS Generators (`function*` & `yield`):** Los algoritmos están codificados paso a paso utilizando generadores de JavaScript para un control de ejecución preciso en las simulaciones.
- **Diseño Temático Adaptativo:** Estilo visual personalizado basado en la paleta de color "guayaba", fuentes tipográficas monoespaciadas (`JetBrains Mono`) y animaciones CSS ligeras.

---

## 📚 Estructura de Contenidos

El proyecto cubre 3 métodos fundamentales de búsqueda y una sección comparativa:

1. **6.1 Búsqueda Secuencial:**
   - Concepto y lógica de recorrido lineal $O(n)$.
   - Optimización mediante el uso de **elementos centinela**.
   - Código de referencia en C# / JavaScript.

2. **6.2 Búsqueda Binaria:**
   - Precondición de ordenamiento previo en el conjunto de datos.
   - Algoritmo de división sucesiva en mitades con complejidad $O(\log n)$.
   - Ejemplo analizado paso a paso con vectores numéricos.

3. **6.3 Búsqueda por Funciones de Hash:**
   - Mapeo directo de claves a direcciones de memoria con complejidad promedio $O(1)$.
   - Resolución de colisiones mediante la técnica de **encadenamiento**.
   - Evaluación de funciones de residuo para números y cadenas de texto.

4. **Resumen Comparativo:**
   - Tabla comparativa de eficiencia, costo en comparaciones para $N=1000$, orden requerido e inconvenientes de cada método.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Maquetación semántica, variables CSS avanzadas y animaciones personalizadas.
- **JavaScript (Vanilla / ES6+):** Uso de *Generators* (`yield`) para pausar y reanudar la visualización paso a paso de los algoritmos.
- **Bootstrap 5.3.3 & Bootstrap Icons:** Componentes responsivos, menús colapsables e iconografía técnica.
- **Google Fonts:** `Young Serif`, `DM Sans` y `JetBrains Mono`.

---

## 📂 Estructura del Repositorio

```text
├── index.html           # Estructura principal, estilos y simuladores interactivos
├── YoFoto.jpeg          # Fotografía de Sebastián Durán Palma
├── milofotoface.jpeg    # Fotografía de Luis Emilio Coronado Silva
├── diegofoto.jpeg       # Fotografía de Diego Alexander Nevarez Rodriguez
├── Logo-TecNM (1).png   # Logotipo institucional TecNM
└── README.md            # Documentación del proyecto
👥 Equipo de Desarrollo (guayaba’s team)

Nombre

Sebastián Durán Palma. Número de Control: 25410172

Luis Emilio Coronado Silva: 25410163

Diego Alexander Nevárez Rodríguez: 25410149

© 2026 Guayaba´s Team S.A. de C.V. Todos los derechos reservados.

```
 

