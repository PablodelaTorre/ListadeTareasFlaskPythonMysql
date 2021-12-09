El proyecto permite crear las tablas de una base de datos mysql desde python y con flask, además de conectar los formularios 
de los archivos html con las tablas, de manera totalmente funcional, permite el registro de usuario, y el inicio de sesion,
ademas de la incorporacion de textos que son modificables y guardados en las tablas de datos,
textos a los que solo tiene acceso el usuario que los creo, ademas permite que el usuario los modifique y los elimine. también permite el logout. A tener en cuenta que no se encuentra subida la carpeta de venv (entorno virtual) al repositorio ya que es demasiado pesada, para poder inicializar el programa se necesita desde terminal hacer los siguientes pasos:
pararse en la carpeta con los archivos y:
py -3 -m venv venv, damos enter
venv\Scripts\activate, damos enter
pip install Flask, damos enter
pip3 install mysql-connector-python, damos enter
set FLASK_APP=todo, damos enter
set FLASK_ENV=development, damos enter
set FLASK_DATABASE_HOST=localhost, damos enter
set FLASK_DATABASE_PASSWORD=contraseña, damos enter
set FLASK_DATABASE_USER=nombre de usuario, damos enter
set FLASK_DATABASE=nombre base de datos, damos enter
flask init-db, damos enter
flask run, damos enter