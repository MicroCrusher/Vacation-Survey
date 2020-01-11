# Vacation-Survey
Survey project for freeodecamp

<body>
 <!-- <div class="image">
   <div style="background-image:url(http://www.drodd.com/images15/vacation8.jpg) 
     
  </div>--> 
  
  <div class="title">
<h1 id="title">Favorite Vacation Survey<h1>
  </div>
  <div class="description">
  <p id="description">Help us plan our next Family Vacation!</p>
  </div>
  
  <!-- Code for form is below -->
  <form id="survey-form">
    
    <!-- Input Name Section -->
    
    <div class="name-label">
      
    <label for="name" id="name-label">Name</label>
      <input id="name" name="name" type="text" required minlength+"3" maxlength="15" placeholder="Your name here">
    </div>
    <br> <br>
    
    <!--email code section-->
    
      <div class= "email-label">
    <label for="email"id ="email-label">Email</label>
        <input id="email" name="email" type="email" required minlength="3" maxlength="50" pattern="[a-zA-Z0-9]@" placeholder="Your email address">
               </div>
            <br> <br>
        <!-- input number section -->
        <div class="number-label">
    <label for="number" id="number-label">Age<label> 
      <input id ="number" name="number" type="number" min="1" max="100" placeholder="100">
      <br> <br>
      <!-- Code for dropdown menu-->
      <label for="dropdown">Which family vacation have you enjoyed the most?
      </label>
      <br>
      <select name="dropdown" id="dropdown">
        <option value="maui">Maui</option>
        <option value="wakiki beach">Wakiki Beach</option>
        <option value="disney">Disney</option>
        <option value="up north/camping">Up North/Camping</option>
      </select>
      
      <!-- Radio Button code-->
            
      <div class="radioButtons">
        <p>Where would you like to go on vacation this year?</p>
        <input type="radio" name="vacation" id="maui" value="maui">
        <label for="maui">Maui</label>

        <input type="radio" name="vacation" id="wakiki" value="wakiki">
        <label for="wakiki">Wakiki Beach</label>

        <input type="radio" name="vacation" id="disney" value="disney">
        <label for="disney">Disney</label>

        <input type="radio" name="vacation" id="upnorth" value="upnorth">
        <label for="upnorth">Up North</label>

        <input type="radio" name="vacation" id="home" value="home">
        <label for="home">Stay at Home</label>

      </div> <!-- End of .radioButtons -->
      <br> <br> <br> <br> <br>
    
      
      <!-- Checkbox Code-->
      <div class="favact">Pick your favorite vacation activity</div>
      <br>
      <div class="checkButtons">
        <input type="checkbox" name="vacay" id="hiking" value="hiking">
        <label for="">Hiking</label>

        <input type="checkbox" name="vacay" id="eating" value="eating" >
        <label for="">Eating</label>

        <input type="checkbox" name="vacay" id="shopping" value="shopping">
        <label for="">Shopping</label>

        <input type="checkbox" name="vacay" id="museum" value="museum">
        <label for="">Museums/Sight-Seeing</label>

        <input type="checkbox" name="vacay" id="swimming" value="swimming">
        <label for="">Swimming</label>

        <input type="checkbox" name="tech" id="relax" value="relax">
        <label for="">Relaxation</label>
      </div>
      <br>
            <textarea name="message" id="message" cols="30" rows="10" placeholder="Please leave your addition comments here"></textarea>
      <br> <br>

      
      
       <button type="submit" id="submit" >Submit</button>
      </form>
      </body>
    

