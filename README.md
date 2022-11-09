<!DOCTYPE html>
<html>
    <head>
        <style>
            
            div {
                font-family: arial;
                width: 150px;
                height: 220px;
                font-size: 14px;
                vertical-align: top;
                box-shadow: 0px 0px 4px rgba(0, 0, 0, 1);
                display: inline-block;
                
            }
            .friends {
                font-size: 8px;
                opacity: 0.7;
                font-weight: bold;
                padding-left: 5px;
            }
            button {
                display: inline-block;
                vertical-align: bottom;
                margin-left: 5px;
                margin-bottom: 0px;
                margin-right: 2px;
                color: white;
                background-color: rgb(31, 83, 255);
                border: none;
                border-radius: 2px;
                padding-top: 5px;
                padding-bottom: 5px;
                padding-left: 10px;
                padding-right: 10px;
                font-size: 8px;
            }
            .image {
                width: 100px;
                height: 100px;
            }

            
            .div-test {
                
                display: inline-block;
                margin-left: 20px;
                margin-top: 50px;
                margin-bottom: 50px;
                width: 100px;
            
            }
            .div-testA {
                margin-left: 50px;
                margin-top: 50px;
                margin-bottom: 50px;
                width: 100px;
            }
        </style>
    </head>
    <body>
        <div class="div-testA">
            <img src="images/crew.png" class="image">
            <p class="username">
                Yamaguchi gang
            </p>
            <p class="friends">
                2 mutual friends
            </p>
            <button class="add">
                Add Friend
            </button>
        </div>
        <div class="div-test">
            <img src="images/karma.jpg" class="image">
            <p class="username">
                Remz
            </p>
            <p class="friends">
                2 mutual friends
            </p>
            <button class="add">
                Add Friend
            </button>
        </div>
    </body>
</html>

