# ADR 001: Logging Management Strategy

## Context

[Provide context for the decision, including any constraints or requirements that influenced the decision.]

## Decision

Utiliza niveles de loggeo adecuados para cada caso, es decir (debug, info, warning, error, etc.) para diferenciar la severidad de los mensajes registrados. Esto te permite filtrar y manejar los mensajes según su importancia.

Incluir contexto relevante: como el nombre del flujo, el correlation Id, una marca de tiempo, cabeceras etc. Esto facilita la correlación de eventos y el análisis posterior.

Evita la sobrecarga de loggeo: No registrar excesivamente dado que un exceso de loggs puede dificultar la identificación de los problemas reales. Registra solo la información necesaria para diagnosticar problemas y monitorear el funcionamiento del sistema.

Seguridad de los registros: Asegúrate de proteger adecuadamente tus registros para evitar la divulgación de información sensible. Esto puede incluir técnicas de enmascaramiento o cifrado para proteger datos confidenciales en tus registros.


## Status

[Indicate the current status of the decision, such as "proposed", "accepted", "rejected", "superseded", or "obsolete".]

## Consequences

[Describe the consequences, both positive and negative, of the decision, including any risks or dependencies.]

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
