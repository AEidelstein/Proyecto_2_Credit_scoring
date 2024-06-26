# Proyecto_2_Credit_scoring

# Descripción del proyecto

Tu proyecto consiste en preparar un informe para la división de préstamos de un banco. Deberás averiguar si el estado civil y el número de hijos de un cliente tienen un impacto en el incumplimiento de pago de un préstamo. El banco ya tiene algunos datos sobre la solvencia crediticia de los clientes.

Tu informe se tendrá en cuenta al crear una puntuación de crédito para un cliente potencial. Se utiliza una puntuación de crédito para evaluar la capacidad de un prestatario potencial para pagar su préstamo.
# Instrucciones para completar el proyecto

## Paso 1
  Abre el archivo de datos /datasets/credit_scoring_eng.csv  y mira la información general.

## Paso 2
  Preprocesa los datos:

    - Identifica y completa los valores ausentes
    - Reemplaza el tipo de datos de número real con el tipo de número entero
    - Elimina datos duplicados
    - Clasifica los datos

Asegúrate de explicar:

    - Qué valores ausentes identificaste
    - Posibles razones por las que estos valores ausentes estaban allí
    - Qué método utilizaste para completar los valores ausentes
    - Qué método utilizaste para encontrar y eliminar datos duplicados y por qué
    - Posibles razones por las que había datos duplicados
    - Qué método utilizaste para cambiar el tipo de datos y por qué
    - Qué diccionarios has seleccionado para este conjunto de datos y por qué

Los datos pueden contener artefactos o valores que no se corresponden con la realidad (por ejemplo, un número negativo de días empleados). Este tipo de cosas sucede cuando trabajas con datos reales. Debes describir las posibles razones por las que tales datos pueden haber aparecido y procesarlos.

## Paso 3
  Responde estas preguntas:

    - ¿Hay alguna conexión entre tener hijos y pagar un préstamo a tiempo?
    - ¿Existe una conexión entre el estado civil y el pago a tiempo de un préstamo?
    - ¿Existe una conexión entre el nivel de ingresos y el pago a tiempo de un préstamo?
    - ¿Cómo afectan los diferentes propósitos del préstamo al reembolso a tiempo del préstamo?

Interpreta tus respuestas. Explica el significado de los resultados obtenidos.

## Paso 4.
  Escribe una conclusión general.


# Descripción de los datos

    'children' - el número de hijos en la familia
    'days_employed' - por cuánto tiempo ha estado trabajando el cliente
    'dob_years' - la edad del cliente
    'education' - el nivel educativo del cliente
    'education_id' - identificador de la educación del cliente
    'family_status' - estado civil del cliente
    'family_status_id' - identificador del estado civil del cliente
    'gender' - el género del cliente
    'income_type' - el tipo de ingreso del cliente
    'debt' - si el cliente ha incumplido alguna vez un préstamo
    'total_income' - ingresos mensuales
    'purpose' - motivo por el que se solicita un préstamo
