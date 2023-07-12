# Travellingsite

Here's a link to my website [MakeYourTrip]()

## Table of contents

1. Front page [Frontpage](code.txt)
2. About us page [Aboutus](aboutus.html)
3. Contact us page [contactus](contactus.html)
 
## html code for front page

* Here's my code to make frontpage [Frontpage code](code.txt)


Here's a frontpage view of my website


<img src="./frontpagephoto.png"
     alt="VSC code screensot"
     style="float: left; margin-right: 10px;" />




```Html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MakeYourTrip-#Top rated platform</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="styling.css">
    <link rel="stylesheet" href="utility.css">
    <link rel="stylesheet" href="exploredest.css">

</head>

<body>
    <header>



        <nav class="navigate">
            <div class="logo">
                <img src="favicon.ico" alt="" width="29px">
            </div>
            <ul>
                <li><a href="frontpage.html">HOME</a></li>
                <li><a href="">SPECIAL OFFERS</a></li>
                <li><a href="aboutus.html">ABOUT US</a></li>
                <li><a href="contactus.html">CONTACT US</a></li>
            </ul>
            <div class="search">
                <!-- <label for="Search">Search your Destinations</label> -->
                <input type="text" name="Search" id="" placeholder=" Search for Your fav Tourist Places">

                <button class="btn">SEARCH</button>
            </div>

            </div>

        </nav>
    </header>

    <div id="videofix">
        <!-- <video src="naturevideo.mp4" controls width="690px" loop></video> -->
    </div>
    <div class="form">
        <div class="piclines">
            <p id="one">The Trip of Your Dream</p>
            <p>Our Travel agency is ready to offer you an exciting vacation that is <br>designed to fit your own
                needsand wishes.Whether its an exotic tour <br>
                or an trip to your favourite resort.You will surely have the best experience.</p>
            <br><br>
            <button class="submitbtn">Learn More</button>
        </div>
        <div class="formcontent">
            <form action="">
                <caption>FIND YOUR TOUR</caption><br>
                <!-- <label for="name">Enter Your Name</label>
              <input type="text" name="" id="" placeholder="name"> -->
                <br>
                <label for="name">From </label>
                <input type="text" name="" id="" placeholder="Your city name">
                <br><br>
                <label for="name">To</label>
                <input type="text" name="" id="" placeholder=" Your Destination">
                <br><br>
                <label for="name">Enter Your email id</label>
                <input type="email" name="" id="" placeholder="gmail id">
                <br><br>
                <label for="name">Depart</label>
                <input type="date" name="" id="" placeholder="choose date">
                <br><br>
                <label for="name">Duration</label>
                <select name="" id="">
                    <option value="">Select no. of days</option>
                    <option value="">1 night and 2 days</option>
                    <option value="">2 night and 3 days</option>
                    <option value="">3 night and 4 days</option>
                    <option value="">4 night and 5 days</option>
                    <option value="">5 night and 6 days</option>
                    <option value="">1 week or more</option>
                </select><br>

                <br><button class="submitbtn">submit</button>

            </form>
        </div>
    </div>
    <h2 id="topdest">Explore Top Destinations</h2>
    <br> <br>
    <div class="exploredestinations">
        <div class="destination1">
            <div class="border">
                <h3>India</h3>
                <p> 100 cities
                </p>
            </div>
        </div>
        <div class="destination2">
            <div class="border">
                <h3>Paris</h3>
                <p> 100 cities
                </p>
            </div>
        </div>
        <div class="destination3">
            <div class="border">
                <h3>Greece</h3>
                <p> explore
                </p>
            </div>
        </div>
        <div class="destination4">
            <div class="border">
                <h3>Canada</h3>
                <p> Niagara Falls
                </p>
            </div>
        </div>
    </div>
    <marquee behavior="alternate" direction="right to left">Book Your package with MakeYourTrip and avail 10% extra discount</marquee>
    <div class="exploredestinations">
        <div class="destination5">
            <div class="border">
                <h3>Dubai</h3>
                <p> 100 cities
                </p>
            </div>
        </div>
        <div class="destination6">
            <div class="border">
                <h3>Egypt</h3>
                <p> 100 cities
                </p>
            </div>
        </div>
        <div class="destination7">
            <div class="border">
                <h3>Maldives</h3>
                <p> explore
                </p>
            </div>
        </div>
        <div class="destination8">
            <div class="border">
                <h3>Bali</h3>
                <p>Visit Now
                </p>
            </div>
        </div>
    </div>
    <div class="megaoffer">
        <div class="megaofferlines">
            <h3 id="megahead"><u>Mega Offer</u></h3>
            <br>
            <h2>
                <h1>30%</h1> OFF For Family Vacation
            </h2>
            <!-- <h3>HURRY UP !!</h3> -->
            <!-- <h3>Grab The Offer</h3> -->

            <p id="term">T&C Apply</p>
        </div>
        <div class="megaofferform">
            <form action="">
                <h2>SIGN UP NOW</h2>

                <br>
                <input class="inputform" type="text" placeholder="Your name">
                <br><br>
                <input class="inputform" type="email" placeholder="Your email">
                <br><br>
                <select class="inputform" name="Destination" id="">
                    <option value="">SELECT DESTINATION</option>
                    <option value="">Andhra Pradesh</option>
                    <option value="">Arunachal Pradesh</option>
                    <option value="">Goa</option>
                    <option value="">Gujarat</option>
                    <option value="">Haryana</option>
                    <option value="">Himachal Pradesh</option>
                    <option value="">Jammu and Kashmir</option>
                    <option value="">Kerala</option>
                    <option value="">Meghalaya</option>
                    <option value="">Maharashtra</option>
                    <option value="">Rajasthan</option>
                    <option value="">Tamil Nadu</option>
                    <option value="">Uttarakhand</option>
                    <option value="">West Bengal</option>
                    <option value="">Andaman and Nicobar Islands</option>
                    <option value="">Delhi</option>
                    <option value="">Ladakh </option>
                    <option value="">Lakshadweep</option>
                    <option value="">Madhya Pradesh</option>
                    <option value="">Chandigarh</option>
                </select><br><br>
                <button type="button" class="submitbtn">SIGNUP</button>
            </form>
        </div>
    </div>
    <div class="refund">
        <div class="refundlines">
            <h2>Full Refund</h2>
            <p>Due to any medical reasons, according to our terms and conditions ,<br>
                after you submit us with proper
                medical <br>Refund will be provided to the account provided <br>100% refund would be provided to you.
                <br> REFUND WITHIN 10 DAYS ONLY !!
            </p>
        </div>
    </div>
    <div class="whybooking">
        <div class="whybook">
            <h2 class="h2book">Why Book With US ?</h2>
            <div class="backimage">
                <div class="photo">
                    <img src="https://www.easemytrip.com/images/desk-img/easy-booking.svg" alt="">
                    <div class="descrip">
                        <p class="heading"><b>Easy Booking</b></p>

                    </div>
                </div>



                <div class="photo">
                    <img src="https://www.easemytrip.com/images/desk-img/lowest-booking.svg" alt="">
                    <div class="descrip">
                        <p class="heading"><b>Lowest Price</b></p>

                    </div>
                </div>



                <div class="photo">
                    <img src="https://www.easemytrip.com/images/desk-img/exc-deal.svg" alt="">
                    <div class="descrip">
                        <p class="heading"><b>Exciting Deals</b></p>

                    </div>
                </div>



                <div class="photo">
                    <img src="https://www.easemytrip.com/images/desk-img/support.svg" alt="">
                    <div class="descrip">
                        <p class="heading"><b>24/7 Support</b></p>

                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="lowerfooter">
        <div class="container" id="whymake">
            <p>
                <b>Why MakeYourTrip</b>
                <br>
                Established in 2023, MakeYourTrip has since positioned itself as one of the leading companies,
                providing great offers, competitive airfares, exclusive discounts, and a seamless online booking
                experience to many of its customers. The experience of booking your flight tickets, hotel stay, and
                holiday package through our desktop site or mobile app can be done with complete ease and no hassles
                at all. We also deliver amazing offers, such as Instant Discounts, Fare Calendar, MyRewardsProgram,
                MyWallet, and many more while updating them from time to time to better suit our customers’ evolving
                needs and demands.
            </p>
        </div>
        <div class="container" id="booking">
            <p>
                <b>Booking Flights with MakeYourTrip</b><br>
                At MakeyourTrip, you can find the best of deals and cheap air tickets to any place you want by booking
                your tickets on our website or app. Being India’s leading website for hotel, flight, and holiday
                bookings, it helps you book flight tickets that are affordable and customized to your
                convenience. With customer satisfaction being our ultimate goal, we also have a 24/7 dedicated
                helpline to cater to our customer’s queries and concerns. Serving over 5 million happy customers, we
                at MakeYourTrip are glad to fulfill the dreams of folks who need a quick and easy means to find air
                tickets. You can get a hold of the cheapest flight of your choice today while also enjoying the
                other available options for your travel needs with us.
            </p>
        </div>
    </div>

    <!-- <div class="container">  -->
    <!-- <p> -->
    <!-- <b>Domestic Flights with MakeMyTrip</b> -->
    <!-- MakeMyTrip is India's leading player for flight bookings. With the cheapest fare guarantee, experience great value at the lowest price. Instant notifications ensure current flight status, instant fare drops, amazing discounts, instant refunds and rebook options, price comparisons and many more interesting .isit all major cities of India buying cheap domestic flight tickets at EaseMyTrip.com. We display widest network of airlines traveling on different Indian cities and assure you a memorable journey. Book any domestic flight with EaseMyTrip.com and get up to Rs.500 Off. Use promotion code EMT2022 and then compare airfare for anywhere. So, leave all your worries behind and plan a memorable trip with domestic flights at EaseMyTrip.com. -->



    <!-- </p> -->
    <!-- </div> -->

    <footer>
        <div id="footers">
            <p class="copyright">CopyRight &copy;TourismIndustry<br>
                MAKE YOUR TRIP PVT.LTD</p>
        </div>
    </footer>



</body>

</html>




```
## Here's my code for Aboutus page

