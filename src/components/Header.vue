<script>
export default {}
</script>

<template>
  <div class="header">
    <div class="logo">
      <div class="text">SPORT PAGE</div>
      <div class="text">Your Tagline here</div>
    </div>
    <div class="info">
      <ul>
        <li><a>Home</a></li>
        <li><a>Tarrifs</a></li>
        <li><a>Partners</a></li>
        <li><a>Contact us</a></li>
        <li><a href="/"><i class="fa-solid fa-magnifying-glass"></i></a></li>
        <li><a><button>Sign in</button></a></li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.header {
  width: 90%;
  margin: 10px auto;
  position: relative;
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  align-items: center;

  .logo {
    font-size: 2em;

    .text{
      font-weight: bold;

      &:first-of-type{
        color: #c506c5;
      }
    }
  }


  .info ul {
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
    list-style: none;

    li {
      margin-left: 25px;
      font-size: 1.5em;
    }
  }
}
</style>