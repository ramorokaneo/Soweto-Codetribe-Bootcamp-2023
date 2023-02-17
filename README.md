# Soweto-Codetribe-Bootcamp-2023
<!DOCTYPE html>
<html>
    <title>My Profile</title>

    <head>
        <link rel="stylesheet" href="./styles.css"
    </head>

    <body>
        <!--This is the @head and it will encopass my logo and my navigation bar-->
        <head>
            <div>
                <table style="width: 100%">
                <tr>
                    <td>
                        <a href="index.html">
                            <img src="visuals/Neo-Logo.svg.png" width="100px" alt="" />
                        </a>
                    </td>
                    <td align="right">
                        <nav
                            style="
                                margin-right: 50px;
                                margin-top: 16px;
                                margin-bottom: 16px;
                                margin-left: 50px;
                            "
                        >
                            <a href="index.html">Home</a>
                            <a href="about_me.html"style="margin: 16px">About Me</a>
                            <a href="contact_me.html">Contact Me</a>
                        </nav>
                    </td>
                </tr>
            </table>
            </div>
        </head>

    <!---This is my main and it will encompass all my contant for the landing page for my site--->
    <main>
        <table style="width: 50px; height: 50px;">
            <tr>
                <td colspan="2">
                    <iframe width="1500" height="700"
                    src="visuals/pexels-cottonbro-10678930.mp4?">
                </iframe>
                    <h1> Hello, My name is <b>Neo Ramoroka</b>.</h1>
                    <h2>I am a Web Design and Developer, how can I assist you today?</h2>
                </td>
            </tr>

            <td style="padding-left: 50vh; padding-top: 10px;">

                <h1>My Bio</h1>

                <p style="width: fit-content;">
                    I create websites that help organizations address business challenges 
                     and meet their needs. I manage everything from website navigation
                     and layout to a company's web hosting and security architecture.<br /> 
                </p>

            </td>
            <td align="right" style="padding-right: 70vh; padding-top: 10px; padding-bottom: 30px;">
                <img 
                    src="visuals/IMG_8315.JPG" 
                alt="" 
                width="200px" 
                height="200px"
                style="border-radius: 50%; object-fit: cover; border: 5px solid lightgrey"
                />
            </td>
        </tr>
        </table>
    </main>

        <!---This is my footer and it will encompass all the quick links on my website.-->
        <footer>
            <table style="width: 100%; height:100px; background-color: lightgrey;">
                <tr>
                    <td style="padding-left: 20vh;"><h1><b>This is my address:</b></h1></td>
                    <td><h2><b>Richard Street, Naturena, Johannesburg South, South Africa.</b></h2></td>

                    <div class="google-map">
                        <td colspan="2" style="padding-left: 20vh;" ><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3577.2077212375193!2d27.951205100000003!3d-26.287365299999998!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1e95086b6ad9d96f%3A0x7cdf72b6ae0c2aff!2sRichard%20St%2C%20Naturena%2C%20Johannesburg%20South%2C%202095!5e0!3m2!1sen!2sza!4v1676556723203!5m2!1sen!2sza" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></colspan></iframe></td>
                    </div>
                </tr>
                <tr>

                <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

                <a href="#" class="fa fa-facebook"></a>
                <a href="#" class="fa fa-twitter"></a>
                <a href="#" class="fa fa-instagram"></a>
                <a href="#" class="fa fa-linkedin"></a>
                </tr>
            </table>    
        </footer>
</body>
</html>![Neo-Logo svg](https://user-images.githubusercontent.com/114235812/219702565-553f7818-543e-45d0-8b9b-4a2cb799b870.png)
![IMG_8315](https://user-images.githubusercontent.com/114235812/219702629-838c257b-a3b0-48af-9ce2-5abc1fb06c3e.JPG)


p {
    background-color: lightgrey;
    color: black;
    margin: 16px;
}

body{
  background: url(./visuals/pexels-olena-bohovyk-1772123.jpg);
  object-fit: contain;
}

ul {
  /* list-style-type: upper-roman; */
  list-style: square inside url("./visuals/ai.png");
}

#AboutMeID {
   /*background-color: #white; */
}

#AboutMeID li {
  background-color: lightgrey;
  border: 2px solid white;
  padding: 30px;
  margin: 50px;
}

.mainContainer{
  background: lightblue;
}
.containerTitle {
  font-size: medium;
  font-weight: lighter;
}

/* Style inputs, select elements and textareas */
input[type=text], select, textarea{
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    resize: vertical;
  }
  
  /* Style the label to display next to the inputs */
  label {
    padding: 12px 12px 12px 0;
    display: inline-block;
  }
  
  /* Style the submit button */
  input[type=submit] {
    background-color: #04AA6D;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    float: right;
  }
  
  /* Style the container */
  .container {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
  }
  
  /* Floating column for labels: 25% width */
  .col-25 {
    float: left;
    width: 25%;
    margin-top: 6px;
  }
  
  /* Floating column for inputs: 75% width */
  .col-75 {
    float: left;
    width: 75%;
    margin-top: 6px;
  }
  
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  
  /* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
  @media screen and (max-width: 600px) {
    .col-25, .col-75, input[type=submit] {
      width: 100%;
      margin-top: 0;
    }
  }

.google-map {
    padding-bottom: 50%;
    position: relative;
}

/* Style all font awesome icons */
.fa {
    padding: 20px;
    font-size: 30px;
    width: 50px;
    text-align: center;
    text-decoration: none;
  }
  
  /* Add a hover effect if you want */
  .fa:hover {
    opacity: 0.7;
  }
  
  /* Set a specific color for each brand */
  
  /* Facebook */
  .fa-facebook {
    background: #3B5998;
    color: white;
  }
  
  /* Twitter */
  .fa-twitter {
    background: #55ACEE;
    color: white;
  }

  /* Instagram */
  .fa-instagram {
    background: rgb(224, 79, 195);
    color: white;
  }

  /* LinkedIn */
  .fa-linkedin {
    background: #3B5998;
    color: white;
  }

  .fa {
    padding: 20px;
    font-size: 30px;
    width: 30px;
    text-align: center;
    text-decoration: none;
    border-radius: 50%;
  }
  
  
  <!DOCTYPE html>