* Here's the code for contact us page [About us page](aboutus.html)

Here's a about us page view

<img src="./aboutuspage.png"
     alt="VSC code screensot"
     style="float: left; margin-right: 10px;" />


### Here's the code for About us page
```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="aboutus.css">
</head>

<body>
    <div class="img">
        <div class="lines"></div>
        <!-- <img src="https://images.unsplash.com/photo-1502791451862-7bd8c1df43a7?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dHJhdmVsJTIwaW1hZ2V8ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&w=600&q=60" -->
            <!-- alt=""> -->
    
    <div class="aboutus">
        <h3>ABOUT US</h3>
        <h1>We Provide Best Tour Packages In Your Budget</h1>
        <p>At MakeyourTrip, you can find the best of deals and cheap air tickets to any <br>place you want by booking your tickets on our website or app. Being India’s <br>leading website for hotel, flight, and holiday bookings, it helps you book <br>flight tickets that are affordable and customized to your convenience. With <br>customer satisfaction being our ultimate goal, we also have a 24/7 dedicated <br>helpline to cater to our customer’s queries and concerns. Serving over 5 million <br>happy customers, we at MakeYourTrip are glad to fulfill the dreams of folks <br> who need a quick and easy means to find air tickets. You can get a hold of the <br>cheapest flight of your choice today while also enjoying the other available  <br>options for your travel needs with us.</p>
    </div>
</div>
</body>

</html>


```
## Here's my code for contact us page


