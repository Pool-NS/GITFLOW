﻿# Gestor de Tareas
git checkout develop
git merge feature/tareas
git checkout -b release/1.0.0
# Realizar pruebas adicionales y ajustes
git checkout master
git merge release/1.0.0
git tag -a v1.0.0 -m "Lanzamiento de la versión 1.0.0"
git checkout develop
git merge release/1.0.0
