# Piloto público de aprobación por dos personas

Este repositorio contiene únicamente material ficticio para comprobar controles de revisión. No contiene documentos financieros, enlaces internos, credenciales ni configuración del complemento real.

## Circuito

1. Una persona prepara un cambio en una rama y abre una propuesta (pull request).
2. El revisor designado examina el contenido exacto y aprueba con su propia cuenta.
3. GitHub bloquea la incorporación a `main` hasta cumplir las reglas.
4. Si cambia el contenido después de la aprobación, se debe revisar otra vez.

El revisor designado del piloto es `crvelasquez82`. La incorporación de la persona preparadora está pendiente de que cree y confirme su cuenta.

## Pruebas

- Rechazo de un cambio directo sobre `main` sin revisión.
- Rechazo de una propuesta sin aprobación.
- Rechazo de autoaprobación del autor.
- Incorporación de un cambio preparado por la otra cuenta y aprobado por el revisor.
- Invalidación de la aprobación si hay cambios posteriores.

Solo los tres primeros casos pueden prepararse sin la segunda cuenta. El resultado de las pruebas se registra por separado de la mera configuración de reglas.

## Contenido de prueba

`demo/ejemplo.txt` es el único material funcional de demostración. No importar ni sincronizar este repositorio con el complemento de producción.