* Here's the code for contact us page [Contact us page](contactus.html)

Here's a contact us page view

<img src="./contactuspage.png"
     alt="VSC code screensot"
     style="float: left; margin-right: 10px;" />

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact us</title>
    <link rel="stylesheet" href="contact.css">
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
    <!-- <h1>CONTACT US</h1> -->
<div class="container">
    <div class="text">
       Contact us Form
    </div>
    <form action="#">
        <caption>CONTACT US</caption>
       <div class="form-row">
          <div class="input-data">
             <input type="text" required>
             <div class="underline"></div>
             <label for="">First Name</label>
          </div>
          <div class="input-data">
             <input type="text" required>
             <div class="underline"></div>
             <label for="">Last Name</label>
          </div>
       </div>
       <div class="form-row">
          <div class="input-data">
             <input type="text" required>
             <div class="underline"></div>
             <label for="">Email Address</label>
          </div>
          <div class="input-data">
             <input type="text" required>
             <div class="underline"></div>
             <label for="">Website Name</label>
          </div>
       </div>
       <div class="form-row">
       <div class="input-data textarea">
          <textarea rows="8" cols="80" required></textarea>
          <br />
          <div class="underline"></div>
          <label for="">Write your message</label>
          <br />
          <div class="form-row submit-btn">
             <div class="input-data">
                <div class="inner"></div>
                <input type="submit" value="submit">
             </div>
          </div>
    </form>
    </div>
