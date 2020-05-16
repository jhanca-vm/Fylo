<section class="Description">
  <div class="container">
    <div class="text">
      <h1>Stay productive, wherever you are</h1>
      <p>Never let location be an issue when accessing your files. Fylo has you covered for all of your file storage needs.</p>
      <p class="p2">Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required!</p>
      <a href="/">
        <p>See how Fylo works</p>
        <img class="icon" src="images/icon-arrow.svg" alt="icon" />
      </a>
      <div class="card">
        <img class="card__quotes" src="images/icon-quotes.svg" alt="quotes">
        <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.</p>
        <div class="card__profile">
          <img src="images/avatar-testimonial.jpg" alt="avatar">
          <div class="card__profile--data">
            <h3>Kyle Burton</h3>
            <p>Founder & CEO, Huddle</p>
          </div>
        </div>
      </div>
    </div>
    <img class="illustration" src="images/illustration-2.svg" alt="illustration" />
  </div>
</section>

<style>
  .Description {
    margin-top: 130px;
    padding-bottom: 100px;
    background-image: url(../../images/bg-curve-desktop.svg);
    background-repeat: no-repeat;
    background-position: center top;
    background-size: cover;
  }

  .container {
    display: grid;
    grid-template-columns: 60% 40%;
    padding-top: 135px;
  }
  .illustration {
    width: 100%;
    padding-top: 30px;
  }

  .text h1 {
    font-size: 2.52rem;
    line-height: 3.8rem;
    margin-top: 0;
  }
  .text > p {
    width: 73%;
  }
  .text .p2 {
    margin-bottom: 0;
  }
  .text a {
    color: hsl(170, 45%, 43%);
    display: flex;
    align-items: center;
    text-decoration: none;
  }
  .text a p {
    border-bottom: 1px solid hsl(170, 45%, 43%);
    padding-bottom: 3px;
  }
  .text a .icon {
    width: 16px;
    height: 16px;
    padding: 5px 0 4px 8px;
    border-bottom: 1px solid hsl(170, 45%, 43%);
  }

  .card {
    width: 285px;
    margin-top: 30px;
    padding: 30px 38px;
    font-size: 14px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0 0 12px hsl(0, 0%, 75%);
    line-height: 25px;
  }
  .card__quotes {
    height: 15px;
  }
  .card p {
    margin-top: 10px;
  }
  .card__profile {
    display: flex;
    margin-top: 20px;
  }
  .card__profile img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
  }
  .card__profile--data {
    margin-left: 10px;
  }
  .card__profile--data h3 {
    margin: 0;
    margin-top: 4px;
    font-size: 14px;
  }
  .card__profile--data p {
    margin: 0;
    margin-top: -6px;
    font-size: 12px;
  }

  @media screen and (max-width: 1024px) {
    .Description {
      margin-top: 30px;
      padding-bottom: 65px;
      background-image: url(../../images/bg-curve-mobile.svg);
    }

    .container {
      grid-template-columns: 1fr;
      padding-top: 30px;
    }

    .illustration {
      grid-area: 1;
      margin-bottom: 30px;
    }

    .text h1 {
      font-size: 1.8rem;
      line-height: 2.5rem;
      text-align: center;
    }
    .text p {
      width: initial;
    }
    .text a {
      justify-content: center;
      margin-top: 15px;
    }

    .card {
      margin: auto;
      margin-top: 30px;
    }
  }
</style>