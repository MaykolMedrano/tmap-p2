# Guion de 35 minutos

Basado en la presentaci\'on actual de [slide.tex](C:/Users/horio/OneDrive/Desktop/PPT/slide.tex) y en el texto del paper [9b44a171-0b11-4934-8139-812bee0932fe.tex](C:/Users/horio/OneDrive/Desktop/PPT/paper/9b44a171-0b11-4934-8139-812bee0932fe.tex).

## Idea general

La narrativa de la exposici\'on tiene que ser esta:

1. El paper quiere medir el costo econ\'omico del conflicto vasco.
2. El problema es que no existe un contrafactual observable y Espa\~na no sirve como comparaci\'on simple.
3. La contribuci\'on central es construir un contrafactual cre\'ible con `synthetic control`.
4. El resultado principal es una brecha persistente de alrededor de `10%` en PIB per c\'apita.
5. El `event study` de la tregua de `1998--1999` no reemplaza al control sint\'etico; lo complementa.
6. El paper es fuerte, pero no inmune a cr\'iticas: estructura industrial, crisis del petr\'oleo y credibilidad del contrafactual.

## Distribuci\'on del tiempo

- `0:00--2:00`: portada + outline
- `2:00--8:00`: motivaci\'on, pregunta y contexto
- `8:00--22:00`: n\'ucleo del `synthetic control`
- `22:00--30:00`: tregua y `event study`
- `30:00--35:00`: aporte, limitaciones y cierre

## Guion por diapositiva

### 1. Portada
`0:00--0:30`

Guion sugerido:

> Hoy voy a presentar *The Economic Costs of Conflict: A Case Study of the Basque Country*, de Abadie y Gardeazabal, publicado en 2003 en el *American Economic Review*. El paper estudia una pregunta muy concreta: si el conflicto pol\'itico y, en particular, el terrorismo de ETA, tuvo un costo econ\'omico observable sobre el Pa\'is Vasco.

### 2. Outline
`0:30--1:30`

Guion sugerido:

> La presentaci\'on tiene cuatro partes. Primero, explico la pregunta y por qu\'e este caso es dif\'icil de estudiar. Segundo, desarrollo la estrategia principal del paper, que es el `synthetic control`. Tercero, muestro la evidencia complementaria de la tregua de 1998--1999 usando `event study`. Y al final cierro con aporte, limitaciones y conclusiones.

### 3. Motivaci\'on
`1:30--2:30`

Guion sugerido:

> La intuici\'on de fondo parece obvia: m\'as violencia deber\'ia da\~nar la econom\'ia. Pero emp\'iricamente eso es dif\'icil de demostrar, porque la violencia no es un shock puramente ex\'ogeno. Puede estar ligada a tensiones previas, a diferencias institucionales o a caracter\'isticas productivas del territorio. Entonces, el desaf\'io no es solo documentar que hay violencia y bajo crecimiento, sino construir una comparaci\'on cre\'ible.

### 4. Pregunta de investigaci\'on
`2:30--3:30`

Guion sugerido:

> La pregunta central es: \textquestiondown c\'omo habr\'ia evolucionado la econom\'ia del Pa\'is Vasco en ausencia de terrorismo? Ese es el contrafactual relevante, y por definici\'on no lo observamos. El paper responde esa pregunta principalmente con `synthetic control`, y luego contrasta esa historia con evidencia financiera durante la tregua.

### 5. Por qu\'e este paper es interesante
`3:30--4:30`

Guion sugerido:

> Este caso es interesante por dos razones. Primero, porque el Pa\'is Vasco no era una regi\'on pobre o rezagada antes del conflicto; al contrario, era una regi\'on rica e industrializada. Segundo, porque el paper se volvi\'o una referencia cl\'asica justamente por mostrar c\'omo construir un contrafactual cre\'ible cuando no sirve comparar directamente con el promedio nacional.

### 6. Contexto hist\'orico
`4:30--5:30`

Guion sugerido:

> ETA se funda en 1959, pero la violencia a gran escala se intensifica realmente a fines de los 60 y, sobre todo, durante los 70. El punto importante para nosotros es que no se trata de hechos aislados, sino de un conflicto persistente, concentrado territorialmente y con capacidad de afectar inversi\'on, decisiones empresariales y expectativas.

### 7. Algunas cifras del conflicto
`5:30--6:30`

Guion sugerido:

> Esta diapositiva sirve para mostrar que el shock est\'a muy concentrado. Seg\'un la tabla, cerca de `69%` de las muertes causadas por ETA ocurrieron en el Pa\'is Vasco, y en t\'erminos per c\'apita la tasa fue aproximadamente `37` veces mayor que en el resto de Espa\~na. Esto es importante porque sugiere que estamos frente a un shock territorialmente localizado.

