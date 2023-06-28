# test1
-=============================================================================================================
test.css----------------------------------------------------------------------------------------------------------------------------------------
body{
    margin: 0;
}.head{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 50px;
}
.contact{
    display: flex;
    gap: 2px;
}
.logo{
    display: flex;
    gap: 2px;
}
.report{
    color: #1498d9;
}
.number{
    color: #b84224;
}
.imagebackground img{
    width: 100%;
    height: 470px;
}
.imagebackground{
    position: relative;
}
.imagecontent{
    display: flex;
    position: absolute;
    top: 35px;
    margin-left: 100px;
    align-items: center;
    right: 100px;
    text-align: center;
    left: 100px;
    gap: 30px;
}
.imagecontent h2{
    font-weight:  normal;
}
form{
    background-color: #00a9f1;
   
}
.formclass{
    width: 26%;
    position: initial;
}
.imagecontent h1,h2,p{
    color: white;
}
.imagecontent h1{
    margin:0;
}
.formclass h1,h2{
    margin: 0;
}
.formclassh1{
    font-size: 25px;
}
.formclass p{
    margin-top: 0;
}
.formclass input{
    margin-bottom: 2px;
    padding: 5px 0;

}
.formclass{
    background-color: #1eaadd;
}
.formclass button{
    padding: 10px 30px;
    font-weight: bold;
    font-size: 17px;
    background-color: #f04e2f;
    border: 0;
    color: white;
    margin-top: 5px;
}
form{
    padding: 20px 0;
}
.div3-content{
    margin-left: 100px;
    margin-right: 200px;
}
.submit button{
    padding: 10px 20px;
    font-weight: bold;
}
.submit{
    display: flex;
    align-items: center;
    gap: 40px;
}
.div3-content h6{
    font-weight: normal;
    font-style: normal;

}
.div3-content .heading{
    color: #31a0cb;
}
.div3{
    height: 200px;
}
.div3-content .contact h1{
    font-size: 20px;
}
.tick-mark {
    font-size: 20px;
    position: relative;
    color: #01a4ef;
    font-weight: bold;
  
  }
  .tick-icon{
  background-color: white;
  width: 30px;
  height: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 30px;
  margin-bottom: -10px;
  transform: rotate(45deg);
 
}
.down{
    background-color: #01a4ef;
}
.down-1{
    display: flex;
    gap: 26px;
    margin-left: 100px;
    margin-right: 100px;

}.down-1 p{
    font-size: small;
}
.down-1 h1{
color: white;
}
h1{
    font-style: italic;
}
.contact h1{
    font-size: 20px;
}
-----------------------------------------------------------------------------------------------------------------------------------------
test.html
<!DOCTYPE html>
<html>

<head>
    <title>TEST</title>
    <link rel="stylesheet" href="test.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>

<body>
    <div class="wrapper">
        <div class="head">
            <div class="logo">
                <h1>CREDIT</h1>
                <h1 class="report">REPORT</h1>
            </div>
            <div class="contact">
                <h1><i class="fas fa-phone-alt"></i>CALL US TODAY</h1>
                <h1 class="number">800.123.4567</h1>
            </div>

        </div>
        <div class="imagebackground">
            <img src="https://www.shutterstock.com/image-photo/busy-young-businessman-using-laptop-260nw-2080857973.jpg"
                alt="">
            <div class="imagecontent">
                <div>
                    <h1>CHECK YOUR 3-IN-1 </h1>
                    <h1>CREDIT REPORT ONLINE TODAY</h1>
                    <h2> YOU'LL BE GLAD YOU DID TOMORROW</h2>
                </div>
                <div class="formclass">
                    <form action="">
                        <h2>GET YOUR FREE</h2>
                        <h1>CREDIT REPORT</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <input type="text" name="firstname" placeholder="FIRST NAME"><br>
                        <input type="text" name="lastname" placeholder="LAST NAME"><br>
                        <input type="email" name="gmail" placeholder="E-MAIL ADDRESS"><br>
                        <input type="number" name="phonenumber" placeholder="PHONE NUMBERP"><br>
                        <input type="text" name="code" placeholder="OTP CODE">
                        <button type="submit">CLICK HERE</button>
                    </form>
                </div>
            </div>
        </div>
        <div class="div3">
            <div class="div3-content">
                <h1 class="heading">ACCESS TO ALL 3 NATIONAL CREDIT BUREAUS</h1>
                <h6>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quam adipisci corrupti provident pariatur
                    debitis ullam, sint doloribus, incidunt in soluta nostrum? Magni perspiciatis, voluptates culpa
                    voluptas ipsa incidunt sit delectus dolores aperiam quisquam blanditiis asperiores, illum sequi
                    veritatis? Soluta, harum autem sapiente reiciendis fugit assumenda aspernatur similique cupiditate a
                    exercitationem unde quae numquam. At molestias et dolores eaque nesciunt nisi veritatis praesentium
                    nihil magni, ullam iure exercitationem? Excepturi, modi! Error nam quaerat id! Sunt enim accusantium
                    id pariatur fugit, dolore commodi maxime quos perferendis praesentium. Vero perspiciatis illo quis
                    iste quae ratione praesentium adipisci, voluptatum enim repudiandae, facilis necessitatibus
                    accusantium!</h6>
                <div class="submit">
                    <div>
                        <button type="submit">LEARN MORE</button>
                    </div>

                    <div class="contact">
                        <h1><i class="fas fa-phone-alt"></i>CALL US TODAY</h1>
                        <h1 class="number">800.123.4567</h1>
                    </div>
                </div>


            </div>
        </div>
        <div class="down">
            <div class="down-1">
                <div >
                    <div class="tick-icon">
                        <span class="tick-mark">&#10004;</span>
                    </div>
                    <h1>MORE VALUE</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, praesentium. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Porro, corporis.</p>
                </div>
                <div>
                    <div class="tick-icon">
                        <span class="tick-mark">&#10004;</span>
                    </div>
                    <h1>MORE CONFIDENT</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat, assumenda.Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, praesentium.</p>
                </div>
                <div>
                    <div class="tick-icon">
                        <span class="tick-mark">&#10004;</span>
                    </div>
                    <h1>MORE PEACE OF MIND</h1>
                    <p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quis, asperiores?Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, praesentium.</p>
                </div>
            </div>
        </div>

    </div>
</body>

</html>
