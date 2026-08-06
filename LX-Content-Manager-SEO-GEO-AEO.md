# LADX — Contenido Web optimizado (SEO / GEO / AEO)

Basado en `Website/Website pichuda/260716 - LADX_Contenido_Web.docx` (no modificado). Este archivo acumula la redacción ya aprobada, sección por sección.

Leyenda: 🟢 LISTO (dato verificado, sin cambios) · 🟠 reescrito SEO/GEO/AEO · ⚪ PENDIENTE (bloqueado, falta confirmar con Iván) · 🆕 sugerencia adicional del equipo de estrategia

**Nota — posicionamiento:** se reforzó la frase de posicionamiento "plataforma de intercambio digital (de América Latina)" a lo largo de todo el documento, sin perder "Internet Exchange Point (IXP)" como término técnico (necesario para que motores de IA/AEO identifiquen la entidad correctamente). Se actualizaron: subtítulo del hero, texto de la franja narrativa, descripción de la evolución, "Everything exchangeable", FAQ 1 y FAQ 5; se agregó una línea de apertura nueva en Servicios. Se decidió **no** forzar la frase en textos transaccionales cortos (CTAs, tarjetas de servicio de 120 caracteres, texto de confirmación del formulario) porque ahí compite con la claridad de la acción — el patrón que sigue este documento es "IXP" como definición técnica + "plataforma de intercambio digital" como frase de marca, usados juntos en los bloques narrativos más largos, no en cada micro-texto.

**Nota — descarga de contenido:** el artifact tiene un botón "Descargar contenido" con el texto de las Secciones 01–08 más el resumen de Pendientes. Intenta generar un `.docx` real (editable en Word); si esa extensión no está habilitada en la vista de quien descarga, cae automáticamente a `.txt` con el mismo contenido. No incluye las Secciones 09 (RADAR) y 10 (Banco de contenido) — son notas de estrategia SEO interna, no copy de página — ni la sección "Desarrollo web" de más abajo. Para no generar un documento de 20+ páginas, solo se agrega una línea de anotación bajo un texto cuando ese campo tiene un estado real (aprobado, comentario o respuesta a un pendiente); los campos sin marcar no suman ninguna línea extra.

---

## Desarrollo web — estado de avance (Backend / Frontend)

Proyecto paralelo al de contenidos. Fuente: `Website/Website pichuda/260803 - Acta_de_seguimiento_Desarrollo_web_LADX.docx`. Estado al 3 de agosto de 2026 — es una foto fija de la Acta, no información en vivo.

**Resumen ejecutivo:** Backend 80% completado. Frontend pendiente, no ha iniciado su fase de desarrollo. Próximo hito: entrega del contenido web el 7 de septiembre de 2026 *(fecha corregida por Andrea; la Acta original decía 31 de agosto)*.

**Avance técnico — Backend:**
- Base de datos descargada y procesada (aprox. 15 MB).
- Visualización en bloques que prioriza los registros más recientes para agilizar las consultas.
- Desarrollo centralizado mediante un plugin personalizado para WordPress.
- Funciones de importación y exportación ya incorporadas.
- Restricciones de importación para reducir errores de formato.
- Paginación, búsqueda y gestión de clientes mediante etiquetas implementadas.
- Arquitectura multidioma preparada, pendiente de activación.
- Páginas dinámicas para reducir el mantenimiento de contenido a escala.

**Próximo foco — pendientes:**
1. Cerrar los ajustes de interfaz, usabilidad y experiencia de usuario.
2. Iniciar el desarrollo visual y funcional del frontend.
3. Activar la configuración multidioma e integrar el contenido definitivo.

**Calendario — próximos hitos:**
- Entrega del contenido web → 7 de septiembre de 2026 *(corregido por Andrea; Acta original: 31 de agosto)*.
- Finalización prevista del desarrollo completo → 21–28 de septiembre de 2026.

**Riesgos identificados:**
- Dependencia crítica de contenido: la entrega del contenido web es clave para mantener el calendario de cierre.
- Ventana de validación final: los ajustes de UX, frontend y multidioma deben cerrarse con margen suficiente para pruebas integrales.
- Cambios de alcance: cambios relevantes de requisitos o contenidos en fase final pueden afectar plazo y alcance.

Conclusión de la Acta: el backend avanza según lo previsto. La prioridad operativa es coordinar el contenido web e iniciar el frontend para proteger el hito de septiembre.

---

## Sección 01 — Home

### Hero — primera pantalla

**Supertítulo (sobre el H1)** — sin cambios, ya funciona como expansión del acrónimo (clave para SEO de marca):
> Latin America Digital Exchange

**Subtítulo del hero** 🟠 *(actualizado)* — se refuerza el concepto de posicionamiento "plataforma de intercambio digital" en toda la web, no solo en un par de puntos. Aquí se antepone esa frase (la promesa de marca) y se usa "Internet Exchange Point (IXP)" como su definición técnica — así queda cubierto el posicionamiento y la precisión que necesita AEO:
> La plataforma de intercambio digital de América Latina: un Internet Exchange Point (IXP) neutral y abierto que conecta redes, nubes e infraestructura crítica en Chile y la región.

**CTA principal** — se mantiene (corto, con marca):
> Conéctate a LADX

**CTA secundario** — se mantiene:
> Conoce la red →

### Indicadores de red en tiempo real
Sin cambios — son datos 🟢 LISTO (ASNs 151 / Puertos 368 / Capacidad 30.6 Tbps).
⚪ **Países**: bloqueado — falta que Iván confirme si hay desglose por país y si la actualización es en tiempo real o manual. **Comentario del cliente (06-ago-2026):** pide evaluar con cuidado si conviene mostrar los indicadores separados por país o consolidados, porque la forma en que se presenten debe reforzar la percepción de LADX como compañía regional y no como operaciones independientes por país. **Recomendación de trabajo:** mantener aquí en Home la cifra agregada/regional (como hoy: 151 ASNs / 368 puertos / 30.6 Tbps a nivel de red), y dejar el desglose técnico detallado por país en la Sección 04 — así el Home refuerza la escala regional y el detalle por país queda disponible para quien lo busque. Sigue pendiente de aprobación final del cliente antes de redactar copy definitivo.

