<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Form</title>
    <style>
       *{
         margin: 0;
         padding: 0;
         box-sizing:  border-box;
       }
       body{
         background: #3275a8;
       }

       .container{
         width: 400px;
         height: 500px;
         background: white;
         margin: 30px auto;
         padding: 10px;
         box-shadow: 0px 10px #0D2785;
       }

       .container h3{
         text-align: center;
         font-size: 25px;
       }

       h5{
         text-align: center;
       }

       form{
         width: 100%;
         height: 400px;
         border: 1px solid #E0E3E5;
         padding: 30px;
       }

       input,select{
         display: flex;
         margin-top: 5px;
         margin-bottom: 5px;
         padding: 8px;
         width: 100%;
         border: 2px solid grey;
         border-radius: 5px;
       }

       select{
          background:#807b38;
          color: #ebd834;
          font-size: 16px;
       }

       label{
         font-size: 20px;
       }

    </style>
</head>
<body>
    <div class="container">
        <form action="">
            <h3>Styled Select Option <br> Field in Form</h3>
            <br>
            <hr>
            <br>
             <div>
                 <label>Name:</label>
                 <input type="text" >
             </div>

            <div>
                 <label>Email:</label>
                 <input type="email" >
            </div>

            <div>
                 <label>Age:</label>
                 <select name="Age">
                     <option >---Choose age from here---</option>
                     <option value="">Below 18 years</option>
                     <option value="">Between 18-25 years</option>
                     <option value="">Between 40-60 years</option>
                     <option value="">Above 60 years</option>
                 </select>
            </div>


        </form>

        <h5>By Angelpeter2023</h5>
    </div>
</body>

--->
