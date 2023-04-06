
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Introduction</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>

    <header class="header">
        <p id="name">SHEETAL</p>
        <p id="profile">WEB DEVELOPER</p>
    </header>

    <img src="images/shh.jpg" height="120" width="100">

    <h1>Profile</h1>
    <hr>
    <p id="Introduction">
        I am pursuing Bachelor of Technology in Computer Science.<br>
        Organized and dependable candidate successful at managing multiple priorities with a positive attitude.<br>
        Willingness to take on added responsibilities to meet team goals.
    </p>
    <hr>
    <h2>Education</h2>
    <table border="">
        <tr id="heading">
            <th>Class</th>
            <th>Board</th>
            <th>Marks</th>
        </tr>
        <tr>
            <td>10th</td>
            <td>CBSE</td>
            <td>78%</td>
        </tr>
        <tr>
            <td>Diploma in Digital Electronics</td>
            <td>BTE</td>
            <td>70%</td>
        </tr>
    </table><br>

    <h2>Hobbies</h2>
    <ol>
        <li>
            <p>painting</p>
        </li>
        <li>
            <p>Coding</p>
        </li>
    </ol>

    <br>
    <h2>Skills</h2>
    <p>
    <ul>
        <li>Programming Language-Java, C++</li>
        <li>Data Structure</li>
        <li>Frontend-HTML, CSS</li>
    </ul>
    </p>

    <br>

    <h2>Sem-Wise Marks</h2>
    <table border="">
        <tr id="heading">
            <th>Semester</th>
            <th>Marks</th><br>
        </tr>

        <tr>
            <td>3rd</td>
            <td>87%</td>
        </tr>

        <tr>
            <td>4th</td>
            <td>85%</td>
        </tr>
    </table>
    </div>

<div class="Contact">
                <h2>Contact</h2>
                <p><b>Email id:</b>sssheetal8120@gmail.com</p>
                <p><b>Mobile no :</b>+91 8851591456</p>
            </div>
</body>

</html>

*{
    margin: 10px;
    padding: 0px;
    border-radius: 5px;
    box-sizing: border-box;
}
body{
    font-family: 'Times New Roman', Times, serif;
    font-size: 15px;
    
    color: palevioletred;
        border-radius: 10px;
}

#Contact{
    margin: auto;
    margin-right: 25px;
    text-align: right;


}
header{
    font-family: 'Times New Roman', Times, serif;
    text-align: right;
    color: palevioletred;
     padding-bottom: 10px;
    height: 3px;
    width: 98%;
    margin-bottom: 10px;
}

#name{
    float: center;
    margin-right: 25px;
    color: palevioletred;
    padding-bottom: 10px;
    font-size: larger;
    text-transform: uppercase;
    font-family: 'Times New Roman', Times, serif;
    }
#Introduction{
    float: center;
    margin: 25px;
    padding-bottom: 10px;
    
    font-size: large;
    font-family: 'Times New Roman', Times, serif;
    text-transform: none;
    color: palevioletred;
}


#image{
    display: inline;
    border: 0px solid black;
    max-width: 100%;
}
#profile{
font-style:normal;
font-family: 'Times New Roman', Times, serif;
padding-bottom: 10px;
margin-bottom: 5px;

}

table{
    float: center;
    border:1px black;
}
th{
    padding: 20px;
    margin-bottom: 10px;
}

td{
 float: center;
}



table th{
    margin-top: 1px;
    padding: 20px;
}
