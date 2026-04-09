# Introducción a los Sistemas Dinámicos y la Teoría Ergódica

Resúmenes y apuntes de clase en LaTeX para el curso "Introducción a los Sistemas Dinámicos y la Teoría Ergódica".

**Semestre:** Otoño 2026  
**Facultad:** Facultad de Ciencias Físicas y Matemáticas  
**Universidad:** Universidad de Chile

## Contenido

- **C1** - Capítulo 1
- **C2** - Capítulo 2

## Compilación en VS Code

### Requisitos
- LaTeX instalado (TeX Live o MiKTeX)
- Extensión "LaTeX Workshop" instalada en VS Code

### Pasos
1. Abre VS Code y navega a la carpeta del proyecto
2. Abre el archivo `main.tex` dentro de cada capítulo
3. Presiona `Ctrl + Alt + B` (o usa la paleta de comandos: "LaTeX Workshop: Build")
4. El PDF se generará automáticamente en la misma carpeta

### Alternativa: compilar manualmente
```bash
cd C1  # o C2
pdflatex main.tex
pdflatex main.tex  # ejecutar dos veces para referencias
```

## Estructura del proyecto

```
Ergodica/
├── C1/
│   ├── main.tex           # Archivo principal del capítulo
│   ├── main.pdf           # PDF compilado
│   ├── commands.tex       # Comandos y definiciones personalizadas
│   ├── recuerdo.tex       # Contenido previo/recordatorio
│   ├── classes/           # Notas de clases individuales
│   └── img/               # Imágenes y figuras
├── C2/
│   └── (estructura similar)
└── README.md
```

## Nota
Los archivos PDF compilados no se incluyen en el repositorio (están en `.gitignore`). Para obtener los PDFs, compila los archivos `.tex` localmente.
