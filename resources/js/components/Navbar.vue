<template>
  <header id="header" class="header d-flex align-items-center fixed-top">
      <div class="container-fluid container-xl position-relative d-flex align-items-center">
          <a href="#" class="logo d-flex align-items-center me-auto">
              <img src="/public/images/gurr-logo.png" alt="ico">
              <h1 class="sitename">Gurr</h1>
          </a>
          <nav id="navmenu" class="navmenu">
              <ul>
                  <li><a href="#banner" class="active">Home</a></li>
                  <li><a href="#services">Services</a></li>
                  <li><a href="#contact">Contact</a></li>
              </ul>
              <i class="mobile-nav-toggle d-xl-none bi bi-list"></i>
          </nav>
      </div>
  </header>
</template>

<script>
export default {
  name: "Navbar"
};
</script>
