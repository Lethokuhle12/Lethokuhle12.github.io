<!DOCTYPE html>
<html>
<head>
       <title>My learning</title>

       <link rel="stylesheet" href="NewStyleSheet.css">
</head>

<body>


        <header><h1>@Lethokuhle</h1></header>

      <div> <nav><ul>
            <button><li>about</li></button>
            <button><li>contact</li></button>
            <button><li>email</li></button>
            <button><li>menu</li></button>
        </ul></nav></div>

       <main>
        <aside><img src="pexels-vojtech-okenka-392018.jpg" height="300px" width="500"></aside>
        <section><img src="pexels-tranmautritam-326502.jpg" height="300px" width="500"></section>
        <article><img src="pexels-josh-sorenson-1714202.jpg" height="300" width="464"></article>
       </main>


       <footer>

      <form>

        <h2>Personal infomation</h2>
         <label for="name">Name:</label>
        <input type="text" id="name">

         <label for="surname">Surname:</label>
         <input type="text" id="surname">
         <br>
         <br>
         <label for="age">Age:</label>
         <input type="number" id="age" min="16" max="25" value="16">
         <label for="date">Date of birth:</label>
         <input type="date" id="date">
         <br>
         <br>
         <label for="gender">Gender:</label>
         <label for="male">Male</label>
         <input type="radio" id="male" value="Male" name="gender">
         <label for="female">Female</label>
         <input type="radio" id="female" value="female" name="gender">
         <br>
         <br>
         <label for="email">Email:</label>
         <input type="email" id="email">
         <label for="number">Contacts:</label>
         <input type="tel" id="number" placeholder="012-345-6789" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}">
         <br>
         <br>
         <input type="submit">
         <input type="reset">



      </form>
       </footer>


     <script src="jscript.js"></script>



    </body>


