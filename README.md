# haukai
Haukai Restaurant Website



Question Part 2, b.
I have set the viewport as <meta name="viewport" content="width=device-width, initial-scale=1.0"> as matches the mobile device's screen width in device independent 
pixels.

I have added media queries so that the webpages can be adjusted to fit better on smaller screens.

I have added max-width to all images so that they also adjust for a smaller mobile device screen.

I have tested the website on https://search.google.com/test/mobile-friendly website and have been advised that the website is "Page is mobile friendly".



Question Part 2, d.
HTTP Caching is used to significantly improve performance, by eliminating the need to send requests in many cases and send full responses in many other cases.  With 
a website this means you can save a copy of images, stylesheets, javascript or the entire page to the browser.  Then the next time a user requires this resource the 
browser does not need to download it again, fewer downloads leads to a faster website with happier users.

Content Delivery Networks (CDN) is designed to shorten the path between the server and the user, it is a network of servers in different geographical locations.  When
a website is accessed by a user the information is pulled from the server which is located closest to them, this will result in a faster flow of data.  Using a CDN
can speed up your website by making the time it takes to ask for information, retrieve that information and send it to the user much faster.



EXTRA NOTES:
This is the code that gave me the look that I wanted for my reservation form however the assignment brief said to use Google Forms and I was unable to work 
out how to format the form to how I wanted it for my web page.

<div class="row">
      <div class="column1" style="border-left: 5px solid black;">
      <h3>TABLE RESERVATION:</h3>
<div style="padding-bottom: 18px;">Name<span style="color: red;">*</span><br/>
      <input type="text" id="data_3" name="data_3" style="width: 400px;" class="form-
      control"/>
      </div>
      <div style="padding-bottom: 18px;">Phone<br/>
      <input type="text" id="data_4" name="data_4" style="width: 400px;" class="form- 
control"/>
      </div>
      <div style="padding-bottom: 18px;">Email<br/>
      <input type="text" id="data_5" name="data_5" style="width: 400px;" class="form-
control"/>
      </div></div>
      <div class="column2" style="background-color: white;" style="padding-left: 50px;">
      <br><br><br>
      <div style="padding-bottom: 18px;">Date<span style="color: red;"> *</span><br/>
      <input type="text" id="data_6" name="data_6" style="width : 250px;" class="form-
control"/>
      </div>
      <div style="padding-bottom: 18px;">Time<span style="color: red;"> *</span><br/>
      <input type="text" id="data_7" name="data_7" style="width: 250px;" class="form-
control"/>
      </div>
      <div style="padding-bottom: 18px;">Number of Attendees<span style="color: red;"> 
*</span><br/>
      <select id="data_8" name="data_8" style="width : 250px;" class="form-control">
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
      <option>5</option>
      <option>6</option>
      <option>7</option> 
      <option>8</option>
      <option>9</option>
      <option>10</option>
      <option>10+ (Specify in Comments)</option>
      </select>
      </div></div>
      <div class="column3" style="border-right: 5px solid black;">
      <br><br><br>
      <div style="padding-bottom: 18px;">Comments / Additional Requests<br/>
      <textarea id="data_9" false name="data_9" style="width : 400px;" rows="6" 
class="form-control"></textarea>
      </div>
      <div style="padding-bottom: 18px;"><input name="skip_Submit" value="Submit" 
type="submit"/></div>
      <div>  
      </div></div>
      </script>