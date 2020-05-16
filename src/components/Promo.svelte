<section class="Promo">
  <div class="container">
    <div class="Promo__text">
      <h2>Get early access today</h2>
      <p>It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.</p>
    </div>
    <div class="Promo__input">
      <input type="text" placeholder="email@example.com" />
      <button>Get Started For Free</button>
    </div>
  </div>
</section>

<style>
 .Promo {
   padding: 100px 0 60px 0;
   background-color: hsl(238, 22%, 44%);
   color: white;
 }

 .container {
   display: grid;
   grid-template-columns: 1fr 1fr;
 }

 .Promo__text h2 {
   margin-top: 0;
   font-size: 30px;
 }
 .Promo__text p {
   font-size: 16px;
   width: 82%;
 }

 .Promo__input {
   display: flex;
   flex-direction: column;
   align-items: flex-start;
   justify-content: center;
   padding-left: 18%;
 }
 .Promo__input input {
   width: 82%;
   height: 45px;
   border-radius: 4px;
   border: none;
   padding: 0 20px;
   color: hsl(238, 22%, 44%);
   box-shadow: 2px 4px 8px -5px hsl(243, 87%, 12%);
   outline: none;
 }
 .Promo__input input::placeholder {
   color: hsl(0, 0%, 75%);
 }
 .Promo__input button {
    height: 45px;
    width: 38%;
    margin-top: 15px;
    border: none;
    background-color: hsl(224, 93%, 58%);
    border-radius: 4px;
    color: hsl(240, 75%, 98%);
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    box-shadow: 1px 1px 10px -5px hsl(243, 87%, 12%);
    outline: none;
    cursor: pointer;
 }

 @media screen and (max-width: 1024px) {
   .Promo {
     padding: 60px 0 75px;
   }

   .container {
    grid-template-columns: 1fr;
    text-align: center;
   }

   .Promo__text h2 {
     font-size: 24px;
   }
   .Promo__text p {
     width: initial;
   }
   .Promo__input {
     margin-top: 25px;
     padding-left: 0;
     align-items: center;
   }
   .Promo__input input {
     width: 80%;
   }
   .Promo__input button {
     width: 80%;
   }
 } 
</style>