### Servicios — tarjetas resumen en Home
- **Peering / Internet Exchange** 🟠 *(remate final más aspiracional; sin tocar el dato técnico)*:
  > Interconexión directa entre redes con route servers redundantes IPv4/IPv6. La base sobre la que se construye todo lo demás.
- **Cloud Exchange** 🟠 — el original ("Acceso directo a los grandes proveedores de nube desde la red") no nombra proveedores porque **la descripción completa sigue ⚪ PENDIENTE** (pitchile.cl solo tiene un banner sin texto). Reescritura mínima, sin inventar proveedores:
  > Conexión directa a proveedores de nube, sin pasar por la red pública de internet.
  > *Nota: en cuanto Iván confirme los proveedores (AWS/Azure/GCP u otros), conviene nombrarlos explícitamente — nombres propios de marca son lo que más ayuda a que un motor de respuesta cite esta tarjeta.*
- **Ecosistema Digital** — ⚪ PENDIENTE, no existe como servicio publicado; no se redacta tarjeta hasta que el cliente defina el alcance (igual que dice el borrador original).

**Comentario del cliente (06-ago-2026):** confirmó mantener estas dos líneas de negocio (Peering, Cloud Exchange) junto con Ecosistema Digital como tercera categoría, y pidió eliminar la tarjeta de **Colocation** — no es un servicio que LADX presta. Tarjeta retirada.

### Franja narrativa "Quiénes somos"

**Título de la franja** 🟠 — se mantiene el arco narrativo "de X a Y" del original, pero se inserta la keyword IXP y la geografía objetivo:
> De IXP líder en Chile a plataforma de intercambio digital para América Latina.

**Texto principal** 🟠 *(actualizado)* — el original ya usaba las cifras correctamente; el ajuste nombra "Internet Exchange Point (IXP)" explícitamente, cierra con la frase de posicionamiento exacta "plataforma de intercambio digital", y remata con un beat aspiracional ("el futuro ya llegó") en vez de terminar en la palabra pasiva "convergen":
> Durante 10 años construimos el Internet Exchange Point (IXP) más importante de Chile: 151 ASNs, 368 puertos y 30.6 Tbps de capacidad, bajo el mismo estándar de neutralidad. Hoy damos un paso más: LADX es la plataforma de intercambio digital donde redes, nubes y ecosistemas convergen, en Chile y en América Latina. El futuro del intercambio digital no se anuncia: ya está aquí, y se llama LADX.

---

## Sección 02 — Qué es LADX

### Historia y evolución

Año de fundación de PIT Chile — 🟢 2016. Año del cambio a LADX — 🟢 2026.

