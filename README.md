# StudentHub

StudentHub es una plataforma digital para gestionar estudiantes, cursos y servicios académicos universitarios.

## Funcionalidades

- Gestión de estudiantes
- Gestión de cursos

## Equipo

- Developer A
- Developer B

El proyecto será desarrollado colaborativamente utilizando Git y GitHub.

# 12. Preguntas de reflexión

Responder individualmente al finalizar.

### 1. ¿Cuál es la diferencia entre `git add` y `git commit`?
El git add prepara el archivo para que posteriormente con el git commit se guarde la version del archivo

---

### 2. ¿Cuál es la diferencia entre `git push` y `git pull`?
git push envia del repositorio local al repositorio remoto
git pull envia del repositorio remoto al repositorio local

---

### 3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?
el repositorio local se encuentra en la maquina que estamos utilizando
el repositorio remoto se encuentra en la aplicacion web de github

---

### 4. ¿Qué problema resuelve una rama?
la rama es un espacio de trabajo independiente en el cual se pueden realizar cambios y dichos cambios no se van a ver reflejados en el main

---

### 5. ¿Qué diferencia existe entre `git merge` y `git rebase`?
git merge mezcla dos versiones en una sola
git rebase cambia el orden en el que esta organizada la historia de versiones

---

### 6. ¿Por qué ocurre un conflicto?
porque git no sabe como reaccionar cuando tiene que decidir que version escoger por encima de otra, en los casos que al estar en espacios de trabajo diferentes se puede modificar la misma linea, el mismo nombre de archivo, etc. de cada rama involucrada, al intentar juntar las versiones ocurre un conflicto

---

### 7. ¿Quién debe decidir cómo resolver un conflicto?
la persona
---

### 8. ¿Qué problema resuelve un Pull Request?
revisar antes de mezclar versiones

---

### 9. ¿Por qué es recomendable revisar un Pull Request antes de integrarlo?
para que la decision de los cambios a integrar sea en conjunta y monitoreada
---

### 10. ¿Qué ventaja tiene trabajar en una rama en lugar de modificar directamente `main`?
los cambios que se hagan en ramas distintas a la del main no van a modificar la rama main, por lo tanto el codigo siempre va a mantener su estructura y las ramas antes de llegar a la rama main pasan por muchos filtros de revision.

---