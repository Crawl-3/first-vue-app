<template>
  <div class="home">
    <section class="hero">
      <h1 class="header">first-vue-app</h1>
      <div class="content">
        <p class="description">
          My first app with Vue. Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae
          magni est voluptatibus in, rem distinctio molestiae tempora.
        </p>

        <div class="buttons">
          <a
            href="https://github.com/WitecuseDev/first-vue-app"
            target="_blank"
            rel="noopener noreferrer"
          >
            <button class="primary">View on Github</button>
          </a>
        </div>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  display: flex;
  flex-direction: column;
  height: calc(100vh - 75px);
  justify-content: center;
  align-items: center;
  text-align: center;
  .header {
    font-size: 4rem;
    color: #42b983;
    margin-bottom: 20px;
  }
  .content {
    width: 50%;
    .description {
      font-size: 1.6rem;
      font-weight: 600;
      color: #777;
    }
    .buttons {
      // display: flex;
      // justify-content: flex-start;
      margin-top: 20px;
    }
  }
}
</style>
