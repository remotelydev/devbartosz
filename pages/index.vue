<template>
  <section class="home">
    <h1>Bartosz Trzos</h1>
    <p>Progressive JavaScript engineer, with passion for UI and UX of web applications. Fast thinker and learner with a deep understanding of frontend side of website creation. Usually, work with Vue and React.</p>
    <div class="social">
      <a href="https://twitter.com/devbartosz">
        <Icon icon="twitter" />
      </a>
      <a href="https://github.com/Trzosoo">
        <Icon icon="github" />
      </a>
      <a href="https://www.linkedin.com/in/bartosz-trzos/">
        <Icon icon="linkedin" />
      </a>
    </div>
  </section>
</template>

<script>
import Icon from "../components/Icon";

export default {
  components: {
    Icon
  }
};
</script>
<style lang="scss" scoped>
@import "~/scss/vars.scss";

.home {
  max-width: 20rem;
  padding: 1rem;
}
.social {
  display: flex;
  justify-content: space-between;
  font-size: 2rem;
  a {
    color: $secondary;
    &:hover {
      color: darken($secondary, 10);
    }
  }
}
</style>

