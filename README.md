# card_design
I have used Html and Css

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Card Design</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Poppins:wght@300&display=swap');
        *{
            margin: 0;
            padding: 0;
        }
        body{
            background-color: gray;
            padding: 45px;
            display: flex;
        }
        .card{
            background-color: white;
            width: 198px; 
            border-radius: 7px;
            padding: 0 0 34px 0;
            margin: 4px;
        }

        .image{
            padding: 5px;
        }
        .image img{
            border-radius: 7px;
        }
        .content{
            padding: 7px 13px; 
font-family: 'Poppins', sans-serif;
        }

        .content p{
            font-size: 9px;
            color: gray;
        }
        .capsules{
            padding: 0 28px 0 14px;
        }
        .capsules span{
            border: 1px solid gray;
            padding: 0px 6px;
            border-radius: 7px;
            font-size: 8px;
            font-family: 'Baloo Bhai 2', sans-serif; 

        }
        .button{
            text-align: center;
        }
        .button button{
            padding: 7px 15px;
            border-radius: 15px;
            background-color: rgb(216, 236, 253);
            color: rgb(14, 150, 234);
            font-size: 10px;
            margin-top: 7px;
            border: none;
            font-weight: bold;
            cursor: pointer;
        }

        .button button:hover{
            background-color: rgb(194, 225, 246);
            color: rgb(10, 136, 214);
        }
    </style>
</head>
<body>
    <div class="card"> 
        <div class="image">
            <img width="188" src="https://images.pexels.com/photos/3880179/pexels-photo-3880179.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
        </div>

        <div class="capsules">
            <span>Nature</span>
            <span>Lake</span>
        </div>
        <div class="content">
            <h2>FARHEEN KHAN</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas nemo numquam vel cumque ullam alias sequi suscipit velit! Enim cumque aperiam tempore tenetur?</p>
        </div>
        <div class="button">
            <button>Read More</button>
        </div>

    </div>

    <div class="card"> 
        <div class="image">
            <img width="188" src="https://images.pexels.com/photos/3880179/pexels-photo-3880179.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
        </div>

        <div class="capsules">
            <span>Nature</span>
            <span>Lake</span>
        </div>
        <div class="content">
            <h2>FARHEEN KHAN</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas nemo numquam vel cumque ullam alias sequi suscipit velit! Enim cumque aperiam tempore tenetur?</p>
        </div>
        <div class="button">
            <button>Read More</button>
        </div>

    </div>

    <div class="card"> 
        <div class="image">
            <img width="188" src="https://images.pexels.com/photos/3880179/pexels-photo-3880179.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
        </div>

        <div class="capsules">
            <span>Nature</span>
            <span>Lake</span>
        </div>
        <div class="content">
            <h2>FARHEEN KHAN</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas nemo numquam vel cumque ullam alias sequi suscipit velit! Enim cumque aperiam tempore tenetur?</p>
        </div>
        <div class="button">
            <button>Read More</button>
        </div>

    </div>
</body>
</html>
