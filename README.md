# bhawesh-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="pubg.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css



    ">
</head>
<body>
   <header>
    <div class="logo">
        <img src="save.jpg" alt="institute-logo">
    </div><nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Note's ↓</a>
            <ul class="dropdown">
                <li><a href="#">HTML</a></li>
                <li><a href="#">CSS</a></li>
                <li><a href="#">Java Script</a></li>
                <li><a href="#">C++</a></li>
                
                <li><a href="#">C#</a></li>
            </ul>
            </li>
            <li><a href="#">About us</a></li>
            <li><a href="#">Addmission</a></li>
            <li><a href="pubgad.html">Contact</a></li>
        </ul>
    </nav>
   </header> 
   <main>
    <section class="intro">
        <h1 id="changingText">Welcome to my institiute</h1>
    </section>
    <section class="courses">
        <div class="cover">
            <div class="box">
                <img src="app.png">
                <h2>App devloper</h2>
                <p>Application developers write software programs for use across mobile operating systems, including Apple, Android, and Windows devices. Once applications are created, application developers are also responsible for testing the application and providing updates whenever necessary.
                </p>
            </div>
            <div class="box">
                <img src="web.jpg">
                <h2>Web designing</h2>
                <p>A web designer creates the layout and design of a website. In simple terms, a website designer makes a site look good. They use design programmes to create visual elements and usually have expertise in user interface (UI), which means they strategically design a site that's intuitive and easy for visitors to navigate.
                </p>
            </div>
                <div class="box">
                    <img src="basic.jpg">
                    <h2>Basic of computer</h2>
                    <p>A computer is composed of hardware and software, and can exist in a variety of sizes and configurations. The term hardware refers to the physical components of your computer such as the system unit, mouse, keyboard, monitor etc. The software is the instructions that makes the computer work.
                    </p>
                </div>
        </div>    
    </section>
    </main>
    <footer>
        <div class="footercontainers">
            <div class="icon">
                <a href=""><i class="fa-brands fa-facebook"></i></a>
                <a href="https://instagram.com/boi.from_the.mountains?igshid=MTNiYzNiMzkwZA=="><i class="fa-brands fa-instagram"></i></a>
                <a href="https://www.snapchat.com/add/systemmmmm_hang?share_id=XlzUFdmlaCU&locale=en-GB"><i class="fa-brands fa-snapchat"></i></a>
                <a href=""><i class="fa-brands fa-twitter"></i></a>
            </div>
        </div>
        <p>&copy; 2023 my instiute . all right reserved</p>
    </footer>

   </main>
   <script>
    let changingText=document.getElementById('changingText');
let currentIndex=0;
let textArray=["Learn and Grow","Quality Education","Innotvative Programes"];
setInterval(() => {
   changingText.textContent=textArray[currentIndex];
   currentIndex=(currentIndex + 1) % textArray.length;
},2000);
   </script>
</body>
</html>
