> # **Practical: 09**
> 
**Task** : **Create a survey form by using CSS give a beautiful design to layout like text-decoration, text color, background color, text alignment, margin, padding, etc.** 

**code:**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="p9.css">
    <title>Document</title>
</head>

<!-- code of html -->

<body>
    <div id="main">
        <div id="personal">
            <h1>personal info:</h1>   
        <span id="in1" >Name: <br> <input type="text" ></span> <br>
        <span id="in2" >Father Name: <br> <input type="text" ></span> <br>
        <span id="in3" >Email: <br> <input type="text" ></span> <br>
        <span id="in3" >Phone Number: <br> <input type="text" ></span> <br>
        <span id="in3" >Gender:  <input type="radio" >Male<span id="" ><input type="radio" >Feamale</span></span> <br> <br>
        <span id="in4"> Age:  <input type="number" value="0"  min="1" max="100" step="1" required> <br> <br>
        </span> 
        <span id="in5">
        <select>
            <option value="">Choose Dept:</option>
            <option value="">Software Enginnering</option>
            <option value="banana">Mechanical Enginnering</option>
            <option value="">Chemical Enginnering</option>
            <option value="">Electrical Enginnering</option>
            <option value="">Electronics Enginnering</option> 
        </select>
    </span>
        <div id="questions">
            <span >Question 1: What do you believe are the strengths of our educational program? </span> <br>
            <textarea id="comments" name="comments" rows="4" cols="50"></textarea> <br>
            <span>Question 2:What suggestions do you have for improving the overall learning experience at Software 
                Enginnering Dept?</span>  <br>
                <textarea id="comments" name="comments" rows="4" cols="50"></textarea> <br>
                <span  >Question 3:Are you satisfied with the resources (library, labs, materials) available to you for your studies? Please explain.</span> <br>
                <textarea id="comments" name="comments" rows="4" cols="50"></textarea> <br>
        </div>
        </div>
    </div> 
</body>
</html>
```
**code of css:**
```CSS
#main{
    background-color: rgb(208, 208, 42);
    display: flex;
    justify-content: center;
    height: 1200px;
    background: rgb(63,94,251);
background: radial-gradient(circle, rgba(63,94,251,1) 5%, rgba(103,19,36,1) 100%);
}
#personal{
    position: relative;
    top: 90px;
    color: white;
   
    box-shadow: 1px 1px 30px 1px gray;
    height: 400px;
    width: auto;
    background: rgb(63,94,251);
    background: radial-gradient(circle, rgba(63,94,251,1) 0%, rgba(252,70,107,1) 100%);
}
#questions{
   position: relative;
   top: 80px;

}
h1{
    text-align: center;
}
#in1,#in2,#in3,#in4,#in5{
    top: 20px;
    position: relative;
    left: 260px;
    font-size: 15px;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  border-radius: 60px; 
}
```