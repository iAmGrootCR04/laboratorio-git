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

## Capturas de la terminal
<img width="1600" height="582" alt="Primera" src="https://github.com/user-attachments/assets/cd1b651b-d4af-41db-a4c9-aa0b2fb4b144" />

<img width="1600" height="412" alt="Segunda" src="https://github.com/user-attachments/assets/649f0433-3f52-4cb5-bd7a-20f70bb4c2bd" />

<img width="1600" height="846" alt="Css sin cambios" src="https://github.com/user-attachments/assets/66658d10-8c70-431b-9d9c-e16fcf7c0951" />

<img width="1600" height="786" alt="Cambios en el css sin commit" src="https://github.com/user-attachments/assets/ae5667fd-b4d0-4a0f-8fed-e77c545ba3d3" />

<img width="1600" height="926" alt="Eliminar commit con cambios" src="https://github.com/user-attachments/assets/fd7b0f38-4d1d-4093-837d-8744bc844fc0" />

<img width="1505" height="365" alt="Recuperación de un commit borrado" src="https://github.com/user-attachments/assets/1bb6d332-8822-4190-82d7-d0785dfeac78" />

<img width="1600" height="589" alt="Creacion del gitignore" src="https://github.com/user-attachments/assets/fab5dc73-e7f8-4df0-a7e0-b1082331c78f" />

<img width="1584" height="556" alt="Vinculación con github" src="https://github.com/user-attachments/assets/80185e26-a847-43b7-885b-d8f2f581c7f1" />

<img width="1600" height="456" alt="Solución del problema" src="https://github.com/user-attachments/assets/354cfd33-07ba-4c5c-9b6e-1ef2c9c9afa9" />

## Autor

**Erick Sánchez Hidalgo**
