> # **practical:08**

**Task: create an attractive webpage for any shop in which the frame layout should look something like this. .**

**Code:**

>  ![](q1.png)

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<frameset cols="35%,35%,35%" >
   
    <frameset rows="40%,60%" >
        <frame src="Frame1.htm" >
            <frame src="Frame2.htm" >
    </frameset>
        <frame src="Frame3.htm" >
            <frame src="Frame4.htm" >
</frameset>
</html>
```
**code Of Frame1:**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<!-- code of css -->
<style>
    *{
        padding: 0px;
        margin: 0px;
    }
    img{
        width: 100%;
        height: 100%;
     }
</style>

<!-- code of html -->
<body>
    <div>
        <img src="https://img.freepik.com/premium-psd/man-woman-holding-sign-concept-mock-up_23-2148624276.jpg?w=740" alt="">
    </div>
</body>
</html>
```
**code Of Frame2:**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    /* code of css */
    body
    {
        background-color: rgba(137, 43, 226, 0.515);
        opacity: 0.95;
    }
    li{
        list-style: none;
        text-align: center; 
        margin-top: 30px;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;  }
    button{
        border: 2px solid rgb(109, 46, 109);
        color: black;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        width: 120px;
        background-image: url("https://img.freepik.com/free-photo/indifferent-unbothered-woman-man-spread-hands-sideways_273609-27552.jpg?w=740&t=st=1694849411~exp=1694850011~hmac=45ac681b94ce3fb8556f9cffff702347c6649c01c060926a4b89be52152f665e");
        opacity: 0.75px;
    }
    button:hover{
        color: white;
    }
    img{
        width: 100%;
        height: 100%; }
    </style>

    <!-- code of HTML -->
<body>
    <div id="main" >
        <div id="flex" >
            <nav>
            <ul>
                <li>
                   <button>Home</button>
                </li>
                <li>
                  <button>  About Us</button>
                </li>
                <li>
                  <button>  Products Category</button>
                </li>
                <li>
                    <button>Contact us</button>
                </li>
            </ul>
        </nav>
        </div>
    </div>
    <img src="https://img.freepik.com/free-photo/happy-man-opens-box-with-surprise-shows-something-girlfriend-who-has-unhappy-puzzled-look-frowns-face-wears-yellow-t-shirt-pink-trousers-headphones-around-neck_273609-32574.jpg?w=740&t=st=1694849204~exp=1694849804~hmac=88bae6ddcf80a89d0855067004dd8d3f0c22e91ecb4442463692f0f223029dae" alt="">