</body>
</html>

```     
## Here's the CSS codes of the above website

* The given are the sets of CSS codes that i have used to make this website look attractive:

```css

@import url('https://fonts.googleapis.com/css2?family=Caprasimo&display=swap');
header {

    background-color: var(--main-bg-color);
    font-family: sans-serif;
}

nav {
    display: flex;
}

.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 48px;
    padding: 0 25px;
}

nav ul li {
    list-style: none;
    padding: 0 24px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a:hover {
    color: rgb(236, 146, 156);
    font-weight: bolder;
}

nav ul {
    display: flex;
    justify-content: flex-start;
    height: 58px;
    align-items: center;
}

.navigate {
    height: 50px;
    background-color: rgb(191, 4, 4);
    color: aliceblue;
}

.navitems a {
    background-color: rgb(191, 4, 4);
    margin: 15px;
    color: aliceblue;
    text-decoration: none;
}

#videofix {
    position: relative;

}

#footers {
    background-color: rgb(191, 4, 4);
    color: aliceblue;
    height: 80px;
    text-align: center;
    font-family: 'lato', sans-serif;
    /* margin-top: 30px; */
}

.search {
    display: flex;
    align-items: center;
}

.search input {
    width: 280px;
    height: 25px;
    border-radius: 4px;
    margin: 0 16px 0 76px;
    padding: 0 14px;
}

.submitbtn {
    font-family: cursive;
    font-weight: bolder;
    border-radius: 3px;
    width: 100px;
    border-color: rgb(149, 0, 0);
    cursor: pointer;
}

.search button {
    font-family: cursive;
    font-weight: bolder;
    border-radius: 3px;
    width: 100px;
    border-color: rgb(149, 0, 0);
    cursor: pointer;
}

.search button:hover {
    color: rgb(114, 100, 100);
}

.refund {
    /* background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRIwZxxt8iR0qr61KhHDDiMVBLnKxdn3q0ueA&usqp=CAU'); */
    background-repeat: no-repeat;
    background-size: contain;
    height: 200px;
    /* background-color: rgb(91, 153, 204); */
    background-color: rgba(5, 127, 188, 0.5);
    
    padding: 10px;
    margin: 20px;
    border-radius: 25px;
    background-image: url('https://media.istockphoto.com/id/1437853553/photo/3d-medical-history-icon-health-document-on-clipboard-pill-white-capsule-red-heart-personal.webp?b=1&s=170667a&w=0&k=20&c=igAEGN6JmNoTBpdvvlofcSfBRgu0Ws8UBRofkc41-Qc=');
}
.refundlines{
    /* text-align: right; */
    padding-right: 20px;
    padding-left: 340px;
    font-size: 20px;
    color: aliceblue;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.megaoffer{
    background-image: url('https://media.istockphoto.com/id/1397843969/photo/rearview-shot-of-a-happy-family-walking-towards-the-sea.webp?b=1&s=170667a&w=0&k=20&c=q_dlVsV0rJq86G-pX6ug37BExOfJgljHDobyhMH7XyQ=');
height: 500px;
background-repeat: no-repeat;

margin-left: 35px;
margin-right: 35px;
border-radius: 19px;
background-size: cover;
text-align: center;
}
.megaofferlines{
    text-align: left;
    color: rgb(0, 0, 0);
    font-size:30px ;
    /* border: 1px solid black; */
    width: 550px;
    height: 400px;
    margin-left: 6px;
    margin-bottom: 120px;
    display: inline-block;
    padding-top: 100px;
    padding-left: 47px;
    /* font-family: poppins,sans-serif ; */
    font-family: 'Caprasimo', cursive;
}
#megahead{
    /* text-align: center; */
    /* font-family: 'Courier New', Courier, monospace; */
    color: #2d0505;
    padding-left: 50px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
#term{
    font-size: small;
}
.megaofferform{
    display: inline-block;
    
    background-color: rgba(0,0,0,.5);
    /* background-color: azure; */
    font-family: 'lato';
    font-weight: bolder;
    border-radius: 14px;
    
    /* border: 1px solid black; */
    margin-left: 20px;
    margin-top: 30px;
    padding: 30px;
    /* color: rgb(31, 20, 20); */
    font-size: 17px;
    

    display: inline-block;
}
inputform{
    /* height: 12px; */
    /* width: 100%; */
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    /* display: flex; */
}





