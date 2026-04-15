# Laboratorio Git

Proyecto correspondiente al **Laboratorio #2** de Git realizado por **Erick Sánchez**.


## Comandos utilizados

### Inicialización y configuración

```bash
git init
git branch -m main
git status
git log --graph --decorate --all --oneline
```

### Manejo de ramas

```bash
git checkout -b desarrollo
git branch
git merge desarrollo
```

### Control de cambios

```bash
git add .
git commit -m "Agrega contenido en index"
git diff
git reset --hard HEAD~1
git commit -m "Agrega gitignore"
```

### Conexión con repositorio remoto

```bash
git remote add origin https://github.com/iAmGrootCR04/laboratorio-git.git
git push -u origin main
git pull origin main
git pull origin main --allow-unrelated-histories
```

### Nueva funcionalidad (login)

```bash
git checkout -b login
git add .
git commit -m "Agrega login"
git push origin login
```

---

## Notas adicionales

* Se trabajó con múltiples ramas (`main`, `desarrollo`, `login`)
* Se resolvió un conflicto de historiales con:

  ```bash
  git pull origin main --allow-unrelated-histories
  ```
* El resto de la gestión del repositorio se realizó directamente en GitHub

---

## Autor

**Erick Sánchez Hidalgo**





