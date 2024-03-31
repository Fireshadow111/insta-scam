<template>
  <div id="home">
    <header>
      <h1>This is the home page</h1>
    </header>
    <aside>
      <h2>Navigation</h2>
      <nav>
        <ul>
          <li><a href="#explore">Explore</a></li>
          <li><a href="#following">Following</a></li>
          <li><a href="#profile">Profile</a></li>
          <!-- Add more navigation items as needed -->
        </ul>
      </nav>
    </aside>
    <main>
      <section id="explore">
          <h2>Explore</h2>
          <div class="post">
            <img src="https://via.placeholder.com/400" alt="Post 1">
            <p>This is a sample post.</p>
          </div>
            <!-- Add more posts as needed -->
      </section>
      <section id="following">
        <h2>Following</h2>
        <!-- Add posts for the Following section -->
      </section>
      <section id="profile">
        <h2>Profile</h2>
        <!-- Add profile information here -->
      </section>
    </main>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
/* Basic styling */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
header {
  margin-left: 270px;
  background-color: #405DE6;
  color: #fff;
  padding: 10px;
  text-align: center;
}
aside {
  background-color: #f4f4f4;
  padding: 10px;
  width: 250px;
  height: 100vh;
  overflow-y: auto; /* Enable scrolling if content exceeds the height */
  position: fixed;
  top: 0;
  left: 0;
}
main {
  margin-left: 270px; /* Width of aside + some space */
  padding: 20px;
}
section {
  margin-bottom: 30px;
}
/* Style for the posts */
.post {
  border: 1px solid #ccc;
  padding: 10px;
  margin-bottom: 20px;
}
.post img {
  max-width: 100%;
  height: auto;
}

</style>