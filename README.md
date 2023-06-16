<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/intl-tel-input/17.0.8/css/intlTelInput.css"/>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/intl-tel-input/17.0.8/js/intlTelInput.min.js"></script>
    <link rel="stylesheet" href="contact_us.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,400;0,600;1,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
    <div class="fill">
      
        <div class="contact">
            <div class="left">
                  <p>Are you a potential learner or Tutor? Our friendly team would love to hear from you</p>
                <form action="">
                    <div class="input-row">
                        <div class="input-area">
                            <label for="fname">First Name</label>
                            <input type="text" placeholder="First Name" name="firstname">
                        </div>
                        <div class="input-area">
                            <label for="lname">Last Name</label>
                            <input type="text" placeholder="Last Name" name="lastname">
                        </div>
                    </div>
                    <div class="input-row">
                        <div class="input-area">
                            <label for="email">Email</label>
                            <input type="text" placeholder="Enter email" name="email">
                            
                        </div>
                        <div class="input-area">
                            <label for="pnumber">Phone Number</label>
                            <input type="tel"  name="Phone" id="phone">
        
                        </div>
                    </div>
                       
                   
                    <label for="message">Message</label>
                    <textarea name="message" id="message" rows="5"></textarea>
                  
                   
                   
                    <p>  <i class="fa fa-check-circle" aria-hidden="true"></i> Prospective tutors will be contacted through the contact details they have provided for further steps</p>
                    <button type="submit">Send Message</button>
                </form>

            </div>
            <div class="right">

            </div>
        </div>
       
        <!-- <form action="">
            <p>Are you a potential learner or Tutor? Our friendly team would love to hear from you</p>
          <div class="names">
            <div class="name">
                <label for="fname">First Name</label>
                <input type="text" placeholder="First Name" name="firstname">
            </div>
            <div class="name">
                <label for="lname">Last Name</label>
            <input type="text" placeholder="Last Name" name="lastname">
            </div>
          </div>
            <div class="other">
                <label for="email">Email</label>
            <input type="text" placeholder="Enter email" name="email">
            
            <label for="pnumber">Phone Number</label>
            <input type="tel"  name="Phone" id="phone">

            <label for="message">Message</label>
            <textarea name="message" id="message"></textarea>

            <p>Prospective tutors will be contacted through the contact details they have provided for further steps</p>

            <input type="submit" value="Submit">
            </div>
            
        </form> -->
    </div>
</body>
<script>
    const phoneInputField = document.querySelector("#phone");
    const phoneInput = window.intlTelInput(phoneInputField, {
      utilsScript:
        "https://cdnjs.cloudflare.com/ajax/libs/intl-tel-input/17.0.8/js/utils.js",
    });
  </script>
</html>
