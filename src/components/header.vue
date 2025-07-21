<template>
  <header>
    <h1>My Work</h1>
    <nav>
      <ul>
        <li><a href="#">About</a></li>
        <li><a href="#">Works</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Contact</a></li>
        <li>
          <a href="#">
            <img src="../assets/icon-instagram.png" alt="インスタグラムのロゴ" />
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  width: 960px;
  margin: 0 auto;
  padding: 12rem 4%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
h1 {
  font-size: 3.2rem;
}
ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
  column-gap: 3rem;
}
li {
  font-size: 1.4rem;
}
a {
  display: block;
  display: flex;
  align-items: center;
}
img {
  width: 2rem;
  height: 2rem;
  object-fit: cover;
}
</style>
