<html>
   <title>Animal Information</title>
      <body>

     <form action ="animal.php" method        ="POST">

    Name of Animal: <input type ="text" name = "user_name">

   Category: <input type ="radio" name ="category " value ="herbivores">herbivores

       <input type ="radio" name ="category " value ="omnivores">omnivores

       <input type ="radio" name ="category " value ="carnivores">carnivores

   Image: <img src = " (URL) ">

    Description: <textarea rows =" 3" cols="20"> 
    Enter text here.... 
   </textarea>

   Life expectancy: <select name ="life" id ="life">
            <option
                 <value = "0-1 year"> 0-1 year
             </option>
         <option
                 <value = "1-5 year"> 1-5 year
             </option>
          <option
                 <value = "5-10 year"> 5-10 year
             </option>
         <option
                 <value = "10+ year">10+ year
             </option>
     </select>
  
   submit: <input type = " submit" value = "submit">
    
  </form>
           
       </body>
</html>
