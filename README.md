

Dependencias

flask
flask_sqlalchemy
mysql-connector-python
mysqlclient

Conectando ao banco:
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://usuario:senha@localhost/banco'


Rotas

Create (post):
http://seu-ip/usuario

Update (put):
http://seu-ip/usuario/id

Delete (delete):
http://seu-ip/usuario/id

Listar usuarios (get):
http://seu-ip/usuarios

Filtar usuarios (get):
http://seu-ip/usuario/id

