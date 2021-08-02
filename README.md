# htmlprojectregrestration

<!DOCTYPE html>
<html>
<head>
  <h1 style="color: #aa5f24"> ICS Student Information Form</h1>
  <style>
    plt{
      padding: 200px;
    }
    before{
      padding: 45px;
    }

  </style>
  <body>
<form>
    <before><big> <fieldset><legend> <strong style="color: #aa5f24">Personal Information</strong> </big></before>
      <br>
      <br>
      Title:
      <div style="position:relative;  left: 350px; top: -20px">
      First Name: <input type = "text" name = "firstname" id = "firstname" placeholder="Enter first name">
      </div>
      <div style="position:relative;  left: 800px; top: -40px">
      Last Name: <input type = "text" name = "lastname" id = "lastname" placeholder="Enter last name"
    </div>
    <br>
    <br>
    <div style="position: relative; left: -750px; top: -20px">
    <input type="radio" id="Mr." name="radioGender">
    <label for = "Mr."> Mr. </label>
    <br>
    <input type="radio" id="Ms." name="radioGender">
    <label for = "Ms."> Ms. </label>
    <br>
    <input type="radio" id="Mrs." name="radioGender">
    <label for = "Mrs."> Mrs. </label>
    <br>
    <input type="radio" id="N/A" name="radioGender">
    <label for = "N/A"> Prefer not to say </label>
  </div>
    </legend> </fieldset>
    <br/>

    <br>
    <br>
    <br>

    <before><big> <fieldset><legend><strong style="color: #aa5f24"> Contact Info</strong> </big></before>
      <br>
      <br>
      E-mail: <input type = "email" id = "email" placeholder="someone12@gmail.com"></input>
      <plt> Phone Number: <input type = "Phone" id = "number" placeholder="000-000-0000" maxlength="10" size = "10"></input></plt>
    </legend> </fieldset>
    <br>
    <br>
    <br>


    <before><big> <fieldset><legend><strong style="color: #aa5f24"> Enrollment Information</strong> </big></before>
      <br>
      <br>
      <big>Date first enrolled:<input type = "date" id = 'date' placeholder="mm/dd/yyyy"</big>
      <br>
      <br>
      <big> Major: </big>
      <br>
      <input type = "radio" id = "Buisness Informatics" name = "Major">
      <label for = "Buisness Informatics"> Buisness Informatics</label>
      <br>
      <input type = "radio" id = "Health Informatics" name = "Major">
      <label for = "Health Informatics"> Health Informatics</label>
      <br>
      <input type = "radio" id = "Computer Science" name = "Major">
      <label for = "Computer Science"> Computer Science</label>
      <br>
      <input type = "radio" id = "Informatics Post-Baccalaureate Certificate" name = "Major">
      <label for = "Informatics Post-Baccalaureate Certificate"> Informatics Post-Baccalaureate Certificate</label>
      <br>
      <br>
      <label for = "GPA"> Choose your <strong>GPA:</strong> </label>
      <select name= "GPA" id = "GPA">
        <option value = "1.0"> 1.0 </option>
        <option value = "2.0"> 2.0 </option>
        <option value = "2.0"> 3.0 </option>
        <option value = "3.0"> 4.0 </option>
        <option value = "4.0"> 5.0 </option>
      </select>
      <br>

      <label for = "classes"> <strong> INFO </strong> classes taken: </label>
      <br>
      <select name = "classes" id = "classes" <div style="position: relative; left: 100px; top: 0px">
        <option value = "INFO 1181"> INFO 1181</option>
        <option value="INFO 1182"> INFO 1182 </option>
        <option value = "INFO 2285"> INFO 2285 </option>
        <option value = "INFO 3307"> INFO 3307 </option>
      </select>
    </fieldset></legend>
    <br>
    <br>

    <before><big> <fieldset><legend><strong style="color: #aa5f24"> Enrollment Information</strong> </big></before>
      <br>
      Are you employed?
      <br>
      <div style= "position: relative; left: 25px; top: 0px">
      <input type ="radio" id= "employed" name = "employmentstatus">
      <label for = "employed"> Yes </label>
      <br>
      <input type = "radio" id = "unemployed" name = "employmentstatus">
      <label for = "unemployed"> No </label>
    </div>
    <br>
    <br>
    If so, full time or part time?
    <br>
    <div style = "position: relative; left: 25px; top: 0px">
    <input type = "radio" id = "Fulltime" name = "time">
    <label for ="Fulltime"> Full time</label>
    <br>
    <input type = "radio" id = "Parttime" name = "time">
    <label for = "Parttime"> Part time</label>
  </div>
  <br>
  If you are intrested in internships, etc., please upload your resume:
  <br>
  <form action="/action_page.php">
  <label for="myfile"> </label>
  <input type="file" id="myfile" name="myfile"><br><br>
</form>
</legend></fieldset>
<br>
<br>
    <before><big> <fieldset><legend><strong style="color: #aa5f24"> Feedback</strong> </big></before>
      Please share any ideas that you have for improving the ICS Department.
      <br>
      <textarea name = "comment" rows = "20" cols = "70"></textarea>
      <br>
    </legend></fieldset>
    <input style="color: orange" type="submit" value="Submit">
    <input style = "color: orange" type="reset" value="Reset">
  </form>
    </body>


  </head>

  </html>
