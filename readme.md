**Taller de Consultas SQL Avanzadas**

**Objetivo**: Los estudiantes deberán realizar consultas avanzadas utilizando las vistas y tablas del esquema `cultivo_extendido`. Cada consulta incluirá una explicación técnica, el resultado explícito y un análisis de negocio relacionado con el query.

**Instrucciones**: 
1. Explica por qué realizaste el query de esa manera (incluyendo cualquier decisión técnica o elección de funciones).
2. Incluye el resultado explícito del query.
3. Realiza un análisis de negocio sobre lo que este query nos revela y cómo puede ser útil para la toma de decisiones en la empresa.

---

### Query 1: Comparar la eficiencia de las fincas en términos de ingreso por hectárea.

**Instrucciones específicas**:

1. Calcula el ingreso total de cada finca en función de las cantidades recogidas y los precios por cultivo en el mes en que se realizó la recogida. El ingreso se calcula multiplicando la cantidad recogida por el precio del cultivo que se recogió en el mes que se dio esa recogida.

2. Calcula el tamaño de cada finca. Puedes asumir que cada lote mide 4 hectáreas.

3. Calcula el ingreso total por hectárea de cada finca, usando la fórmula:

   \[
   \text{Ingreso por hectárea} = \frac{\text{Ingreso total de la finca}}{\text{Tamaño en hectáreas de la finca}}
   \]

** Análisis **

Realiza un análisis de negocio de este query:
   - ¿Cómo pueden los administradores de las fincas utilizar este resultado para mejorar la eficiencia de su operación?
   - ¿Qué impacto tiene este análisis en la toma de decisiones relacionadas con el manejo del cultivo o la expansión de la finca?