### 8. Por qu\'e no basta comparar con el resto de Espa\~na
`6:30--7:30`

Guion sugerido:

> El problema es que el Pa\'is Vasco ya era distinto antes del terrorismo. Ten\'ia m\'as ingreso, m\'as inversi\'on, mayor densidad y una estructura industrial distinta. Entonces, comparar Pa\'is Vasco versus Espa\~na mezclar\'ia el efecto del conflicto con diferencias previas de crecimiento. Por eso el paper necesita un contrafactual mejor que el promedio nacional.

### 9. Estrategia de identificaci\'on
`7:30--8:30`

Guion sugerido:

> La identificaci\'on del paper descansa en dos dise\~nos. El principal es el `synthetic control`, que busca medir el efecto de largo plazo sobre el PIB regional. El segundo usa la tregua de `1998--1999` como experimento natural para ver si el mercado valora m\'as a las firmas expuestas al Pa\'is Vasco cuando la paz parece cre\'ible. Mi lectura, y la del propio paper, es que el coraz\'on est\'a en el primer dise\~no.

### 10. Estrategia emp\'irica 1
`8:30--9:30`

Guion sugerido:

> La idea del control sint\'etico es conceptualmente simple. Se construye un “Pa\'is Vasco sint\'etico” como una combinaci\'on de otras regiones espa\~nolas que se parezcan al Pa\'is Vasco antes del terrorismo. Si antes del shock ambas trayectorias son similares y luego divergen, esa divergencia se interpreta como evidencia de un costo econ\'omico del conflicto.

### 11. C\'omo se arma el control sint\'etico
`9:30--11:00`

Guion sugerido:

> Para armar el sint\'etico, los autores usan predictores pretratamiento asociados al potencial de crecimiento: PIB per c\'apita, raz\'on de inversi\'on, densidad poblacional, estructura sectorial y capital humano. El algoritmo elige pesos no negativos sobre otras regiones para minimizar la distancia respecto del Pa\'is Vasco. En la pr\'actica, los pesos \'optimos recaen sobre todo en `Catalu\~na` y `Madrid`: aproximadamente `0.8508` y `0.1492`, respectivamente.

> Esto es razonable porque ambas regiones compart\'ian con el Pa\'is Vasco altos niveles de ingreso y urbanizaci\'on. Pero ya aqu\'i aparece una limitaci\'on: el ajuste no es perfecto, especialmente en la intensidad industrial, porque el Pa\'is Vasco era la regi\'on m\'as industrializada de todas.

### 12. Control sint\'etico: formulaci\'on m\'inima
`11:00--12:30`

Guion sugerido:

> La formulaci\'on del m\'etodo es esta. `X_1` contiene los predictores pretratamiento del Pa\'is Vasco; `X_0` contiene esos mismos predictores para las regiones donantes; `W` es el vector de pesos; y `V` es una matriz diagonal que le da importancia relativa a cada predictor. El objetivo es encontrar los pesos que mejor repliquen el Pa\'is Vasco antes del terrorismo.

> Una vez elegidos esos pesos, se usa la combinaci\'on ponderada de regiones donantes para construir la trayectoria contrafactual `Y_1^*`. Lo importante en la presentaci\'on no es la notaci\'on en s\'i misma, sino la l\'ogica: aproximar un contrafactual no observado con una regi\'on artificial pero comparable.

### 13. Por qu\'e esta estrategia es cre\'ible
`12:30--13:30`

Guion sugerido:

> La credibilidad del m\'etodo no viene de asumir que el terrorismo sea ex\'ogeno, sino de que el sint\'etico reproduzca bien la trayectoria previa. Si antes de `1975` ambas series se comportan parecido, entonces es m\'as plausible usar esa regi\'on sint\'etica como referencia para el per\'iodo posterior.

### 14. Resultado principal 1: PIB per c\'apita
`13:30--14:30`

Guion sugerido:

> El hallazgo principal es que, desde mediados de los 70, el PIB per c\'apita del Pa\'is Vasco cae por debajo del sint\'etico. La brecha alcanza valores cercanos a `12%` y, en promedio, ronda `10%` durante los 80 y 90. Esa es la estimaci\'on m\'as citada del paper.

### 15. Figura 1: el resultado central
`14:30--16:00`

Guion sugerido:

> Esta es probablemente la figura m\'as importante de toda la presentaci\'on. Hasta `1975`, el Pa\'is Vasco real y el sint\'etico se mueven de forma muy parecida. Desde `1975`, cuando la actividad terrorista pasa a ser un fen\'omeno de gran escala, ambas trayectorias divergen. Esa es justamente la visualizaci\'on del efecto estimado.

> Si quieres resumir esta figura en una frase: antes del shock, las trayectorias coinciden; despu\'es, se abre una brecha persistente.

### 16. Intensidad del terrorismo y brecha de PIB
`16:00--17:30`

