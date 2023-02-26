<template>
  <footer>
    <ul class="hz">
      <li>
        <a class="flex" href="https://github.com/AsserElfeki/nuxtfood#readme">
          <img class="img" src="../assets/github.png" alt="github icon" />
          <p>GithubRepo</p>
        </a>
      </li>

      <li>
        <a class="flex" href="https://www.linkedin.com/in/asserelfeki/">
          <img class="img" src="../assets/linkedin.png" alt="LinkedIn icon" />
          <p>LinkedIn</p>
        </a>
      </li>
    </ul>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.hz{
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;
    padding: 0;
    margin: 0;
}

.flex {
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  flex-direction: column;
}
.img {
  width: 30px;
  height: 30px;
}
</style>
