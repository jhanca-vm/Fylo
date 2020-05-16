<footer>
  <div class="container">
    <h1>Fylo</h1>
    <div class="footer__sections">
      <div class="contact">
        <span>
          <figure>
            <img src="images/icon-phone.svg" alt="icon phone">
          </figure>
          <p>Phone: +1-543-123-4567</p>
        </span>
        <span>
          <figure>
            <img src="images/icon-email.svg" alt="icon email">
          </figure>
          <p>example@fylo.com</p>
        </span>
      </div>
      <div class="links">
        <a href="/">About Us</a>
        <a href="/">Jobs</a>
        <a href="/">Press</a>
        <a href="/">Blog</a>
      </div>
      <div class="links info">
        <a href="/">Contact Us</a>
        <a href="/">Terms</a>
        <a href="/">Privacy</a>
      </div>
      <div class="social">
        <i class="fab fa-facebook"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-instagram"></i>
      </div>
    </div>
  </div>
</footer>

<style>
  footer {
    padding: 60px 0;
    background-color: hsl(243, 87%, 12%);
    color: white;
  }
  footer h1 {
    font-size: 48px;
  }

  .footer__sections {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
  }
  .footer__sections span {
    display: flex
  }
  .footer__sections span p {
    margin-top: 0;
    margin-left: 20px;
  }

  .links {
    display: flex;
    flex-direction: column;
  }
  .social i {
    color: white;
    font-size: 24px;
    margin-right: 8px;
    cursor: pointer;
  }

  figure {
    margin: 0;
  }

  a {
    text-decoration: none;
    color: white;
    margin-bottom: 15px;
  }

  @media screen and (max-width: 1024px) {
    footer {
      padding: 30px 0;
    }

    footer h1 {
      text-align: center;
    }

    .contact {
      margin: auto;
      margin-top: 0;
    }

    .footer__sections {
      grid-template-columns: 1fr 1fr;
    }
    .footer__sections .links, .social {
      align-self: center;
      justify-self: center;
    }
  }
</style>