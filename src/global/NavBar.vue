<template>
    <nav class="navbar navbar-expand-lg fixed-top navbar-scroll" :class="{ 'navbar-scroll': hasScrolled }">
        <div class="container">
            <img src="Assets/logo.png" height="70" alt="" loading="lazy" />
            <button class="navbar-toggler ps-0" type="button" data-mdb-toggle="collapse" data-mdb-target="#navbarExample01"
                aria-controls="navbarExample01" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon d-flex justify-content-start align-items-center">
                    <i class="fas fa-bars"></i>
                </span>
            </button>
            <div class="collapse navbar-collapse" id="navbarExample01">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item active">
                        <a class="nav-link" aria-current="page" href="#news">News</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#pets">Pets</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#adoptions">Adoptions</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#foundation">Foundation</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#help">How can I help?</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#education">Education</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#about">About us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page" href="#contact">Contact</a>
                    </li>
                </ul>

                <ul class="navbar-nav flex-row">
                    <li class="nav-item">
                        <a class="nav-link px-2" href="#!">
                            <i class="fab fa-facebook-square"></i>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link px-2" href="#!">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link ps-2" href="#!">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
.navbar {
  background-color: transparent; /* Set the background to transparent to make it see-through */
}

.navbar-scroll {
  background-color: #000; /* Change this to the desired background color when scrolling */
}

.navbar-nav .nav-link {
  color: white !important; /* Change the text color of the navbar links to white */
}
</style>

<script scoped>
export default {
    name: 'navBar',
    data() {
    return {
      hasScrolled: false,
    };
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  methods: {
    handleScroll() {
      this.hasScrolled = window.scrollY > 0;
    },
  },
}
</script>