```
* second set of css code:

```css

@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=PT+Sans+Narrow&display=swap');
*{
    margin: 0;
    padding: 0;
    /* color: grey; */
    /* background-color:rgb(197, 196, 196); */
}
.lowerfooter{
    background-color: rgb(203, 203, 203);
    color: grey;
}
.container{
    /* border: 1px dotted black; */
    width: 520px;
    display: inline-block;
    padding: 10px;
   

     /* margin : 25px;  */
} 
#whymake{
    height: 200px;
    margin-top: 33px;
    margin-left: 20px;
}
#booking{
    margin-top: 10px;
    margin-right: 10px;
    margin-left: 70px;
    padding-right: 10px;
   width: 590px;
}
.piclines{
    text-align: left;
    color: white;
    font-size:25px ;
    /* border: 1px solid black; */
    width: 750px;
    height: 400px;
    /* margin-left: 60px; */
    display: inline-block;
}


.formcontent{
    background-color: azure;
    font-family: 'lato';
    font-weight: bolder;
    border-radius: 14px;
    
    /* border: 1px solid black; */
    margin-left: 20px;
    margin-top: 30px;
    padding: 5px;
    color: rgb(31, 20, 20);
    font-size: 17px;
    /* opacity: 0.8; */
    background-color: rgba(239, 236, 236, 0.5);
    
    /* width: fit-content; */

    display: inline-block;
    /* margin-left: 800px; */
    /* margin-right: 40px; */
   /* margin-top: 40px; */
    /* margin-bottom: 3300px; */
    /* padding-bottom: 200px; */
    /* margin-top: 30px; */
}
#one{
   padding-bottom: 30px;
   color: white;
   font-size: 40px;
   padding-top: 100px;
}
.form{
    /* border: 0.025px solid black; */
    border-radius: 15px;
    text-align: center;
    height: 400px;
    padding: 40px;
    margin: 40px;
    background-repeat: no-repeat;
    /* background-size: 1000px 600px; */
    background-size: cover;
    background-image: url('https://plus.unsplash.com/premium_photo-1680129305219-ccb4db9613e1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8dHJhdmVsJTIwYmFja2dyb3VuZHxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=600&q=60');
}
.places{
    max-width: 89vw;
    margin: 35px auto;
    font-family: 'PT Sans Narrow', sans-serif;
}
.place3{
    color: rgb(0, 0, 0);
}
.place1{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}
.placedes{
    display: inline-flex;
    justify-content: center;
    flex-direction: column;
    margin: 0 16px;
    border-radius: 14px;
}
.contain{
    min-height: calc(100vh - 58px - 12vh);
}
.backimage{
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNWDAgcgJYMOxShuTe086gKx3aXesLoPpl3Q&usqp=CAU');
    background-repeat: no-repeat;
    background-size: 1290px 113px;
}
/* .whybook{ */
    /* max-width: 89vw; */
    /* margin: 45px; */
    /* font-family: 'PT Sans Narrow', sans-serif; */
    /* display: inline; */
    /* height: 200px; */
/* } */
.photo{
    display: inline-block;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    margin-bottom: 15px;
    padding-bottom: 30px;
    padding-right: 85px;
    padding-left: 85px;
    /* width: 100%; */
    /* margin: auto; */
}
.h2book{
    color: rgb(105, 101, 101);
    padding-bottom: 40px;
    text-align: justify;
    padding-left: 40px;
}
.descrip{
    padding: auto;
    justify-content: center;
    font-family: 'lato','Courier New', Courier, monospace;
    font-weight: bolder;
    color: rgb(242, 69, 69);
    margin: 3px;
    align-items: center;
}




