<!DOCTYPE html>
<html>
<head>
<title>Attraction Beauty Salon</title>
<meta charset="utf-8"/>
<link href="style.css" rel="stylesheet" type="text/css"/>
<link href="photo.css" rel="stylesheet" type="text/css"/>
<script src="modernizr.custom.05819.js"></script>
<script src="calendar.js"></script>
</head>
<body>
<div id="wrapper"> <!-- container -->
<div id="header">
    
</div>
<!-- Navigation -->
<ul id="navlist">
    <li><a href="home.htm">Home</a></li>
    <li><a href="create.htm">Create Promotion</a></li>
    <li><a href="signup.htm">Sign Up</a></li>
</ul>

<div id="main">
    <div style="padding:20px; line-height:25px;">

        <p>
        Attraction Beauty Salon is the best salon in the whole of Johannesburg CBD. We are the providers of beautiful makeovers, from 
        weaving to braiding. We have the best stylist on standby to take care of your hair need. Check our style catalog for the hair styles we 
        have to stock for you.
        </p>
        
        <table>
            <tr>
                <td><img src="IMG_01.jpg" width="250" height="200"></td>
                <td><img src="IMG_02.jpg" width="250" height="200"></td>
                <td><img src="IMG_03.jpg" width="250" height="200"></td>
            </tr>
            <tr>
                <td><p>Weaving</p></td>
                <td><p>Braiding</p></td>
                <td><p>Last Weaving</p></td>
            </tr>
            
            <tr>
                <td><img src="IMG_04.jpg" width="250" height="200"></td>
                <td><img src="IMG_05.jpg" width="250" height="200"></td>
            </tr>
            <tr>
                <td><p>New style</p></td>
                <td><p>Colored Braiding</p></td>
            </tr>
            
            
        </table>
        
        <article>
            <table>
                <caption>April 2020</caption>
                
                <thead>
                    <tr>
                        <th>Sunday</th>
                        <th>Monday</th>
                        <th>Tuesday</th>
                        <th>Wednesday</th>
                        <th>Thursday</th>
                        <th>Friday</th>
                        <th>Saturday</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td></td>
                        <td></td>
                        <td>1</td>
                        <td>2<br>Eye lash fix<br>@14:00</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                    </tr>
                    
                    <tr>
                        <td>6</td>
                        <td>7</td>
                        <td>8</td>
                        <td>9</td>
                        <td>10<br>Free Make-up<br>@12:00</td>
                        <td>11</td>
                        <td>12</td>
                        
                    </tr>
                    
                    <tr>
                        <td>13</td>
                        <td>14</td>
                        <td>15</td>
                        <td>16</td>
                        <td>17<br>Manicure<br>@14:00</td>
                        <td>18</td>
                        <td>19</td>
                        
                    </tr>
                    
                    <tr>
                        <td>20</td>
                        <td>21</td>
                        <td>22</td>
                        <td>23</td>
                        <td>24</td>
                        <td>25<br>Free Make-p<br>@All Day</td>
                        <td>26</td>
                        
                    </tr>
                    
                    <tr>
                        <td>27 <br>Free Treatment<br>@14:00</td>
                        <td>28</td>
                        <td>29</td>
                        <td>30</td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    
                </tbody>
                
            </table>
        
        </article>
        

    </div>

</div>
<div id="footer">
Attraction Beauty Salon &bull; 2020
</div>
</div>
<script src="photo.js"></script>
</body>
</html>

Page 2 – Create Promotion

<!DOCTYPE html>
<html>
<head>
<title>Attraction Beauty Salon</title>
<meta charset="utf-8"/>
<link href="style.css" rel="stylesheet" type="text/css"/>
<link href="date.css" rel="stylesheet" type="text/css"/>
<script src="modernizr.custom.05819.js"></script>
<script src="meeting.js"></script>
<script src="date.js"></script>
</head>
<body>
<div id="wrapper"> <!-- container -->
<div id="header">
    
</div>
<!-- Navigation -->
<ul id="navlist">
    <li><a href="home.htm">Home</a></li>
    <li><a href="create.htm">Create Promotion</a></li>
    <li><a href="signup.htm">Sign Up</a></li>
</ul>

<div id="main">

<div style="padding:20px; line-height:25px;">

