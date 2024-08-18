<script>
</script>

<style>
 @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

.header-container {
  display: flex;
  justify-content: center;
  width: 100%;
  padding: 0 0.2rem; 
  box-sizing: border-box; 
}

header {
  display: flex;
  align-items: center;
  border: 2px solid #661f96;
  color: #661f96;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: 5px;
  font-family: 'Poppins', sans-serif;
  text-align: center;
  box-sizing: border-box;
}

.logo-title {
  display: flex;
  align-items: center;
  flex-direction: column;
  margin-bottom: 1rem;
}

.logo {
  max-height: 150px;
}

.middle-header {
  display: flex;
  flex-direction: column;
  align-items: center;
}

h1 {
  margin: 0;
  font-size: 1.5rem;
}

nav {
  padding: 0.2rem;
  border-radius: 5px;
  width: 100%; /* Make nav take full width */
}

nav ul {
  display: flex;
  flex-direction: column;
  align-items: center;
  list-style-type: none;
  padding: 0;
  margin: 0;
}

nav li {
  margin: 0.5rem 0; /* Add spacing between nav items */
}

nav a {
  text-decoration: none;
  color: #661f96; /* Ensure link color matches the theme */
}

nav a:hover {
  text-decoration: underline;
}

.sejour {
  max-height: 300px; 
  margin-top: 1rem;
}

@media (max-width: 600px) {

  header {
    padding: 0.5rem;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
    margin-bottom: 1rem;
    width: 100%;
    box-sizing: border-box; /* Ensure padding is included in the width */
  }

  h1 {
    font-size: 1.2rem;
  }

  .logo {
    max-height: 120px;
  }

  nav ul {
    flex-direction: column;
  }

  nav li {
    margin: 0.5rem 0;
  }
}

</style>

<div class="header-container">
  
  <header>
    <!-- <img src="sejour_intergen.png" alt="sejour intergen" class="sejour"> -->

    <div class="middle-header">
    <div class="logo-title">
      <img src="/petitprince.png" alt="Petit Prince Logo" class="logo" />
      <h1>Collection custom shoes <br />
        château d'Alleret été 2024 </h1>
    </div>
    <nav>
      <ul>
        <li><a href="/about">A propos de la collection</a></li>
        <li><a href="https://www.associationlepetitprince.fr/">L'association le petit prince</a></li>
      </ul>
    </nav>
  </div>
    <img src="petit_prince_custom_shoes.png" alt="petit prince avec custom shoes" class="sejour">
  </header>
</div>
