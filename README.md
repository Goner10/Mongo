# Mongo 🖥️🛠️ 

<h2>Crear colecciones de Users y Posts</h2>

- db.createCollection('posts')
- db.createCollection('users')

<h2>Insertar al menos 15 publicaciones nuevas</h2>

- db.posts.insertOne([
 {
   Title: 'Cómo cocinar arroz',
   Body: 'Aquí te enseñamos paso a paso cómo cocinar arroz perfecto.',
   Username: 'Chef Juan',
   Comments: {
     Username: 'Mariana',
     Body: '¡Gracias por la receta! Acabo de probarla y me quedó delicioso.'
   }
 }
 ])
 
 - db.posts.insertMany([
 {
   Title: 'Cómo cuidar a tu perro en verano',
   Body: 'Con el calor del verano, es importante tomar medidas para cuidar a tu mascota. Aquí te damos algunos consejos útiles.',
   Username: 'Doglover',
   Comments: {
     Username: 'Mariana',
     Body: '¡Gracias por los consejos! Acabo de probarla y me quedó delicioso.'
   }
 },
 {
   Title: 'Reseña de la película Joker',
   Body: 'Esta película es una obra maestra del cine. Joaquin Phoenix ofrece una actuación impresionante.',
   Username: 'Cine23',
   Comments: {
     Username: 'Mariana',
     Body: '¡Coincido!'
   }
 }
 ])
 
 -  db.posts.insertMany([
 {
   Title: 'Los mejores destinos para viajar en otoño',
   Body: 'El otoño es una temporada ideal para viajar y disfrutar de los paisajes con tonos anaranjados y rojizos. Descubre los destinos más hermosos para visitar en esta época del año.',
   Username: 'TravelerX',
   Comments: {
     Username: 'Pablo',
     Body: 'Me encantaría visitar todos estos lugares.'
   }
 },
 {
   Title: 'Receta de ensalada de quinoa y aguacate',
   Body: 'La quinoa es un ingrediente muy saludable y versátil en la cocina. Te compartimos una deliciosa receta de ensalada con quinoa, aguacate y otros ingredientes nutritivos.',
   Username: 'HealthyEats',
   Comments: {
     Username: 'Ana',
     Body: 'Me encanta la quinoa, definitivamente voy a probar esta receta.'
   }
 }
 ])
 
 - db.posts.insertMany([
 {
   Title: 'Los mejores libros para leer en vacaciones',
   Body: 'Si buscas una buena lectura para disfrutar en tus vacaciones, aquí te recomendamos algunos de los mejores libros de todos los tiempos. ¿Cuál es tu favorito?',
   Username: 'Bookworm',
   Comments: {
     Username: 'Juan',
     Body: 'Me encantó "Cien años de soledad" de Gabriel García Márquez.'
   }
 },
 {
   Title: 'Consejos para ahorrar en la compra del supermercado',
   Body: 'Hacer la compra en el supermercado puede ser costoso, pero existen trucos para ahorrar dinero en tus compras sin tener que sacrificar la calidad. Aquí te contamos algunos.',
   Username: 'FrugalLiving',
   Comments: {
     Username: 'María',
     Body: 'Gracias por los consejos, definitivamente los pondré en práctica.'
   }
 }
 ])
 
 **Vista de los posts creados en MongoDB**
 
