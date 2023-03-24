<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <form action="">
        <h1> payment Form</h1>
        <h2>Contact Information</h2>
        <p>
            <p>Enter Your Name</p>
          First Name: <input type="text" name="First Name" id="fn">
          Last Name: <input type="text" name="last Name" id="fn">
        </p>
        <fieldset>
            <legend>Gender</legend>
            <p>     
                Male <input type="radio" name="Male" id="Male">
                Female <input type="radio" name="Female" id="Female">
            </p>
        </fieldset>
        <p>Address: <textarea name="address" id="address" cols="90" rows="12"></textarea></p>
        <p>Email: * <input type="email" name="email" id="email" required></p>
        <p>Pincode: * <input type="number" name="pincode" id="pincode"></p>
        <h2>Payment information</h2>
        <p>Card Type: 
            <select name="card" id="card">
                <option value="">--select a card Type--</option>                
                <option value="Visa">visa</option>                
                <option value="Rupay">rupay</option>                
                <option value="Master card">master card+</option>                
            </select>
        </p>
        <p>
            Card Number <input type="number" name="number" id="number">
        </p>
        <p>
            Expiry Date: * <input type="date" name="exp_date" id="exp_date">
        </p>
        <p>
            CVV * <input type="password" name="cvv" id="cvv" required>
            <input type="submit" value="pay Now">
        </p>
    </form>
</body>
</html>

