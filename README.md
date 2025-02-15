# Cosas a tomar en cuenta, ya que soy principiante:

# 1- Pasos para guardar cambios en Git

# Si hiciste cambios en tu código y quieres guardarlos correctamente en Git, sigue estos pasos: 
# - Ver los archivos modificados (opcional)
# Antes de guardar los cambios, puedes ver qué archivos han sido modificados con el siguiente comando:
# git status
# Este comando te mostrará qué archivos han cambiado, cuáles están listos para ser guardados y cuáles aún no.

# - Preparar los cambios para guardarlos
# Antes de guardar los cambios, debes agregarlos a la "zona de preparación". Puedes hacer esto de dos formas:

# - Para agregar todos los archivos modificados:
# git add .

# Si quieres agregar solo un archivo específico, usa:
# git add nombre_del_archivo.ext
# Esto le indica a Git que esos archivos deben incluirse en el siguiente commit.

# - Guardar los cambios con un commit
# Una vez que los archivos están preparados, debes hacer un commit con un mensaje descriptivo sobre los cambios:
# git commit -m "Descripción de los cambios"

# Ejemplo:

# git commit -m "Corregí un bug en la función de login"

# Un commit no sube los cambios a GitHub, solo los guarda localmente.

# - Subir los cambios a GitHub
# Para enviar los cambios a tu repositorio en GitHub, usa:
# git push origin main

# Si tu rama principal se llama master en lugar de main, usa master en lugar de main."