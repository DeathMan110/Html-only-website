# Html-only-website
<!DOCTYPE html>
<html>
  <head>
    <title>Restaurant Of The Pirates</title>
    <style>
      #input-width {
        width: 200px;
      }
    </style>
  </head>

  <body>
    <header>
      <figure>
        <img id="header-img" src="https://files.oaiusercontent.com/file-U8FJMfJcX2jvpduTHmJZPc?se=2025-03-27T08%3A27%3A55Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Dc0b8eb22-6154-4620-9ab4-207cc25894eb.webp&sig=oboq1HCuyjMIGuI9iRC1kz6UaGEL4zilunbtuArPw%2BY%3D" width="100px" height="100px" alt="Restaurant Logo">
        <ficaption><h1>The Pirate's Table</h1></ficaption>
      </figure>
        <nav id="nav-bar">
        <h3><a style="float: right;" href="#order-form">Order</a></h2>
        <h3><a style="float: right;" href="#menu">Menu ,</a></h2>
      </nav>
    </header>
    <hr style="width: 95%; height: 2px; background-color: black;">
    <menu>
      <section id="menu">
        <h2>Menu</h2>
        <article>
          <figure>
            <li><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMqxblUCytv_3FcErsPcP8oQe_0iK9kezGHw&s" alt="Chicken Burger"></li>
            <figcaption><h3>Chicken Burger</h3></figcaption>
            <p>Sink your teeth into our legendary Chicken Burger, a symphony of flavors that will transport you to burger bliss! We start with a juicy, perfectly seasoned chicken patty, grilled to golden perfection. Nestled between a toasted, buttery bun, it's layered with crisp lettuce, ripe tomatoes, and our signature tangy sauce.  <i>Price: 10$(with fries). </i> <br><b>Order no. 1</b></p>
          </figure>
            </article>
        <article>
          <figure>
            <li><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPDoJFyF9xo-5NHwaG_yGuQYH3ePIl1LJB_Q&s" alt="Fish and Chips"></li>
            <figcaption><h3>Fish and Chips</h3></figcaption>
            <p>Dive into our classic Fish and Chips, a taste of the seaside right here in town! We take flaky, tender white fish, lightly battered and fried to a golden crisp, ensuring each bite melts in your mouth. Served alongside a generous portion of our perfectly seasoned, hand-cut chips, it's a hearty and satisfying meal.  <i>Price: 15$. </i> <br><b>Order no. 2</b></p>
          </figure>
        </article>
        <article>
          <figure>
            <li><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSdlPEmNKL5JJmvn0vjgkFLBujlRaWQYkeM2w&s" alt="Chicken Wings"></li>
            <figcaption><h3>Chicken Wings</h3></figcaption>
            <p>Indulge in our delectable Chicken Wings, a symphony of flavors that will transport you to a wing-eating experience. We start with a juicy, perfectly seasoned chicken patty, grilled to golden perfection. Nestled between a toasted, buttery bun, it's layered with crisp lettuce, ripe tomatoes, and our signature tangy sauce.  <i>Price: 15$(with fries and buffalo sauce). </i> <br><b>Order no. 3</b></p>
          </figure>
        </article>
      </section>
         <section id="order-form">
        <h2>Place Your Order:</h2>
        <form>
          <label for="input-width">Order number: </label><input type="number" min="0" max="3" placeholder="Order no." id="input-width">
          <br>
          <h4>Sides/Add Ons</h4>
          <input type="checkbox">Ketchup
          <input type="checkbox">Ranch
          <input type="checkbox">Mayonaise
          <input type="checkbox">BBQ sauce
          <input type="checkbox">Salad
          <br><br>
          <h4>Any Special Requests?</h4>
          <textarea placeholder="Special Requests optional" rows="7" cols="50"></textarea>
          <br><br>
          <label for="submit"></label><input type="submit" value="Go to checkout" id="submit">
        </form>
      </section>
    </menu>
     <hr style="width: 95%; height: 2px; background-color: black;">
    <footer>
      <p style="text-align: center;"><b>Made with love by DeathMan ^^</b></p>
      <p style="text-align: center;"><b>Copyrighted © by Pirates🏴‍☠️</b></p>
    </footer>
  </body>
</html>
