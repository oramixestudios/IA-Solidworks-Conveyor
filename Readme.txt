Este proyecto nace como un primer acercamiento a la integración de Inteligencia Artificial en el diseño CAD. El objetivo inicial fue analizar cómo, a partir de instrucciones escritas, se puede generar un modelo 3D de forma automática.

Durante las pruebas utilizamos Zoo Design Studio (a quien le hemos estado dando seguimiento desde el año 2023), una plataforma que con ciertas instrucciones logra generar modelos en KCL (Knowledge Creation Language). Sin embargo, descubrimos que los resultados iniciales eran muy incompletos y solo representativos: la estructura del conveyor aparecía sin rodillos o con piezas mal posicionadas.
Esto se define y argumenta con bases en la experiencia laboral (mas de 10 años) y conocimiento adquirido en la carrera de Ingeniería mecatrónica

Iteración y correcciones

Se partió de:
Analizar la opción de ayuda con IA dando un Promp claro y completo 

Primero arrojo una estructura incompleta del conveyor (solo largueros y soportes).

Se creó un subensamble de rodillos para intentar complementarlo.

Finalmente, tras muchas horas de ajustes y correcciones en el código KCL, se logró integrar la estructura completa con rodillos, en un modelo paramétrico funcional.

Aprendizajes

La IA todavía no genera modelos CAD completos en Zoo, pero ofrece un punto de partida.

Es posible acelerar el flujo de trabajo si se combina la generación automática con correcciones manuales.

Este tipo de proyectos abre la puerta a que, en un futuro cercano, un ingeniero pueda simplemente dar una instrucción de voz o texto (“diseña un conveyor de 5.5 m de largo con rodillos de 4 pulgadas”) y obtener el modelo 3D listo para producción.

Futuro del proyecto

La visión es conectar estas instrucciones con SolidWorks mediante API o macros para que el diseño se genere en automático, sin necesidad de redibujar cada componente. Esto transformaría la forma en que se realizan cotizaciones y diseños industriales, reduciendo tiempos de horas a minutos.