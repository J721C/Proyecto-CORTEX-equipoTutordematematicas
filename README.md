# **Proyecto-CORTEX-equipoTutordematematicas.**
## **Integrantes**
- **Juan Sebastian Lopez Moreno**
- **Joshwann Steven Diaz Santamaria**
- **Leonardo Gomez Sanchez**
# Profesor Universitario de Matematicas.
# Perfil del agente
<img width="1454" height="366" alt="image" src="https://github.com/user-attachments/assets/a79a1d14-e9ea-47a5-b4f4-7944ab97ac68" />

# **El radar Cognitivo**
<img width="684" height="633" alt="image" src="https://github.com/user-attachments/assets/7f957a91-e60c-4c22-9e4d-c499374d03be" />

# 1. Sistema de Percepción y Atención
<img width="1055" height="527" alt="image" src="https://github.com/user-attachments/assets/27a66193-dc0f-434f-8ae6-648b5bdee963" />

## Diagrama
<img width="620" height="858" alt="image" src="https://github.com/user-attachments/assets/4dcae927-f5f3-44f0-be85-150fec433cd7" />

# 2. Arquitectura de Atención con las reglas lógicas definidas.
## Ruido
cualquier información que no aporta directamente a la comprensión o resolución del problema matemático.
Unos ejemplos serian:
- Texto redundante o repetitivo
- Historias personales irrelevantes
- Explicaciones vagas sin contenido matemático
- Lenguaje emocional que no afecta la resolución
- Preguntas múltiples no relacionadas
- Errores tipográficos que dificultan parsing

## Reglas
- Filtrado por longitud, Si el mensaje tiene más de 500 palabras:
- Priorizar: Sustantivos clave, Variables matemáticas, Números y ecuaciones.
- Ignorar: Adjetivos innecesarios, Texto narrativo no técnico
## Regla 2: Detección de intención
- Si hay una pregunta explícita → priorizarla,  Si hay múltiples preguntas → seleccionar la más matemática,  Si no hay pregunta → inferir intención principal.
## Regla 3: Prioridad matemática
 - Detectar y priorizar:
 Ecuaciones,  Símbolos matemáticos,  Expresiones formales, 
 - Reducir peso de:
 Texto descriptivo
## Regla 4: Manejo de ruido emocional
 Detectar emociones (frustración, confusión)
- No ignorarlas completamente, pero:
 Priorizar contenido matemático, Ajustar tono de respuesta
 ## Regla 5: Claridad vs ambigüedad
- Si el problema está incompleto:
 Solicitar información mínima necesaria
- Si está claro:
 Proceder directamente a resolver
## Regla 6: Compresión inteligente
- Resumir el input en:
 Problema central, Datos conocidos, Lo que se pide, Ignorar contenido no esencial
## Regla 7: Contexto acumulado
- Priorizar información reciente, Mantener coherencia con mensajes anteriores,  Evitar repetir explicaciones ya dadas

 # 3. Arquitectura de Memoria
 
|Tipo de Memoria|	Categoría de Datos|	Descripción|	Ejemplo de Entrada|
|---------------|-------------------|------------|-------------------|
|Semántica (LTM)|	Matemáticas Avanzadas	|Teorías, fórmulas y conceptos matemáticos|	"Teorema de Riemann, definición formal"|
|Semántica (LTM)|	Métodos de Enseñanza	|Estrategias pedagógicas para explicar conceptos	|"Uso de analogías para explicar integrales"|
|Episódica (LTM)|	Perfil del Usuario	|Información relevante del estudiante|"Nombre: Ana, Nivel: Universitario"|
|Episódica (LTM)|	Historial de Interacción|	Conversaciones previas importantes	|"Dificultad en cálculo diferencial"|
|Trabajo (RAM)|	Pregunta Actual|	Input actual del usuario|	"¿Cómo resolver esta integral?"|
|Trabajo (RAM)| Contexto Activo|	Información relevante reciente|	"Tema: Integrales por partes"|

# Diagrama
<img width="1616" height="618" alt="image" src="https://github.com/user-attachments/assets/82a5e770-8160-4669-a8f1-4dab9706cb07" />
