<style>
.navbar-light .navbar-toggler {
  border: none;
}
.navbar.sac {
  position: fixed;
  z-index: 10;
  padding: 0;
}
.navbar.sac button {
  padding: 0.5rem 1rem;
}
.navbar.sac .navbar-collapse {
  background: rgba(255, 255, 255, 0.8)
}
</style>

<template>
  <nav class="navbar navbar-expand-lg navbar-light sac">
    <button class="navbar-toggler" type="button" v-on:click.stop="active = !active">
      <span color="white" class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" :class="active ? 'show' : ''">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#about">About US<span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#schedule">Schedule</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      active: false
    }
  }
}
</script>