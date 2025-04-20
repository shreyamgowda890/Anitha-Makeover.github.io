<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anitha Make-Up Artist</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css" integrity="sha512-5Hs3dF2AEPkpNAR7UiOHba+lRSJNeM2ECkwxUIxC1Q/FLycGTbNapWXB4tP889k5T5Ju8fs4b1P5z/iB4nMfSQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    
    <style>
        /* Page Styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
           background-image: url('https://th.bing.com/th/id/OIP.6hT0OW4gqGPBbeS7_UHsbwHaEJ?rs=1&pid=ImgDetMain');
            background-size: cover;
            height: 100px;
            background-position: center;
            color: white;
            text-align: center;
        }

        header {
            background-color: black;
            padding: 20px;
        }

        h1 {
            font-size: 3em;
            margin: 0;
        }
       .imgradius{
           border-radius: 40px;
       }
        nav {
            margin-top: 20px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            margin: 50px 20px;
            padding: 30px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
        }

        .services, .gallery, .video {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .service, .gallery-item {
            margin: 15px;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.3);
            border-radius: 10px;
            width: 250px;
        }

        .gallery-item img {
            width: 100%;
            border-radius: 10px;
        }

        .video iframe {
            width: 100%;
            max-width: 600px;
            height: 350px;
            border-radius: 10px;
        }

        footer {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
            color: white;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Contact Form */
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: none;
        }

        .contact-form button {
            padding: 15px 25px;
            background-color: #ff6347;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1.1em;
        }

        .contact-form button:hover {
            background-color: #ff4500;
        }

    </style>
</head>
<body>

<header>
    <h1>Anitha Make-Up Artist</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#video">Videos</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Anitha</h2>
    <p>Anitha is a professional make-up artist with over 2 years of experience. Specializing in bridal, party, and event make-up, she brings beauty and confidence to every individual. Book your appointment now and let Anitha transform you!</p>
	<h1><center><b>CERTIFICATE OF COMPLETION</h1></center></b>
    <img src='C:\Users\i5 6TH GEN 8GB 256GB\Documents\Downloads\WhatsApp Image 2025-04-10 at 10.23.52 AM.jpeg'height="250" width="250">
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="service">
            <h3>Bridal Make-Up</h3>
            <p>Flawless bridal make-up for your special day.</p>
        </div>
        <div class="service">
            <h3>Party Make-Up</h3>
            <p>Glam up for any event with professional make-up.</p>
        </div>
        <div class="service">
            <h3>Event Make-Up</h3>
            <p>Perfect looks for parties, photoshoots, and more!</p>
        </div>
		<div class="service"
		<h3><b>Maternity Make-Up</h3></b>
		<p>Mirror,mirror,on the wall,who's the most elegant of them all!Memories with two</p>
</div>		</div>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
       
       <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="4"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="C:\Users\i5 6TH GEN 8GB 256GB\Documents\Downloads\WhatsApp Image 2025-04-10 at 6.17.35 PM.jpeg" height="500"width="400"alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h2>Bridal</h2>
      </div>
    </div>
    <div class="carousel-item">
      <img src="C:\Users\i5 6TH GEN 8GB 256GB\Documents\Downloads\WhatsApp Image 2025-04-10 at 6.33.30 PM.jpeg"height="500"width="400" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h2>Partylook</h2>
      </div>
    </div>
    <div class="carousel-item">
      <img src="C:\Users\i5 6TH GEN 8GB 256GB\Documents\Downloads\WhatsApp Image 2025-04-10 at 6.44.12 PM.jpeg"height="500"width="400" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h2>Event</h2>
      </div>
    </div>
    <div class="carousel-item">
      <img src="C:\Users\i5 6TH GEN 8GB 256GB\Documents\Downloads\WhatsApp Image 2025-04-10 at 6.48.33 PM.jpeg"height="500"width="600" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h2>Maternity</h2>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
       
    </div>
</section>

<section id="video">
    <h2>Watch Us in Action</h2>
    <div class="video">
        <video width="1500"height="500" controls>
		<source src='C:\Users\i5 6TH GEN 8GB 256GB\Documents\Downloads\WhatsApp Video 2025-04-10 at 6.58.34 PM.mp4'>
		your browser doesnot support the video tag.s
		</video>
    </div>
</section>

<section id="availability">
    <h2>Availability</h2>
    <p>As per the booking dates</P>
	<p>Don't delay booking,especially if you have a specific artist in mind.</p>
</section>

<section id="location">
    <h2>Our Location</h2>
    <p>Beechagondhalli,kolar(taluk),kolar(district),sk.halli(post),563128 @Makeover_with_anitha</p>
    <p>Click below to see our location on the map.</p>
    <a href="https://www.bing.com/maps?&ty=30&q=Beechagondhalli%20kolar&satid=id.sid%3A5b98f998-a707-ed19-e6bb-38f839c7c2b4&vdpid=7466656456826159105&mb=13.310158~77.885909~13.033049~78.336412&cardbg=%23F98745&dt=1744295400000&tt=Kolar%2C%20Kolar%20District%2C%20Karnataka&tsts0=%2526ty%253D30%2526q%253DBeechagondhalli%252520kolar%2526satid%253Did.sid%25253A5b98f998-a707-ed19-e6bb-38f839c7c2b4%2526vdpid%253D7466656456826159105%2526mb%253D13.310158~77.885909~13.033049~78.336412%2526cardbg%253D%252523F98745%2526dt%253D1744295400000&tstt0=Kolar%2C%20Kolar%20District%2C%20Karnataka&cp=13.171614~78.003519&lvl=11.664612&pi=0&ftst=0&ftics=False&v=2&sV=2&form=S00027" target="_blank">View on Google Maps</a>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Have any questions or want to book an appointment? Fill out the form below!</p>
    <form class="contact-form" onsubmit="return validateForm()">
        <input type="text" id="name" name="name" placeholder="Your Name" required>
        <input type="email" id="email" name="email" placeholder="Your Email" required>
        <textarea id="message" name="message" placeholder="Your Message" rows="4" required></textarea>
        <button type="submit">Submit</button>
    </form>
    <p id="formMessage"></p>
</section>

<footer>
    <p>&copy; 2025 Anitha Make-Up Artist. All rights reserved.</p>
</footer>

<script>
    // JavaScript form validation
    function validateForm() {
        const name = document.getElementById("name").value;
        const email = document.getElementById("email").value;
        const message = document.getElementById("message").value;
        if (name === "" || email === "" || message === "") {
            document.getElementById("formMessage").textContent = "Please fill out all fields!";
            return false;
        } else {
            document.getElementById("formMessage").textContent = "Thank you for contacting us, we will get back to you soon!";
            return false;  // Prevent form from submitting for this example
        }
    }
</script>

</body>
</html>
