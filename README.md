# Temario curso Microsoft 365

Versión completa con temario agrupado en Básico y Avanzado. Tiene píldoras adicionales para añadir temario transversal como Teams, IA o OneDrive.

## Enlaces

- Netlify: Rama `inserta-andalucia` [https://curso-office365.netlify.app/](https://curso-office365.netlify.app/). 
- GitHub: Rama `main` [https://borilio.github.io/curso-microsoft365/](https://borilio.github.io/curso-microsoft365/)

## Ramas

Se crearán distintas ramas para distintas versiones que pueda tener el curso.

- 2025/07/07 -> `main`: Rama principal con la primera versión del curso.
- 2025/07/07 -> `inserta-andalucia`: Rama con la versión preparada para el curso Inserta Andalucía. Es la que está desplegada en netlify.

## Crear nueva rama (curso nuevo)

Se crea la rama y nos movemos a ella:

```bash
git checkout -b curso-nuevo main
```

Se hacen las modificaciones oportunas (dejando la rama `main` a salvo) y se despliega en netlify usando la rama concreta del curso.

## Hacer cambios en temario base y fusionar ramas

Si se mejora el temario base en `main`, se puede actualizar la rama de un curso concreto:

```bash
git checkout curso-nuevo
git merge main
```

Recuerda actualizar el `README.md` para explicar las ramas y los cambios y las fechas.

