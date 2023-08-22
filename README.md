# html-github
<!DOCTYPE html>
<html lang="en">
<!-- comments  (Enter ctrl + /)  -->

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA- Compatiable " content="ie=edge">
    <meta name="discrption " content="This is description">
    <meta name="keywords " content="html, web development">
    <title>title</title>

    <!-- This is how to include external CSS in html -->
    <link rel="stylesheet" href="Manahil.css">

    <!-- This is how to include external javascript in html -->
    <script src="Manahil.js"></script>

</head>

<body>
    <h1>Manahil Sohail</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.<strong>this is strong text </strong> <br>
        Aliquid consequatur eligendi quae harum eos neque? Dicta, sed? Maiores similique esse placeat. Labore, <br>
        ipsum necessitatibus. Dicta, dolore dolorum! Reprehenderit laboriosam <em>this is emphasized text
        </em>laudantium at fugiat, beatae odit impedit minus quae, hic voluptate dicta!</p>

    <!-- lorem30 for 30 dummy text -->
    <!-- for making like loop we can use p*no.of times like p*4 and enter   -->
    <!-- for inserting line we use hr -->
    <hr>
    <!-- ctrl + Enter to jump into a new line  -->

    <!-- To open internal link : <a href="/begning.html"></a>    -->
    <a href="/begning.html" target="_blank">Internal link of my html </a><br>

    <!-- To open some external links in a new tab Add attribute: target="_blank" -->
    <a href="https://facebook.com " target="_blank">Go to facebook</a><br>
    <a href="https://Google.com " target="_blank">Go to Google</a><br>
    <!-- for inserting imgage: img -->
    <!-- when image is not loaded alt text will be shown -->
    <img src="https://source.unsplash.com/user/erondu/1600x900" alt="" width="300">


    <hr>
    <h1>Table and List </h1><br>
    <!-- for different styles of an unorders list we can use "ul type "	disc ,circle ,square" -->
    <ul>
        <li type="circle">This is first item of unorderd list </li>
        <!-- Nested list -->
        <ul>
            <li>inside nested list</li>
            <li>inside nested list</li>
            <li>inside nested list</li>
        </ul>
        <li type="circle">This is second item of unorderd list </li>
        <li type="circle">This is third item of unorderd list </li>
    </ul>

    <ol type="1">
        <li>This is first item of orderd list </li>
        <li>This is second item of orderd list </li>
        <li>This is third item of orderd list </li>
    </ol>
    <!-- for different styles of a orders list we can use "ol type" -->

    <!-- Table -->
    <hr>
    <h1>HTML Table</h1>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Id</th>
                <th>Employee</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Manahil</td>
                <td>first</td>
                <td>Student</td>
            </tr>
            <tr>
                <td>Shumahil</td>
                <td>second</td>
                <td>Student</td>
            </tr>


        </tbody>
    </table>
    <hr>
    <h1>Forms</h1>
    <form action="backend.php">
        <div>
            <label for="N ame">Name</label>
            <input type="text" name="myname" id="Name">
        </div><br>
        <div>
            Role: <input type="text" name="myrole">
        </div><br>
        <div>
            Email: <input type="email" name="my email" >
        </div><br>
        <div>
            Date: <input type="date" name="mydate">
        </div><br>
        <div>
            Numer: <input type="number" name="mynumber">
        </div><br>
        <div>
            Are you eligibal <input type="checkbox" name="myeligibility">
        </div><br>
        <div>
            Gender: Male <input type="radio" name="myGender"> female <input type="radio" name="myGender">
        </div><br>
        <div>
        </div><br>
        <form action="car">Car</form>
        <select name="Car" id="car">
            <option value="vezel">vezel</option>
            <option value="corola">colora</option>
        </select><br>
        <div>
            Write your feedback <br> <textarea name="mytextarea" cols="30" rows="10"></textarea>
        </div><br>
        <div>
            <input type="submit" value="Submit Now">
            <input type="reset" value="Reset Form">
        </div><br>
        <hr>
        <h1>Inline and BlockElements</h1>
        <!-- for in line we use span for multiple paragraphs also a -->
        <span>This is a paragraph</span>
        <span>This is a paragraph</span>
        <span>This is a paragraph</span>

        <!-- li, em ,div , img -->


        <hr>
        <h1>Ids & Classes</h1>
        <div id="mainBox" class="redBg"></div>
        one id is for only one element 
        class can be given to multiple elements.
        <br>
        <h3>Emmet</h3>
        .for class and # is for id <br>
        <span class="redBeg"></span>
        <sapn id="mainBox"></sapn>
        <div class="redBeg blackBorder anotherclass"></div>
        Emmet takes div tag as default    .blackground
        <div class="blackground"></div>

        creating multiple elements using Emmet
        <!-- span.myClass.myClass2.myClass3*4 + tab -->
        <span class="myClass myClass2 myClass3">First</span>
        <span class="myClass myClass2 myClass3">Second</span>
        <span class="myClass myClass2 myClass3">Third</span>
        <span class="myClass myClass2 myClass3">Fourth</span>
        
    </form>

    <h1> Html Entites </h1>
    
    <div class="container"> 
    <!-- for spacing we use &nbsp;  nbsp stands for non breaking space  -->
    <p>this is another &nbsp; paragraph</p>
    <!-- for showing  reserved tags like <p></p> we use &lt p &gt  -->
    <p>paragraph is written like this &lt;p&gt;</p>
    <!-- for some symb like £ &pond -->
    <p>paragraph is written like this &pound;</p>
    <p>this written like this &rAarr; </p>
    </div>
    <br><hr>
    <h1>Semantic Elements</h1>
    <DEtails>
        <summary>My data</summary>
        This is a just an example of DEtails semantic element.
    </DEtails>
    



    
    </html>
