# box-sizeing-border
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>box sizing</title>
    <style>
        body
        {
            background-color: rgb(230, 166, 243);
        }
        p
        {
            color: rgb(245, 245, 248);
        }
        .container
        {
            background-color: rgb(81, 156, 241);
            margin: 30px;
            border: 13px solid red;
            border-radius: 25px;
            padding: 22px 23px 24px 25px; /*top bottom left right; */
            /* padding: 20px 30px; */
            box-sizing: border-box;
        }
    </style>
</head>
<body>
    <div class="container"><p>Lorem ipsum dolor sit.</p></div>
    <div class="container"><p>Lorem ipsum dolor sit amet.</p></div>
    <div class="container"><p>Lorem ipsum dolor sit amet consectetur.</p></div>

    
</body>
</html>
