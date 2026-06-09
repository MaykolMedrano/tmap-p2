# Guion de 35 minutos

Basado en la presentación actual de [slide.tex](C:/Users/horio/OneDrive/Desktop/PPT/slide.tex) y en el texto del paper [9b44a171-0b11-4934-8139-812bee0932fe.tex](C:/Users/horio/OneDrive/Desktop/PPT/paper/9b44a171-0b11-4934-8139-812bee0932fe.tex).

## Idea general

La narrativa de la exposición tiene que ser esta:

1. Los autores buscan medir el costo económico del conflicto vasco.
2. El problema es que no existe un contrafactual observable y España no sirve como comparación simple.
3. La contribución central es construir un contrafactual creíble con `synthetic control`.
4. El resultado principal se presenta como una brecha persistente de alrededor de `10%` en PIB per cápita.
5. El `event study` de la tregua de `1998--1999` no reemplaza al control sintético; aporta evidencia complementaria.
6. El paper es fuerte, pero no inmune a críticas: estructura industrial, crisis del petróleo y credibilidad del contrafactual.

## Distribución del tiempo

- `0:00--2:00`: portada + outline
- `2:00--8:00`: motivación, pregunta y contexto
- `8:00--22:00`: núcleo del `synthetic control`
- `22:00--30:00`: tregua y `event study`
- `30:00--35:00`: aporte, limitaciones y cierre

## Guion por diapositiva

### 1. Portada
`0:00--0:30`

Guion sugerido:

> Hoy voy a presentar *The Economic Costs of Conflict: A Case Study of the Basque Country*, de Abadie y Gardeazabal, publicado en 2003 en el *American Economic Review*. El paper estudia una pregunta muy concreta: si el conflicto político y, en particular, el terrorismo de ETA, es decir, *Euskadi Ta Askatasuna*, una organización separatista vasca, tuvo un costo económico observable sobre el País Vasco.

**Transición a la siguiente diapositiva:**
> Para ordenar la exposición, primero les muestro brevemente la ruta que voy a seguir.

### 2. Outline
`0:30--1:30`

Guion sugerido:

> La presentación tiene cuatro partes. Primero, explico la pregunta y por qué este caso es difícil de estudiar. Segundo, desarrollo la estrategia principal del paper, que es el `synthetic control`. Tercero, muestro la evidencia complementaria de la tregua de 1998--1999 usando `event study`. Y al final cierro con aporte, limitaciones y conclusiones.

**Transición a la siguiente diapositiva:**
> Con esa hoja de ruta clara, parto por la motivación general del paper.

### 3. Motivación
`1:30--2:30`

Guion sugerido:

> La intuición de fondo parece obvia: más violencia debería dañar la economía. Pero empíricamente eso es difícil de demostrar, porque la violencia no es un shock puramente exógeno. Puede estar ligada a tensiones previas, a diferencias institucionales o a características productivas del territorio. Entonces, el desafío no es solo documentar que hay violencia y bajo crecimiento, sino construir una comparación creíble.

**Transición a la siguiente diapositiva:**
> Una vez planteado el problema, la pregunta concreta del paper es la siguiente.

### 4. Pregunta de investigación
`2:30--3:30`

Guion sugerido:

> La pregunta central es: ¿cómo habría evolucionado la economía del País Vasco en ausencia de terrorismo? Ese es el contrafactual relevante, y por definición no lo observamos. El paper responde esa pregunta principalmente con `synthetic control`, y luego contrasta esa historia con evidencia financiera durante la tregua.

**Transición a la siguiente diapositiva:**
> Antes de entrar al método, vale la pena explicar por qué este caso es especialmente interesante.

### 5. Por qué este paper es interesante
`3:30--4:30`

Guion sugerido:

> Este caso es interesante por dos razones. Primero, porque el País Vasco no era una región pobre o rezagada antes del conflicto; al contrario, era una región rica e industrializada, lo que descarta que la violencia sea un mero síntoma de pobreza previa. Segundo, porque este es el paper fundacional que introdujo el método de `synthetic control` en la econometría, cambiando la forma en que estudiamos shocks agregados.

**Transición a la siguiente diapositiva:**
> Con eso en mente, paso ahora al contexto histórico del conflicto.

### 6. Contexto histórico
`4:30--5:30`

Guion sugerido:

