<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form</title>
</head>
<body>
    <form action="">
        <div>
            <label for="first">First name: </label>
            <input type="text"  name="first_name" id="first">
            <lable for="">second name: </lable>
            <input type ="text" name="second_name">
        </div>
        <br>
        <div>
            <lable for="">email id:</lable>
            <input type="email" name=""email>
            <lable for="">password: </lable>
            <input type="password" >

        </div>
        <br>
        <div>
            date:<input type="date">
            time:<input type="time">
        </div>
        <br>
        <div>
            <h4>Height</h4>
            <input type="radio" id="five" name="height" >
            <label for="five">5 feet</label><br>
            <input type="radio" id="four" name="height" >
            <label for="four">4 feet</label><br>
        </div>
        <br>
        <div>
            color:<input type="color">
        </div><br>
        <div>
            <label for="collage">Choose a collage:</label>
                <select name="collaeg" id="collages">
                <option value="ecmt">ecmt</option>
                <option value="ecpt">ecpt</option>
                <option value="brainware">brainware</option>
                <option value="kingstron">kingstron</option>
                </select>
        </div><br>
        <div>
            <input type="submit">
            <input type="reset">
        </div>
    </form>
</body>
</html>
