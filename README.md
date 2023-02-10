# User Base API.

## Api realizada en Node JS y Postgres.

### Su principal funcion es permitirnos crear usuarios protegiendo a este a traves de un token.

## Dependencias del Proyecto.

<ul>
<li>Bcrypt</li>
<li>Dotenv</li>
<li>Express</li>
<li>Jsonwebtoken</li>
<li>Passport</li>
<li>Passport JWT</li>
<li>Pg pg-hstore</li>
<li>Sequelize</li>
<li>UUID</li>
</ul>

## Instalar dapendencias

```sh
npm install
```

## Models

### Users

<ul>
<li>First Name</li>
<li>Last Name</li>
<li>User Name</li>
<li>Email</li>
<li>Password</li>
<li>Age</li>
<li>Rol</li>
<li>Country</li>
</ul>

## Routes

### Users

<ul>
<li>GET 
<br>
/api/v1/users
<br>

```
{TODOS LOS USUARIOS/ALL USERS}
```

</li>
<li>POST 
<br>
/api/v1/users
<br>

```
{Crear Usuario/Create User}
```

</li>
<li>GET 
<br>
/api/v1/users/:id
<br>

```
{Obtener Usuario segun ID/Get User By ID}
```

</li>
<li>PATCH 
<br>
/api/v1/users/:id
<br>

```
{Modificar Usuario segun ID/Patch User By ID}
! Login Requerido
```

</li>
<li>DELETE 
<br>
/api/v1/users/:id
<br>

```
{Eliminar Usuario segun ID/Delete User By ID}
!Login Requerido
```

</li>
</ul>

### Login

<ul>
<li>POST
<br>
/api/v1/login
<br>

```
{Logearse/Login}
! Regresa un Token para poder acceder a rutas como PATCH y DELETE
```

</li>
</ul>
