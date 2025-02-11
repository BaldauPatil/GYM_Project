# GYM_Project
The GYM_Project is a responsive HTML &amp; CSS website for fitness centers, featuring a modern design, navigation bar, membership plans, trainer profiles, and a contact form. 💪🔥
HTML Code starts from here 👇

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baldau GYM</title>

</head>
<link rel="stylesheet" href="Css/style.css">
<link href="https://fonts.googleapis.com/css2?family=Caprasimo&display=swap" rel="stylesheet">

<style>
    body {
        margin: 0px;
        padding: 0px;
        background: url(img/bs.jpg);
        height: 3000px;

    }

    .left {
        margin: 10px;
        display: inline-block;
        border-radius: 23px;
    }

    .mid {
        height: 30px;
        position: absolute;
        display: block;
        left: 270px;
        top: 50px;
        font-size: 24px;
        font-family: 'Caprasimo', cursive;
    }

    .right {
        background-color: black;
        border-radius: 15px;
        color: white;
        height: 35px;
        font-size: 27px;
        padding: 13px;
        position: absolute;
        display: inline-block;
        right: 80px;
        top: 58px;
        cursor: pointer;
        font-family: 'Caprasimo', cursive;

    }

    .right:hover {

        background-color: rgb(107, 101, 101);
    }


    .Navbar {
        margin: 30px;
        float: left;
    }

    .Navbar a {
        color: black;
        text-decoration: none;
    }

    .Navbar a:hover {

        color: rgb(202, 200, 200);
        text-decoration: underline;
    }

    h1 {
        margin: 100px;
        color: white;
        font-size: 80px;
        padding-right: 442px;
        /* position:absolute; */
        /* top: 300px; */

    }




    .left img {

        width: 175px;
        height: 175px;
        margin: 5px 20px;
    }

    .container {
        width: 550px;
        margin: 20px;
        padding: 20px;
        color: white;
        position: absolute;
        display: inline-block;
        right: 10px;
        font-size: 20px;
        top: 851px;
    }

    .simg img {
        width: 677px;
        height: 389px;
        margin: 115px 108px;
        border-radius: 40px;
    }

    #girl img {

        position: absolute;
        right: 0px;
    }

    .container2 {

        width: 550px;
        margin: 20px;
        padding: 20px;
        color: white;
        position: absolute;
        display: inline-block;
        left: 10px;
        font-size: 25px;


    }

    .form_container {
    padding: 63px;
    margin: 16px;
    position: absolute;
    display: inline-block;
    top: 2663px;
    left: 560px;
    border-radius: 18px;
    background-color: #383838;
    font-family: 'Caprasimo', cursive;    
}

h2 {
    color: white;
    position: absolute;
    left: 90px;
    top: 1px;
    margin: 18px;
    font-size: 33px;
    margin-left: -9px;
}

#inst img {
    position: absolute;
    left: 279px;
    top: 2120px;
}

</style>

<body>
    <header>
        <div class="header">
            <div class="left">
                <!-- <img id = "img" src="https://o.remove.bg/downloads/134611cd-768d-4f80-b8e0-2eb38ff12f70/attachment_108553569-removebg-preview.png" alt="Please try again" > -->

                <img src="img/logo.png" alt="Please wait">

            </div>

            <div class="mid">

                <div class="Navbar"><a href="#">About</a></div>
                <div class="Navbar"><a href="#">Facilities</a></div>
                <div class="Navbar"><a href="#">Membership</a></div>
                <div class="Navbar"><a href="#">Contect us</a></div>
                <div class="Navbar"><a href="#">Log In/Sign Up</a></div>

            </div>

            <div class="right">
                Join Now

            </div>
        </div>
    </header>

    <h1>THE REAL WORKOUT START WHEN YOU WANT TO STOP</h1>

    <div class="container">

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt modi impedit laboriosam voluptatibus nam,
            quibusdam itaque adipisci minus vel, maiores fugit repudiandae! Nihil, distinctio perferendis. Odit, facilis
            tenetur non ratione quo quam deleniti, vel illum, error laborum architecto quaerat quis commodi
            necessitatibus praesentium asperiores velit consectetur molestias iste recusandae itaque laboriosam.
            Molestiae eum debitis porro a sapiente numquam provident quae! Ad ullam impedit id deserunt libero totam
            pariatur asperiores, voluptas aliquid ipsam eligendi ea minus quas voluptate suscipit. Eos ea blanditiis
            ipsa fugiat consequuntur eligendi, consequatur aspernatur eum, culpa optio nemo, fuga incidunt id rem
            consectetur delectus soluta vel enim accusantium porro? Assumenda velit tempora similique tempore earum
            quia, voluptate maiores dolor soluta laborum nemo hic, omnis nisi. Neque, fuga?</p>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br><br><br><br><br><br><br><br><br><br>
    <div class="simg">

        <img src="https://i.ytimg.com/vi/gey73xiS8F4/maxresdefault.jpg">

    </div>
    <div class="simg" id="girl">

        <img
            src="https://images.moneycontrol.com/static-mcnews/2021/01/Gym-workout-India.jpg?impolicy=website&width=770&height=431">
    </div>


    <div class="container2" id="p2">

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Illum voluptas exercitationem dolorum vero? Sit
            delectus corrupti sunt error sequi. Officia, sapiente, aliquam magnam voluptates perferendis ipsum hic alias
            exercitationem quaerat adipisci asperiores praesentium, assumenda dolor quae unde maxime libero doloremque
            consectetur corporis suscipit temporibus! Ea accusamus veniam officia odio. Rem obcaecati quis sequi
            voluptatibus id laudantium. Voluptatem at vel voluptates fuga error autem et rerum suscipit iusto sint
            tempore sunt ex repellendus officia soluta, harum quia aspernatur dolorum sequi neque aliquid. Nesciunt
            nostrum veritatis libero rerum harum officia sit, quibusdam unde inventore sunt est. Impedit animi pariatur
             </p>
    </div>

    <div class="form_container">
        <h2 id="h2">Fill Form</h2>
        <br>
        <div>
            <input type="text" placeholder="Full Name">
        </div>
        <br>
        <div>
            <input type="text" placeholder="Email Id">
        </div>
        <br>
        <div>
            <input type="text" placeholder="Contect Number">
        </div>
        <br>
        <div>
            <input type="submit" value="Submit Now">
            <input type="reset" value="Reset">
        </div>
    </div>

    <div class="simg" id="inst">

        <img src="https://fitnessvolt.com/wp-content/uploads/2022/10/Gym-Equipment-Guide.jpg">

    </div>

</body>

</html>

CSS Code starts from here 👇


