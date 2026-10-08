# 2.1.3 Coeficiente de Tau de Kendall (τ)

**Asignatura:** Análisis y visualización de datos (GAD-2401)  
**Carrera:** Ingeniería Informática  
**Institución:** Tecnológico de Estudios Superiores de Chalco  

---

## Descripción

Sitio web educativo (HTML) + práctica en Jupyter sobre el **Coeficiente Tau de Kendall**, basado en pares concordantes y discordantes.

Ideal para **GitHub Pages**.

## Estructura

```
tema-2.1.3-kendall-html/
├── index.html
├── 01-introduccion.html
├── 02-formula-y-calculo.html
├── 03-interpretacion.html
├── 04-propiedades.html
├── 05-ejemplos.html
├── css/estilos.css
├── ejercicios/ejercicios-manuales.html
├── practica/practica_kendall.ipynb
├── requirements.txt
└── README.md
```

## Cómo ver las páginas

- **Local:** abrir `index.html` en el navegador.
- **GitHub Pages:** Settings → Pages → rama `main`, carpeta root.

## Práctica Jupyter

```bash
pip install -r requirements.txt
jupyter notebook practica/practica_kendall.ipynb
```

O subir el `.ipynb` a [Google Colab](https://colab.research.google.com).

## Flujo recomendado

1. Leer teoría HTML (1 → 5).
2. Resolver ejercicios manuales en el cuaderno (contar pares C y D).
3. Verificar con el notebook.
4. Completar ejercicios adicionales.

## Los tres coeficientes (resumen)

| Aspecto | Pearson | Spearman | Kendall |
|---------|---------|----------|---------|
| Base | Valores | Rangos | Pares C/D |
| Relación | Lineal | Monótona | Monótona |
| Muestra pequeña | — | Bien | Excelente |
| Empates | — | Aceptable | Muy bueno |

---

**Material generado para GAD-2401 · Uso educativo · 2026**
