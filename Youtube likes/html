<!-- html code goes here -->
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title></title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="./style.css">
    </head>
    <body>
        <div>
            <button type="button" id="increment" onclick="increment()">
                Likes
            </button>
            
            <h3 id="counter">
                Count
            </h3>
            
            <button type="button" id="decrement" onclick="decrement()">
                Dislikes
            </button>
        </div>
        
        <script src="./script.js" async defer></script>
    </body>
</html>

// javascript code goes here
var data = 0;

document.getElementById("counter").innerText = data;
  

function increment() {
    data = data + 1;
    document.getElementById("counter").innerText = data;
}

function decrement() {
    data = data - 1;
    if(data <= 0){
        data = 0;
    }
    document.getElementById("counter").innerText = data;
}