> ETA, sigla de *Euskadi Ta Askatasuna*, es una organización separatista vasca fundada en 1959. La violencia a gran escala se intensifica realmente a fines de los 60 y, sobre todo, durante los 70. El punto importante para nosotros es que no se trata de hechos aislados, sino de un conflicto persistente, concentrado territorialmente y con capacidad de afectar inversión, decisiones empresariales y expectativas.

**Transición a la siguiente diapositiva:**
> Ese contexto se entiende mejor cuando uno mira qué tan concentrada estuvo la violencia.

### 7. Algunas cifras del conflicto
`5:30--6:30`

Guion sugerido:

> Esta diapositiva sirve para mostrar que el shock está muy concentrado. Según la tabla, cerca de `69%` de las muertes causadas por ETA ocurrieron en el País Vasco, y en términos per cápita la tasa fue aproximadamente `37` veces mayor que en el resto de España. Eso sugiere que estamos frente a un shock territorialmente localizado.

**Transición a la siguiente diapositiva:**
> Pero que el shock esté concentrado no basta; todavía queda el problema de la comparación.

### 8. Por qué no basta comparar con el resto de España
`6:30--7:30`

Guion sugerido:

> El problema es que el País Vasco ya era distinto antes del terrorismo. Tenía más ingreso, más inversión, mayor densidad y una estructura industrial distinta. Entonces, comparar País Vasco versus España mezclaría el efecto del conflicto con diferencias previas de crecimiento. Por eso el paper necesita un contrafactual mejor que el promedio nacional.

**Transición a la siguiente diapositiva:**
> Justamente por esa dificultad, el paper necesita una estrategia de identificación más cuidadosa.

### 9. Estrategia de identificación
`7:30--8:30`

Guion sugerido:

> La identificación del paper descansa en dos diseños. El principal es el `synthetic control`, que busca medir el efecto de largo plazo sobre el PIB regional. El segundo usa la tregua de `1998--1999` como experimento natural para ver si el mercado valora más a las firmas expuestas al País Vasco cuando la paz parece creíble. Mi lectura, y la del propio paper, es que el corazón está en el primer diseño.

**Transición a la siguiente diapositiva:**
> De las dos estrategias, la central es el `synthetic control`, así que empiezo por ahí.

### 10. Estrategia empírica 1
`8:30--9:30`

Guion sugerido:

> La idea del control sintético es conceptualmente simple. Se construye un "País Vasco sintético" como una combinación de otras regiones españolas que se parezcan al País Vasco antes del terrorismo. Si antes del shock ambas trayectorias son similares y luego divergen, los autores interpretan esa divergencia como evidencia consistente con un costo económico del conflicto.

**Transición a la siguiente diapositiva:**
> La intuición ya la vimos; ahora veamos cómo se construye ese contrafactual en la práctica y cómo se resume en una formulación mínima.

### 11. Cómo se arma el control sintético
`9:30--12:00`

Guion sugerido:

> Para armar el sintético, los autores usan predictores pretratamiento asociados al potencial de crecimiento: PIB per cápita, razón de inversión, densidad poblacional, estructura sectorial y capital humano. El `donor pool` está compuesto por las otras `16` regiones españolas disponibles como controles, excluyendo al País Vasco. Dentro de ese conjunto, el algoritmo elige pesos no negativos para minimizar la distancia respecto del País Vasco. En la práctica, los pesos óptimos recaen sobre todo en `Cataluña` y `Madrid`: aproximadamente `0.8508` y `0.1492`, respectivamente.

> Esto parece razonable porque ambas regiones compartían con el País Vasco altos niveles de ingreso y urbanización. Pero ya aquí aparece una limitación: el ajuste no es perfecto, especialmente en la intensidad industrial, porque el País Vasco era la región más industrializada de todas.

> La formulación del método es esta. `X_1` contiene los predictores pretratamiento del País Vasco; `X_0` contiene esos mismos predictores para las regiones donantes; `W` es el vector de pesos; y `V` es una matriz diagonal que le da importancia relativa a cada predictor. Un detalle clave es que empíricamente `V` se elige de forma iterativa para que el control sintético minimice el error de predicción sobre la trayectoria del PIB per cápita *antes* del tratamiento.

> Una vez elegidos esos pesos, se usa la combinación ponderada de regiones donantes para construir la trayectoria contrafactual `Y_1^*`. Lo importante en la presentación no es la notación en sí misma, sino la lógica: aproximar un contrafactual no observado con una región artificial pero comparable.

**Transición a la siguiente diapositiva:**
> Más allá de la notación, lo importante es por qué este ejercicio resulta creíble.