```

* third set of css code for explore destinations

```css

#topdest{
    font-size: 40px;
    text-align: center;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.destination1 {
    background-image: url('https://images.unsplash.com/photo-1548013146-72479768bada?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8aW5kaWElMjB0cmF2ZWx8ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&w=600&q=60');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
     
}
.destination2 {
    background-image: url('https://media.istockphoto.com/id/944842098/photo/the-eiffel-tower-and-river-seine-at-twilight-in-paris.webp?b=1&s=170667a&w=0&k=20&c=tBWG093tD0L7ro1SB4-x3T78WyZQXGT1J-2Z8zDUsE8=');
    width: 180px;
    height: 150px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}
.destination3 {
    background-image: url('https://images.unsplash.com/photo-1580502304784-8985b7eb7260?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTh8fGdyZWVjZXxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=600&q=60');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}
.destination4 {
    background-image: url('https://media.istockphoto.com/id/1346270784/photo/niagara-falls-horseshoe-falls.webp?b=1&s=170667a&w=0&k=20&c=Tay5_rhwRPcyFUBjOhnWNCXVB7Zv3-uwJ-6Qv7PZVMg=');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}
.destination5 {
    background-image: url('https://media.istockphoto.com/id/183342824/photo/stylized-aerial-view-of-dubai-city.webp?b=1&s=170667a&w=0&k=20&c=8znCwSW4E99HibS2N1hUb7IEcTJC04VVDj-t7_WHPpU=');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}
.destination6 {
    background-image: url('https://media.istockphoto.com/id/1320446784/photo/landscape-with-egyptian-pyramids-great-sphinx-and-silhouettes-ancient-symbols-and-landmarks.webp?b=1&s=170667a&w=0&k=20&c=cpzEbS9g9aqqpoHOoW9FFkmZebDaB6owjWy65SncEtY=');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}
.destination7 {
    background-image: url('https://media.istockphoto.com/id/1348963437/photo/foot-path-to-jetty.webp?b=1&s=170667a&w=0&k=20&c=Q7w_lNSnql0k6jeFNfaaxFDyxM0Z8NXj81ATK6mtSL4=');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}
.destination8 {
    background-image: url('https://media.istockphoto.com/id/1471856897/photo/ulun-danu-beratan-temple-bali-indonesia.webp?b=1&s=170667a&w=0&k=20&c=jgjsM3lDjMhII8oNdY4XZSh9HwB8evwXQRrgHQTRt4E=');
    width: 180px;
    height: 190px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 20px;
    color: white;
    padding: 55px;
    text-align: center;
    font-size: 20px;
     font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     border-radius: 20px;
}

.destination1 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination2 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination3 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination4 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination5 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination6 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination7 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.destination8 :hover{
    background-color: rgba(222, 200, 200, 0.5);
    cursor: pointer;

}
.border{
    border: 1px solid rgb(230, 220, 220);
    /* padding: 40px; */
    /* padding-top: 2px; */
    margin: 0px;
    padding-bottom: 40px;
    padding-top: 20px;
    border-radius: 4px;
    background-color: rgba(74, 72, 72, 0.5);
}
.exploredestinations{
    display: inline-flex;
    height: 400px;
    margin-bottom: 0px;
    background-image: url('https://media.istockphoto.com/id/1323067500/photo/gray-digital-network-image-background.webp?b=1&s=170667a&w=0&k=20&c=bWtrHTVA7UxTlzCHzSFfm1JAw6sPi-t5_BZ6dv_rWWM=');
    background-repeat: no-repeat;
    background-size: cover;
}
marquee{
    color: red;
    font-size: 30px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}




