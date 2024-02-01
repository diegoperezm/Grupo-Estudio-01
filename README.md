# Grupo-Estudio-01


## Configuración Linux

Descargar repositorio a carpeta local:

```sh
git clone https://github.com/diegoperezm/Grupo-Estudio-01.git
```

Ingresar a carpeta del grupo de estudio

```sh
cd Grupo-Estudio-01
```

Crear carpeta con el nombre del participante (reemplazar `<nombre>`):

```sh
mkdir <nombre> 
```
crear un archivo con el nombre "apuntes" (reemplazar `<nombre>`):

```sh
echo 'Apuntes' > <nombre>/apuntes.txt 
```

Add y commit (reemplazar `<nombre>`)

```sh
git add <nombre>/apuntes.txt && git commit -m 'Agregar carpeta y archivo apuntes: <nombre>'

```

Subir los cambios a Github:

```sh
git push 
```




