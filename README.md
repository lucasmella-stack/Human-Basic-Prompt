# Human Basic Prompt · v0.2

Una entrevista breve con tu IA para generar instrucciones sobre cómo comunicarse con vos: qué priorizar, cuánto explicar y cuándo preguntar.

## Probalo

1. Abrí un chat nuevo en tu IA habitual.
2. Copiá y pegá todo el contenido de [interviewer.md](interviewer.md).
3. Respondé la entrevista: hasta 6 respuestas tuyas, adaptadas a lo que ya contaste. Podés escribir «terminar» en cualquier momento.
4. Copiá el HBP generado a un chat nuevo y usalo con una consulta real.
5. Devolvé a Lucas tu HBP y [esta ficha breve](feedback.md). Si podés, compará la misma consulta con y sin HBP en chats separados del mismo modelo.

No hace falta enviar conversaciones completas ni información del trabajo. Revisá lo que compartís y quitá datos personales, de clientes o de la empresa. La IA no envía resultados automáticamente.

## Qué estamos probando

Que una interacción corta permita producir reglas útiles para entender y trabajar con menos esfuerzo. El perfil es provisional y puede cambiar según la tarea, los conocimientos y el tiempo disponible.

Es un prototipo inspirado en evaluación dinámica, evaluación adaptativa y carga cognitiva; todavía no es un instrumento validado. No diagnostica capacidades ni asigna estilos de aprendizaje fijos. La duración real se recogerá en las pruebas.

La primera versión es un prompt portable; no requiere instalar una skill ni modificar AGENTS.md. [Ejemplo ficticio de salida](examples/HBP-example.md).

## Qué cambia en v0.2

Primero recoge actividad, tareas y uso habitual de IA. Después prueba una forma de comunicar adecuada a ese contexto y confirma cuándo sirve y cuándo necesita excepciones. Las horas de uso no se interpretan como cantidad de lectura ni como necesidad automática de respuestas cortas.

## Bases del diseño

- [Evaluación dinámica](https://assets.cambridge.org/052184/9357/excerpt/0521849357_excerpt.htm): observar la respuesta a la ayuda.
- [Criterios de cierre en evaluación adaptativa](https://pmc.ncbi.nlm.nih.gov/articles/PMC3028267/): equilibrar precisión y duración.
- [Medición de carga cognitiva](https://pmc.ncbi.nlm.nih.gov/articles/PMC5696680/): distinguir desempeño y esfuerzo percibido.

Estos antecedentes orientan el diseño; no validan por sí solos este procedimiento.
