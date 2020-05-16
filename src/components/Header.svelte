<header class="container">
  <img src="images/logo.svg" alt="logo">
  <ul>
    <li>
      <a class="features" href="/">Features</a>
    </li>
    <li>
      <a href="/">Team</a>
    </li>
    <li>
      <a href="/">Sing In</a>
    </li>
  </ul>
</header>

<style>
  header {
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 50px;
    padding-bottom: 50px;
  }

  ul {
    list-style: none;
    display: flex;
  }

  a {
    text-decoration: none;
    margin-left: 50px;
    color: hsl(238, 22%, 44%);
  }

  @media screen and (max-width: 1024px) {
    header {
      padding-top: 25px;
    }
    header img {
      height: 28px;
    }

    a {
      margin-left: 25px;
      font-size: .9rem;
    }

    .features {
      margin-left: 0px;
    }
  }
</style>