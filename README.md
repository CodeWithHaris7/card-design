# card-design
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design this card</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&family=Roboto:wght@100&display=swap');

        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: gray;
            padding: 100px;
        }

        .card {
            background-color: white;
            width: 295px;
            height: 430px;
            border-radius: 9px;
            padding: 0 0 1px 1px;


        }

        .image {
            padding: 5px;
        }

        .image img {
            border-radius: 9px;
        }

        .content {
            padding: 9px 9px;
            font-family: 'poppins', sans-serif;
        }

        .content p {
            font-size: 12px;
            color: gray;
        }

        .capsules {
            padding: 0 14px;
            font-family: 'poppins', sans-serif;
            color: rgb(0, 0, 0);
        }

        .capsules span {
            border: 1px solid rgba(128, 128, 128, 0.486);
            padding: 0px 6px;
            margin: 2px;
            border-radius: 9px;
            font-size: 11px;
        }

        .content h2 {
            padding-bottom: 10px;
        }

        .button {
            text-align: center;
        }

        .button button {
            padding: 10px 18px;
            border-radius: 15px;
            background-color: rgba(166, 166, 226, 0.363);
            color: rgba(0, 0, 255, 0.795);
            font-size: 10px;
            font-weight: bold;
            border: none;
            margin-top: 7px;
        }
    </style>

</head>

<body>
    <div class="card">
        <div class="image">
            <img height="190px"
                src="https://images.pexels.com/photos/236047/pexels-photo-236047.jpeg?cs=srgb&dl=clouds-cloudy-countryside-236047.jpg&fm=jpg"
                alt="">
        </div>
        <div class="capsules">
            <span>Nature</span>
            <span>Crops</span>
        </div>
        <div class="content">
            <h2>Haris Card</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus consequatur veritatis nesciunt
                provident nobis molestiae perspiciatis esse sapiente unde neque!</p>
        </div>
        <div class="button">
            <button>Read More</button>
        </div>

    </div>
</body>

</html>
