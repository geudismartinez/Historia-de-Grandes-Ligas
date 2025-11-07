# 📊 Historia de Grandes Ligas

Este repositorio contiene un análisis histórico de estadísticas de MLB (Grandes Ligas de Béisbol) hasta la temporada 2015, usando Power BI y la base de datos Lahman.

---

## 📁 Contenido del proyecto

- `Historia de Grandes Ligas.pbix`: Archivo de Power BI con medidas DAX, visuales y filtros por año.
- `Bitacora_Tecnica.md`: Documentación de medidas, exclusiones lógicas y decisiones de diseño.
- `AVG por Año`, `HR por Año`, `Runs por Año`: Medidas calculadas con `CALCULATE` y `SUMMARIZE`.

---

## 🧠 Objetivos del análisis

- Comparar AVG, HR, RBI y Runs por año.
- Detectar rarezas estadísticas y exclusiones lógicas.
- Documentar el uso de DAX (`CALCULATE`, `SUMMARIZE`, `ALLEXCEPT`) en contexto narrativo.

---

## 🛠️ Cómo usar el archivo `.pbix`

1. Abre `Historia de Grandes Ligas.pbix` en Power BI Desktop.
2. Explora las visuales por año, jugador y métrica.
3. Revisa las medidas DAX en el panel de campos.
4. Consulta la bitácora técnica para entender la lógica detrás de cada medida.

---

## 🧾 Bitácora de medidas clave

| Medida | Descripción | Contexto |
|--------|-------------|----------|
| `Runs por Año` | Total de carreras por año | Usa `CALCULATE` con `FILTER` |
| `HR por Año` | Total de home runs por año | Corrige error de contexto |
| `AVG por Año` | Promedio de bateo por año | Calculado con `SUMMARIZE` |

---

## 📚 Recursos usados

- [Lahman Database](http://www.seanlahman.com/baseball-archive/statistics/)
- Power BI Desktop
- DAX: `CALCULATE`, `SUM`, `FILTER`, `SUMMARIZE`

---

## 📢 Autor

**Geudis Miguel Martínez**  
Auditor técnico y narrador de exclusiones lógicas en sistemas y deportes.  
[LinkedIn](https://www.linkedin.com/in/geudis-mart%C3%ADnez-0173ba11b/)