### 12. Por qué esta estrategia es creíble
`12:30--13:30`

Guion sugerido:

> La credibilidad del método no descansa en asumir que el terrorismo cayó del cielo como un shock puramente exógeno. Más bien, la fortaleza está en que, al replicar la trayectoria previa, el sintético absorbe shocks comunes y heterogeneidad no observada. Si antes de `1975` ambas series se comportan parecido, es mucho más creíble usar esa región artificial como referencia contrafactual para el período posterior.

**Transición a la siguiente diapositiva:**
> Si aceptamos esa lógica, entonces podemos mirar el resultado principal del paper.

### 13. Resultado principal 1: PIB per cápita
`13:30--14:30`

Guion sugerido:

> Los autores estiman que, desde mediados de los 70, el PIB per cápita del País Vasco cae por debajo del sintético. La brecha alcanza valores cercanos a `12%` y, en promedio, ronda `10%` durante los 80 y 90. Esa es la estimación más citada del paper.

**Transición a la siguiente diapositiva:**
> Y ese resultado se ve con mucha claridad en la figura central del artículo.

### 14. Figura 1: el resultado central
`14:30--16:00`

Guion sugerido:

> Esta es probablemente la figura más importante de toda la presentación. Hasta `1975`, el País Vasco real y el sintético se mueven de forma muy parecida. Desde `1975`, cuando la actividad terrorista pasa a ser un fenómeno de gran escala, ambas trayectorias divergen. La figura sugiere visualmente el efecto que los autores estiman.

> Si quieres resumir esta figura en una frase: antes del shock, las trayectorias coinciden; después, se abre una brecha persistente.

**Transición a la siguiente diapositiva:**
> El paper no se queda solo con esa brecha promedio; también estudia cómo cambia con la violencia.

### 15. Intensidad del terrorismo y brecha de PIB
`16:00--17:30`

Guion sugerido:

> El siguiente paso del paper es ver si la brecha de PIB se mueve junto con la intensidad de la violencia. Y la figura sugiere exactamente ese patrón: cuando la actividad terrorista aumenta, la brecha tiende a ampliarse. Esto no prueba por sí solo causalidad, pero sí hace más plausible la interpretación de que la brecha no es un artefacto puramente mecánico del método.

**Transición a la siguiente diapositiva:**
> Además, los autores intentan mostrar que ese efecto no es solo contemporáneo, sino dinámico.

### 16. Figura 3: respuesta dinámica
`17:30--18:30`

Guion sugerido:

> Esta figura añade una dimensión dinámica. El efecto del terrorismo sobre la brecha del PIB no parece instantáneo, sino rezagado. El impacto máximo aparece alrededor de `2` a `3` años después y luego se va disipando gradualmente. Eso es consistente con la idea de que la violencia afecta inversión y actividad económica con cierto desfase.

**Transición a la siguiente diapositiva:**
> Hasta aquí vimos el resultado principal; ahora viene una validación clave del método.

### 17. Placebo con Cataluña
`18:30--20:00`

Guion sugerido:

> Aquí el paper hace algo muy importante para la credibilidad del método: un placebo. Aplica la misma lógica a Cataluña, una región comparable en varios aspectos, pero sin una escalada similar de terrorismo. La pregunta es si el método produciría una brecha artificial incluso donde no debería hacerlo.

> El resultado placebo no reproduce una brecha prolongada como la del País Vasco. Eso hace más plausible la interpretación causal del ejercicio principal. Al mismo tiempo, el paper reconoce que Cataluña tuvo un desempeño especialmente fuerte en los 90, asociado entre otras cosas a los Juegos Olímpicos de Barcelona de `1992`, y eso incluso podría exagerar un poco la brecha del País Vasco en la parte final de la muestra.

**Transición a la siguiente diapositiva:**
> Una vez mostrado el resultado y su validación, vale la pena preguntarse por qué canales podría operar ese efecto económico.

### 18. Mecanismos plausibles
`20:00--21:00`

Guion sugerido:

> Aquí conviene hacer una distinción fina. El paper estima un efecto agregado sobre el PIB, pero no identifica causalmente cada mecanismo por separado. Aun así, los autores discuten tres canales plausibles: primero, la violencia y la extorsión directa contra empresarios y firmas; segundo, la salida de empresarios del País Vasco para escapar de secuestros o amenazas, lo que implica pérdida de capital humano empresarial; y tercero, el efecto disuasivo sobre la inversión doméstica y extranjera por riesgo e inseguridad.

