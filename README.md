# Data Science Tools and Ecosystem
#### In this notebook, Data Science Tools and Ecosystem are summarized.
#### Some of the popular languages that Data Scientists use are:
1. Python.
2. R.
3. SQL.
4. Java.
5. Julia.
6. Scala.
7. C/C++
8. JavaScript.
   
#### Some of the commonly used libraries used by Data Scientists include:
1. TensorFlow
2. NumPy
3. SciPy 
4. Pandas

| Data Science Tools  | 
| -------------       | 
|     RStudio         |
| Apache Spark        | 
| TensorFlow          | 

### Below are a few examples of evaluating arithmetic expressions in Python
#### This a simple arithmetic expression to mutiply then add integers
 N: 3;
B: 4;
F: 5;
AL: (N*4)+F;
run: AL


function sec2hms ($sec, $padHours = false, $asArray = false)
{

    // start with a blank string
    $hms = "";

    // do the hours first: there are 3600 seconds in an hour, so if we divide
    // the total number of seconds by 3600 and throw away the remainder, we're
    // left with the number of hours in those seconds
    $hours = intval(intval($sec) / 3600);

    // add hours to $hms (with a leading 0 if asked for)
    $hms .= ($padHours)
          ? str_pad($hours, 2, "0", STR_PAD_LEFT). ":"
          : $hours. ":";

    // dividing the total seconds by 60 will give us the number of minutes
    // in total, but we're interested in *minutes past the hour* and to get
    // this, we have to divide by 60 again and then use the remainder
    $minutes = intval(($sec / 60) % 60);

    // add minutes to $hms (with a leading 0 if needed)
    $hms .= str_pad($minutes, 2, "0", STR_PAD_LEFT). ":";

    // seconds past the minute are found by dividing the total number of seconds
    // by 60 and using the remainder
    $seconds = intval($sec % 60);

    // add seconds to $hms (with a leading 0 if needed)
    $hms .= str_pad($seconds, 2, "0", STR_PAD_LEFT);

    // done!
    return ($asArray) ? explode(':', $hms) :  $hms;



}

 

