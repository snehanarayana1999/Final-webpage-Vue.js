<template>
  <nav class="navbar is-dark">
      <div class="container">
          <div class="navbar-brand">
              <a class="navbar-item brand-text" href="../index.html">
       BDJM
      </a>
              <div class="navbar-burger burger" data-target="navMenu">
                  <span></span>
                  <span></span>
                  <span></span>
              </div>
          </div>
          <div id="navMenu" class="navbar-menu">
              <div class="navbar-start">
                  <a class="navbar-item" href="admin.html">
          Home
        </a>
                  <a class="navbar-item" href="admin.html">
          New Request
        </a>
                               <a class="navbar-item" href="admin.html">
          Reports
        </a>
        <a class="navbar-item" href="admin.html">
          Documentation
        </a>
              </div>

          </div>
      </div>
  </nav>
</template>
<style scoped>
html, body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
  font-size: 16px;
  line-height: 1.5;
  height: 100%;
  background: #ECF0F3;
  
}
nav.navbar {
   border-top: 4px solid #276cda;
  margin-bottom: 1rem;
  
 
}

.navbar-item.brand-text {
  font-weight: 300;
  
}
.navbar-item, .navbar-link {
  font-size: 14px;
  font-weight: 700;
}
</style>