```


* css code for contact us page

```css
@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');
*{
  margin: 0;
  padding: 0;
  outline: none;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
caption{
    text-align: center;
}
body{
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  padding: 10px;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(115deg, #56d8e4 10%, #9f01ea 90%);
}
.container{
  max-width: 800px;
  background: #fff;
  width: 800px;
  padding: 25px 40px 10px 40px;
  box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
}
.container .text{
  text-align: center;
  font-size: 41px;
  font-weight: 600;
  font-family: 'Poppins', sans-serif;
  background: -webkit-linear-gradient(right, #56d8e4, #9f01ea, #56d8e4, #9f01ea);
  /* -webkit-background-clip: text; */
  -webkit-text-fill-color: transparent;
}
.container form{
  padding: 30px 0 0 0;
}
.container form .form-row{
  display: flex;
  margin: 32px 0;
}
form .form-row .input-data{
  width: 100%;
  height: 40px;
  margin: 0 20px;
  position: relative;
}
form .form-row .textarea{
  height: 70px;
}
.input-data input,
.textarea textarea{
  display: block;
  width: 100%;
  height: 100%;
  border: none;
  font-size: 17px;
  border-bottom: 2px solid rgba(0,0,0, 0.12);
}
.input-data input:focus ~ label, .textarea textarea:focus ~ label,
.input-data input:valid ~ label, .textarea textarea:valid ~ label{
  transform: translateY(-20px);
  font-size: 14px;
  color: #3498db;
}
.textarea textarea{
  resize: none;
  padding-top: 10px;
}
.input-data label{
  position: absolute;
  pointer-events: none;
  bottom: 10px;
  font-size: 16px;
  transition: all 0.3s ease;
}
.textarea label{
  width: 100%;
  bottom: 40px;
  background: #fff;
}
.input-data .underline{
  position: absolute;
  bottom: 0;
  height: 2px;
  width: 100%;
}
.input-data .underline:before{
  position: absolute;
  content: "";
  height: 2px;
  width: 100%;
  background: #3498db;
  transform: scaleX(0);
  transform-origin: center;
  transition: transform 0.3s ease;
}
.input-data input:focus ~ .underline:before,
.input-data input:valid ~ .underline:before,
.textarea textarea:focus ~ .underline:before,
.textarea textarea:valid ~ .underline:before{
  transform: scale(1);
}
.submit-btn .input-data{
  overflow: hidden;
  height: 45px!important;
  width: 25%!important;
}
.submit-btn .input-data .inner{
  height: 100%;
  width: 300%;
  position: absolute;
  left: -100%;
  background: -webkit-linear-gradient(right, #56d8e4, #9f01ea, #56d8e4, #9f01ea);
  transition: all 0.4s;
}
.submit-btn .input-data:hover .inner{
  left: 0;
}
.submit-btn .input-data input{
  background: none;
  border: none;
  color: #fff;
  font-size: 17px;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
  cursor: pointer;
  position: relative;
  z-index: 2;
}
@media (max-width: 700px) {
  .container .text{
    font-size: 30px;
  }
  .container form{
    padding: 10px 0 0 0;
  }
  .container form .form-row{
    display: block;
  }
  form .form-row .input-data{
    margin: 35px 0!important;
  }
  .submit-btn .input-data{
    width: 40%!important;
  }
}


```


* code for about us page

```

*{
    margin: 10px;
    padding: 10px;
    background-color: rgb(194, 201, 201);
}
.img{
    border-radius: 10px;
    background-repeat: no-repeat;
    /* background-size: 1400px; */
    height:800px;
    background-image: url('https://images.unsplash.com/photo-1502791451862-7bd8c1df43a7?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dHJhdmVsJTIwaW1hZ2V8ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&w=600&q=60');
}
.lines{
    /* background-color: blue; */
    width: 1000px;
    height: 100px;
    margin-right: 450px;
    display: inline;
    
}
h3{
    background-color: aliceblue;
    color: #1fd304;
    font-family: 'poppins',sans-serif;
    font-size: 35px;
}
h1{
    background-color: aliceblue;
    color: #000;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
p{
    background-color: aliceblue;
    color: #000;
    font-family: 'lato';
    color: grey;
}
.img :hover{
    opacity: 0.8;
}
.aboutus{
    background-color: aliceblue;
    height: 600px;
    display: inline-block;
    margin-right: 50px;
    width: 550px;
    margin-top: 70px;
    text-align: justify;
    border-radius: 15px;
}


```