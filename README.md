# REVISAR ARCHIVO PC3.IPYNB



# PC3 - Grupo B
## Parte II. Recuperacion de datos
Se utilizó la API pública TheCatAPI mediante el endpoint:

```text
https://api.thecatapi.com/v1/breeds
```

Se recuperaron 15 registros de razas de gatos.

### Atributos extraídos

- Nombre de la raza
- País de origen
- Inteligencia
- Esperanza de vida

### Expresión regular utilizada

```python
re.findall(r"\d+", vida)
```

Esta expresión permite extraer los números presentes en el campo de esperanza de vida.
