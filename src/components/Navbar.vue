<template>
  <div class="navbar-contianer">
    <h1>Konsulter & Partners AB</h1>
    <nav class="nav">
      <router-link to="/"
        ><i class="fas fa-home nav-icons"></i>
        <p>Hem</p>
      </router-link>
      <router-link to="/about"
        ><i class="fas fa-address-card nav-icons"></i>
        <p>Om oss</p></router-link
      >
      <router-link to="/contact"
        ><i class="fas fa-envelope nav-icons"></i>
        <p>Kontakt</p>
      </router-link>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navbar-contianer {
  background-color: #0652dd;
}

h1 {
  text-align: center;
  color: white;
  padding-top: 20px;
  font-size: 50px;
}

.nav {
  display: flex;
  list-style-type: none;
  justify-content: center;
  font-size: 20px;

  &-icons {
    display: flex;
    justify-content: center;
  }

  a {
    text-decoration: none;
    color: white;
    margin: 0 20px 0;
  }

  a:hover {
    color: cornflowerblue;
  }
}
</style>
