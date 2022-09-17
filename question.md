<!-- head excercise -->
<!DOCTYPE html>
<html lang ="en"> 
    <head> 
        <meta charset="UTF-8" />
        <meta name ="viewport"/>
        <title> Welcome to my website</title>
        <meta property="og:title" content="HTML Head excercise" />
        <meta property="og:type" content="website" />
        <meta property="og:url" content="https://www.mywebsite.com"/>
        <meta property="og:description" content="The first html head excercise" />
        <meta property="og:article:author" content="Toshikazu Kawaguchi" />
        <link rel="shortcut icon" href="favicon.icon" type="image/x-icon" />
    </head>
</html>

<!-- 2 html tags -->
<!DOCTYPE html>
<html lang="en">
   <head>
    <meta http-equiv="X-UA-Compatible" content="IE=egde" />
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device width, initial scale=1.0, maximum scale=1.0, user scalable=no" />
    <title> WElcome to my website</title>
    <style>
        h1 {color:red;}
        h2 {color:blue;}
        </style>
   </head>
   <body>
    <h1>This is the main the tile</h1>
    <h2> And along woth the secong title, they both belong to the header tag. </h2>
    <hr>
    <p>Tag usually used for the sidebar of a website. However, in order to make it as a real sidebar, we need to apply CSS properties.</p>
    <ul>
        <li><a href="#">Link 1</a></li>
        <li><a href="#">Link 2</a></li>
        <li><a href="#">Link 3</a></li>
        <li><a href="#">Link 4</a></li>
        <li><a href="#">Link 5</a></li>    
    </ul>
    <hr>
    <main> Main content of the page</main>
    <h3> Inside the body there are some sections</h3>
    <q> Hello World</q>
    <p> <sup> text</sup> </p>
    <sub> text</sub>
    <em> text </em>
    <p> <strong> text </strong></p>
    <h4> This is the end of the page </h4>
    <p> This is a paragraph</p>
   </body>
</html>

<!-- 3 attributes -->
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UFT-8" />
        <title> Wekcome to my website</title> 
    </head>
    <body> 
        <button disabled><Button></button>
            <br/>
            <label for="num">Choose an even number</label>
            <input type="number" min="0" max="100" step="2" id="num" autofocus />
            <br/>
            <label for="Math" > I like Math</label>
            <input type="checkbox" id="math" checked />
            <br/>
            <input type="date" />
            </body>
</html>

<!--4 Table-->
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UFT-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" /> 
        <title> Welcome to my website</title>
        <style>
            table, th, td {
              border: 1px solid black;
              border-collapse: collapse;
            }
            </style>
    </head>
    <body>
        <h2> Header Table</h2>
        <table>
            <tr>
                <th>Months</th>
                <th>Cash Entry</th>
                <th>Cash Outflow</th>
            </tr>
            <tr> 
                <td>January</td>
                <td>40tl</td>
                <td>45tl</td>
            </tr>
            <tr>
                <td>February</td>
                <td>30tl</td>
                <td>24tl</td>
            </tr>
            <tr>
                <td>March</td>
                <td>45tl</td>
                <td>25tl</td>
            </tr>
            <tr>
                <td>April</td>
                <td>50tl</td>
                <td>52tl</td>
            </tr>
            <tr>
                <td>May</td>
                <td>54tl</td>
                <td>30tl</td>
            </tr>
            <tr>
                <td>June</td>
                <td>50tl</td>
                <td>35tl</td>
            </tr>
            <tr>
                <td>July</td>
                <td>45tl</td>
                <td>25tl</td>
            </tr>
            <tr>
                <td>August</td>
                <td>65tl</td>
                <td>56tl</td>
            </tr>
            <tr>
                <td>September</td>
                <td>95tl</td>
                <td>59tl</td>
            </tr>
            <tr>
                <td>October</td>
                <td>75tl</td>
                <td>57tl</td>
            </tr>
            <tr>
                <td>November</td>
                <td>87tl</td>
                <td>78tl</td>
            </tr>
            <tr>
                <td>December</td>
                <td>15tl</td>
                <td>25tl</td>
            </tr>
        </table>
    </body>
</html>

