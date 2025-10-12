# SOL_ECUA_LINEAL

**¡Bienvenido al Tutor de Ecuaciones Lineales!**  
Este proyecto usa una **IA basada en un agente reactivo** para resolver ecuaciones lineales de forma interactiva, guiando al estudiante paso a paso como un profesor paciente. Perfecto para estudiantes de precalculo de universidad que quieren aprender a resolver ecuaciones como `2*x + 3 = 7` con explicaciones claras y advertencias sobre errores comunes (¡como olvidar los paréntesis!).

## Descripción
Este tutor interactivo:
- Resuelve ecuaciones lineales (tipo `ax + b = c`) mostrando cada paso: restar términos, simplificar, igualar a cero y despejar `x`.
- Usa **LaTeX** para mostrar ecuaciones de forma bonita.
- Incluye advertencias para evitar errores, como olvidar paréntesis al restar términos.
- Funciona en cualquier navegador como una página web (`index.html`), sin necesidad de instalar nada.

Desarrollado con **SymPy.js** para cálculos matemáticos y **MathJax** para visualización, este proyecto es ideal para aprender álgebra de manera práctica.

## Cómo usarlo
1. Abre la página web en un navegador:
   - Si estás en GitHub Pages, visita [ENLACE A TU PÁGINA WEB] (actualiza este enlace tras configurar GitHub Pages).
   - O descarga `index.html` y ábrelo localmente con Chrome/Firefox.
2. Ingresa una ecuación lineal en el campo de texto (ej., `2*x + 3 = 7`).
3. Haz clic en **Empezar** para ver la ecuación.
4. Haz clic en **Siguiente Paso** para avanzar por los pasos de resolución, con explicaciones y advertencias.
5. ¡Aprende a tu ritmo! El tutor te guía sin darte la solución de una.

## Instrucciones para escribir ecuaciones
- Usa `x` como variable (ej., `2*x`, no `2x`).
- Escribe la multiplicación con `*`, suma con `+`, resta con `-`, y división con `/`.
- Asegúrate de incluir el signo `=` en la ecuación.
- Usa paréntesis para agrupar términos (ej., `(4/3)*x`).
- **Recomendación**: Deja un espacio entre cada carácter para mayor claridad (ej., `2 * x + 3 = 7`).

### Ejemplo
**Ecuación**: `2 * x + 3 = 7`  
**Pasos**:
1. Restamos `(7)` a ambos lados: `2 * x + 3 - (7) = 0`. **¡Cuidado!** Usa paréntesis al restar.
2. Simplificamos: `2 * x + 3 - 7 = 2 * x - 4`.
3. Igualamos a cero: `2 * x - 4 = 0`.
4. Despejamos `x`: `2 * x = 4 \implies x = 2`.

**Resultado**: \( x = 2 \)

## Requisitos
- Un navegador web moderno (Chrome, Firefox, etc.).
- Conexión a internet para cargar SymPy.js y MathJax (o puedes descargarlos para uso offline).
- No necesitas instalar Python ni otras herramientas.

## Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/SOL_ECUA_LINEAL.git
