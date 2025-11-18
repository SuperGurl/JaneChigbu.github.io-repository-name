[home.html](https://github.com/user-attachments/files/23615314/home.html)# Jane Chigbu
Website
[Uploading home.h<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="mobile.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jane Chigbu's navbar</title>
</head>
<body>
    <header>
    <div class="header"><h1>Jane Chigbu</h1></div>
      <nav class="nav">
        <ul>
          <li><a class="active" href="home.html">Home</a></li>
          <li><a class="active" href="images.html">Projects</a></li>
          <li><a class="active" href="about.html">About</a></li>
          <li><a class="active" href="JaneChigbuResume copy.pdf">Resume</a></li>
          <li><a lass="active" href="contact.html">Contact</a></li>
        </ul>
      </nav>
  </header>
  <main id="Home">
        <div class="Home">
            <ul>
            <li><b>Introduction:</b> Welcome to Jane Chigbu's created web page. Where you will learn more about Jane Chigbu!</li>
            <li><b>Description:</b> My name is Jane, also known as Holy Macaron. <br> I am a New Paltz student who likes digital art and Web Design! </li>
            <li><b>Languages: </b>HTML, CSS, Javascript</li>
            </ul>
        </div>
  </main>
      <footer>
        <div class="container">
          <div class="footer">
          <hr>
          <h4>Web Design&reg;</h4></li>
          </div>
      </footer>  
    </main>
</body>
</html>tml…]()

[mobile.css](https://github.com/user-attachments/files/23615312/mobile.css)
  body {
      margin: 0;
      padding: 0;
      background-color: rgb(57, 87, 188);
      font-family: Arial, Helvetica, sans-serif;
    }

    h1 {
      justify-content: space-around;
      letter-spacing: 0.1em;
      text-align: center;
      color: rgb(69, 196, 255);
    }

    h3 {
      justify-content: space-around;
      letter-spacing: 0.1em;
      text-align: center;
      color: rgb(69, 196, 255);
    }

    dl {
      justify-content: space-around;
      letter-spacing: 0.1em;
      text-align: center;
      color: rgb(69, 196, 255);
    }

    .container {
      justify-content: space-around;
      height: auto;
      gap: 10px;
      border-radius: 50px;
      padding: 10px;
      display: grid;
      grid-template-rows:  1fr 300px 20% 40%;
      grid-template-columns: 200px 300px 100px 400px;
      gap: 10px;
      grid-template-columns: repeat (4, 1fr);
      grid-template-areas: 
      "header header header"
      "navbar content content"
      "footer footer footer";
    }
.Home ul li {
    flex-flow: row;
    flex-wrap: wrap;
    height: auto;
    list-style-type: none;
    text-decoration: none;
    color: white;
}
.Home ul li a {
    text-decoration: none;
    color: white;
    font-size: 50px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
    .nav ul {
      color: rgb(39, 104, 169);
      text-decoration: none;
      justify-content: space-around;
      border-radius: 10px;
      list-style-type: none;
      display: flex;
       align-items: stretch;
     flex: 0 100 100px;
      position: relative;
    flex-flow: row;
    flex-wrap: wrap;

    }
    .nav ul li a {
      color: rgb(255, 255, 255);
      text-decoration: none;
      border-radius: 15px;
      padding:  30px 80px;
      gap: 2px;
      justify-content: center;
      margin: 0;
      background-color: rgb(154, 204, 255);
      flex-flow: row;
      align-items: stretch;
      display: flex;
      
    }

    .nav a:hover, .active {
      color: white;
      background-color: rgb(37, 109, 164);
    }

    .main-content {
        justify-content: space-around;
        text-align: center;
        grid-column: 1 / 6;
        grid-row: 1 / 5;
        grid-template-columns: 1fr 6fr 2fr 1fr;
        border-radius: 5px;
        height: auto;
    }

    .container .list   {
    justify-content: space-around;
    grid-column: 2 / 6;
    grid-row: 1 / 5;
    grid-template-columns: 1fr 6fr 2fr 1fr;
    height: auto;
    flex-flow: row;
    flex-wrap: wrap;

}
 .list h3 {
    grid-column: 1 / 6;
    grid-row: 1 / 5;
    flex-flow: row;
    flex-wrap: wrap;
    height: auto;
    text-decoration: none;
    list-style-type: none;
    justify-content: space-around;
    color: rgb(69, 131, 255);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
 }
    .list ul li  {
    flex-flow: row;
    flex-wrap: wrap;
    grid-column: 2 / 6;
    grid-row: 8 / 5;
    height: auto;
    text-decoration: none;
    list-style-type: none;
    justify-content: space-around;
    color: rgb(69, 131, 255);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

}
    .list ul li a {

    text-decoration: none;
    list-style-type: none;
    color: rgb(69, 131, 255);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

    .footer {
        grid-row: 9 / 5;
        grid-column: 1/ 6;
        color: rgb(69, 131, 255);
        justify-content: space-around;
        padding: 5px;
        border-radius: 5px;
        margin-top: 0;
        text-align: center;
        padding-top: 30px;
        text-decoration: none;
        list-style-type: none;
        height: auto;
    }

     h3 ul li a {
      height: auto;
     text-decoration: none;
    list-style-type: none;
    color: (69, 131, 255);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
 .cards {
    display: flex;
    justify-content: center;
    position: relative;
    flex-flow: row;
    flex-wrap: wrap;
  }
  .card {
    list-style-type: none;
    flex: 0 100 100px;
    display: flex;
    margin: 10px;
    border: 1px solid #ccc;
    box-shadow: 2px 2px 6px 0px  rgb(13, 21, 56);
    align-items: stretch;
    justify-content: space-around;
    background-color: rgb(102, 108, 200);
  } 
  .card img {
    list-style-type: none;
    width: 160px;
    height: 250px;
    flex-flow: row;
    align-items: stretch;
    flex-direction: column;
    display: flex;
    flex-wrap: wrap;
    
  }
  .card .text {
    padding: 0 20px 20px;
    color: white;
    justify-content: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
  }
@media only screen and (max-width: 600px) {
    .nav ul {
        display: grid;
        grid-template-columns: 1fr;
        text-align: center;
        
    }
    .nav ul li {
      grid-column: 1/-1;
    }
    

}