Guion sugerido:

> El siguiente paso del paper es ver si la brecha de PIB se mueve junto con la intensidad de la violencia. Y eso es lo que muestra esta figura: cuando la actividad terrorista aumenta, la brecha tiende a ampliarse. Esto no prueba por s\'i solo causalidad, pero s\'i refuerza la interpretaci\'on de que la brecha no es un artefacto puramente mec\'anico del m\'etodo.

### 17. Figura 3: respuesta din\'amica
`17:30--18:30`

Guion sugerido:

> Esta figura a\~nade una dimensi\'on din\'amica. El efecto del terrorismo sobre la brecha del PIB no parece instant\'aneo, sino rezagado. El impacto m\'aximo aparece alrededor de `2` a `3` a\~nos despu\'es y luego se va disipando gradualmente. Eso es consistente con la idea de que la violencia afecta inversi\'on y actividad econ\'omica con cierto desfase.

### 18. Placebo con Catalu\~na
`18:30--19:30`

Guion sugerido:

> Aqu\'i el paper hace algo muy importante para la credibilidad del m\'etodo: un placebo. Aplica la misma l\'ogica a Catalu\~na, una regi\'on comparable en varios aspectos, pero sin una escalada similar de terrorismo. La pregunta es si el m\'etodo producir\'ia una brecha artificial incluso donde no deber\'ia hacerlo.

### 19. Figura 4: placebo con Catalu\~na
`19:30--20:30`

Guion sugerido:

> El resultado placebo no reproduce una brecha prolongada como la del Pa\'is Vasco. Eso fortalece la interpretaci\'on causal del ejercicio principal. Al mismo tiempo, el paper reconoce que Catalu\~na tuvo un desempe\~no especialmente fuerte en los 90, asociado entre otras cosas a los Juegos Ol\'impicos de Barcelona de `1992`, y eso incluso podr\'ia exagerar un poco la brecha del Pa\'is Vasco en la parte final de la muestra.

### 20. Fortalezas y dudas de esta estrategia
`20:30--22:00`

Guion sugerido:

> Yo presentar\'ia esta l\'amina con un tono equilibrado. La fortaleza del paper es que hace muy transparente c\'omo se construye el contrafactual y ofrece varias validaciones: ajuste pretratamiento, relaci\'on con intensidad del terrorismo y placebo.

> Pero las dudas son reales. La principal es que el Pa\'is Vasco ten\'ia una composici\'on industrial excepcional, y la crisis industrial de los 70 y 80 podr\'ia contaminar parte del resultado. El propio paper discute este punto y argumenta que la asociaci\'on con la intensidad del terrorismo y algunos ejercicios adicionales hacen dif\'icil explicar toda la brecha solo por declive industrial. Aun as\'i, es una limitaci\'on seria que vale la pena mencionar.

### 21. Transici\'on a la segunda estrategia
`22:00--22:30`

Guion sugerido:

> Hasta aqu\'i, la evidencia central viene del PIB regional. La segunda parte del paper cambia de margen: en vez de mirar crecimiento de largo plazo, mira c\'omo reaccionan los mercados cuando cambia la credibilidad de la paz.

### 22. La tregua de 1998--1999
`22:30--23:30`

Guion sugerido:

> ETA declara una tregua en septiembre de `1998` y la rompe en noviembre de `1999`. La idea del paper es que la tregua genera un experimento natural. Si el conflicto realmente da\~naba la econom\'ia vasca, entonces las firmas expuestas al Pa\'is Vasco deber\'ian apreciarse cuando la tregua se vuelve cre\'ible y caer cuando el proceso de paz colapsa.

### 23. Dise\~no del event study
`23:30--24:30`

Guion sugerido:

> El dise\~no compara un portafolio de firmas “vascas”, es decir, con exposici\'on econ\'omica importante al Pa\'is Vasco, con un portafolio de firmas no vascas. Un punto delicado del paper es justamente esa clasificaci\'on, porque no se basa solo en direcci\'on legal, sino en el juicio de analistas de mercado sobre exposici\'on econ\'omica real.

### 24. Event study: ecuaci\'on e interpretaci\'on
`24:30--26:00`

Guion sugerido:

> Como la tregua se desarrolla de forma gradual durante `14` meses, el paper no usa una ventana cort\'isima como en un event study tradicional. En cambio, estima un modelo tipo Fama-French y a\~nade dos dummies: `Good News` y `Bad News`.

> `Good News` cubre `22` sesiones burs\'atiles, desde que la tregua gana credibilidad hasta que el gobierno autoriza contactos con ETA. `Bad News` cubre `66` sesiones, desde el deterioro del proceso hasta el fin de la tregua. La interpretaci\'on de los coeficientes es directa: capturan retornos anormales promedio durante esos per\'iodos.

