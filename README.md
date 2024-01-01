Student Registration Project HTML 
<html>                                        
     <head>                               
         <title>College Registration</title>   
            </head>                                    
              <body>
                  <header>
<h3> College Registration </h3>
<h2>LCA College</h2>
</header>

<p>Additional Document for registration.</p> 
 <p> Bring the student registration form and the following documentation to the  school office.</p>                                         
                  <form>
                      <main>
<p> Original Certified Birth Certificate </p>
</main> 
<main>
<p>Original Social Security Card </p>
</main> 
<main>
<p>Current Immunization Form</p>
</main> 
<main>
<p>Current Proofs of Residence (ex. power, water, or gas bill)</p>
</main>                                                           
                       <h1> Student Information.</h1>                    
                       <label for="s1">Name</label> <br>                        
                       <input type="text"  "text"> 
                            <option value="s">First Name</option>

                       <input type="text"  "text">
                    <option value="">Last Name</option> <BR>

                  <label for="s1">SSN</label> <BR>
                  <input type="text"  "text"><br>

       <label  for="s1">Birth Date</label> <br>                        
                       <input type="text"  "text"> <br>
                     <option value="s">day month years</option><br

<label for="s1">Gender</label> <br> 
<input type="text"  ""> <br>
                 
                           <option value="m">*Male </option>        
                           <option value="f">Female</option> <br>     

 <label for="e">Ethnicity</label> <br> 
 
<select id="dropdown"> <br>
                   
          <option value="m">Please Select</option>        
            
         <option value="m">African American</option>        
          <option value="f">Hispanic/Latino</option>
         <option value="f">Asian</option>
       <option value="m">Native American</option>        
          <option value="f">Middle Eastern</option>
         <option value="f">Other</option> <br>
</select> <br>

<label for="e" style="padding-left: 130px;"> </label>
    <button onclick="saveChanges()">Save Changes</button>
  <h2>Email Address</h2> 
  <label for=> Email Addres</label> <br>
         <input type="text"  "text"> <br>
     <button="ex:yourname@example.com()">ex:yourname@example.com
       </button> <br>

<label for="s1">Phone Number</label> <br> 
<input type="text"  "text"> <br>
 <button="Please enter a valid phone number()">Please enter a valid phone number
       </button> <br>
       <label for="s1">Grade</label> <br> 
       <select id="dropdown"> <br>
                   
          <option value="m">Please Select</option>        
            
         <option value="m">1</option>        
          <option value="f">2</option>
         <option value="f">3</option>
         <option value="f">4</option> </select><br>

         <label for="s1">Semester</label> <br> 
         <input type="text"  "text"> <br>
 <p> Have you previously applied to or attended this school?</p>
         <ul>
          <li>Yes</li>
          <li>No</li>
        </ul>
        <p>if yes, what year? </p>
        <input type="text"  "text"> <br>
  <h2>Current Resident Information</h2> 
    <label for="s1">Address</label> <br> 
  <input type="text"  "text"> <br>
   <button="Street Address()">Street Address</button> <br>

    <input type="text"  "text"> <br>
   <button="Street Address Line()">Street Address Line</button> <br>

 <input type="text" + "text"> <br>
    <button="City()">City      State/Province</button> <br>

   <input type="text" + "text"> <br>
    <button="P()">Postal/    Zip Code</button> <br>

    <label for="s1">Home Phone Number</label> <br> 
 <input type="text" + "text"> <br>
    <button="Ac()">Area Code  /  Phone Number</button> <br>

<h2>Primary Resident Information (if different from above)</h2> 
  <label for="s1">Address</label> <br> 
  <input type="text"  "text"> <br>
   <button="Street Address()">Street Address</button> <br>

    <input type="text"  "text"> <br>
   <button="Street Address Line()">Street Address Line<2/button> <br>

 <input type="text" + "text"> <br>
    <button="City()">City      State/Province</button> <br>

   <input type="text" + "text"> <br>
    <button="P()">Postal/    Zip Code</button> <br>

    <h2>Parent/Guardian Resident Information(if different from above)</h2> 
  <label for="s1">Address</label> <br> 
  <input type="text"  "text"> <br>
   <button="Street Address()">Street Address</button> <br>

    <input type="text"  "text"> <br>
   <button="Street Address Line()">Street Address Line</button> <br>

 <input type="text" + "text"> <br>
    <button="City()">City      State/Province</button> <br>

   <input type="text" + "text"> <br>
    <button="P()">Postal/    Zip Code</button> <br>

    <label for="e" style="padding-left: 200px;"> </label>
    <button onclick="saveChanges()">Next</button><br>