</body>
</html>
```
**code Of Frame3:**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<!-- code of css -->
<style>
    body
    {
        justify-content: center;
        background-image: url("https://img.freepik.com/premium-photo/blurry-modern-background-abstract-high-speed-motion-blur_87555-18291.jpg?w=740");
        background-size: cover;
       background-repeat: no-repeat;
    }
    *{
        padding: 0px;
        margin: 0px;
        box-sizing: border-box;
    }
    img{
       width: 100%;
       height: 100%;
       border-radius: 45px;
       box-shadow: 3px 3px 8px;
    }
    h1{
        text-align: center;
        margin-top: 70px;
        margin-bottom: 70px;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        color: rgba(255, 255, 6, 0.972);
           box-shadow: 3px 3px 14px  black;}
    #flex{
        display: flex;
        flex-direction: column;
        text-align: center;
        justify-content: center;
        background-image: url("https://img.freepik.com/premium-photo/blurry-modern-background-abstract-high-speed-motion-blur_87555-18291.jpg?w=740");
        background-size: cover;
       background-repeat: no-repeat;   
    }
    p{
        padding-top: 50px;
    }
    .design{
        margin-top: 70px;
        padding: 7px;
        margin-left: 20px;
        margin-right: 20px; }
    #head{
        border-radius: 0px; }
</style>

<!-- code of HTML -->
<body>
    <h1>Our Products For Feamales</h1>
    <div>
        <img id="head" src="https://img.freepik.com/premium-photo/happy-woman-with-cute-dog_23-2148510267.jpg?w=740" alt="">
    </div>
    <div id="flex">
        <div class="design" >
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/premium-photo/pretty-young-asian-lady-looking-excited-happy-using-her-phone-carrying-handbag_264197-10920.jpg?w=360" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
        <div class="design" >
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/free-photo/high-angle-female-with-flowers_23-2148490454.jpg?w=360&t=st=1694852420~exp=1694853020~hmac=fb344813db1e4748ce3348053d29e2728ea083369316e4f0e29aeaf34b995fc68" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
        <div class="design" >
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/premium-photo/cute-little-girl-staying-yellow-background-space-text_475671-115.jpg?w=740" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
        <div class="design" > 
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/free-photo/cheerful-redhead-woman-posing-yellow-polka-dress-straw-hat_273609-32082.jpg?w=740&t=st=1694852999~exp=1694853599~hmac=bd4d936b17409f4a9f9375eba69418be84df5de4e58639bb74addc344473a814" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
    </div>
</body>
</html>
```
**code Of Frame4:**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<!-- code for css -->
<style>
    body{
        justify-content: center;
        background-image: url("https://img.freepik.com/premium-photo/blurry-modern-background-abstract-high-speed-motion-blur_87555-18291.jpg?w=740");
        background-size: cover;
       background-repeat: no-repeat;
    }
    *{
        padding: 0px;
        margin: 0px;
        box-sizing: border-box;
    }
        img{
            width: 100%;
            height: 100%;
            border-radius: 45px;
            box-shadow: 3px 3px 8px;}    
    h1{
        text-align: center;
        margin-top: 70px;
        margin-bottom: 70px;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        color: rgba(255, 255, 6, 0.972);
        box-shadow: 3px 3px 14px  black;
    }
    #flex{
        display: flex;
        flex-direction: column;
        text-align: center;
        justify-content: center;
        justify-content: center;
        background-image: url("https://img.freepik.com/premium-photo/blurry-modern-background-abstract-high-speed-motion-blur_87555-18291.jpg?w=740");
        background-size: cover;
       background-repeat: no-repeat; 
    }
    .design{
        
        margin-top: 70px;
        padding: 7px;
        margin-left: 20px;
        margin-right: 20px;}
    p{
        padding-top: 50px;}
    #head{
        border-radius: 0px;}
    
</style>

<!-- code for html -->

<body>
    <h1>Our Products For Males</h1>
    <div>
        <img style="height: 330px;" id="head" src="https://img.freepik.com/premium-photo/young-male-dog-shopping-cart_157917-2814.jpg?w=740" alt="">
    </div>
    <div id="flex">
        <div class="design" >
            <img style="width: 300px; height: 300px; " src=https://img.freepik.com/free-photo/portrait-young-man-yellow-scene_23-2148184701.jpg?w=360&t=st=1694853050~exp=1694853650~hmac=cd531433df3100cea5de8e16ce98afb87aba3fea04710ed706ea937bf8b7b3cb" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
        <div class="design" >
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/free-photo/portrait-handsome-smiling-model-sexy-stylish-man-dressed-summer-clothes-fashion-hipster-male-posing-near-yellow-wall-studio_158538-22527.jpg?w=740&t=st=1694853085~exp=1694853685~hmac=fbdcb4dbf32a6e40e82d937cc559e2e296780195c22695a52cd0562bc748a5f9" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
        <div class="design" > 
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/free-photo/indoor-portrait-smiling-black-man-standing-with-hands-pockets-blithesome-african-guy-isolated_197531-20084.jpg?w=740&t=st=1694853109~exp=1694853709~hmac=b7e79f605b9e3f102f7d676f94c4b54d8e1adce16cdcf8a6c3952bb52ce45cc8" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
        <div class="design" > 
            <img style="width: 300px; height: 300px; " src="https://img.freepik.com/premium-photo/man-calm-face-posing-confidently-yellow-background-guy-wear-unbuttoned-shirt-with-smooth-skin-chest-hair-removal-procedure-take-off-clothes-be-ashamed-male-hair-depilation-chest_474717-16431.jpg" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis temporibus sed deleniti voluptate perspiciatis? Fugiat reprehenderit quos esse explicabo at. Eum maiores excepturi distinctio pariatur dolorem magni libero nihil ipsam.</p>
        </div>
    </div>
</body>
</html>
```