**Hitos clave (timeline)** ⚪ — el contenido ya está recopilado, pero el propio documento lo marca PENDIENTE de confirmar con Iván. Se deja tal como está, como borrador de trabajo — **no publicar sin validar cada hito**. **Comentario del cliente (06-ago-2026):** pidió que la historia se construya alrededor de hitos corporativos contundentes, evitando asociarlos al nombramiento de personas específicas, para que el protagonismo quede en la compañía y no se personalice en exceso. Se retiraron del timeline los dos nombramientos (Gerente General, CTO) y se agregaron hitos corporativos de expansión, todos pendientes de fecha exacta salvo donde se indica:
- 2016 — Fundación de PIT Chile, liderada por [Iván Žilić](https://www.linkedin.com/in/ivan-%C5%BEili%C4%87-schmidt-78a35b/) (fundador y CEO)
- 2017 — Primera Reunión Abierta de la comunidad, en Osorno
- 2018 — Reunión Abierta en Concepción
- 2019 / 2020 / 2023 / 2024 / 2025 — Reuniones Abiertas anuales en Santiago; red distribuida hasta 15 datacenters en Chile
- 2024 — Apertura del tercer punto de presencia propio en Estados Unidos (Ashburn, Virginia)
- 2024 — Nuevo nodo ZGH en el sector sur de Santiago
- 2026 — PIT Chile se transforma en LADX
- ⚪ *Fecha a confirmar* — Apertura de operaciones en México
- ⚪ *Fecha a confirmar* — Apertura de operaciones en Perú
- ⚪ *Fecha a confirmar* — Constitución y puesta en marcha de la empresa en Argentina
- 2026 — Apertura de operaciones en Ecuador (dato confirmado por el cliente en su email del 06-ago-2026; sin más detalle público aún)
- ⚪ *Fecha a confirmar* — Inicio y desarrollo del negocio de Cloud Exchange
- ⚪ *Fecha a confirmar* — Expansión de la red y del ecosistema de interconexión regional

Los nombramientos de Fernando Clavijo Saldaña (Gerente General) y Hernán Moguilevsky (CTO) se mantienen como contenido en la Sección 06 — Noticias, y en la FAQ de liderazgo (Sección 08); solo se retiraron de este timeline de hitos corporativos.

**Descripción de la evolución** 🟠 *(actualizado)* — la primera oración (citable sola para GEO) queda intacta; se ajusta solo el cierre para terminar en clave aspiracional en vez de un verbo técnico ("proyecta"):
> LADX es la plataforma de intercambio digital de América Latina, evolución de PIT Chile: el Internet Exchange Point (IXP) que en 2016 comenzó como el punto neutro donde las redes de Chile empezaron a interconectarse directamente. Diez años y 151 ASNs después, esa misma infraestructura ya no solo mueve tráfico: conecta nubes, plataformas y ecosistemas digitales. LADX hereda esa base técnica y esa neutralidad, y las proyecta a escala latinoamericana — construyendo hoy la infraestructura que América Latina necesitará mañana.

**¿LADX reemplaza a PIT Chile?** 🆕 — framing explícito de continuidad, no de ruptura:
> LADX no reemplaza a PIT Chile ni representa una ruptura con su historia: es la expresión natural de lo que PIT Chile ha llegado a ser después de diez años de evolución — una nueva forma de representar una realidad que ya existía.

### Propósito corporativo
**Comentario del cliente (06-ago-2026):** antes de presentar los principios, pidió incorporar primero una declaración clara del propósito corporativo de LADX, para que los principios se desprendan de ese propósito. El texto ya existía en el borrador (antes como campo suelto dentro de Historia); se elevó a su propio subtítulo, inmediatamente antes de Principios, sin cambiar el contenido.

**Propósito fundacional** 🆕 — de dónde viene la neutralidad que hoy define a LADX:
> PIT Chile nació con un propósito simple: interconectar el país desde la neutralidad, con un ecosistema abierto, colaborativo y eficiente para todos los actores de Internet. Ese mismo propósito es hoy el punto de partida de LADX a escala latinoamericana.

### Principios de marca
*(Nota ya presente en el original: los 5 principios son traducción de los 5 atributos que PIT Chile ya declara — Neutro, Público, Abierto, Transparente, Distribuido — no un cambio de valores. Comentario del cliente 06-ago-2026: los principios están bien encaminados, pero pidió darles mayor contundencia en su redacción — definiciones reescritas abajo.)*

- **Neutralidad** 🟠 *(reescrito 06-ago-2026: se agrega "sin excepciones" y "país de origen" para que la definición ya lea regional, no solo Chile)*:
  > Neutralidad sin excepciones: las mismas reglas de peering aplican a todos los miembros de la red, sin importar su tamaño, su país de origen o el tipo de organización que sean.
- **Apertura** 🟠 *(reescrito 06-ago-2026: "en cada país donde está presente" y "sin barreras de entrada distintas a las técnicas" refuerzan alcance regional y contundencia)*:
  > LADX opera como IXP público en cada país donde está presente: cualquier ISP, CDN, universidad o institución que cumpla los requisitos técnicos puede conectarse a la red, sin barreras de entrada distintas a las técnicas.
- **Resiliencia** 🟠 *(reescrito 06-ago-2026: apertura más contundente y cierre que explica el porqué, no solo el dato técnico)*:
  > Una red diseñada para no fallar: NOC operativo 24x7 y validación RPKI activa desde 2020, que descarta automáticamente las rutas inválidas antes de que se conviertan en un problema.
- **Confianza** 🟠 *(reescrito 06-ago-2026: el comentario del cliente pidió que la diferenciación no dependa solo de Chile — se reordena para liderar con los reconocimientos regionales/internacionales y dejar SUBTEL como el dato específico de Chile, no como el encabezado)*:
  > Una confianza construida durante una década y reconocida por los principales organismos técnicos de internet: LACNIC, ISC.org, PCH, PeeringDB y Verisign, además de SUBTEL en Chile.
- **Transparencia** 🟠 *(reescrito 06-ago-2026: apertura más directa)*:
  > Nada que esconder: indicadores de tráfico públicos y en tiempo real, disponibles para cualquiera, sin necesidad de login.

### Diferenciador central
**Comentario del cliente (06-ago-2026):** en esta sección había bastante contenido específico de Chile; pidió un planteamiento más global y regional, y que la diferenciación no dependa principalmente de cifras (ej. cantidad de ASNs) — porque eventualmente otro operador puede tener más y esa comparación deja de favorecer a LADX. Pidió apoyarse en su lugar en: neutralidad, resiliencia y confiabilidad de la red, capacidad para soportar altos volúmenes de tráfico, presencia en distintos países y puntos estratégicos de la región, capacidad de interconectar redes/empresas/ecosistemas a nivel regional, y la visión de construir una verdadera red latinoamericana de intercambio e interconexión. Los dos textos de abajo se reescribieron sobre esa base, usando solo datos ya presentes en el documento.

**Lo que distingue a LADX** 🟠 *(reescrito 06-ago-2026: se retira el dato "90% del tráfico de Chile" como argumento principal — queda disponible como comparación técnica en la Sección 09, no como diferenciador de marca — y se reemplaza por los ejes cualitativos que pidió el cliente, con Root DNS como prueba técnica, no como cifra a superar)*:
> LADX no compite solo por tamaño de red: compite por neutralidad, resiliencia y capacidad de sostener el tráfico crítico de una región entera. La misma infraestructura que hoy aloja seis réplicas de servidores Root DNS (B, D, E, I, J y K) — la base que sostiene la resolución de nombres en internet a nivel mundial — con NOC 24x7 y validación RPKI activa, es la que LADX proyecta hoy a Chile y Estados Unidos, y a los mercados de México, Perú, Argentina y Ecuador donde ya está construyendo presencia. Esa es la apuesta de LADX: no ser el mayor operador de un país, sino la red que interconecta redes, empresas y ecosistemas digitales a lo largo de toda América Latina.

**¿Qué significa "Everything exchangeable" para LADX?** 🟠 *(actualizado 06-ago-2026: se quita la mención a Colocation, ya no es un servicio de LADX, y se agrega el cierre regional que pidió el cliente)*:
> Para LADX, "Everything exchangeable" es la idea detrás de ser la plataforma de intercambio digital de América Latina: el intercambio va más allá del tráfico de red — incluye nubes (Cloud Exchange) y, a futuro, datos y servicios (Ecosistema Digital), todo bajo el mismo estándar de neutralidad con el que nació PIT Chile como IXP y que hoy se proyecta a cada país donde LADX opera.

**Visión de largo plazo** 🆕 — lenguaje de marca/visión, no una descripción de servicios ya disponibles (Cloud Exchange y Ecosistema Digital siguen con su propio estado de avance más arriba):
> El intercambio digital ya no se trata solamente de tráfico: se trata de habilitar el próximo sistema nervioso digital de América Latina. Bajo esa visión, LADX proyecta un horizonte donde el intercambio incluye también inteligencia — la misma lógica de neutralidad y apertura aplicada a todo lo que las redes del futuro necesiten conectar.

---

## Sección 03 — Servicios

**Línea de apertura** 🆕 *(nueva — no estaba en el documento original; propuesta para conectar los 3 servicios con el concepto de posicionamiento, sujeta a tu aprobación. Ajustado 06-ago-2026: eran 4 servicios, ahora 3 tras retirar Colocation)*:
> Todo bajo un mismo techo: los servicios que hacen de LADX la plataforma de intercambio digital de América Latina.

### A. Peering / Internet Exchange 🟢 LISTO
- Descripción completa:
  > Peering multilateral en IPv4 e IPv6 con route servers redundantes, operado en Capa 2. Incluye validación RPKI (los prefijos RPKI INVALID se descartan automáticamente desde enero de 2020) y peering bilateral disponible para quienes lo requieran. La red exige un mínimo de ASN propio, bloque IPv4/IPv6 válido y BGP4 como protocolo de enrutamiento, con velocidades de puerto de 1, 10, 25, 40 y 100 Gbps (multiplicables).
- ¿A quién va dirigido? 🟠 *(reescrito 06-ago-2026: el original mencionaba específicamente a SUBTEL, el regulador chileno — válido para Chile pero no necesariamente comprensible para visitantes de otros países. Se generaliza a "autoridades competentes de cada país" para que la descripción sirva para todas las operaciones de LADX; se mantiene LACNIC porque es el organismo técnico regional, no uno país-específico)*:
  > ISPs, operadores de red, proveedores de contenido (CDN), universidades, entidades de gobierno e instituciones financieras que cumplan los requisitos técnicos y regulatorios establecidos por las autoridades competentes de cada país, además de los estándares técnicos de LACNIC.
- Ventajas clave: Peering multilateral IPv4/IPv6 con route servers redundantes · Peering bilateral disponible · Validación RPKI activa (descarta prefijos inválidos) · DNS público con DNSSEC (resolver1/2.pitchile.cl)

### B. Cloud Exchange ⚪ PENDIENTE
En su totalidad. pitchile.cl solo tiene un banner gráfico sin texto. No se redacta ficha de servicio con datos inventados (proveedores, público objetivo, ventajas). Bloqueado hasta que Iván confirme qué proveedores de nube conectan y cómo se describe el servicio.

**Comentario del cliente (06-ago-2026):** Colocation no es un servicio que LADX presta — se retira por completo esta ficha (descripción, tipos de espacio, público objetivo y ventajas clave).

### C. Ecosistema Digital ⚪ PENDIENTE
En su totalidad. Es un concepto nuevo de marca sin servicio publicado hoy; no se redacta hasta que el cliente defina el alcance.

---

## Sección 04 — Red, presencia por país
*(Sección de datos/directorio — el original no tiene campos BORRADOR NARRATIVO aquí; se organiza igual, sin agregar redacción de marketing donde el contenido es una ficha técnica.)*

**Comentario del cliente (06-ago-2026):** pidió preparar desde esta primera versión una descripción detallada de nodos y puntos de presencia para cada país donde opera LADX — Chile, Perú, México, Ecuador, Argentina y Estados Unidos. Se agrega Ecuador (país nuevo) y se deja explícito el pedido de ficha detallada en cada bloque de país de abajo.

**Chile** — 🟢 LISTO: Santiago, Concepción, Temuco y Valparaíso (nodo Curauma); 151 ASNs / 368 puertos / 30.6 Tbps (cifras nacionales). Estos son los nodos que forman parte de nuestra red: Equinix, Cirion, GTD, Entel, EdgeConnex, Sonda, Ascenty, Kyndryl, ZGH, Scala, entre otros (15 datacenters en total).
Confirmado: el contacto de Chile migra a `info@ladx.net` con el lanzamiento de la nueva web.

**Comentario del cliente (06-ago-2026):** (1) se retiró "Sede corporativa: Badajoz 45, Piso 17, Las Condes, Santiago" de esta ficha — es la dirección legal/tributaria de la compañía en Chile, no una oficina operativa ni un nodo de red, así que no corresponde en Infraestructura/Presencia. Queda pendiente definir dónde se publica (hoy sigue apareciendo en Sección 07 — Conectarse, como dato de contacto/corporativo; eventualmente podría vivir en una sección legal/T&C aparte). (2) Se retira la clasificación "nodos secundarios" — el cliente pidió no calificar públicamente ningún nodo como secundario frente a otros "primarios" que tampoco están descritos así; se usa en su lugar "estos son los nodos que forman parte de nuestra red".

⚪ **Ejecución de la migración de correo/teléfono** — confirmado que el contacto pasa a `info@ladx.net`; falta definir quién ejecuta el cambio (aspecto operativo, no de contenido).

⚪ **Resolver DNS público** — `resolver1/2.pitchile.cl` (Sección 03) es un hostname técnico real. Confirmar si también pasa a un hostname bajo `ladx.net` o si se mantiene igual — no se cambia sin que el equipo técnico lo confirme.

**Perú · Argentina · México** — ⚪ PENDIENTE por completo. No hay ciudad, datacenter, ASNs, puertos, capacidad ni contacto local publicados en pitchile.cl. El único rastro público en el sitio propio es un banner de imagen ("Cobertura 2025") que menciona Perú sin cifras. No se redacta contenido para estos 3 países hasta tener datos de Iván.

⚪ **Argentina — posible actualización pendiente (ver Sección 09):** un directorio externo (PeeringDB) muestra una sede en Buenos Aires con estado "Operational" desde jun. 2024 y creciendo en miembros — no coincide con "sin datos públicos" de arriba. Antes de redactar contenido para Argentina, confirmar con Iván si esa sede ya se puede presentar como operativa en la web nueva. Perú y México siguen sin evidencia de estar activos.

**Pedido del cliente (06-ago-2026):** preparar ficha detallada de nodos/PoP para los 3 países desde esta primera versión — ciudad, datacenter, ASNs, puertos, capacidad. Pendiente de que Iván entregue los datos.

**Ecuador** — ⚪ PENDIENTE. País nuevo: el cliente confirmó en su email del 06-ago-2026 la apertura de operaciones en Ecuador durante 2026, sin más detalle público todavía (sin ciudad, datacenter, ASNs, puertos, capacidad ni contacto local). No se redacta contenido adicional hasta tener esos datos.

**USA** — parcial: 🟢 LISTO ciudad y datacenter (Ashburn, Virginia — PoP propio inaugurado en febrero de 2024, descrito como "tercer punto de presencia"; Equinix MIA1 en Miami también figura listado). ⚪ PENDIENTE: ASNs/puertos/capacidad propios de EE.UU. (hoy solo existe la cifra nacional total) y contacto local.

---

## Sección 05 — Eventos
*(Sin campos BORRADOR NARRATIVO en el original — es contenido logístico/factual.)*

**Evento destacado** — 🟢 LISTO: Neura Mare 2026, 8ª Reunión Abierta de PIT Chile, 11 de junio de 2026, Santiago (Centro de Eventos Metropolitan, Vitacura), con streaming. ⚠️ **Ya ocurrió** — era el evento más reciente al momento de redactar este borrador (16 jul. 2026); no publicar como "próximo evento" sin confirmar antes con Iván cuál es el siguiente real.

**Próximo evento** — ⚪ PENDIENTE: no hay ninguno anunciado públicamente todavía.

**Histórico de eventos** — 🟢 LISTO, migrar completo (8 años documentados, activo real de comunidad que refuerza la continuidad PIT → LADX): Osorno 2017, Concepción 2018, Santiago 2019/2020/2023/2024, Santiago 2025 (7ª reunión, con Nokia) y Santiago 2026 (Neura Mare, 8ª reunión).

**Resumen visual por evento** 🆕 — **Pedido del cliente (06-ago-2026):** preparar, para cada evento del histórico de arriba, un pequeño resumen visual con selección de fotografías, principales participantes y una breve descripción de lo realizado — busca que clientes, proveedores y conocidos de la compañía se vean reflejados en eventos anteriores y vean la evolución de este componente del ecosistema. ⚪ Bloqueado hasta que el cliente entregue el material (fotos y listado de participantes) por evento — no se redactan descripciones ni se seleccionan fotos sin ese insumo.

---

## Sección 06 — Noticias

### Noticia de lanzamiento — LADX

**Titular** 🟠:
> PIT Chile se transforma en LADX: nace la plataforma de intercambio digital de América Latina

**Resumen / bajada** 🟠:
> Después de 10 años como el Internet Exchange Point (IXP) de referencia en Chile, PIT Chile da el salto a LADX: misma red, misma neutralidad, ahora a escala regional.

⚪ **Contenido completo** — PENDIENTE. No se redacta el comunicado completo: falta fecha de lanzamiento confirmada y aprobación de todos los socios antes de publicar. El titular/resumen de arriba son borrador de trabajo, ajustables cuando haya fecha real (hoy está en presente/futuro genérico, no amarrado a un día específico).

### Noticias adicionales — 🟢 LISTO, sin cambios
- "Fernando Clavijo Saldaña asume como nuevo Gerente General de PIT Chile" — asume en noviembre de 2025.
- "Hernán Moguilevsky asume como nuevo CTO de PIT Chile" — asume en febrero de 2026, tras cinco años como ingeniero de redes en la organización.

⚪ **Proceso editorial de Noticias** — **Comentario del cliente (06-ago-2026):** le parece muy positivo tener esta sección, pero advierte que el principal desafío es sostenerla: hace falta definir internamente un proceso dinámico, con responsables y una periodicidad concreta, para que la sección se mantenga siempre actualizada. Una sección de Noticias desactualizada genera el efecto contrario al buscado. Es un tema operativo/de proceso, no de redacción — pendiente de que el cliente asigne responsable y cadencia.

---

## Sección 07 — Conectarse

**Información corporativa** — 🟢 LISTO: teléfono +56 2 2840 9984; dirección Badajoz 45, Piso 17, Las Condes, Santiago; email `info@ladx.net`; LinkedIn `linkedin.com/company/pit-chile`.
⚪ Abierto: si el LinkedIn se renombra o se crea una página nueva para LADX (el email ya está confirmado: `info@ladx.net`).
*Nota (06-ago-2026): Badajoz 45 se mantiene aquí como dato de contacto/corporativo — el cliente pidió sacarla de la Sección 04 (Infraestructura/Presencia por país) porque es dirección legal/tributaria, no un nodo de red; en Conectarse sí corresponde como información de contacto de la compañía.*

**Contactos por país** — Chile: `info@ladx.net`. ⚪ Perú · Argentina · México · Ecuador · USA: PENDIENTE, ningún contacto local publicado todavía. **Comentario del cliente (06-ago-2026):** considera clave crear puntos de contacto locales por país — idealmente teléfono, correo y nombre de contacto (o alguna referencia) que demuestre estructura local en cada mercado, en vez de mostrar solo datos genéricos o el teléfono de Chile para todas las operaciones, lo que puede transmitir una presencia poco desarrollada en el resto de los países. El cliente va a trabajar internamente en definir estos contactos locales — queda pendiente de que lo entregue, no bloqueado en nuestro lado.

**Formulario de solicitud de conexión**
- Campos del formulario — 🟢 LISTO: Nombre, Correo, Teléfono, Organización, Asunto, Mensaje (actuales) + País (por agregar).
- ⚪ Email de destino de las solicitudes: PENDIENTE decidir entre `conexiones@ladx.net` o `info@ladx.net` (las dos ya bajo el dominio confirmado) — es una decisión de negocio, no de redacción; no se elige por el usuario.
- **Texto de confirmación tras enviar** 🟠 — se mantiene el tono, se agrega una confirmación explícita de recepción (mejora de UX/confianza, no cambia el hecho de las 48 horas):
  > Gracias por contactar a LADX. Tu solicitud ya fue recibida — nuestro equipo técnico se pondrá en contacto contigo dentro de las próximas 48 horas hábiles.

---

## Sección 08 — Preguntas frecuentes (FAQ / AEO)

Reescritas como oraciones completas y autocontenidas (pregunta + respuesta corta), que es el formato que mejor citan los motores de respuesta y el candidato directo a marcado `schema.org/FAQPage`. Ningún dato nuevo respecto del resto del documento.

1. **¿Qué es LADX?** 🟠 *(actualizado — la respuesta que más van a citar los motores de IA, ahora lidera con la frase de posicionamiento)*
   > LADX (Latin America Digital Exchange) es la plataforma de intercambio digital de América Latina: la evolución de PIT Chile, el Internet Exchange Point (IXP) neutral, público y abierto que opera en Chile desde 2016 y hoy proyecta su modelo de intercambio a escala regional.

2. **¿LADX reemplaza a PIT Chile o representa una ruptura con su historia?** 🆕
   > No. LADX no reemplaza a PIT Chile ni representa una ruptura con su historia: es la expresión natural de lo que PIT Chile ha llegado a ser después de diez años de evolución — una nueva forma de representar una realidad que ya existía.

3. **¿Cómo se pronuncia LADX?** 🆕
   > Se pronuncia "LADEX."

4. **¿Cuántos ASNs, puertos y qué capacidad tiene la red?** ⚪ *(cifra vigente — confirmar con Iván antes de publicar)*
   > 151 ASNs activos, 368 puertos y 30.6 Tbps de capacidad total (cifra nacional; confirmar que sigue vigente a la fecha de publicación).

5. **¿En qué países tiene presencia LADX?** ⚪ *(incompleto — Perú, Argentina, México y Ecuador sin confirmar; actualizado 06-ago-2026 para agregar Ecuador, país nuevo confirmado por el cliente)*
   > Con presencia confirmada: Chile y un punto de presencia propio en Ashburn, Virginia (Estados Unidos). La presencia en Perú, Argentina, México y Ecuador (apertura anunciada para 2026) está confirmada como parte de la expansión regional, pero aún sin datos públicos de ASN, capacidad o contacto local.

6. **¿Cuándo se fundó PIT Chile / LADX?**
   > PIT Chile, hoy LADX, se fundó en 2016.

7. **¿Qué servicios ofrece LADX?** 🟠 *(actualizado 06-ago-2026: se retira Colocation, ya no es un servicio de LADX — pasa de "cuarto servicio" a "tercer servicio")*
   > Como plataforma de intercambio digital, LADX ofrece Peering / Internet Exchange y Cloud Exchange. Un tercer servicio, Ecosistema Digital, todavía no tiene alcance ni descripción pública definidos.

8. **¿Qué tipo de peering ofrece?**
   > Peering multilateral en IPv4 e IPv6 con route servers redundantes, más peering bilateral disponible, con validación RPKI activa desde enero de 2020 que descarta automáticamente los prefijos inválidos.

9. **¿LADX aloja infraestructura crítica de Internet?**
   > Sí: LADX es el hogar de seis réplicas de servidores Root DNS (B, D, E, I, J y K), operadas por Verisign, Packet Clearing House, RIPE, University of Southern California y Netnod.

10. **¿Cómo se conecta una empresa a la red?**
    > Necesita un ASN propio válido, un bloque de direcciones IPv4 o IPv6, y usar BGP4 como protocolo de enrutamiento. Los puertos disponibles son de 1, 10, 25, 40 y 100 Gbps, multiplicables.

11. **¿Cuál es el próximo evento de la comunidad?** ⚪ PENDIENTE
    > Todavía no hay un próximo evento anunciado públicamente. El más reciente fue Neura Mare 2026 (8ª Reunión Abierta), el 11 de junio de 2026.

12. **¿Quién lidera LADX / PIT Chile?** ⚪ *(un nombre sin corroborar)*
    > [Iván Žilić](https://www.linkedin.com/in/ivan-%C5%BEili%C4%87-schmidt-78a35b/) (fundador y CEO), Fernando Clavijo Saldaña (Gerente General) y Hernán Moguilevsky (CTO). El documento fuente también menciona a Daniel Fried como co-fundador, pero ese dato no aparece corroborado en ninguna otra parte del borrador — verificar con Iván antes de publicarlo.

---

## Sección 09 — RADAR (optimización para motores de IA) 🆕

Sección adicional que aplica 3 fases de la metodología RADAR (sarauter.com) para optimizar el contenido antes de publicar: Datos comparativos (fase 4), Autoridad/E-E-A-T (fase 5) y Prompts objetivo (fase 8). Todo lo verificado acá viene de fuentes públicas reales (PeeringDB, PCH, Internet Society Pulse, el propio sitio pitchile.cl) — nada fue inventado. Donde no hay dato público confirmado, queda marcado ⚪ PENDIENTE, igual que en el resto del documento.

### Fase 4 — Datos comparativos
🆕 Con datos reales de 4 puntos de comparación en la región (Brasil, Argentina, Perú, México). Donde una fuente no tenía el dato, queda como *Sin dato público* — no se completó nada a ojo.

| Dimensión | LADX (Chile) | IX.br — São Paulo (Brasil) | CABASE (Argentina) | NAP Perú | DE-CIX México |
|---|---|---|---|---|---|
| Año de fundación | 2016 | 2001¹ | — | *Sin dato público* | 2023–2025¹ (entrada al mercado) |
| ASNs / miembros conectados | 151 | 1.870¹ | 550 | 4 | ~30 |
| Puertos activos | 368 | 4.983¹ | *Sin dato público* | *Sin dato público* | *Sin dato público* |
| Capacidad total | 30.6 Tbps² | 30.4 Tbps¹ (46.6 Tbps red nacional) | 16.96 Tbps | *Sin dato público* | ~300 Gbps³ |
| Root DNS alojados | 6: B, D, E, I, J, K⁴ | Sí, varias instancias (letras por ciudad sin confirmar) | Sin evidencia pública | No | No |
| Validación RPKI | Activa desde 2020 | Promovida, sin fecha confirmada | *Sin dato público* | *Sin dato público* | *Sin dato público* |
| Presencia geográfica | Chile + Ashburn, VA (EE.UU.); Perú/Argentina/México anunciados⁵ | 39 sedes en Brasil | 28 sedes en Argentina | Lima | Ciudad de México y Querétaro (+ Brasil) |
| Certificación MANRS | Aprobado — IXP Participant desde may. 2024 | *Sin dato público* | *Sin dato público* | *Sin dato público* | *Sin dato público* |

**Notas al pie:**
1. Cifra de una sola sede (São Paulo para IX.br; entrada al mercado mexicano para DE-CIX), no de la operación nacional completa del país.
2. LADX reporta 30.6 Tbps; un segundo tracker independiente (Internet Society Pulse) le asigna solo 12.8 Tbps a 2026 — el mismo patrón de desactualización que ya vimos en PeeringDB (ver Fase 5). Recomendable resolver esta discrepancia antes de usar la cifra en comparaciones públicas.
3. Tráfico pico observado, no capacidad provisionada — no es directamente comparable a las cifras de Tbps de capacidad de las otras columnas.
4. Fuentes secundarias sin fecha confirmada sugieren que Santiago podría alojar también instancias F y L — ver hallazgo aparte más abajo, pendiente confirmar antes de cambiar el "seis" ya aprobado.
5. Un hallazgo nuevo indica que la sede en Argentina ya figura como "Operational" en PeeringDB — ver nota en Sección 04.

⚪ **Ranking regional por tráfico — replanteado.** No se encontró una fuente primaria (PCH, Internet Society Pulse o Euro-IX) que confirme "2° lugar en Latinoamérica / 4° mundial". Comparando capacidad reportada: LADX (30.6 Tbps autoreportados) superaría a CABASE Argentina (16.96 Tbps), pero el tracker independiente Pulse solo le asigna 12.8 Tbps a LADX — con esa cifra, quedaría por debajo de Argentina. **Recomendación: no publicar un ranking numérico ("2°/4° lugar") sin que Iván aporte la fuente original de esa cifra; apoyarse en cambio en las comparaciones de capacidad ya documentadas arriba.**

⚪ **Root DNS — posible hallazgo adicional.** Además de B, D, E, I, J, K (ya aprobados), aparecen menciones sin fecha confirmada de una instancia **F** (anuncio propio de pitchile.cl) y **L** (Wikipedia) también en Santiago. Si se confirma, LADX alojaría 8 réplicas de root DNS en vez de 6 — reforzaría aún más el diferenciador. **Verificar con Iván/equipo técnico antes de cambiar la cifra ya aprobada.**

⚪ **Presencia en Argentina — posible desactualización del propio sitio.** El directorio PeeringDB muestra una sede "PIT AR" (Buenos Aires) con estado **Operational** desde jun. 2024, ASN propio, y creciendo de 7 a 19 miembros en el último año. Esto contrasta con el contenido actual (Sección 04), que dice que Argentina está "anunciada pero no operativa". **Revisar con Iván si ya se puede publicar Argentina como sede operativa** (México, en cambio, no tiene evidencia pública de estar activo — ese punto sigue igual).

### Fase 5 — Autoridad y fuentes externas (E-E-A-T)
🆕 Fuentes reales, con URL, para respaldar las menciones de "reconocido por..." que ya están en el documento:

- **PeeringDB** (organización): https://www.peeringdb.com/org/14704 · (IXP Santiago): https://www.peeringdb.com/ix/1514
  ⚠️ **Hallazgo importante**: el perfil público muestra capacidad de **12.9 Tbps** y fecha de última actualización **22 de enero de 2020** — desactualizado y contradice la cifra nueva de 30.6 Tbps que se va a publicar en ladx.net. **Recomendación: actualizar el perfil de PeeringDB antes o al mismo tiempo del lanzamiento**, para que un motor de IA que cruce ambas fuentes no encuentre cifras contradictorias.
- **Packet Clearing House (PCH)**: https://www.pch.net/ixp/details/1931 (Santiago) — perfil sin cifras técnicas públicas detalladas, pero confirma la relación PIT Chile ↔ PCH (uno de los operadores de Root DNS ya mencionados).
- **Internet Society Pulse — IXP Tracker**: https://pulse.internetsociety.org/en/ixp-tracker/ixp/517/
- **Euro-IX / IXPDB**: https://ixpdb.euro-ix.net/en/explore/ixp/680/
- **MANRS — IXP Participant** (aprobado desde el 28 de mayo de 2024): https://manrs.org/ixps/participants/ — buena fuente de autoridad adicional, no estaba en la lista anterior.
- **Página propia "Así nos ven"** (recopilación de menciones de PIT Chile en directorios externos — Subtel, LACNIC, PCH, PeeringDB, Wikipedia, Hurricane Electric, RIPE NCC, Oracle Cloud Partner): https://www.pitchile.cl/wp/asi-nos-ven/
- ⚪ **Root DNS**: para la cita de mayor autoridad posible, lo ideal es enlazar directamente al listado oficial de operadores de root servers (IANA: iana.org/domains/root/servers) en vez de fuentes secundarias — **pendiente que el equipo técnico confirme cuál prefieren citar**.

### Fase 8 — Prompts objetivo (para monitorear después del lanzamiento)
🆕 Preguntas reales que un usuario podría hacerle a un LLM sobre LADX, agrupadas por intención, con impacto y probabilidad estimados — para revisar cada dos semanas (fase 9 de RADAR) si LADX aparece bien representado en las respuestas.

| Prompt | Clúster | Impacto | Probabilidad |
|---|---|---|---|
| ¿Qué es LADX? | Definicional | Alto | Alta |
| ¿LADX y PIT Chile son lo mismo? | Definicional | Alto | Alta |
| ¿Qué es un Internet Exchange Point (IXP) y para qué sirve? | Definicional | Medio | Alta |
| ¿Cuál es el IXP más grande de Chile? | Comparativo | Alto | Media |
| ¿Qué IXP en Latinoamérica aloja servidores Root DNS? | Comparativo | Alto | Media |
| ¿Cómo conecto mi ISP o CDN a un IXP en Chile? | Decisión / acción | Alto | Media-alta |
| ¿Cuáles son los requisitos técnicos para hacer peering en Chile? | Decisión / acción | Alto | Media |
| ¿LADX ofrece colocation en Santiago? | Decisión / acción | Medio | Media |
| ¿Es confiable el IXP de Chile? ¿Qué reconocimientos tiene? | Confianza / autoridad | Medio | Media |
| ¿Hay un IXP operado por LADX en Perú, Argentina o México? | Geográfico / expansión | Medio | Baja (crecerá cuando se confirme presencia) |

---

## Sección 10 — Banco de contenido (temas para artículos y FAQ) 🆕

No estaba en el documento original. Son **ideas de contenido para desarrollar a futuro** (blog, FAQ extendida), no copy aprobado para publicar tal cual — por eso no llevan pill de Listo/Reescrito/Pendiente como el resto del documento, todas son 🆕. Organizado por pilar temático. El detalle completo de fuentes de los pilares 2, 3 y 4 vive en `LADX CLAUDE/Investigacion_IXP_gobernanza_regulacion.md` (para no duplicar tablas gigantes acá); el pilar 1 ya tiene sus datos en la Sección 09.

| Pilar | De qué trata | Candidatos a artículo | Candidatos a FAQ |
|---|---|---|---|
| **1. El mercado de IXP en Latinoamérica** | Panorama comparativo regional (Brasil, Argentina, Perú, México) — datos ya en Sección 09 | "¿Cómo se compara la infraestructura de internet de Chile con la región?" | "¿Cuál es el IXP más grande de Latinoamérica?" |
| **2. Modelos de gobernanza de IXP** | Sin fines de lucro (CABASE, NAP Perú) vs. multistakeholder (IX.br/CGI.br Brasil) vs. comercial (LADX, DE-CIX) vs. híbrido. LADX es un caso atípico: empresa comercial que declara neutralidad — una diferenciación real, bien planteada | "Por qué LADX opera distinto al resto de los IXP de la región (y qué significa para ti)" | "¿LADX es una empresa privada o una asociación sin fines de lucro?" |
| **3. Regulación estatal: qué funciona y qué no** | Casos de Brasil (habilitante, exitoso), Chile (obligación legal, funciona), Bolivia (imposición, problemático), México (cumplimiento parcial), Ecuador (sin regulación, funciona) | "Lo que Chile hizo bien al regular la interconexión de internet" | "¿La ley chilena obliga a los ISP a conectarse a un IXP local?" |
| **4. Por qué la neutralidad y la independencia importan** | Riesgos documentados de la intervención estatal en IXP (pérdida de neutralidad, vigilancia/censura vía DPI, inestabilidad política, competencia desleal) — en contraste, por qué un modelo privado + neutral + transparente como el de LADX da más garantías | "Neutralidad de red: por qué importa quién controla el punto de intercambio" | "¿Qué garantiza que LADX trate a todos los miembros por igual?" |
| **5. Qué es un IXP y por qué importa** | Educativo/definicional, para audiencias que no conocen el concepto | "Qué es un Internet Exchange Point y por qué tu empresa debería conectarse a uno" | "¿Qué es un IXP?" |
| **6. Infraestructura crítica de Internet** | Root DNS, RPKI, seguridad — usa los datos ya verificados en Secciones 02 y 09 | "Por qué alojar servidores Root DNS es un activo estratégico para un país" | "¿Qué significa que un IXP aloje servidores Root DNS?" |
| **7. Expansión regional de LADX** | Chile → Perú/Argentina/México — usa el estado real de cada país (Sección 04 y hallazgos de Sección 09) | "El camino de LADX hacia una red latinoamericana" | "¿En qué países opera LADX?" |
| **8. Cómo conectarte** | Guía práctica para ISP/CDN/universidades — usa los requisitos técnicos ya en Sección 03 | "Guía técnica para hacer peering en Chile" | "¿Qué necesito para conectarme a LADX?" |

---

## Resumen — pendientes de confirmar con Iván (consolidado de las 8 secciones)

*Actualizado 06-ago-2026 con la ronda de comentarios del cliente.*

1. **Países en los indicadores de Home:** decisión pendiente de aprobación final — recomendación de trabajo es cifra agregada/regional en Home y desglose técnico detallado por país en Sección 04 (ver Sección 01), a pedido de que refuerce la percepción de LADX como compañía regional.
2. **Cloud Exchange**: descripción completa del servicio, proveedores de nube conectados, público objetivo, ventajas.
3. **Ecosistema Digital**: qué incluye, alcance del servicio (hoy no existe como oferta publicada).
4. **Timeline de hitos** (Sección 02): confirmar fecha exacta de los hitos corporativos nuevos — apertura en México, apertura en Perú, constitución en Argentina, inicio de Cloud Exchange y expansión de red/ecosistema regional (Ecuador ya tiene año confirmado: 2026).
5. **Validación del copy reescrito de Principios y Diferenciador central** (Sección 02): se redactaron versiones más contundentes y con mirada regional a pedido del cliente — quedan como borrador sujeto a su aprobación antes de publicar.
6. **Perú, Argentina, México**: ciudades, datacenter, ASNs, puertos, capacidad, contacto local — hoy sin datos públicos. Ficha detallada pedida explícitamente por el cliente para esta primera versión.
7. **Ecuador** (país nuevo, Sección 04): solo se confirmó apertura de operaciones en 2026 — falta ciudad, datacenter, ASNs, puertos, capacidad y contacto local.
8. **USA**: ASNs/puertos/capacidad propios (hoy solo hay cifra nacional agregada) y contacto local.
9. **Ubicación final de Badajoz 45** (dirección legal/tributaria): se retiró de Infraestructura (Sección 04) y hoy solo aparece en Conectarse (Sección 07) como dato de contacto/corporativo — confirmar con el cliente si debe vivir ahí o en una futura sección legal/T&C.
10. **Migración de LinkedIn** (renombrar la página actual vs. crear una nueva para LADX) — el correo ya está confirmado: `info@ladx.net`.
11. **Quién ejecuta** la migración de correo/teléfono a `info@ladx.net` (aspecto operativo).
12. **Resolver DNS público** (`resolver1/2.pitchile.cl`, Sección 03): confirmar si también pasa a un hostname bajo `ladx.net`.
13. **Próximo evento** de la comunidad — ninguno anunciado aún.
14. **Resumen visual por evento histórico** (Sección 05): pedido nuevo del cliente — selección de fotos, principales participantes y breve descripción por evento; bloqueado hasta que entregue el material.
15. **Proceso editorial de Noticias** (Sección 06): definir responsable y periodicidad para que la sección no quede desactualizada — aspecto operativo, pedido por el cliente.
16. **Email de destino** del formulario de conexión (`conexiones@ladx.net` vs. `info@ladx.net`).
17. **Contactos locales** para Perú, Argentina, México, Ecuador y USA — el cliente confirmó que lo trabaja internamente (teléfono, correo y nombre de contacto por país).
18. **Fecha de lanzamiento oficial** de LADX y aprobación de todos los socios para el comunicado completo (Sección 06).
19. **Vigencia de las cifras** 151 ASN / 368 puertos / 30.6 Tbps a la fecha real de publicación, y el rol de "Daniel Fried, co-fundador" (FAQ, pregunta 10) — nombre no corroborado en el resto del documento.
20. **Discrepancia de capacidad (30.6 Tbps vs. 12.8–12.9 Tbps)** (Sección 09): dos trackers independientes (PeeringDB y Internet Society Pulse) muestran una capacidad muy inferior a la que se va a publicar — resolver antes del lanzamiento, sea actualizando esos perfiles o confirmando por qué difieren.
21. **Ranking regional por tráfico** (Sección 09): no se encontró fuente primaria para "2° en Latinoamérica / 4° mundial" — decidir con Iván si se publica igual (con su propia fuente) o se reemplaza por la comparación de capacidad ya documentada.
22. **Fuente oficial para citar Root DNS** (Sección 09): confirmar con el equipo técnico si prefieren enlazar al listado oficial de IANA u otra fuente primaria.
23. **Posibles Root DNS adicionales F y L en Santiago** (Sección 09): si se confirman, la cifra "seis réplicas" pasaría a ocho — verificar antes de cambiar el dato ya aprobado.
24. **Argentina posiblemente ya operativa** (Secciones 04 y 09): PeeringDB muestra una sede en Buenos Aires activa desde 2024, contradice el "sin datos públicos" actual — confirmar con Iván si ya se puede publicar.