> Esta slide sirve para interpretar la brecha de PIB: no estamos diciendo que el paper prueba cada canal individualmente, sino que muestra un efecto agregado consistente con estos mecanismos.

**Transición a la siguiente diapositiva:**
> Además de esta interpretación económica, el paper aporta una segunda fuente de evidencia desde el mercado bursátil.

### 19. Por qué mirar la tregua
`22:00--22:30`

Guion sugerido:

> Hasta aquí, la evidencia central viene del PIB regional. La segunda parte del paper cambia de margen: en vez de mirar crecimiento de largo plazo, mira cómo reaccionan los mercados cuando cambia la credibilidad de la paz.

**Transición a la siguiente diapositiva:**
> Esa segunda estrategia se apoya en un episodio político muy concreto: el alto al fuego de ETA entre 1998 y 1999.

### 20. La tregua de 1998--1999
`22:30--23:30`

Guion sugerido:

> Antes de hablar de bolsa, conviene ubicar bien el episodio. ETA declara un alto al fuego en septiembre de `1998` y lo rompe en noviembre de `1999`. Al comienzo, esa tregua no se percibe como plenamente creíble; de hecho, hay bastante escepticismo. La gracia del episodio es que, a medida que avanzan los meses, aparecen señales que hacen subir o bajar la probabilidad de paz. Eso es justamente lo que los autores explotan en el `event study`.

> La intuición entonces es simple: si el conflicto realmente dañaba la economía vasca, las firmas expuestas al País Vasco deberían apreciarse relativamente cuando la tregua gana credibilidad y caer cuando el proceso de paz colapsa.

**Transición a la siguiente diapositiva:**
> A partir de esa tregua, el paper construye el diseño empírico del `event study`.

### 21. Diseño del event study
`23:30--24:30`

Guion sugerido:

> El diseño compara un portafolio de firmas "vascas", es decir, con exposición económica importante al País Vasco, con un portafolio de firmas no vascas. Un punto delicado del paper es justamente esa clasificación, porque no se basa solo en dirección legal, sino en el juicio de analistas de mercado sobre exposición económica real.

**Transición a la siguiente diapositiva:**
> Con ese diseño en mente, ahora sí podemos mirar la ecuación y su interpretación.

### 22. Event study: ecuación e interpretación
`24:30--26:00`

Guion sugerido:

> Como la tregua se desarrolla de forma gradual durante `14` meses, el paper no usa una ventana cortísima como en un event study tradicional. En cambio, parte de un modelo tipo Fama-French para portafolios `Basque` y `non-Basque`, y luego agrega dos dummies: `Good News` y `Bad News`.

> Más precisamente, el paper parte estimando esa ecuación para dos portafolios por separado, `Basque` y `non-Basque`. Luego, en `Table 6`, agrega las dummies `Good News` y `Bad News` a esa especificación y además reporta una `difference regression` en la última columna, que resume el retorno relativo `Basque - non-Basque`.

> Aquí conviene hacer una aclaración verbal muy simple: cuando el paper habla de `sesiones`, se refiere a `sesiones bursátiles`, es decir, días en que la bolsa está abierta y podemos observar retornos accionarios.

> `Good News` cubre `22` sesiones bursátiles, desde que la tregua gana credibilidad hasta que el gobierno autoriza contactos con ETA. `Bad News` cubre `66` sesiones, desde el deterioro del proceso hasta el fin de la tregua. Para la exposición, conviene poner el foco en esa columna diferencial, pero sin perder de vista que el paper primero estima ambos portafolios por separado.

**Transición a la siguiente diapositiva:**
> Una vez entendida la especificación, pasemos al resultado principal de esta segunda estrategia.

### 23. Resultado principal 2
`26:00--27:00`

Guion sugerido:

> Los resultados van en la dirección esperada. Las firmas expuestas al País Vasco muestran mejor desempeño relativo durante las buenas noticias y peor desempeño relativo durante las malas noticias. Eso es consistente con la idea de que el mercado valora económicamente la paz.

**Transición a la siguiente diapositiva:**
> Ese resultado también se puede ver visualmente en la trayectoria de los retornos acumulados.

### 24. Figura 6: retornos anormales acumulados
`27:00--28:30`

Guion sugerido:

> Esta figura resume visualmente esa historia. Durante la tregua, el portafolio vasco tiende a superar al no vasco a medida que la paz se vuelve más creíble. Y al final del proceso esa ganancia relativa se revierte. Lo atractivo de esta figura es que sugiere que el mercado no reacciona solo al anuncio inicial, sino a la evolución de la credibilidad del proceso.

