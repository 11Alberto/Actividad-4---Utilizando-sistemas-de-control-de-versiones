git init
git remote add origin https://github.com/usuario/Actividad-4---Utilizando-sistemas-de-control-de-versiones.git

git add .
git commit -m "Subir proyecto funcional"
git push origin main

git checkout -b crear-tarea
git checkout -b editar-tarea
git checkout -b eliminar-tarea
git checkout -b completar-tarea
git checkout -b ver-tareas

git checkout main
git merge crear-tarea
git merge editar-tarea
git merge eliminar-tarea
git merge completar-tarea
git merge ver-tareas
git push origin main
