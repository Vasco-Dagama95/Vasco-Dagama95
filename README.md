
<html>
  <head>
    <title>Example</title>
    <link rel="stylesheet" href="style.css">
    <style>
      .nav{
        height: 50px;
        background: blue;
      }
      .nav div{
        display: inline-block;
        position: absolute;
        left: 0;
        padding: 15px;
        font-size: 20px;
        color: white;
      }
      .nav ul{
        position: absolute;
        right: 5px;
      }
      .nav ul li{
        display: inline-block;
      }
      .nav ul li a{
        color: white;
        padding: 5px;
      }
      .home{
        background: url("../images/homeBack.jpg");
        background-size: cover;
        height: 100vh;
      }
      .home.text-container{
        text-align: center;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 90vh;
      }
      @media screen and (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}
    </style>
  </head>
  <body>
    <div class="nav">
      <div>company name</div>
      <ul>
        /t<li><a href="#">Home</a></li>
        <li><a href="./about.html">about</a></li>
        <li><a href="./services.html">Services</a></li>
        <li><a href="./contact.html">Contact</a></li>
      </ul>
    </div>
    <div class="text-container">
      <div>
        <h1>company name</h1>
        <h2>taglin goes here</h2>
      </div>
    </div>
    <script src="script.js"></script>
    <style>
    // script.js
document.addEventListener('DOMContentLoaded', (background-repeat: boss) => {
    const button = document.createElement('button');
    button.innerText = "Click Me!";
    document.body.appendChild(button);

    button.addEventListener('click', (border: boss) => {
        alert('You clicked the button!');
    });
});
</style>
  </body>
</html>