 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Payment Form</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>

<!--Payment Form-->

<form action="">
        <h1>Payment Form</h1>
        <h2>Contact Information</h2>
        <p>Name: <input type="text" name="name" required></p>
        <fieldset >
                <legend>Gender</legend>
                 <p>
                 Male<input type="radio" name="gander" id="male" required>
                 Female<input type="radio" name="gander" id="male" required>    
                </p>
        </fieldset> 
        
        <p>Address:
        
        <textarea name="address" id="address" cols="100" rows="7" ></textarea>
                
        </p>
        
        <p>Email:
         <input type="email" name="email" id="email" required>       
        </p>       
        
        <p>Pincode:
        <input type="number" name="pincode" id="pincode" required>      
        </p>
                <h2>Payment Information</h2>

        <p>Card-type:
                <select name="Card type" id="Card type">
                        <option value="">--Select a Card Type--</option>
                        <option value="">Visa</option>
                                                <option value="MasterCard">MasterCard</option>


                        <option value="rupay">rupay</option>

                </select>
        </p>   
        <p>
                Card Number <input type="number" name="" id="Card_number" required>
        </p>
        <p>
                Expiring Date:<input type="date" name="expiring date" id="expiring date" required>
        </p>
        <p>
                CVV<input type="password" name="cvv" id="cvv" required>
        </p> 
   
        <input type="submit" value="Pay Now" name="" id="">
        
 
 
</form>


 
 
 
 
 
 
 
  
  <!-- Project -->
  <script src="main.js"></script>
</body>
</html>
 # www.vodafone.es
Vodafone