<!--5,6 Form and validation-->
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
    </head>
    <body>
        <form action="/action_page.php">
            <div class="container">
              <h1>Register</h1>
              <p>Please fill in this form to create an account.</p>
              <hr>
              <p>All fields marked with * are required</p>
          
              <label for="email"><b>Email *</b></label>
              <input type="text" placeholder="Enter Email" name="email" id="email" required>
              <hr>
          
              <label for="psw"><b>Password *</b></label>
              <input type="password" placeholder="Enter Password" name="psw" id="psw" required>
              <hr>
          
              <label for="name"><b>Name *</b></label>
              <input type="text" placeholder="Enter Name" name="name" id="name" required>
              <hr>

              <label for="last-name"><b>LastName *</b></label>
              <input type="text" placeholder="Enter LastName" name="last-name" id="last-name" required>
              <hr>

              <label for="D-o-b"><b>Date of Bith *</b></label>
              <input type="date" placeholder="Date of Birth" name="D-o-b" id="D-o-b" required>
              <hr>

              <label for="t-number"><b>Telephone number *</b></label>
              <input type="number" placeholder="Telephone Number" name="t-number" id="t-number" required>
              <hr>

              <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>.</p>
              <hr>
              <h3> Plans</h3>
              <label for="cars">Choose a plan:</label>
              <select name="plans" id="plans">
                <option value="select">Select</option>
                <option value="f-plans">Free plans</option>
                <option value="plan-2">A group of 3 plans with increasing price</option>
                <option value="plan-3">Checkbox for a Pro Plan</option>
              </select>
              <hr>
              <h3> Payment</h3>
            
                <span class="cdnum">Card Number *<span>(Dashes not required)</span></span>
                <input name="cardnumber" maxlength="16" type="text" placeholder="DONT-USEA-REAL-NMBR">
              </label>
              <hr>
              <label class="exp">
                <span class="expdt">Exp. Date *</span>
                <input name="experationdate" type="text" placeholder="MM/YYYY">
              </label>
              <hr>
              <label class="cvc">
                <span class="cvcnum">CVC *</span>
                <input name="cvcnumber" maxlength="3" type="text" placeholder="XXX">
              </label>
              <hr>
              <label class="Adress">
                <span class="billingaddress">Billing Address *</span>
                <input name="Billing Address" type="text" placeholder="XXX">
              </label>
              <hr>
              <button type="submit">
                Submit
              </button>
          </form>
    </body>
</html>

<!--7Navbar-->
<!DOCTYPE html>
<html>
<body>
<section>
<ul>
    <nav> Navbar</nav> 
  <li><a href="#home">Home</a></li>
  <li><a href="#news">Link</a></li>
  <li><a href="disabled">Link</a></li>
  <li><a href="#contact">Dropdown</a></li>
  <li><a href="#about">Disabled</a></li> 
</ul>
<input type="search" id="site-search" name="Search">

<button>Search</button>
<hr>
</section>
</body>
</html>

<!--8 card-->
<body>
    <figure>
    <img src="/media/cc0-images/elephant-660-480.jpg"
         alt="Elephant at sunset">
    <figcaption>An elephant at sunset</figcaption>
</figure>
    <section id="card">
        <article class="forecast">
            <h1>Card Title</h1>
            <p> Some quick example text to build on the card title and makeup the bulk of the card's output</p>
            <article class="day-forecast">
                <p>An item</p>
            </article>
            <article class="day-forecast">
                <p>2nd item</p>
            </article>
            <article class="day-forecast">
                <p>A third item</p>
            </article>
        </article>
    </section>

    </body>

    <!--9 HTML blog page-->

    <!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Add a gray background color with some padding */
body {
  font-family: Arial;
  padding: 20px;
  background: #f1f1f1;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  font-size: 40px;
  text-align: center;
  background: white;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  padding-left: 20px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
   background-color: white;
   padding: 20px;
   margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}
</style>
</head>
<body>
<article>
<div class="header">
  <h2>Books:)</h2>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Before the Coffee Gets Cold</h2>
      <h5> Sep 16, 2022</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Author: Toshikazu Kawaguchi</p>
      <p>TOSHIKAZU KAWAGUCHI was born in Osaka, Japan, in 1971. He has produced, directed and written for the theatrical group Sonic Snail. As a playwright, his works include COUPLE , Sunset Song and family time .</p>
    </div>
    <div class="card">
      <h2>About the Book</h2>
      <h5> His play Before the Coffee Gets Cold won the grand prize</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>The author talks about a cafe in Tokyo</p>
      
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>I'm a Full Stack student at Develhope :)</p>
    </div>
    <div class="card">
      <h3>Popular Post</h3>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div>
    </div>
    <div class="card">
      <h3>Follow Me</h3>
      <p>I hope you like my content..</p>
    </div>
  </div>
</div>
</article>
<form>
    <label for="email"><b>Email *</b></label>
    <input type="text" placeholder="Enter Email" name="email" id="email" required>
    <br>
    <button type="submit">
        Submit
      </button>
</form>

<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>