<html>
    <title>About Me</title>

    <head>
        <link rel="stylesheet" href="./styles.css"
    </head>

    <body>
        <!--This is the @head and it will encopass my logo and my navigation bar-->
        <head>
            <div>
                <table style="width: 100%">
                <tr>
                    <td>
                        <a href="index.html">
                            <img src="visuals/Neo-Logo.svg.png" width="100px" alt="" />
                        </a>
                    </td>
                    <td align="right">
                        <nav
                            style="
                                margin-right: 50px;
                                margin-top: 16px;
                                margin-bottom: 16px;
                                margin-left: 50px;
                            "
                        >
                            <a href="index.html">Home</a>
                            <a href="about_me.html"style="margin: 16px">About Me</a>
                            <a href="contact_me.html">Contact Me</a>
                        </nav>
                    </td>
                </tr>
            </table>
            </div>
        </head>
		
		
		![pexels-olena-bohovyk-1772123](https://user-images.githubusercontent.com/114235812/219703189-2402b5fb-100b-4829-b722-6f82cb9a12f9.jpg)
![ai](https://user-images.githubusercontent.com/114235812/219703205-35f3bdb9-f875-4f23-b8bf-c30cc7db8703.png)


<!DOCTYPE html>
<html>
    <title>Contact Me</title>

    <head>
      <link rel="stylesheet" href="./styles.css"
    </head>

    <body>
        <!--This is the @head and it will encopass my logo and my navigation bar-->
        <head>
            <div>
                <table style="width: 100%">
                <tr>
                    <td>
                        <a href="index.html">
                            <img src="visuals/Neo-Logo.svg.png" width="100px" alt="" />
                        </a>
                    </td>
                    <td align="right">
                        <nav
                            style="
                                margin-right: 50px;
                                margin-top: 16px;
                                margin-bottom: 16px;
                                margin-left: 50px;
                            "
                        >
                            <a href="index.html">Home</a>
                            <a href="about_me.html"style="margin: 16px">About Me</a>
                            <a href="contact_me.html">Contact Me</a>
                        </nav>
                    </td>
                </tr>
            </table>
            </div>
        </head>

        <!---This is my main and it will encompass all my contant for the landing page for my site--->
        
          <img src="visuals/screenshot.png" style="height: 70vh; width: 210vh;" title="screenshot">
            <h1>Need any assistance?. Don't hasitate, just Contact Me.</h1>
            <ul>
              <li><b>Contact Number: (+27)630808051<b></li>
              <li><b>Email Address: ramoroka.neo@gmail.com</b></li>
              <li><b>Social Media Links</b></li>
            </ul>

            <div class="container">
                <form action="action_page.php">
                  <div class="row">
                    <div class="col-25">
                      <label for="fname">First Name</label>
                    </div>
                    <div class="col-75">
                      <input type="text" id="fname" name="firstname" placeholder="Your name..">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-25">
                      <label for="lname">Last Name</label>
                    </div>
                    <div class="col-75">
                      <input type="text" id="lname" name="lastname" placeholder="Your last name..">
                    </div>
                </div>
                  <div class="row">
                    <div class="col-25">
                      <label for="country">Country</label>
                    </div>
                    <div class="col-75">
                      <select id="Province" name="Province">
                        <option value="gauteng">Gauteng</option>
                        <option value="north-west">North-West</option>
                        <option value="northern cape">Northern</option>
                        <option value="western cape">Western Cape</option>
                        <option value="estern cape">Estern Cape</option>
                        <option value="free state">Free State</option>
                        <option value="kwa-zulu-natal">Kwa-Zulu-Natal</option>
                        <option value="mpumalanga">Mpumalanga</option>
                        <option value="limpopo">Limpopo</option>
                      </select>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-25">
                      <label for="subject">Subject</label>
                    </div>
                    <div class="col-75">
                      <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
                    </div>
                  </div>
                  <div class="row">
                    <input type="submit" value="Submit">
                  </div>
                </form>
              </div>
              
        </main>

        <!---This is my footer and it will encompass all the quick links on my website.-->
        <footer>
            <table style="width: 100%; height:100px; background-color: lightgrey;">
                <tr>
                    <td style="padding-left: 20vh;"><h1><b>This is my address:</b></h1></td>
                    <td><h2><b>Richard Street, Naturena, Johannesburg South, South Africa.</b></h2></td>
                    <div class="google-map">
                    <td colspan="2" style="padding-left: 20vh;" ><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3577.2077212375193!2d27.951205100000003!3d-26.287365299999998!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1e95086b6ad9d96f%3A0x7cdf72b6ae0c2aff!2sRichard%20St%2C%20Naturena%2C%20Johannesburg%20South%2C%202095!5e0!3m2!1sen!2sza!4v1676556723203!5m2!1sen!2sza" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></colspan></iframe></td>
                    </div>
                </tr>
                <tr>
                    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

                    <a href="#" class="fa fa-facebook"></a>
                    <a href="#" class="fa fa-twitter"></a>
                    <a href="#" class="fa fa-instagram"></a>
                    <a href="#" class="fa fa-linkedin"></a>
                </tr>
            </table>
        </footer>
    </body>
</html>

