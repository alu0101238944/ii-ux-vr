
# **Grupo** <!-- omit in toc -->

* Viren Sajju Dhanwani Dhanwani
* José Daniel Escánez Expósito
* Gabriel García Jaubert
* Ángel Tornero Hernández

# **Tabla de contenidos** <!-- omit in toc -->

- [**Dibujar el suelo**](#dibujar-el-suelo)
- [**Generar perspectiva atmoférisca**](#generar-perspectiva-atmoférisca)
- [**Características del terreno**](#características-del-terreno)
- [**Paisajes sonoros**](#paisajes-sonoros)
- [**Guiar al usuario con objetos**](#guiar-al-usuario-con-objetos)
- [**Retícula contextual**](#retícula-contextual)
- [**Objetos interactivos**](#objetos-interactivos)
- [**Fuente**](#fuente)

# **Dibujar el suelo**
Crear un terreno estático sirve de referencia para el jugador, ayudándole a orientarse

# **Generar perspectiva atmoférisca**
Esta perspectiva puede ayudar al usuario a entender la escala del entorno virtual

# **Características del terreno**
| Característica | Descripción |
| -- | -- |
| Suelo | Entorno de movimiento, de manera abierta (menos usual) o cerrada |
| Camino | Permite el movimiento de los elementos del terreno |
| Obstáculo | Objeto de tamaño considerable que permita colisión |
| Barrera | Tipo específico de obstáculo que suele bloquear tanto la visión como el movimiento |
| Margen de agua | Impide el movimiento de los elementos |
| Borde | Límite de aproximación. Es una zona de peligro, los elementos deben evitar estos lugares |
| Escalera | Disposición de escalones adyacentes que permiten tanto el descenso como el ascenso |
| Pendiente | Puede permitir o no el movimiento de los elementos en función del ángulo y la textura del suelo |

# **Paisajes sonoros**

Crear una introducción suave a un nuevo entorno puede lograrse desvaneciendo primero el paisaje sonoro del lugar y luego la imagen. Esto permite construir una imagen mental del entorno a través del sonido, reduciendo el factor de choque

# **Guiar al usuario con objetos**

Utilizar elementos propios del entorno para guiar de manera intuitiva al usuario (remplazando la típica interfaz de usuario) 

Ejemplo: Colocación de flores en las proximidades de una senda para atraer la atención del usuario hacia el camino correcto, podrían mantener la autenticidad del lugar

Estas pistas deben ser contextuales (las flores no funcionarían en un paisaje marciano)

# **Retícula contextual**

| Característica | Descripción |
| -- | -- |
| Estado de reposo | Retícula mínima necesaria para ubicar el centro |
| Movimiento | Al mirar a cualquier lugar al que se puede desplazar el jugador, se debe transformar en un puntero grande que resalte el área destacada |
| Interacción con objetos | Al dirigir la atención a un objeto interactivo, la retícula debe reaccionar en consecuencia |
| Coloración de la retícula | Modificar brillo de la retícula para mantenerse visible en todas las condiciones de iluminación |
| Objetos como retícula | En momentos puntuales, sustituir la retícula por un objeto en 3D para facilitar la interacción |

# **Objetos interactivos**

Si no todos los objetos permiten interacción, los usuarios requieren de ayuda para conocer aquellos que sí la permitan. Dado que los cambios en la retícula contextural pueden resultar confusos en algunos casos, estas pistas pueden consistir en cambios en los propios objetos (por ejemplo en su textura) o en la emisión de sonidos sutiles cuando se les mira directamente

---

# **Fuente**
[https://marvelapp.com/blog/design-practices-virtual-reality/](https://marvelapp.com/blog/design-practices-virtual-reality/)
