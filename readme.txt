Crear .env y colocar DB_URL= + conection string como lo da el mismo mongodb, ejemplo:
"mongodb://usuario:contraseña@localhost/dbname".
Crear database con nombre "practicaIntegradora2" y dentro las colecciones "courses" y "users".
Dentro de "courses" agregar:
{
  "_id": {
    "$oid": "65cd5b5a8b01d3003a5a7a8f"
  },
  "title": "Programacion Full stack",
  "description": "En este curso aprenderas a programar desde 0 hasta tener una pagina en produccion",
  "teacher": "sin asignar",
  "students": [],
  "__v": 0
};
{
  "_id": {
    "$oid": "65cd5b738b01d3003a5a7a91"
  },
  "title": "Programacion de aplicaciones mobiles",
  "description": "En este curso aprenderas a programar desde 0 hasta tener una aplicacion en las tiendas",
  "teacher": "sin asignar",
  "students": [],
  "__v": 0
};
{
  "_id": {
    "$oid": "65cd5b978b01d3003a5a7a93"
  },
  "title": "Diseno de experiencias UX/UI",
  "description": "Todo lo necesario para crear experiencias de usuarios que generen impacto",
  "teacher": "sin asignar",
  "students": [],
  "__v": 0
}

Rutas: http://localhost:8080/
       http://localhost:8080/signup
       http://localhost:8080/users
       http://localhost:8080/courses
       http://localhost:8080/profile