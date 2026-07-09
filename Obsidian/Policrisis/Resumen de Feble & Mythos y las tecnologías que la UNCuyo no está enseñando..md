
---
Por **Ricardo R. Palma** 
para themys.sid.uncu.edu.ar



## El veto a Anthropic y los límites de la interdependencia militarizada"

En junio de 2026, el gobierno de Estados Unidos emitió una orden de control de exportaciones sin precedentes. En lugar de apuntar a componentes físicos como semiconductores, la restricción prohibió el acceso directo a los modelos de inteligencia artificial _Fable 5_ y _Mythos 5_ de Anthropic a cualquier ciudadano extranjero, incluidos los propios empleados de la compañía. Ante la imposibilidad técnica de segmentar a sus usuarios de inmediato, Anthropic desactivó globalmente ambos modelos. Este hecho transformó el software (servido mediante APIs y cuentas en la nube) en un artículo regulado por seguridad nacional, alterando las dinámicas de control tecnológico tradicionales.

---

## La teoría de la interdependencia militarizada

El análisis se fundamenta en la teoría de Henry Farrell y Abraham Newman, que explica cómo los Estados transforman la centralidad económica y de red en palancas de influencia geopolítica. Esta dinámica opera mediante dos mecanismos principales:

1. El efecto panóptico: Capacidad de extraer información estratégica de los flujos que cruzan un nodo central.
2. El efecto de estrangulamiento (_chokepoint_): Capacidad de denegar el acceso a la infraestructura de la red.

Históricamente, Estados Unidos ha explotado su jurisdicción sobre nodos clave como el sistema ==SWIFT o el dólar==. No obstante, el caso de Anthropic expone una fase reflexiva: el uso excesivo o impreciso de estas herramientas puede socavar la previsibilidad y la estabilidad del propio centro que se busca proteger.

---

## El problema de la falta de discriminación

La efectividad de un punto de estrangulamiento radica en su selectividad. Sin embargo, la orden contra Anthropic aplicó un filtro generalizado basado en la nacionalidad que afectó simultáneamente a adversarios, aliados comerciales, usuarios comunes y personal interno de la empresa.

Esta falta de discriminación generó severas fricciones internacionales y domésticas:

- **Reacción de los aliados:** Líderes del G7, como el presidente francés Emmanuel Macron, criticaron la naturaleza discriminatoria de la medida, mientras que funcionarios europeos y canadienses advirtieron sobre los peligros de depender de la discrecionalidad administrativa de Washington.
- **Quiebre del enfoque tradicional:** La estrategia previa de _"patio pequeño, valla alta"_ pretendía proteger tecnologías críticas sin aislar a los socios comerciales. Al trasladarse el objeto de control a un servicio en la nube multinacional, la valla regulatoria terminó rodeando a todos.
- **Dimensión interna:** El veto coincidió con tensiones entre Anthropic y la administración Trump respecto al uso de IA en sistemas de armas autónomos, evidenciando que estas restricciones externas también se entrelazan con la gobernanza de actores privados locales.

Al no poder separar eficientemente a amigos de enemigos, el centro tecnológico norteamericano proyectó una imagen de inestabilidad regulatoria, incentivando a los usuarios globales a buscar alternativas fuera de su jurisdicción.

---

## La difusión de modelos abiertos como contra-estrangulamiento

La coerción estatal genera respuestas adaptativas. En el ecosistema de la inteligencia artificial, la respuesta más contundente no ha sido la creación de nuevos modelos cerrados, sino la difusión masiva de modelos de código abierto (_open-weight_) impulsados por firmas chinas como ==Alibaba (Qwen), DeepSeek, Moonshot, MiniMax y Zhipu==.

A diferencia de la estrategia estadounidense, basada en el control continuo del acceso a servidores remotos, la estrategia china distribuye libremente los pesos y herramientas de los modelos. Esto permite a desarrolladores de todo el mundo localizar, ajustar y ejecutar workloads en infraestructuras propias, trasladando la dependencia desde una cuenta comercial hacia un ecosistema comunitario de desarrollo.

Indicadores de plataformas como ==OpenRouter y Hugging Face== reflejan el impacto de este fenómeno:

- En mayo de 2026, los modelos abiertos chinos procesaban el <u>61% de los tókenes</u> enrutados en OpenRouter.
- China superó a Estados Unidos en descargas mensuales y globales dentro de Hugging Face.
- Informes oficiales estadounidenses (como _Two Loops_) confirman que el bajo costo y la apertura de los laboratorios chinos generan un bucle donde la adopción global acelera la optimización del software.

Para gobiernos, empresas medianas y universidades, la disponibilidad y la previsibilidad política se han convertido en características geopolíticas cruciales. Si un modelo estadounidense de frontera puede desactivarse unilateralmente por una decisión en Washington, las alternativas abiertas ganan valor estratégico inmediato, aunque su rendimiento técnico sea ligeramente inferior.  ==Esto constituye una oportunidad para Latinoamérica y Caribe== porque tiene población joven (si bien el nucle familiar se ha establecido en 2,8 personas por familia y menos del 60% en un mismo hogar) y porque conserva un sistema educativo que resiste los embates a en los que la región está sumergida hace décadas, sin perder calidad educativa.
Esto neutraliza el poder del "interruptor" norteamericano: Estados Unidos puede retener el techo de calidad y de ingresos, pero la capa operativa del desarrollo global migra hacia arquitecturas descentralizadas.

