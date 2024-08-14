<script>
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

  .header-container {
    display: flex;
    justify-content: center; /* Center horizontally */
    width: 100%;
  }

  header {
    display: flex;
    justify-content: space-between; /* Distribute space between items */
    align-items: center;
    border: 2px solid #661f96; /* Add border with the specified color */
    color: #661f96;
    padding: 1rem;
    margin-bottom: 1rem;
    border-radius: 5px;
    /* display: inline-block; */
    font-family: 'Poppins', sans-serif;
  }

  .logo-title {
    display: flex;
    align-items: center;
    flex-direction: column;
    /* text-align: center; */
  }

  .logo {
    max-height: 130px;
    /* border-radius: 5px; */
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
    margin-top: 1rem;
    border-radius: 5px;
  }

  nav ul {
    display: flex;
    justify-content: space-around;
    list-style-type: none;
    padding: 0;
    margin: 0;
  }

  nav li {
    margin: 0 1rem;
  }

  nav a {
    text-decoration: none;
  }

  nav a:hover {
    text-decoration: underline;
  }
  .sejour {
    max-height: 300px;
  }
</style>

<div class="header-container">
  
  <header>
    <!-- <img src="sejour_intergen.png" alt="sejour intergen" class="sejour"> -->

    <div class="middle-header">
    <div class="logo-title">
      <img src="/petitprince.png" alt="Petit Prince Logo" class="logo" />
      <h1>Collection custom shoes <br />
        Chateau d'Alleret été 2024 </h1>
    </div>
    <nav>
      <ul>
        <li><a href="https://www.associationlepetitprince.fr/">l'association</a></li>
        <li><a href="/about">A propos de la collection</a></li>
      </ul>
    </nav>
  </div>
    <img src="petit_prince_custom_shoes.png" alt="petit prince avec custom shoes" class="sejour">
  </header>
</div>
