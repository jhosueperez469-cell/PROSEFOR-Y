 Certificado Web — GitHub Pages

Este repositorio contiene el certificado exportado desde Word, funcionando correctamente con imágenes y fecha automática.

## Estructura obligatoria
```
/
├─ index.html
└─ index_archivos/
     image001.png
     image002.png
```

## Cómo publicar en GitHub Pages
1. Sube `index.html` al repositorio.
2. Sube la carpeta `index_archivos/` completa con las imágenes.
3. Ve a **Settings → Pages**.
4. Selecciona:
   - **Branch:** main
   - **Folder:** /(root)
5. Guardar.

URL resultante:
```
https://<usuario>.github.io/<repositorio>/
```

## Fecha automática
El archivo index.html actualiza la fecha cada día automáticamente.

## Probar local
```
python -m http.server 8000
```
Abrir:
http://localhost:8000