---

## Conclusión y preguntas pendientes

El episodio de Anthropic demuestra que poseer una palanca de interdependencia y usarla de manera efectiva son dos capacidades distintas. Cuando un punto de estrangulamiento es incapaz de discriminar entre riesgos legítimos y usuarios comerciales aliados, deja de ser un bisturí político para convertirse en un riesgo sistémico que explicita la vulnerabilidad de depender de un único nodo central. Es como si un neurocirujano entrase al quirófano con un hacha.

La teoría de las relaciones internacionales se enfrenta ahora a una nueva interrogante: evaluar cuándo el ejercicio agresivo del poder de red precipita la fuga de usuarios, la desconfianza institucional y la descentralización tecnológica. El límite fundamental de la interdependencia militarizada no radica en su capacidad para obligar o coaccionar, sino en los severos costos sistémicos que acarrea el ejercer dicha coerción de forma demasiado amplia.

---

## ¿Que deberíamos enseñar sin perder más tiempo?

Para que un estudiante universitario explote al máximo el potencial de la inteligencia artificial actual (tanto modelos cerrados comerciales como modelos abiertos distribuidos), debe dominar un ecosistema de herramientas que resuelvan tres necesidades clave: ==acceso y pruebas rápidas, cómputo en la nube y desarrollo/despliegue local.==

Aquí tenés la lista de las herramientas esenciales clasificadas por su función y el motivo de su importancia:

## 🌐 Hubs de Modelos y Comunidad (El punto de partida)

- Hugging Face: Es el ecosistema central y "registro universal" de la IA de código abierto. Un estudiante debe aprender a navegar por él para descargar pesos de modelos (LLMs, generación de imágenes, audio), leer documentación técnica, usar sus librerías (`transformers`, `diffusers`) y explorar _Spaces_ (demos en vivo creadas por otros desarrolladores).
- Civitai: La plataforma de referencia absoluta para modelos de difusión y generación de imágenes/video (especialmente derivados de Stable Diffusion). Es clave para aprender sobre _Checkpoints_, _LoRAs_ (micro-entrenamientos para estilos específicos) y técnicas de control visual preciso como _ControlNet_.

## 💻 Entornos de Ejecución e Infraestructura (Cómputo en la nube)

- Google Colab: La herramienta de cabecera para estudiantes porque permite ejecutar código de Python en un navegador web y ofrece acceso gratuito (y opciones de pago accesibles) a GPUs de Google. Es indispensable para probar código de repositorios de GitHub, correr cuadernos de Jupyter ==(_Jupyter Notebooks y R-Cran_)== y experimentar con modelos medianos sin depender del hardware de una computadora personal.
- Kaggle: Propiedad de Google, ofrece cuadernos en la nube similares a Colab, pero con un beneficio crítico: otorga hasta 30 horas semanales de uso gratuito de GPUs duales (T4). Además, aloja una de las bases de datos públicas y competencias de ciencia de datos más grandes del mundo.
- RunPod / Vast.ai: Plataformas de alquiler de GPUs en la nube por hora a precios muy bajos (centavos de dólar). Un estudiante avanzado debe conocerlas para cuando los límites gratuitos de Google Colab no alcancen para entrenar un modelo propio o ejecutar arquitecturas muy pesadas.

## 🔌 Agregadores y APIs de Consumo Avanzado (Acceso multimodelo)

- OpenRouter: Una plataforma crucial que unifica docenas de los modelos de lenguaje más potentes del mundo (tanto cerrados como _Anthropic_ u _OpenAI_, y abiertos como _Llama_ o _Qwen_) bajo una única API. Permite a los estudiantes comparar rendimientos, costos de procesamiento (tókenes) y velocidades en tiempo real en una misma interfaz.
- DeepInfra / Together AI: Proveedores de servicios de inferencia que permiten consumir los modelos de código abierto más populares a velocidades extremas y costos mínimos mediante API, ideal para integrar IA en proyectos de software universitarios sin necesidad de hostear el modelo uno mismo.

## 🏠 Interfaces y Ejecución Local (Privacidad y soberanía de datos)

- Ollama: Una herramienta de terminal que permite descargar y ejecutar modelos de lenguaje (como Llama 3 o Mistral) de forma 100% local, privada y sin conexión a Internet en la computadora del usuario. Es fundamental para aprender a optimizar recursos mediante la cuantización (reducción del peso del modelo para que quepa en memoria de consumo).
- LM Studio / AnythingLLM: Interfaces gráficas de usuario (GUI) amigables que se conectan a motores locales como Ollama. Permiten crear un clon privado de ChatGPT en la computadora del estudiante y aplicar técnicas de RAG (Generación Aumentada por Recuperación), es decir, subirle archivos PDF personales, libros o apuntes de la facultad para que el modelo responda basándose estrictamente en esos documentos.
- ComfyUI / Automatic1111: Las interfaces definitivas para la generación y edición avanzada de imágenes mediante IA. Dominar ComfyUI (que funciona mediante un sistema de nodos y flujo de datos visual) enseña a los estudiantes la lógica técnica exacta de cómo operan los modelos de difusión por dentro.

---
