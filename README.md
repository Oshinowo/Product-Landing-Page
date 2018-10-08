<!DOCTYPE html>
<html>
<head>
	<title></title>
<style type="text/css" > #page-wrapper {
  position: relative;
  top: 0px;
  left: 0px;
  right: 0px;
  bottom: 0px;
}

#header {
  font-size: 20px;
  background-color: hsl(80, 0%, 98%);
  position: fixed;
  top: 0px;
  right: 0px;
  left: 0px;
  display: flex;
  flex-wrap: wrap;
}

@media (max-width: 580px) {
  #header {
    display: flex;
    flex-wrap: wrap;
    height: 24vh;
  }
  .left{
    display: none;
  }
}

#header-img {
  height: 23vh;
  position: relative;
  top: 0px;
  right: 0px;
  bottom: 0px;
  left: 0px;
  margin: 0px auto;
}

#nav-bar {
  position: relative;
  top: 0px;
  left: 0px;
  right: 0px;
  height: 23vh;
  background-color: hsl(80, 0%, 98%);
  flex-grow: 1;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

@media (max-width: 580px) {
  #nav-bar {
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    height: 10vh;
  }
}

.nav-link {
  padding: 15px;
  margin: auto;
}

a {
  text-decoration: none;
}

#main {
  margin: 230px auto;
  margin-bottom: 0px;
  width: 70vw;
  text-align: center;
  font-size: 18px;
}

@media (max-width: 580px) {
  input[type="submit"] {
    margin-top: 20px;
  }
}

input[type="submit"]:hover,
#btn:hover,
#btn2:hover,
#btn3:hover {
  background-color: rgba(0, 0, 225, 0.5);
  transition: background-color 1s;
}

p {
  margin: 20px auto;
  padding: 5px;
}

.product {
  margin: 150px auto;
}

.left {
  float: left;
  width: 150px;
  height: 180px;
}

section {
  margin-top: 10%;
  padding: 5px;
}

#form {
  margin: auto;
  padding: 10px;
  text-align: center;
}

#price {
  display: flex;
  margin: 120px auto;
  padding: 10px;
}

@media (max-width: 580px) {
  #price {
    display: flex;
    flex-wrap: wrap;
    margin: auto;
    padding: 8px;
  }
  .pricehead {
    background-color: grey;
  }
}

@media (max-width: 580px) {
  #video {
    width: 70vw;
    height: 50vh;
    margin: auto;
  }
}

#iphne,
#ipd,
#macbook {
  border-width: 2px;
  border-style: solid;
  padding: 2px 25px;
  margin: 2px auto;
  border-radius: 5px;
}

.pricehead {
  background-color: grey;
}

footer {
  background-color: hsl(80, 0%, 90%);
  margin: 10px auto;
}

#btn,
#btn2,
#btn3 {
  margin: 20px auto;
  padding: 8px;
}


</head>
<body>
  <div id="page-wrapper">
    <header id="header">
      <div><img src="https://www.apple.com/lae/apple-events/september-2017/video/poster_medium.jpg" id="header-img" alt="apple logo"></div>
      <nav id="nav-bar">
        <div><a href="#product" class="nav-link">Product</a></div>
        <div><a href="#learn" class="nav-link">Learn More</a></div>
        <div><a href="#price" class="nav-link">Pricing</a></div>
      </nav>
    </header>
    <main id="main">
      <div>
        <h2>Get the Latest iOS Device!!!</h2>
        <form id="form" action="https://www.freecodecamp.com/email-submit">
          <input type="email" name="email" id="email" placeholder="Enter Your Email Address" required="">
          <input type="submit" name="submit" id="submit" value="ORDER NOW">
        </form>
      </div>
      <section id="product">
        <div id="iphone" class="product"><img src="https://store.storeimages.cdn-apple.com/8755/as-images.apple.com/is/image/AppleInc/aos/published/images/i/ph/iphone/x/iphone-x-select-2017?wid=189&hei=376&fmt=png-alpha&.v=1504378258086" class="left" alt="iphone image">
          <h3>iPhone</h3>
          <p>iPhone is a line of smartphones designed and marketed by Apple Inc. The iPhone line of products use Apple's iOS mobile operating system software. The first-generation iPhone was released on June 29, 2007, and multiple new hardware iterations
            with new iOS releases have been released since.</p>
        </div>
        <div id="ipod" class="product"><img src="https://images-na.ssl-images-amazon.com/images/I/61sDhQEUV%2BL._SX425_.jpg" class="left" alt="ipad image">
          <h3>iPad</h3>
          <p>The iPad is a line of tablet computers designed, developed and marketed by Apple Inc., which run the iOS mobile operating system. The first iPad was released on April 3, 2010; the most recent iPad models are the iPad (2018), released on March
            27, 2018, the 10.5-inch (270 mm) and 12.9-inch (330 mm) 2nd generation iPad Pro released on June 13, 2017. The user interface is built around the device's multi-touch screen, including a virtual keyboard. All iPads can connect via Wi-Fi; some
            models also have cellular connectivity</p>
        </div>
        <div id="mac" class="product"><img src="https://media.wired.com/photos/59e952e4f572231fe56c3937/master/w_2500,c_limit/rosegold-macbook-1.jpg" class="left" alt=" macintosh">
          <h3>Macbook</h3>
          <p>The MacBook is a brand of notebook computers manufactured by Apple Inc. from May 2006 to February 2012, and relaunched in 2015. It replaced the iBook series and 12-inch PowerBook series of notebooks as a part of the Apple-Intel transition from
            PowerPC. Positioned as the low end of the MacBook family, below the premium ultra-portable MacBook Air and the powerful MacBook Pro, the MacBook was aimed at the consumer and education markets. It was the best-selling Macintosh ever. For five
            months in 2008, it was the best-selling laptop of any brand in US retail stores. Collectively, the MacBook brand is the "world's top-selling line of premium laptops.</p>
        </div>
      </section>
      <div id="learn">
        <iframe width="853" height="480" src="https://www.youtube.com/embed/IprmiOa2zH8" allowfullscreen id="video"></iframe>

        <div id="price">
          <div id="iphne">
            <h2 class="pricehead">iPhone</h2>
            <h3>$1200</h3>
            <p>
              Lorem ipsum.<br> Lorem ipsum.<br> Lorem ipsum dolor.<br> Lorem ipsum.              
            </p>
            <button id="btn">SELECT</button>
          </div>

          <div id="ipd">
            <h2 class="pricehead">iPad</h2>
            <h3>$1000</h3>
            <p>
              Lorem ipsum.<br> Lorem ipsum.<br> Lorem ipsum dolor.<br> Lorem ipsum.     
            </p>
            <button id="btn2">SELECT</button>
          </div>

          <div id="macbook">
            <h2 class="pricehead">Macbook</h2>
            <h3>$1600</h3>
            <p>
              Lorem ipsum.<br> Lorem ipsum.<br> Lorem ipsum dolor.<br> Lorem ipsum.              
            </p>
            <button id="btn3">SELECT</button>
          </div>

        </div>

    </main>
    <footer>
      <ul>
        <li><a href="#">Privacy</a></li>
        <li><a href="#">Terms</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <span>Copyright 2018, Apple.Inc</span>

    </footer>
    </div>
    <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</body>
</html>