### 25. Resultado principal 2
`26:00--27:00`

Guion sugerido:

> El patr\'on es el esperado. Las firmas expuestas al Pa\'is Vasco tienen mejor desempe\~no relativo durante las buenas noticias y peor desempe\~no relativo durante las malas noticias. Eso es consistente con la idea de que el mercado valora econ\'omicamente la paz.

### 26. Figura 6: retornos anormales acumulados
`27:00--28:30`

Guion sugerido:

> Esta figura resume visualmente esa historia. Durante la tregua, el portafolio vasco supera al no vasco a medida que la paz se vuelve cre\'ible. Y al final del proceso esa ganancia relativa se revierte. Lo atractivo de esta figura es que muestra que el mercado no reacciona solo al anuncio inicial, sino a la evoluci\'on de la credibilidad del proceso.

### 27. Magnitud de los efectos burs\'atiles
`28:30--30:00`

Guion sugerido:

> En t\'erminos acumulados, el paper encuentra una rentabilidad anormal compuesta de aproximadamente `10.14%` durante el periodo de `Good News` y de `-11.21%` durante el periodo de `Bad News` para el portafolio vasco relativo al no vasco. Son magnitudes econ\'omicamente relevantes, y por eso esta segunda estrategia funciona bien como respaldo al argumento principal.

### 28. Aporte del paper
`30:00--31:00`

Guion sugerido:

> El aporte del paper es doble. Sustantivamente, entrega evidencia de que el conflicto pol\'itico puede tener costos econ\'omicos importantes y persistentes. Metodol\'ogicamente, muestra una forma convincente de construir un contrafactual cuando una comparaci\'on simple no es cre\'ible.

### 29. Limitaciones
`31:00--33:00`

Guion sugerido:

> La limitaci\'on m\'as importante es que el control sint\'etico no reproduce perfectamente la estructura industrial del Pa\'is Vasco, justo en un contexto de crisis industrial y crisis del petr\'oleo. Entonces, parte de la brecha podr\'ia recoger algo m\'as que terrorismo.

> Una segunda limitaci\'on es que el ejercicio burs\'atil depende de una clasificaci\'on no totalmente objetiva de firmas vascas y no vascas. Y una tercera es la validez externa: es un caso muy espec\'ifico, con una historia pol\'itica e institucional muy particular.

### 30. Conclusiones
`33:00--34:30`

Guion sugerido:

> Si tuviera que resumir el paper en una sola idea, dir\'ia lo siguiente: la contribuci\'on central no es solo mostrar que ETA fue costosa, sino hacer visible un contrafactual razonable. El `synthetic control` permite comparar al Pa\'is Vasco con una regi\'on artificial cre\'ible, y esa comparaci\'on sugiere una p\'erdida persistente de alrededor de `10%` en PIB per c\'apita.

> La evidencia de la tregua no reemplaza ese hallazgo, pero s\'i lo complementa: cuando la paz parece cre\'ible, las firmas expuestas al Pa\'is Vasco ganan valor; cuando la tregua colapsa, lo pierden.

### 31. Referencia
`34:30--35:00`

Guion sugerido:

> Muchas gracias. Si quieren, despu\'es podemos discutir tanto la parte metodol\'ogica del `synthetic control` como las principales dudas de identificaci\'on del paper.

## Frases cortas para usar durante preguntas

### Si te preguntan por qu\'e no basta comparar con Espa\~na

> Porque el Pa\'is Vasco ya part\'ia desde otro nivel de ingreso, industrializaci\'on e inversi\'on. El problema no es solo encontrar un control, sino uno que se parezca antes del conflicto.

### Si te preguntan desde cu\'ando se ve el efecto

> En la `Figure 1` la divergencia empieza a verse desde `1975`; despu\'es la brecha se vuelve persistente.

### Si te preguntan cu\'al es la regi\'on sint\'etica

> Principalmente una combinaci\'on de `Catalu\~na` y `Madrid`, con pesos aproximados de `0.85` y `0.15`.

### Si te preguntan por la principal debilidad

> La principal debilidad es que el Pa\'is Vasco ten\'ia una estructura industrial muy particular y eso coincide con una etapa de crisis industrial y del petr\'oleo.

### Si te preguntan por qu\'e el event study no es el centro del paper

> Porque la contribuci\'on principal del art\'iculo es el contrafactual de largo plazo construido con `synthetic control`; el ejercicio burs\'atil funciona m\'as como validaci\'on complementaria.

## Consejo final de exposici\'on

No intentes decir todo lo que est\'a en las diapositivas. En esta presentaci\'on conviene repetir tres ideas una y otra vez:

1. `El problema es el contrafactual.`
2. `El synthetic control es el coraz\'on del paper.`
3. `La tregua refuerza, pero no reemplaza, el resultado principal.`
