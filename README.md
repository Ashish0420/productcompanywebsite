# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### HOME PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KINGS Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">KINGS Ltd.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/produts.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Who are we</h1>
          <img src="./img/s1.jpg" alt="Building1" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make future 
            product users efficient, empowered and happier, so they can focus on what
            matters most for their learning skills. We design and sell our
             products to focus on what is required? to make our products understandable to you,
              and not the other way around.We are a technology & innovation company. 
              Delivering business software for Small and Medium Businesses is our passion.
              What sets a company apart is as much in its DNA as its achievements. 
            <br />
            <br/>
            Our new products like tally prime, etc and many other books
             takes this to a new level, making your programming life to make it
            simple and hassle free, the products we create are easier to use.
            You can now learn tally easily without any hassle.
            There is greater flexibility as you can use these products inspite of your busy schedule
            way of working. And the transformed look and feel will only make you
            love the books even more.
            <ul>
              <li>to learn tally  easily</li>
              <li>Insightful ,accoustamable, conceptual reasoning</li>
              <li>All the products are written by top most authors.</li>
            </ul>
            <h2>OUR MOTTO:</h2>
            <b>"To Make Everyone Who Touches Tally Happier"</b>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 KINGS, Developed by ASHISH.
      </div>
    </div>
  </body>
</html>

### peolpe:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KINGS Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">KINGS Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="peoplecontent">    
          <h1>Our beloved management</h1>
          <div class="peopleitems">
              <div class="peopleitem"> 
                  <div class="itemimage">
                  <img src="img/f1.jpg" alt="people image">
                  </div>
                  <div class="itemname">Sundar </div>
                  <div class="itemprice">LATE Chairperson  </div>
              </div>
              <br/>
              <div class="peopleitem"> 
                  <div class="itemimage">
                  <img src="img/f2.jpg"  alt="people image">
                  </div>
                  <div class="itemname">BERLINE</div>
                  <div class="itemprice">Current chairperson </div>
              </div>
              <br/>
              <div class="peopleitem">
                <div class="itemimage">
                  <img src="img/f3.jpg" alt="people image">
                </div>
                <div class="itemname">Bharat</div>
                <div class="itemprice">CEO </div>
              </div>
              <br/>
              <div class="peopleitem">
                <div class="itemimage">
                  <img src="img/f4.jpg" alt="people image">
                  </div>
                  <div class="itemname">Tejas </div>
                  <div class="itemprice">Managing director </div>
          </div>
          <br/>
          <div class="peopleitem">
            <div class="itemimage">
              <img src="img/f5.jpg" alt="people image">
              </div>
              <div class="itemname">Ganesh.S</div>
              <div class="itemprice">Chief Financial officer</div>
      </div>
      <br/>
          <div class="peopleitem">
            <div class="itemimage">
              <img src="img/f6.jpg" alt="people image">
              </div>
              <div class="itemname">ANODI</div>
              <div class="itemprice">Chief Financial officer</div>
      </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 KINGS Ltd, Developed by ASHISH
      </div>
    </div>
  </body>
</html>

### products:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KINGS Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">KINGS Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/p1.png" alt="product image">
                  </div>
                  <div class="itemname">port folio</div>
                  <div class="itemprice">Price: Rs.1000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/p2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">permier</div>
                  <div class="itemprice">Price: Rs.1500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/p3.jpg" alt="product image">
                </div>
                <div class="itemname">photo shop</div>
                <div class="itemprice">Price: Rs.1300.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="img/p4.jpg" alt="product image">
              </div>
              <div class="itemname">XD</div>
              <div class="itemprice">Price: Rs.1200.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="img/p5.jpg" alt="product image">
            </div>
            <div class="itemname">ST</div>
            <div class="itemprice">Price: Rs.1560.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="img/p6.jpg" alt="product image">
          </div>
          <div class="itemname">AE</div>
          <div class="itemprice">Price: Rs.2340.00 </div>
      </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 KINGS, Developed by ASHISH.
      </div>
    </div>
  </body>
</html>

### contact us:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KINGS Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/j2.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1>
          <div class="contenttext">
            13 ASHISH, PARAM COLONY,  BANGALORE, 240109, INDIA.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              MR.SURANDAR(HR):9656325856<br><br>
              MR.BERLINE(Assistant HR):8956237412
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              Sales:berline65@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 KINGS Ltd., Developed by ASHISH
      </div>
    </div>
  </body>
</html>
## OUTPUT:

### Home Page:

![git log](b1.png)
![git log](b2.png)
![git log](b3.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