**Transición a la siguiente diapositiva:**
> Y además de la figura, conviene mirar la magnitud económica de esos efectos.

### 25. Magnitud de los efectos bursátiles
`28:30--30:00`

Guion sugerido:

> En términos acumulados, el paper encuentra una rentabilidad anormal compuesta de aproximadamente `10.14%` durante el periodo de `Good News` y de `-11.21%` durante el periodo de `Bad News` para el portafolio vasco relativo al no vasco. Son magnitudes económicamente grandes y muy difíciles de explicar solo por azar, por lo que esta segunda estrategia funciona excepcionalmente bien como respaldo al argumento principal de que el conflicto tiene un costo real medible.

**Transición a la siguiente diapositiva:**
> Con ambas estrategias sobre la mesa, ya podemos sintetizar el aporte general del paper.

### 26. Aporte del paper
`30:00--31:00`

Guion sugerido:

> El aporte del paper es doble. Sustantivamente, entrega evidencia muy convincente de que el conflicto político tuvo costos económicos severos. Pero metodológicamente su aporte es histórico: este es el paper fundacional que introdujo el método de `synthetic control` a la econometría aplicada, ofreciendo una forma sistemática y transparente de construir un contrafactual cuando los métodos tradicionales no son viables.

**Transición a la siguiente diapositiva:**
> Pero antes de cerrar, vale la pena dejar explícitas las principales limitaciones.

### 27. Limitaciones
`31:00--33:00`

Guion sugerido:

> La limitación más importante es que el control sintético no reproduce perfectamente la estructura industrial del País Vasco, justo en un contexto de crisis industrial y crisis del petróleo. Entonces, parte de la brecha podría estar recogiendo algo más que terrorismo.

> Una segunda limitación es que el ejercicio bursátil depende de una clasificación no totalmente objetiva de firmas vascas y no vascas. Y una tercera es la validez externa: es un caso muy específico, con una historia política e institucional muy particular.

**Transición a la siguiente diapositiva:**
> Teniendo presentes esas reservas, ahora sí cierro con la idea principal que me gustaría que quedara.

### 28. Conclusiones
`33:00--34:30`

Guion sugerido:

> Si tuviera que resumir el paper en una sola idea, diría lo siguiente: la contribución central no es solo mostrar que ETA fue costosa, sino hacer visible un contrafactual razonable. El `synthetic control` permite comparar al País Vasco con una región artificial creíble, y esa comparación sugiere una pérdida persistente de alrededor de `10%` en PIB per cápita.

> La evidencia de la tregua no reemplaza ese hallazgo, pero sí lo complementa: cuando la paz parece creíble, las firmas expuestas al País Vasco tienden a valorizarse relativamente; cuando la tregua colapsa, registran pérdidas relativas.

**Transición a la siguiente diapositiva:**
> Con esa conclusión, termino dejando la referencia del artículo.

### 29. Referencia
`34:30--35:00`

Guion sugerido:

> Muchas gracias. Si quieren, después podemos discutir tanto la parte metodológica del `synthetic control` como las principales dudas de identificación del paper.

## Frases cortas para usar durante preguntas

### Si te preguntan por qué no basta comparar con España

> Porque el País Vasco ya partía desde otro nivel de ingreso, industrialización e inversión. El problema no es solo encontrar un control, sino uno que se parezca antes del conflicto.

### Si te preguntan desde cuándo se ve el efecto

> En la `Figure 1` la divergencia empieza a verse desde `1975`; después la brecha se vuelve persistente.

### Si te preguntan cuál es la región sintética

> Principalmente una combinación de `Cataluña` y `Madrid`, con pesos aproximados de `0.85` y `0.15`.

### Si te preguntan por la principal debilidad

> Una de las principales debilidades es que el País Vasco tenía una estructura industrial muy particular y eso coincide con una etapa de crisis industrial y del petróleo.

### Si te preguntan por qué el event study no es el centro del paper

> Porque la contribución principal del artículo es el contrafactual de largo plazo construido con `synthetic control`; el ejercicio bursátil funciona más como validación complementaria.

## Consejo final de exposición

No intentes decir todo lo que está en las diapositivas. En esta presentación conviene repetir tres ideas una y otra vez:

1. `El problema es el contrafactual.`
2. `El synthetic control es el corazón del paper.`
3. `La tregua aporta respaldo adicional, pero no reemplaza, el resultado principal.`