<p>
At Attraction Beauty Salon, we believe the key to the heart of customers is constant giveaways and promotions. To create a promotion 
please fill the form below and admin will review your promotion details and revert back to you.
</p>

    <!-- the form -->
    <form action="result.htm">
        <p><label class="name">Duration:</label>
            <select id="duration">
                <p>
                    <option value="15mins">15 MINS</option>
                    <option value="20mins">20 MINS</option>
                    <option value="1hour">1 HOUR</option>
                    <option value="2hours">2 HOURS</option>
                    <option value="4hours">4 HOURS</option>
                </p>
            </select>
            </p>
                    
            <p>
                <label class="name" for="celebDate">Date:</label>
                <input type="text" name="promotionDate" id="promotionDate" size="35" required placeholder="Promotion Date" />
            </p>
                    
            <p><label class="name" for="name">Time:</label>
                <select name="promoterDuration">
                    <p>
                        <option value="12:00PM TO 2:00PM">12:00PM - 2:00PM</option>
                        <option value="2:00PM TO 4:00PM">2:00PM - 4:00PM</option>
                    </p>
                </select>
            </p>
                    
            <p>
                <label class="name" for="venue">Venue:</label>
                <input type="text" id="venue" name="promotionVenue" size="35" required placeholder="Promotion Venue"/>
            </p>
            <p id="venueError" class="errorMsg"></p>

            <p><label class="name" for="celebVenue">Promotion Type:</label></p>
            <p>
            <select name="promotionType" id="promotion">
                <option value="">Select a Promotion Type</option>
                
                <option value="Treatment">Treatment</option>
                <option value="Hair Cut">Free Make-up</option>
                <option value="Manicure">Manicure</option>
                <option value="Pedicure">Pedicure</option>
                <option value="Pedicure">Beard Trim</option>
            </select>
            </p>
                    
            <p>Refreshment(s) served?
                <input type="checkbox" name="refreshment" value="Hot tea" id="tea"/><label for="tea">Hot Tea</label>
                <input type="checkbox" name="refreshment" value="Yummy Biscuit" id="biscuit"/><label for="biscuit">Yumm Biscuit</label>
                <input type="checkbox" name="refreshment" value="Sit-down lunch" id="lunch"/><label for="lunch">Sit Down Lunch</label>
            </p>
                    
            <p>
                <label class="name" for="celebMessage">Promo Message:</label>
                <textarea required name="shortMessage" id="shortMsg" col="" rows="5" placeholder="Enter a short promotion message.."></textarea>
            </p>
            <p id="messageError" class="errorMsg"></p>
            
            <p><label class="name" for="celebSchName">Promoter Name:</label><input type="text" name="name" required id="promoterName" id="contact" size="35" placeholder="John Ndhlovu" /></p>
            <p id="nameError" class="errorMsg"></p>
            
            <p><label class="name" for="celebSchEmail">Promoter Email:</label><input type="text" name="email" required id="promoEmail" id="meetEmail" size="35" placeholder="example@example.com" /></p>
            <p id="emailError" class="errorMsg"></p>
            
            <p><label class="name" for="celebSchPhone">Promoter Phone:</label><input type="text" name="phone" required id="promoPhone" id="meetEmail" size="35" placeholder="0712345678" /></p>
            <p id="phoneError" class="errorMsg"></p>
            
            <p><label class="name" for="password">Password:</label><input type="password" required id="password" id="password" size="35" /></p>
            <p id="passwordError" class="errorMsg"></p>
            
            <p><label class="name" for="conPassword">Confirm Password:</label><input type="password" required id="conPassword" id="meetEmail" size="35" /></p>
            <p id="conPasswordError" class="errorMsg"></p>
            
            <br/>

            <p style="margin-left:200px;"><input type="submit" value="Create Promotion"/></p>
        
    </form>
    
    <!-- create date section widget -->
    <div id="cal">
        <div id="prev">&lt; previous</div>
        <div id="next">next &gt;</div>
        <table>
            <caption></caption>
            <tr>
                <th>Sun</th>
                <th>Mon</th>
                <th>Tue</th>
                <th>Wed</th>
                <th>Thu</th>
                <th>Fri</th>
                <th>Sat</th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
        <p id="close">close <span>&#9746;</span></p>
    </div>

    <!-- end of widget -->  

</div>

</div>
<div id="footer">
Attraction Beauty Salon &bull; 2020
</div>
</div>
<script src="meeting.js"></script>
</body>
</html>

Page 3 – Sign-up for Promotion

<!DOCTYPE html>
<html>
<head>
<title>Attraction Beauty Salon</title>
<meta charset="utf-8"/>
<link href="style.css" rel="stylesheet" type="text/css"/>
<script src="modernizr.custom.05819.js"></script>
</head>
<body>
<div id="wrapper"> <!-- container -->
<div id="header">
    
</div>
<!-- Navigation -->
<ul id="navlist">
    <li><a href="home.htm">Home</a></li>
    <li><a href="create.htm">Create Promotion</a></li>
    <li><a href="signup.htm">Sign Up</a></li>
</ul>

<div id="main">

<div style="padding:20px; line-height:25px;">
    <h3>Join our next meeting</h3>
    
    <!-- use the name property -->
    <form>
        <p><label class="name" for="name">Name:</label><input type="text" name="name" id="name" placeholder="Full name"/></p>
        <p><label class="name" for="company">Company:</label><input type="text" name="company" id="company" placeholder="Company name"/></p>
        <p><label class="name" for="email">Email:</label><input type="text" name="email" id="email" placeholder="Email"/></p>
        <p><label class="name" for="contact">Office Number:</label><input type="text" name="contact" id="contact" placeholder="Phone number"/></p>
        <p><label class="name" for="name">Promotion:</label>
        
        <select name="promotion" id="promotionType">
            <option value="">Select a Promotion Type</option>
            <option value="Treatment">Treatment</option>
            <option value="Hair Cut">Free Make-up</option>
            <option value="Manicure">Manicure</option>
            <option value="Pedicure">Pedicure</option>
            <option value="Pedicure">Beard Trim</option>
        </select>
        
        </p>
        
        
        <p><label>Select Refreshment you want:</label></p>
        
        <p><input type="checkbox" id="item1" value="9" class="item">
        <label for="item1">Chocolate tea (R9.00)</label></p>
        
        <p><input type="checkbox" id="item2" value="14" class="item">
        <label for="item2">Biscuit (R14.00)</label></p>
        
        <p><input type="checkbox" id="item3" value="9" class="item">
        <label for="item3">Coffee (R9.00)</label></p>
        
        <p><input type="checkbox" id="item4" value="35" class="item">
        <label for="item4">Sit Down Lunch (R35.00)</label></p>
        
        <p><input type="checkbox" id="item5" value="12" class="item">
        <label for="item5">Cold drink (R12.00)</label></p>
        
        <div>
            <p id="mytotal" style="font-weight: bold; color: red;"></p>
        </div>
        
        <p><input type="submit" value="Sign Me Up" id="sButton" style="margin-left:300px;"/></p>

    </form>
</div>


</div>
<div id="footer">
Attraction Beauty Salon &bull; 2020
</div>
</div>
<script src="cookies.js"></script>
<script src="calculations.js"></script>
</body>
</html>

