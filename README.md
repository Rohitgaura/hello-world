<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="specificity.css">
    <title>specificity</title>
    <style>
        body{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-weight: bold;
            font-size: 17px;
            padding-right: 50px;
            padding-top: 25px;
            padding-left: 20px;
        }
        .payment{
            text-align: center;
        }
        .rohit{
            border-style: groove;
            border-color: black;
            border-width: 15px;
            padding: 15px;
            background-color: yellow;

        }
        input[type="submit"]
        {
            padding: 10px;
            background-color:rgba(18, 204, 64, 0.925);
            border-radius: 5px;
            width: 500px;
        }
        input[type="submit"]:hover
        {
            background-color: red;
        }
        input[type="text"],input[type="number"]
        {
            border-radius: 5px;
            padding: 3px;
            border-color: lime;
        }
        textarea
        {
            border-radius: 5px;
            padding: 10px;
        }
        fieldset{
            width: 500px;
            border-radius: 10px;
            border-color: brown;
        }
        input[type="password"],input[type="email"],input[type="date"]
        {
            border-radius: 5px;
            padding: 5px;
        }
        select
        {
            border-radius: 5px;
            padding: 5px;
        }
       
    </style>
</head>
<body>
    <div class="rohit">
    <h1 class="payment">Payment Form</h1>
    <hr height="5px" color="red">
    <h2>User Information</h2>
    <p>Name <input type="text" name="rohit" id="" placeholder="Rohit Kumar"></p>
    <p><fieldset>
        <legend>Gender</legend>
        <label for="male">Male</label>
        <input type="radio" name="male" id="" checked="checked">
        <label for="female">Female</label>
        <input type="radio" name="female" id="">
    </fieldset></p>
    <p>
        Address 
        <textarea name="address" id="" cols="30" rows="10">write your address.....</textarea>
    </p>
    <p>Email
        <input type="email" name="email" id="">
    </p>
    <p>Pincode  <input type="number" name="" id=""></p>
    <p>
        <h2>Payment Information</h2>
    </p>
    <p>
        Card Type <select name="card" id="">
            <option value="visa">visa</option>
            <option value="rupay">Rupay</option>
            <option value="lepay">Lepay</option>

        </select>
    </p>
    <p>Card Number <input type="number" name="number" id="">
    </p>
    <p>
        Date of Expiary <input type="date" name="date" id="">
    </p>
    <p>CVV <input type="password" name="cvv" id="">
    </p>
    <p>
        <input type="submit" value="Pay Now">
    </p>
    </div>
</body>
</html>
