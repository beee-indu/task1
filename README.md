# task1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback Form</title>
</head>
<body>
    <div>
        <h1>Feedback  !!</h1>
     <form action="form.php">
            <input type="text" placeholder="Your Name"><br>
            <input type="email" placeholder="Your Mail"><br>
            <span>Give your feedback</span><br>
            <textarea name="feedback" id="feedback" cols="20" rows="10" placeholder="Please give your honest feedback">
  </textarea><br>
            <p>Do rate us</p>
            <label for="excellent">
                <input type="radio" value="excellent" name="feedback" id="excellent">Excellent
            </label>
            <label for="good">
                <input type="radio" value="good" name="feedback" id="good">Good
            </label>
            <label for="okay">
                <input type="radio" value="okay" name="feedback" id="okay">Okay
            </label>
            <label for="bad">
                <input type="radio" value="bad" name="feedback" id="bad">Bad
            </label>
            <label for="worse">
                <input type="radio" value="worse" name="feedback" id="worse"/>Can be better
            </label><hr>
            <input type="submit"/>
    </form>
    </div>
</body>
</html>
