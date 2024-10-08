# Taller de Consultas SQL Avanzadas

**Objetivo**: Los estudiantes deberán realizar consultas avanzadas utilizando las vistas y tablas del esquema `cultivo_extendido`. Cada consulta incluirá una explicación técnica, el resultado explícito y un análisis de negocio relacionado con el query.

**Instrucciones por cada sección**: 
1. Explica por qué realizaste el query de esa manera (incluyendo cualquier decisión técnica o elección de funciones).
2. Incluye el resultado explícito del query y el código del query.
3. Realiza un análisis de negocio sobre lo que este query nos revela y cómo puede ser útil para la toma de decisiones en la empresa.

---

### **Query 1: Comparar la eficiencia de las fincas en términos de ingreso por hectárea**

**Instrucciones específicas**:

1. Calcula el ingreso total de cada finca en función de las cantidades recogidas y los precios por cultivo en el mes en que se realizó la recogida. El ingreso se calcula multiplicando la cantidad recogida por el precio del cultivo que se recogió, en el mes que se dio esa recogida.

2. Calcula el tamaño de cada finca. Puedes asumir que cada lote mide 4 hectáreas.

3. Calcula el ingreso total por hectárea de cada finca, usando la fórmula:

`Ingreso por hectárea = Ingreso total de la finca / Tamaño en hectáreas de la finca`


**Análisis**

Realiza un análisis de negocio de este query. Puedes basarte en estas preguntas para tu análisis:
   - ¿Cómo pueden los administradores de las fincas utilizar este resultado para mejorar la eficiencia de su operación?
   - ¿Qué impacto tiene este análisis en la toma de decisiones relacionadas con el manejo del cultivo o la expansión de la finca?

---

### **Query 2: Comparar el desempeño de los usuarios en términos de recogida vs. el promedio general del lote**

**Instrucciones específicas**:

1. Calcula el promedio de la cantidad de producto recogido en cada lote. El promedio debe ser calculado usando todos los datos de recogida de ese lote.

2. Calcula la diferencia entre la cantidad recogida por cada usuario en un lote y el promedio general de ese lote.

3. Filtra el top 5 de usuarios que más veces hayan superado el promedio de recogida del lote.

**Análisis**

Realiza un análisis de negocio de este query. Puedes basarte en estas preguntas para tu análisis:
   - ¿Cómo pueden los administradores de las fincas utilizar esta información para identificar a los trabajadores más productivos?
   - ¿Qué tipo de estrategias podrían implementarse para incentivar a los trabajadores que consistentemente superan el promedio de recogida?
   - ¿Qué impacto tiene este análisis en la toma de decisiones relacionadas con la gestión del personal y la asignación de recursos?

---

### **Informe Final y calificación:**

Al final de los ejercicios, los estudiantes deberán preparar un informe que incluya los siguientes puntos para cada query:


#### Sección 1:
1. **Código del query y resultado** (15%)
2. **Análisis técnico**: Explica cómo llegaste al query específico, incluyendo cualquier decisión técnica (15%)
3. **Análisis de negocio**: Máximo de 500 palabras por pregunta (20%)

#### Sección 2:
1. **Código del query y resultado** (15%)
2. **Análisis técnico**: Explica cómo llegaste al query específico, incluyendo cualquier decisión técnica (15%)
3. **Análisis de negocio**: Máximo de 500 palabras por pregunta (20%)
