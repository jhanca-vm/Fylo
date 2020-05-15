<section class="Hero">
  <div class="container">
    <div class="Hero__description">
      <h1>All your files in one secure
      location, accessible anywhere.</h1>
      <p>Fylo stores your most important files in one secure location. Access
      them wherever you need, share and collaborate with friends, family,
      and co-workers.</p>
      <div class="Hero__description--input">
        <input type="text" placeholder="Enter your email..." />
        <button>Get Started</button>
      </div>
    </div>
    <img src="images/illustration-1.svg" alt="illustracion" />
  </div>
</section>

<style>
  .container {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

  .Hero__description {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .Hero__description h1 {
    font-size: 2.52rem;
    line-height: 3.8rem;
    margin: 0;
  }
  .Hero__description p {
    font-size: 1.13rem;
    margin-bottom: 25px;
  }

  .Hero__description--input{
    margin-bottom: 30px;
  }
  .Hero__description--input input {
    width: 52%;
    height: 45px;
    padding: 15px;
    box-sizing: border-box;
    border: 1px solid hsl(238, 22%, 44%);
    border-radius: 2px;
    color: hsl(238, 22%, 44%);
    font-size: 14px;
  }
  .Hero__description--input input::placeholder {
    font-family: 'Raleway', sans-serif;
    color: hsl(0, 0%, 75%);
  }
  .Hero__description--input input:focus {
    outline-color: hsl(0, 0%, 75%);
  }
  .Hero__description--input button {
    height: 45px;
    width: 32%;
    margin-left: 10px;
    border: none;
    background-color: hsl(224, 93%, 58%);
    border-radius: 4px;
    color: hsl(240, 75%, 98%);
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    font-size: 14px;
    outline: none;
    cursor: pointer;
  }

  img {
    width: 100%;
    padding-left: 25px;
    box-sizing: border-box;
  }
</style>