# Presentación Ley Notarial — Contexto del Proyecto

## ¿Qué es esto?
Presentación HTML de 19 diapositivas para la ponencia del **Dr. Jorge Isaac Valarezo Guerrero**, Notario 54° del Cantón Quito, en el Colegio de Abogados de Pichincha, 17 de junio de 2026.

**Archivo principal:** `index.html` (todo en un solo archivo)
**Publicado en:** https://jivalare-lab.github.io/presentacion-ley-notarial/
**Repositorio:** https://github.com/jivalare-lab/presentacion-ley-notarial (cuenta: jivalare-lab)

## Regla de oro: NUNCA inventar nada
Todo dato, fecha, nombre, número de artículo o cita debe estar verificado en fuente real antes de escribirse. Si no se puede verificar, no va. Esta regla surgió después de que la primera versión contenía:
- Un nombre incorrecto (Gonzalo Díaz → correcto: Gonzalo Díaz de Pineda)
- Un artículo derogado citado como vigente (Art. 14 → derogado 2009; correcto: Art. 20)
- Un artículo mal asignado (Art. 6 no es de requisitos; los requisitos están en el COFJ)
- Una cita sin autor real ("Doctrina Notarial Latinoamericana")
- Contenido aspiracional presentado como ley vigente (telemática ya es ley desde 2020)

## Estructura actual (19 diapositivas)
1. Portada
2. Agenda
3. Antes de la Ley: Época de los Escribanos (1534)
4. **Del Manuscrito a la Máquina (1534–1966)** ← diapositiva histórica nueva
5. Clemente Yerovi Indaburu / Decreto 1404
6. Lo que cambió la Ley 1404
7. Seis Décadas de Reformas (línea del tiempo)
8. De Testigo a Juez de Paz Preventivo
9. Requisitos para ser Notario
10. Prohibiciones (Art. 20)
11. Deberes del Fedatario
12. Atribuciones del Notario (Art. 18)
13. El Protocolo Notarial
14. La Era Digital (Telemática vigente desde 2020)
15. Firma Electrónica y Comparecencia Telemática
16. Protección de Datos (LOPDP 2021)
17. Ecosistema Notarial del Mañana (perspectivas)
18. Conclusión
19. **Bibliografía con 9 fuentes y links oficiales** ← nueva

## Fuentes verificadas y artículos clave
| Contenido | Fuente | Artículo/RO |
|---|---|---|
| Definición del notario | Ley Notarial | Art. 6 |
| Requisitos para ser notario | COFJ + Const. Art. 200 | COFJ |
| Prohibiciones | Ley Notarial | Art. 20 (Art. 14 fue derogado en 2009) |
| Atribuciones | Ley Notarial | Art. 18 (38 numerales) |
| Deberes | Ley Notarial | Art. 19 |
| Telemática | Ley Org. Ref. COFJ | R.O. 345-S, 8-XII-2020 (Arts. 18.1, 18.2) |
| LOPDP | Ley Org. Prot. Datos | R.O. 459, 26-V-2021 |
| Primer escribano | FEN — historia | Gonzalo Díaz de Pineda, 28-VIII-1534 |
| Cambio nombre 1937 | D.S. 94 | R.O. 464, 6-IV-1937 (Federico Páez) |
| Archivo Nacional | Decreto Presidencial | Creado 17-I-1884 (Pdte. Caamaño) |

## Reformas de la Ley Notarial (cronología verificada con RO)
- **1966:** D.S. 1404, R.O. 158, 11-XI-1966 — Ley Notarial original
- **1978:** D.S. 2386, R.O. 564, 12-IV-1978 — agrega nums. 5 y 6 al Art. 18
- **2006:** Ley 2006-62, R.O. 406, 28-XI-2006 — competencias extrajudiciales
- **2008:** Constitución Montecristi, R.O. 449, 20-X-2008
- **2009:** COFJ, R.O. Suplemento 544, 9-III-2009 — deroga Arts. 9–17 Ley Notarial
- **2015:** COGEP, R.O. Suplemento 506, 22-V-2015 — 8 nuevas atribuciones
- **2020:** Ley Org. Ref. COFJ, R.O. Suplemento 345, 8-XII-2020 — telemática
- **2021:** LOPDP, R.O. Suplemento 459, 26-V-2021 — protección de datos
- **2024:** R.O. 4.° Suplemento 610, 29-VII-2024 — última reforma (lavado de activos)

## Diseño / Estética
- Tipografías: Playfair Display, Cormorant Garamond, Inter (Google Fonts)
- Paleta: ivory, charcoal, gold-muted (#B8A07E), bronze (#A08860)
- Transiciones: blur + scale, 0.85s cubic-bezier
- Navegación: teclas ←→, barra espaciadora, flechas auto-hide, dots, touch swipe
- Botón pantalla completa (F o botón esquina)
- Responsive para móvil

## Scripts útiles del proyecto
- `export_pptx.py` — exporta la presentación a PowerPoint
- `script_to_pdf.py` — genera `SCRIPT_PONENCIA.pdf` desde `SCRIPT_PONENCIA.md`
- `SCRIPT_PONENCIA.md` — guión de 90 minutos con marcas de tiempo y acotaciones
