# Chuleta Altair

## Importar

```python
import altair as alt
```

## Bar Chart

```python
alt.Chart(trends).mark_bar().encode(
  x='search_term',
  y='mean(value)',
    color='search_term'
).properties(height=300, title="Búsquedas medias de términos de Data Science respecto a referencia").interactive()
```

## Scatter plot
```python
scatter = alt.Chart(df).mark_circle().encode(
    x="Body Weight",
    y="Brain Weight"
)
```

## Gráfico de línea
```python
line_years_trends = alt.Chart(trends).mark_line().encode(
    x='year(date):T',
    y='mean(value)',
    color='search_term'
).properties(
    title="Evolución de búsquedas anual",
)
```
