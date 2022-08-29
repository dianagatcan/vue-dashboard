<template>
  <aside class="dashboard">
    <header>
      <img src="@/assets/B-icon.svg" alt="B-icon" />
      <h1 class="header-title">Boundary <span>Care</span></h1>
    </header>
    <img src="@/assets/Line1.svg" alt="line " />
    <section class="profile">
      <h1 class="section-name">Chance Vetrovs</h1>
      <button class="disconnect-btn">Disconnect</button>
    </section>
    <img src="@/assets/Line1.svg" alt="line " />
  </aside>
</template>

<script>
export default {
  name: "SidebarComponent",
};
</script>

<style scoped>
.dashboard {
  width: 16.5rem;
  min-height: 100vh;
  background-color: #0e3469;
  display: flex;
  flex-direction: column;
  align-items: center;
}
header {
  display: flex;
  padding-top: 1.5rem;
  padding-bottom: 1rem;
  font-size: 1.5rem;
}

h1 {
  color: #ffffff;
}

span {
  color: #429580;
}

.header-title {
  padding-left: 1rem;
  font-size: 1.5rem;
}

.profile {
  padding-top: 1.75rem;
  padding-bottom: 1.5rem;
  display: flex;
  flex-direction: column;
}

.section-name {
  font-size: 1rem;
}
.disconnect-btn {
  border: none;
  background-color: inherit;
  text-decoration: underline;
  font-size: 1rem;
  color: #889cb5;
  /* color??? */
}
</style>

<!-- 
/* font-family: $lato;
display: flex;
flex-direction: column;
background-color: $gray;
color: $white;
overflow: hidden;
padding: 1rem; -->
