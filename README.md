# SITE-DO-HEBERT
SITE DO PROJETO SUPORTE
<!DOCTYPE html>
    <html lang ="en">
    <head>
    <meta charset="UTF-8">  
    <meta name ="viewport" content="witdh=device-width, initial-scale=1.0">
    <title>Responsive Contact Us Page</title>
    <link rel="stylesheet" href="Support.css">
    </head>
    <body>
    <div class="contactUs">
      <div class="title">
        <h2>Get in Touch</h2>
      </div>
      <div class="box">
         <!-- Form -->
        <div class="contact form">
          <h3>Send a Message</h3>
          <form>
            <div class="formBox">
              <div class="row50">
                <div class="inputBox">
                  <span>First Name</span>
                  <input type="text" placeholder="John">
                </div>
                <div class="inputBox">
                  <span>Last Name</span>
                  <input type="text" placeholder="Doe">
                </div>
              </div>

              <div class="row50">
                <div class="inputBox">
                  <span>Email</span>
                  <input type="text" placeholder="johndoe@email.com">
                </div>
                <div class="inputBox">
                  <span>Mobile</span>
                  <input type="text" placeholder="+91 987 654 3210">
                </div>
              </div>

              <div class="row100">
                <div class="inputBox">
                  <span>Message</span>
                  <textarea placeholder="Write your message here..."></textarea>
                </div>
              </div>

              <div class="row100">
                <div class="inputBox">
                  <input type="submit" value="Send">
                </div>
              </div>
            </div>
          </form>
        </div>

        <!-- info Box -->
        <div class="contact info">
          <h3>Contact info</h3>
          <div class="infoBox">
            <div>
              <span><ion-icon name="location"></ion-icon></span>
              <p>Cannaught Palace, New Delhi<br>INDIA</p>
            </div>
            <div>
              <span><ion-icon name="mail"></ion-icon></span>
              <a href="mailto:loremipsu@email.com">loremipsu@email.com</a>
            </div>
            <div>
              <span><ion-icon name="call"></ion-icon></span>
              <a href="tel: +919876543210">+91 987 654 3210</a>
            </div>
             <!--Social Media Links-->
            <ul class="sci">
              <li><a href="#"><ion-icon name="logo-facebook"></ion-icon></a></li>
              <li><a href="#"><ion-icon name="logo-twitter"></ion-icon></a></li>
              <li><a href="#"><ion-icon name="logo-linkedin"></ion-icon></a></li>
              <li><a href="#"><ion-icon name="logo-instagram"></ion-icon></a></li>
            </ul>
          </div>
        </div>


        <!-- Map -->
        <div class="contact map">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14008.112313566702!2d77.20653218195781!3d28.628920553070824!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390cfd37b741d057%3A0xcdee88e47393c3f1!2sConnaught%20Place%2C%20Nova%20Delhi%2C%20Deli%20110001%2C%20%C3%8Dndia!5e0!3m2!1spt-BR!2sbr!4v1649367744592!5m2!1spt-BR!2sbr" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
      </div>
    </div>

    <script  type = "module"  src = "https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script> 
    <script  nomodule  src = "https://unpkg .com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
  </body>
  </html>
