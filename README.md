
# MiBancaEnLinea

## Resumen
Este ejercicio está diseñado para probar su capacidad para crear un API RESTful para la gestión de transferencias entre cuentas bancarias. Se le pedirá que cree "endpoints" que permitan a los usuarios agregar depósitos, crear retiros y transferir dinero entre cuentas. También deberá implementar un proceso para calcular el interés diario sobre los saldos de las cuentas.

## Criterios de aceptación
- Cree un API RESTful que permita a los usuarios:
	- Obtener información de la cuenta bancaria, incluido el saldo actual, la lista de transacciones y los intereses devengados.
	- Agregar depósitos a una cuenta.
	- Crear retiros desde una cuenta.
	- Transferir dinero entre cuentas.

**Bonus: Proceso de diseño**

> Implementar la función de interés diario: cree una función que se
> ejecute diariamente para calcular el interés ganado por cada titular
> de cuenta. 
> 
> También deberá crear una tabla de base de datos que lleve el histórico
> de saldos de la cuenta, la tasa de interés y la fecha del último
> cálculo de intereses. 
> 
> La función debe calcular el interés ganado desde la última fecha de
> cálculo y actualizar el saldo de la cuenta en consecuencia.

## Instrucciones

- Implementar la API RESTful según los criterios de aceptación.
- Cree un repositorio en GitHub. Deberá entregar su implementación a través de éste medio. El repositorio deberá ser publico. 
- Utilice .Net 8 y C#.
- Utilice SQL Server para almacenar la información. No hay requisito de una versión en particular.
- Utilice Procedimientos Almacenados para la programación de la lógica de transferencia entre cuentas.
- A su discreción el uso de código C# o Procedimientos Almacenados para la consulta de saldos, agregar depósitos y crear retiros.
- Diseñe y cree las tablas de base de datos necesarias para cumplir con los criterios de aceptación.
- Puede utilizar cualquier librería para interactar con la base de datos. No es requisito utilizar una librería tipo ORM pero lo puede hacer.
- Incluya los Scripts de creación de la base de datos en el repositorio y cualquier otro archivo necesario relacionado a la base de datos.
- **Bonus!** *Implemente el proceso de cálculo de intereses diario (consulte la sección de bonus más arriba).*
- **Bonus!** *Escriba pruebas para su implementación.*


## Criterios de evaluación

- La implementación debe cumplir con todos los criterios de aceptación enumerados anteriormente.
- El código debe estar bien organizado y ser fácil de leer.
- Utilice convenciones de nomenclatura adecuadas para variables, funciones y "endpoints".
- El código debe estar bien documentado con comentarios claros y/o archivos README.
- Aunque se trata de un ejercicio, la implementación debe intentar ser segura y proteger contra vulnerabilidades comunes como la inyección SQL y los ataques XSS.
- La solución deberá compilar al descargarla localmente.

## Notas

- Concéntrese en el diseño de la solución, la calidad del código, el uso de buenas prácticas de programación y recomendaciones en la creación de RESTApis y la mantenibilidad mientras resuelve el problema.
- Las secciones Bonus son opcionales: no sacrifique una entrega de calidad en los otros criterios de aceptación por la intención de entregar la completitud de la prueba.
- Puede entregar secciones incompletas, estamos interesados en conocer su forma de razonar y diseñar aunque sea parcial la entrega.
- Las operaciones son en una sola moneda: colones.
