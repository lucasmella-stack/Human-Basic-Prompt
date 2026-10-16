# Human Basic Prompt · v0.2.1

Una entrevista breve con tu IA para generar instrucciones sobre cómo comunicarse con vos: qué priorizar, cuánto explicar y cuándo preguntar.

## Probalo

1. Abrí un chat nuevo en tu IA habitual.
2. Copiá y pegá todo el contenido de [interviewer.md](interviewer.md).
3. Respondé la entrevista: hasta 6 respuestas tuyas, adaptadas a lo que ya contaste. Podés escribir «terminar» en cualquier momento.
4. Al terminar, la IA genera un único reporte copiable con tu HBP y lo observado en el test. Revisalo, completá «¿Me representa?» y mandáselo a Lucas por WhatsApp.
5. Para probar el HBP, pegá solo la sección «HBP LISTO PARA USAR» en un chat nuevo con una consulta real. Después podés actualizar la devolución: qué ayudó y qué siguió molestando. [Guía breve](feedback.md).

No hace falta enviar conversaciones completas ni información del trabajo. Revisá lo que compartís y quitá datos personales, de clientes o de la empresa. La IA no envía resultados automáticamente.

## Qué estamos probando

Que una interacción corta permita producir reglas útiles para entender y trabajar con menos esfuerzo. El perfil es provisional y puede cambiar según la tarea, los conocimientos y el tiempo disponible.

Es un prototipo inspirado en evaluación dinámica, evaluación adaptativa y carga cognitiva; todavía no es un instrumento validado. No diagnostica capacidades ni asigna estilos de aprendizaje fijos. La duración real se recogerá en las pruebas.

La primera versión es un prompt portable; no requiere instalar una skill ni modificar AGENTS.md. [Ejemplo ficticio de salida](examples/HBP-example.md).

## Qué cambia en esta versión

Primero recoge actividad, tareas y uso habitual de IA. Después prueba una forma de comunicar adecuada a ese contexto y confirma cuándo sirve y cuándo necesita excepciones. Las horas de uso no se interpretan como cantidad de lectura ni como necesidad automática de respuestas cortas. Desde v0.2.1, la salida incluye un reporte completo en un único bloque para copiar y devolver por WhatsApp.

## Bases del diseño

- [Evaluación dinámica](https://assets.cambridge.org/052184/9357/excerpt/0521849357_excerpt.htm): observar la respuesta a la ayuda.
- [Criterios de cierre en evaluación adaptativa](https://pmc.ncbi.nlm.nih.gov/articles/PMC3028267/): equilibrar precisión y duración.
- [Medición de carga cognitiva](https://pmc.ncbi.nlm.nih.gov/articles/PMC5696680/): distinguir desempeño y esfuerzo percibido.

Estos antecedentes orientan el diseño; no validan por sí solos este procedimiento.
