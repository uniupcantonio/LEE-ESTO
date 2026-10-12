# Guía rápida de commits

## Commit 1

1. Descarga `ea7750u202416147-commit1.zip`.
2. Clic derecho > **Extraer aquí**.
3. Abre la carpeta `ea7750u202416147` en WebStorm (**Open**).
4. En la **Terminal** de WebStorm pega esto. Pon el link de tu repositorio donde dice LINK_DE_TU_REPO:

```
npm install
git config user.name "Carlos Céspedes"
git config user.email "u202416147@upc.edu.pe"
git init -b main
git add .
git commit -m "chore: initial project setup with angular material, ngx-translate and json-server"
git remote add origin LINK_DE_TU_REPO
git push -u origin main
```

Si al hacer el push te pide iniciar sesión en GitHub, acepta en el navegador.

**Esta carpeta es tu proyecto.** No la borres ni la cambies de lugar, porque ahí se guardan los commits.

## Commit 2 en adelante (siempre igual)

1. Descarga el zip del commit y haz clic derecho > **Extraer aquí** en otra carpeta, por ejemplo Descargas.
2. Abre la carpeta que salió, selecciona todo (`Ctrl + A`) y copia (`Ctrl + C`).
3. Ve a la carpeta de tu proyecto (la del commit 1), pega (`Ctrl + V`) y elige **Reemplazar los archivos**.
4. En la **Terminal** de WebStorm pega esto, con el mensaje de ese commit:

```
git add .
git commit -m "MENSAJE DEL COMMIT"
git push
```

## Mensajes

| Zip | Mensaje |
|-----|---------|
| commit1 | `chore: initial project setup with angular material, ngx-translate and json-server` |
| commit2 | `feat(shared): add layout with toolbar, sidenav and language switcher` |
| commit3 | `feat(shared): add base infrastructure, routes and page not found view` |
| commit4 | `feat(bookstores): add bookstore and book stock domain, infrastructure and stores` |
| commit5 | `feat(bookstores): add bookstore overview with store inventory summaries` |
| commit6 | `feat(catalog): add open library books api and specialty selection` |
| commit7 | (va con el zip) |
| commit8 | (va con el zip) |

## Para probar la app

En una terminal de WebStorm pega `npm run server`. En otra (botón **+**), `npm start`. Luego entra a http://localhost:4200