<h2>Emergency Contact 1</h2>
<input type="text"  "text"> 
      <option value="s">First Name  / Last Name</option> 
<label for=> Email Addres</label> <br>
<input type="text"  "text"> <br>
     <button="ex:yourname@example.com()">ex:yourname@example.com
       </button> <br>
 <label for="s1">Home Phone Number</label> <br> 
 <input type="text" + "text"> <br>
    <button="Ac()">Area Code  /  Phone Number</button> <br>

<h2>Emergency Contact 2</h2>
<input type="text"  "text"> 
      <option value="s">First Name  / Last Name</option> 
<label for=> Email Addres</label> <br>
<input type="text"  "text"> <br>
     <button="ex:yourname@example.com()">ex:yourname@example.com
       </button> <br>
 <label for="s1">Home Phone Number</label> <br> 
 <input type="text" + "text"> <br>
    <button="Ac()">Area Code  /  Phone Number</button> <br>

<h2>Physician and Medical Information</h2>
<input type="text"  "text"> 
      <option value="s">First Name  / Last Name</option> 
<label for=> Email Addres</label> <br>
<input type="text"  "text"> <br>
     <button="ex:yourname@example.com()">ex:yourname@example.com
       </button> <br>
       
    
 <label for="s1">Home Phone Number</label> <br> 
 <input type="text" + "text"> <br>
 <button="Ac()">  Phone Number</button> <br>

  <input type="text" + "text"> <br>
 <button="Ac()">Area Code/ City/ State</button> <br>

  <label for="s1">Preferred Hospital</label> <br> 
 <input type="text" + "text"> <br>

  <label for="s1">Insurance/ Health Covarage (Company)</label> <br> 
 <input type="text" + "text"> <br>

 <h2>Please list any of the following Current medications, medication allergies,food allergies.</h2>

  <label for="s1">Chronic health concerns</label> <br> 
 <input type="text" + "text"> <br>

  <button onclick="saveChanges()">Back</button>
  <label for="e" style="padding-left: 160px;"> </label>
   <button onclick="saveChanges()">Next</button><br>
 <h3>Previous School.</h3>                    
            <label for="s1">School Name</label> <br>                        
             <input type="text"  "text"> 
                            <option value="s">City</option>
         <input type="text"  "text">
     <option value="s">State</option>

      <select id="dropdown"> <br>
                   
          <option value="m">Please Select</option>        
           <option value="m">AZ</option>        
          <option value="f">AL</option>
         <option value="f">AK</option>
         <option value="f">TX</option>   
        
       <option value="m">AR</option>        
          <option value="f">CA</option>
         <option value="f">FL</option>
         <option value="f">KS</option> 
        </select><br>

<label for="e" style="padding-left: 170px;"> </label>
    <button onclick="saveChanges()">Save Changes</button><br>

     <option value="s">Date Start</option>

      <select id="dropdown"> <br>
                   
          <option value="m">Please Select</option>        
           <option value="m">01.01.2024</option>    <br>
      </select>
       <option value="s">Date End</option>

      <select id="dropdown"> <br>
                   
          <option value="m">Please Select</option>        
           <option value="m">12.31.2024</option>    <br>
      </select>
             

       <h3>Notes</h3>                    
            <label for="s1">Please inform the office of any other vital information you think they may need to know about student in the event of an emergency.<br>
            Thank you.</label> <br>                        
             <input type="text"  "text"> <br>

               <button onclick="b()">Back</button>
  <label for="e" style="padding-left: 160px;"> </label>
   <button onclick="s()">Submit</button><br>
   

