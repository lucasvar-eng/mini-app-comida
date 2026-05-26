# Comidas Lucas

Mini app personal de nutricion: registro diario de comidas, ideas, gustos y tendencia de peso.

PWA estatica (HTML/CSS/JS) servida via GitHub Pages. Datos persistidos en localStorage del navegador.

## Tabs

- **Inicio**: constructor rapido de comidas.
- **Ideas**: ~50 recetas filtrables por ingrediente y situacion.
- **Gustos**: tabla de gustos tipicos (pizza, helado, alfajores, etc.) con kcal y macros.
- **Registro**: check-in diario, comidas por horario, tendencia de peso.

## Correr local

```bash
python3 -m http.server 8787
```

Y abrir `http://localhost:8787`.

## Backup

Tab Registro -> "Exportar registros" guarda un JSON. "Importar registros" lo restaura.
