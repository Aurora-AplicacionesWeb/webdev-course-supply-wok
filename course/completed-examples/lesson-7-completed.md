# Lesson 7 - Completed

## HTML

```
<div class="card">

  <img
    src="https://i.imgur.com/2DhmtJ4.jpeg"
    alt="Foto de perfil de Zayd Ayasta"
    class="profile-image"
  >

  <h1>Zayd Ayasta</h1>

  <p class="description">
    Hola, soy Zayd. Estoy aprendiendo a crear páginas web con HTML y CSS.
  </p>

  <h2>Mis intereses</h2>

  <ul>
    <li>Diseño web</li>
    <li>Música</li>
    <li>Videojuegos</li>
    <li>Tecnología</li>
  </ul>

  <a href="https://example.com" class="profile-link">
    Ver mi perfil
  </a>

</div>
```

## CSS

```
body {
  font-family: Arial, sans-serif;
  background-color: #f3f4f6;
  margin: 0;
  padding: 40px 20px;
}

.card {
  background-color: white;
  max-width: 350px;
  margin: 0 auto;
  padding: 24px;
  border-radius: 16px;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
}

.profile-image {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 16px;
}

h1 {
  margin: 0 0 12px;
  color: #222;
}

.description {
  color: #555;
  margin-bottom: 20px;
}

h2 {
  font-size: 20px;
  margin-bottom: 10px;
  color: #333;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0 0 24px;
}

li {
  background-color: #eef2ff;
  margin: 8px 0;
  padding: 10px;
  border-radius: 8px;
}

.profile-link {
  display: inline-block;
  text-decoration: none;
  background-color: #4f46e5;
  color: white;
  padding: 10px 18px;
  border-radius: 8px;
}

.profile-link:hover {
  background-color: #3730a3;
}
```
