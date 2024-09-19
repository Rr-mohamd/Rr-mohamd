<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <STyle>
        header{
    display: flex;
    animation: test 1s;
    justify-content: center;
    background-color: #ff0037;

}
a{
    transition: all 0.5s;
}
body{
    animation: back 1000s;    
    animation-delay: 0ms;
    animation-iteration-count: infinite;
    margin: 0;
    padding: 0;
    text-align: center;


}
header a{
    text-decoration: none;
    text-shadow: 0px 0px  black;

}
header h2:hover{
    color: rgb(0, 255, 0);
    font: menu;
    font-size: 20px;
    font-weight: bold;
}
header h2{
    color: black;
    font: menu;
    transition: all 0.5s;
    font-size: 20px;
    font-weight: bold;
}
.parent1{
    text-align: center;
    margin-top: 70px;

}
.parent1-link{
    padding: 20px;
    text-decoration: none;
    color: rgb(255, 255, 255);
    transition: border-radius  1s , background-color 1s;
    margin-left: 20px;
    font: menu;
    font-size: x-large;

}
.img{
    background-color: red;
    border-radius: 100%;
    transition: border-radius  1s , background-color 10s;

}

.parent1-link:hover{
    background: linear-gradient(to left,rgb(0, 255, 34), rgb(255, 0, 0));
    border-radius: 20px;
}
.parent2{
    text-align: center;
    
    margin-top: 80px;
}
.parent2-header{
    color: red;
    font: message-box;
    font-weight:900;
    font-size: 60px;
}
.parent2-p{
    color: rgb(0, 0, 0);
    font: message-box;

    font-size:40px;
}
.parent2-p-b{
    color: rgb(0, 0, 0);
    font: message-box;
    font-weight: 900;
    font-size:40px;
}
.parent2-link{
    text-decoration: none;
    padding: 25px;
    border-radius: 10px;
    background-color: rgba(255, 255, 255, 0.336);
    align-items: center ;
    font: menu;
    display: inline-block;
    font-weight: 900;
    font-size: 40px;
    transition: all 0.8s;
    color: rgb(0, 0, 0);
}
.parent2-link:hover{
    color: rgb(255, 255, 255);
    background: linear-gradient(to left , rgb(0,255,0),rgb(255,0,0) );

}
video{
    width: 80%;
    background-color: rgb(255, 255, 255);
    height: 500px;
    margin: 0px 10%;
}
.parent3{
    margin: 80px;
}
.parent4{
    text-align: center;
}
.parent4-header{
    color: red;
    font: menu;
    font-size: 40px;
    font-weight: 900;
}
.parent4-p{
    color: black;

    font: menu;
    font-size: 40px;
    font-weight: 500;
}
.parent5{
    text-align: center;
}
.parent5-items{
    display: inline-block;
    background: linear-gradient(to left,rgba(0, 0, 255, 0.555) ,rgba(255, 0, 0, 0.534));
    border-radius:  5px; ;
    margin: 10px;
    transition: all 0.2s;
    padding: 20px;
}
.img3{
    width: 190px;

}
.img4{
    padding: 0;
    margin: 0;
}
.parent5-items:hover{
    border: 2px solid gold;
    box-shadow: 5px 5px 5px gold;
}
.parent5-title{
    color: rgb(65, 65, 65);
    font: menu;
    font-size: 30px;
    font-weight: 500;
}
.parent5-p{
    color: black;

    font: menu;
    font-weight: 900;
    font-size: 37px;
}
.parent7{
    text-align: center;
    margin-top: 100px;
}
.parent7-title{
    color: rgb(255, 0, 0);
    font: menu;
    font-size: 70px;
    font-weight: 900;
    margin-bottom: 0;
}
.parent7-index{
    background-color: #ffffff86;
    width: 63.05;
    margin: 22px 18.475%;
    box-shadow: 3px 3px 3px rgb(0, 0, 0);
    padding-bottom: 50px;
    padding-top:10px ;
    border-radius: 10px;

}
.parent7-p-b{
    color: rgb(0, 0, 0);
    display: inline-block;
    font: menu;
    font-size: 30px;
    font-weight: 900;
}
.parent7-p{
    color: rgb(0, 0, 0);
    display: inline-block;
    font: menu;
    font-size: 25px;
    font-weight: 700;
    margin: 20px;
    margin-top: 0;
}
.font2{
    font-size: 20px;
    color: rgb(78, 78, 78);
}
.parent6{
    text-align: center;
    margin-top: 100px;
}
.parent6-title{
    color: rgb(255, 0, 0);
    font: menu;
    font-size: 70px;
    font-weight: 900;
    margin-bottom: 0;
}
.parent6-p{
    color: rgb(0, 0, 0);
    display: inline-block;
    font: menu;
    font-size: 25px;
    font-weight: 700;
    margin: 20px;
    margin-top: 0;
}
.parent6-p-b-link{
    color: rgb(0, 0, 0);
    display: inline-block;
    font: menu;
    transition: all 0.5s;
    font-size: 25px;
    font-weight: 900;
    margin: 0px 0px 0px 0px;
    margin: 20px;
    margin-top: 0;
}
.parent6-p-b-link:hover{
    color: red;
}
@keyframes load {
    from{background-color: black;}
    to{background-color: rgba(173, 147, 0, 0.692);}
}
@keyframes load-header{
    from{background-color: black;}
    to{ background-color: rgb(84, 255, 149);}
}
.header1{
    background-color: #f0e7e7a8;
    padding: 10px;
    margin-top: 30px;
    border-radius: 50px;
    width: 80%;
    margin: 0px 10% ;
}
.m2{
   
    background-color: #f0e7e985;
    padding: 10px;
    margin-top: 50px;
    border-radius: 50px;
  
}
.parent8{
    text-align: center;
}
.parent8-index{
    padding: 20px;
}
.parent8-left{
    display: inline-block;
    border-radius: 10px;
    margin: 40px;
}
.parent8-right{
    display: inline-block;
    border-radius: 10px;
}
.parent8-left img{
    border-radius: 20px;
}
.parent8-right img{
    border-radius: 20px;
}
.parent8-left h1{
    color: rgb(255, 0, 0);
    font: menu;
    font-size: 40px;
    font-weight: 900;

}
.parent8-left span{
    color: rgb(0, 0, 0);
    font: menu;
    font-size: 20px;
    font-weight: 900;

}
.parent8-right h1{
    color: rgb(0, 68, 255);
    font: menu;
    margin-top: 55px;
    font-size: 40px;
    font-weight: 900;

}
.parent8-right span{
    color: rgb(0, 0, 0);
    font: menu;
    font-size: 20px;
    font-weight: 900;

}
.parent8-left-b ,.parent8-right-b{
    display: inline-block;
}

.parent8-left-b{
    margin: 40px;
}
.parent8-left-b img , .parent8-right-b img{
    border-radius: 40px;
}
.parent8-right-b h1{
    color: rgb(0, 17, 255);
    font: menu;
    margin-top: 55px;
    font-size: 40px;
    font-weight: 900;

}
.parent8-right-b span{
    color: rgb(0, 0, 0);
    font: menu;
    font-size: 20px;
    font-weight: 900;

}
.parent8-left-b h1{
    color: rgb(255, 0, 0);
    font: menu;
    margin-top: 55px;
    font-size: 40px;
    font-weight: 900;

}
.parent8-left-b span{
    color: rgb(0, 0, 0);
    font: menu;
    font-size: 20px;
    font-weight: 900;

}
.parent9{
    text-align: center;
}
.parent9-index{
    background-color: #ffffff8f;
    width: 63.05%;
    margin: 22px 18.475%;
    box-shadow: 3px 3px 3px rgb(0, 0, 0);
    padding-bottom: 50px;
    padding-top:20px ;
    border-radius: 10px;
}
.parent9-index h1{
    color: rgb(255, 0, 0);
    font: menu;
    margin-top: 55px;
    font-size: 40px;
    font-weight: 900;
}
.parent9-index span{
    color: rgb(95, 95, 95);
    font: menu;
    font-size: 20px;
    font-weight: 600;
}
.parent9-index span p {
    font-size: 25px;
    display: inline-block;
    margin: 0px 0px 0px 0px;
    font-weight: 900;
    color: black;
}
.parent9-index h2 a{
    font-size: 25px;
    display: inline-block;
    font-weight: 900;
    color: black;

}
.parent10{
    text-align: center;
}
.parent10 h1{
    color: rgb(255, 0, 0);
    font: menu;
    margin-top: 55px;
    font-size: 70px;
    font-weight: 900;
}
.finished{
    text-align: center;
    display: flex;
    justify-content: center;
    margin-bottom: 30px;
}
.son{
    max-width: 350px;
    width: 100%;
    text-align: center;
    transition: all 0.5s;
    height: 150px;
    background-color: rgba(0, 255, 115, 0.658);
    margin: 10px;
    border: 7px solid gray;
    border-radius: 10px;    
    padding: 20px;
}
.headerfinish{
    text-align: center;
    margin-top: -40px;   
    margin-bottom: 20px;
    margin-left: 90px;
    border-radius: 5px;
    background-color: red;
    width: 150px;
    padding: 10px;
}
.son a{
    
    color: black;
    font: medium;
    font-size: 30px;
    font-weight: 900;
}
.son p{
    font-size: 15px;
    font: medium;
    font-weight: 900;
}
.son:hover{
    border: 7px solid red;
}
.parent11{
    text-align: center;
    color: rgb(255, 255, 255);
    font-size: 25px;
    font: medium;
    font-weight: 900;
}
.parent11 a{
    color: yellow;
}
.parent11 a:hover{
    color: rgb(0, 0, 0);
}
.parent11 span{
    font-size: 25px;
}
.parent11 span p{
    display: inline-block;
    font: menu;
    font-weight: 900;
    font-size: 30px;
    color: rgb(0, 255, 0);
}
.parent11 span a{
    font: menu;
    font-weight: 900;
    font-size: 25px;
    color: rgb(0, 255, 0);
}
.parent12{
    background-color: #eeff6dce;
    text-align: center;
    border-top-left-radius: 100%;
    border-top-right-radius: 10%;
    padding: 50px;

}
.parent12 img{
    margin-bottom: 50px;
}
.parent12 a{
    text-decoration: none;
    padding-left: 30px;
    color: gray;
    margin-left: 20px;
    font: medium;
    font-weight: 900;
    font-size: 20px;
    border-radius: 10px;
}
.parent12 a:hover{
    text-decoration: underline;

}
@keyframes back {
    1%{
        background: url(./1.jpg);
        background-attachment: fixed;
    }
    
    
    2%{
        background: url(./2.jpg);
        background-attachment: fixed;
    }
    
    
    3%{
        background: url(./3.jpg);
        background-attachment: fixed;
    }
    
    
    4%{
        background: url(./4.jpg);
        background-attachment: fixed;
    }
    
    
    5%{
        background: url(./5.jpg);
        background-attachment: fixed;
    }
    
    
    6%{
        background: url(./6.jpg);
        background-attachment: fixed;
    }
    
    
    7%{
        background: url(./7.jpg);
        background-attachment: fixed;
    }
    
    
    8%{
        background: url(./8.jpg);
        background-attachment: fixed;
    }
    
    
    9%{
        background: url(./9.jpg);
        background-attachment: fixed;
    }
    
    
    10%{
        background: url(./10.jpg);
        background-attachment: fixed;
    }
    
    
    11%{
        background: url(./11.jpg);
        background-attachment: fixed;
    }
    
    
    12%{
        background: url(./12.jpg);
        background-attachment: fixed;
    }
    
    
    13%{
        background: url(./13.jpg);
        background-attachment: fixed;
    }
    
    
    14%{
        background: url(./14.jpg);
        background-attachment: fixed;
    }
    
    
    15%{
        background: url(./15.jpg);
        background-attachment: fixed;
    }
    
    
    16%{
        background: url(./16.jpg);
        background-attachment: fixed;
    }
    
    
    17%{
        background: url(./17.jpg);
        background-attachment: fixed;
    }
    
    
    18%{
        background: url(./18.jpg);
        background-attachment: fixed;
    }
    
    
    19%{
        background: url(./19.jpg);
        background-attachment: fixed;
    }
    
    
    20%{
        background: url(./20.jpg);
        background-attachment: fixed;
    }
    
    
    21%{
        background: url(./21.jpg);
        background-attachment: fixed;
    }
    
    
    22%{
        background: url(./22.jpg);
        background-attachment: fixed;
    }
    
    
    23%{
        background: url(./23.jpg);
        background-attachment: fixed;
    }
    
    
    24%{
        background: url(./24.jpg);
        background-attachment: fixed;
    }
    
    
    25%{
        background: url(./25.jpg);
        background-attachment: fixed;
    }
    
    
    26%{
        background: url(./26.jpg);
        background-attachment: fixed;
    }
    
    
    27%{
        background: url(./27.jpg);
        background-attachment: fixed;
    }
    
    
    28%{
        background: url(./28.jpg);
        background-attachment: fixed;
    }
    
    
    29%{
        background: url(./29.jpg);
        background-attachment: fixed;
    }
    
    
    30%{
        background: url(./30.jpg);
        background-attachment: fixed;
    }
    
    
    31%{
        background: url(./31.jpg);
        background-attachment: fixed;
    }
    
    
    32%{
        background: url(./32.jpg);
        background-attachment: fixed;
    }
    
    
    33%{
        background: url(./33.jpg);
        background-attachment: fixed;
    }
    
    
    34%{
        background: url(./34.jpg);
        background-attachment: fixed;
    }
    
    
    35%{
        background: url(./35.jpg);
        background-attachment: fixed;
    }
    
    
    36%{
        background: url(./36.jpg);
        background-attachment: fixed;
    }
    
    
    37%{
        background: url(./37.jpg);
        background-attachment: fixed;
    }
    
    
    38%{
        background: url(./38.jpg);
        background-attachment: fixed;
    }
    
    
    39%{
        background: url(./39.jpg);
        background-attachment: fixed;
    }
    
    
    40%{
        background: url(./40.jpg);
        background-attachment: fixed;
    }
    
    
    41%{
        background: url(./41.jpg);
        background-attachment: fixed;
    }
    
    
    42%{
        background: url(./42.jpg);
        background-attachment: fixed;
    }
    
    
    43%{
        background: url(./43.jpg);
        background-attachment: fixed;
    }
    
    
    44%{
        background: url(./44.jpg);
        background-attachment: fixed;
    }
    
    
    45%{
        background: url(./45.jpg);
        background-attachment: fixed;
    }
    
    
    46%{
        background: url(./46.jpg);
        background-attachment: fixed;
    }
    
    
    47%{
        background: url(./47.jpg);
        background-attachment: fixed;
    }
    
    
    48%{
        background: url(./48.jpg);
        background-attachment: fixed;
    }
    
    
    49%{
        background: url(./49.jpg);
        background-attachment: fixed;
    }
    
    
    50%{
        background: url(./50.jpg);
        background-attachment: fixed;
    }
    
    
    51%{
        background: url(./51.jpg);
        background-attachment: fixed;
    }
    
    
    52%{
        background: url(./52.jpg);
        background-attachment: fixed;
    }
    
    
    53%{
        background: url(./53.jpg);
        background-attachment: fixed;
    }
    
    
    54%{
        background: url(./54.jpg);
        background-attachment: fixed;
    }
    
    
    55%{
        background: url(./55.jpg);
        background-attachment: fixed;
    }
    
    
    56%{
        background: url(./56.jpg);
        background-attachment: fixed;
    }
    
    
    57%{
        background: url(./57.jpg);
        background-attachment: fixed;
    }
    
    
    58%{
        background: url(./58.jpg);
        background-attachment: fixed;
    }
    
    
    59%{
        background: url(./59.jpg);
        background-attachment: fixed;
    }
    
    
    60%{
        background: url(./60.jpg);
        background-attachment: fixed;
    }
    
    
    61%{
        background: url(./61.jpg);
        background-attachment: fixed;
    }
    
    
    62%{
        background: url(./62.jpg);
        background-attachment: fixed;
    }
    
    
    63%{
        background: url(./63.jpg);
        background-attachment: fixed;
    }
    
    
    64%{
        background: url(./64.jpg);
        background-attachment: fixed;
    }
    
    
    65%{
        background: url(./65.jpg);
        background-attachment: fixed;
    }
    
    
    66%{
        background: url(./66.jpg);
        background-attachment: fixed;
    }
    
    
    67%{
        background: url(./67.jpg);
        background-attachment: fixed;
    }
    
    
    68%{
        background: url(./68.jpg);
        background-attachment: fixed;
    }
    
    
    69%{
        background: url(./69.jpg);
        background-attachment: fixed;
    }
    
    
    70%{
        background: url(./70.jpg);
        background-attachment: fixed;
    }
    
    
    71%{
        background: url(./71.jpg);
        background-attachment: fixed;
    }
    
    
    72%{
        background: url(./72.jpg);
        background-attachment: fixed;
    }
    
    
    73%{
        background: url(./73.jpg);
        background-attachment: fixed;
    }
    
    
    74%{
        background: url(./74.jpg);
        background-attachment: fixed;
    }
    
    
    75%{
        background: url(./75.jpg);
        background-attachment: fixed;
    }
    
    
    76%{
        background: url(./76.jpg);
        background-attachment: fixed;
    }
    
    
    77%{
        background: url(./77.jpg);
        background-attachment: fixed;
    }
    
    
    78%{
        background: url(./78.jpg);
        background-attachment: fixed;
    }
    
    
    79%{
        background: url(./79.jpg);
        background-attachment: fixed;
    }
    
    
    80%{
        background: url(./80.jpg);
        background-attachment: fixed;
    }
    
    
    81%{
        background: url(./81.jpg);
        background-attachment: fixed;
    }
    
    
    82%{
        background: url(./82.jpg);
        background-attachment: fixed;
    }
    
    
    83%{
        background: url(./83.jpg);
        background-attachment: fixed;
    }
    
    
    84%{
        background: url(./84.jpg);
        background-attachment: fixed;
    }
    
    
    85%{
        background: url(./85.jpg);
        background-attachment: fixed;
    }
    
    
    86%{
        background: url(./86.jpg);
        background-attachment: fixed;
    }
    
    
    87%{
        background: url(./87.jpg);
        background-attachment: fixed;
    }
    
    
    88%{
        background: url(./88.jpg);
        background-attachment: fixed;
    }
    
    
    89%{
        background: url(./89.jpg);
        background-attachment: fixed;
    }
    
    
    90%{
        background: url(./90.jpg);
        background-attachment: fixed;
    }
    
    
    91%{
        background: url(./91.jpg);
        background-attachment: fixed;
    }
    
    
    92%{
        background: url(./92.jpg);
        background-attachment: fixed;
    }
    
    
    93%{
        background: url(./93.jpg);
        background-attachment: fixed;
    }
    
    
    94%{
        background: url(./94.jpg);
        background-attachment: fixed;
    }
    
    
    95%{
        background: url(./95.jpg);
        background-attachment: fixed;
    }
    
    
    96%{
        background: url(./96.jpg);
        background-attachment: fixed;
    }
    
    
    97%{
        background: url(./97.jpg);
        background-attachment: fixed;
    }
    
    
    98%{
        background: url(./98.jpg);
        background-attachment: fixed;
    }
    
    
    99%{
        background: url(./99.jpg);
        background-attachment: fixed;
    }
    
    
    100%{
        background: url(./1.jpg);
        background-attachment: fixed;
    }
}
    </STyle>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="./favicon-32x32.png">
    <title>mohamd</title>
</head>
<body>
    <div class="header2">
    <header>
        <a href="#">
        <h2>Rails World is sold out. See you in Toronto Sept 26 & 27.</h2>
    </a>
    </header>
    <div class="parent1">
        <a href="#" class="parent1-link">Guides</a>
        <a href="#" class="parent1-link">API</a>
        <a href="#" class="parent1-link">  Forum</a>
        <a href="#" class="parent1-link">Contribute</a>
        <a href="#" class="parent1-link img"><img src="./logo.svg" alt=""></a>
        <a href="#" class="parent1-link">Foundation</a>
        <a href="#" class="parent1-link">Team</a>
        <a href="#" class="parent1-link">Blog</a>
        <a href="#" class="parent1-link">jobs</a>

    </div>
    <div class="header1 m2">
    <div class="parent2">
        <h1 class="parent2-header">Compress the complexity <br> of modern web apps.</h1>
        <h3 class="parent2-p">Learn just what you need to get started, then keep leveling up as <br> you go. <span class="parent2-p-b"> Ruby on Rails scales from HELLO WORLD to IPO.</span>
        </h3>
        <a href="#" class="parent2-link">Rails 7.2.1 — released August 22, 2024</a>
    </div>
</div>
    <div class="parent3">

   
    <video poster="/assets/videos/rails7-screencast-poster.jpg" width="1920" height="1080" controls="">
        <source src="https://d1snj8sshb5u7m.cloudfront.net/Rails7.mp4" type="video/mp4">
        <track kind="captions" label="English" src="/assets/videos/rails7-screencast-english.vtt" srclang="en" default="false">
      </video>
    </div>
</div>

        <div class="header1">
        <div class="parent4">
            <h1 class="parent4-header">You’re in good company.</h1>
            <h3 class="parent4-p">Over the past two decades, Rails has taken countless companies <br> to millions of users and billions in market valuations.
            </h3>
        </div>
        <div class= "parent5">
            <div class="parent5-items"><img src="./1.svg" alt="" class="parent5-items-img img2"></div>
            <div class="parent5-items"><img src="./2.svg" alt="" class="parent5-items-img img2"></div>
            <div class="parent5-items"><img src="./3.svg" alt="" class="parent5-items-img img2"></div>
            <div class="parent5-items"><img src="./4.svg" alt="" class="parent5-items-img img2"></div><br>
            <div class="parent5-items"><img src="./5.svg" alt="" class="parent5-items-img img2"></div>
            <div class="parent5-items "><img src="./6.svg" alt="" class="parent5-items-img img2"></div>
            <div class="parent5-items"><img src="./7.svg" alt="" class="parent5-items-img img3"></div>
            <div class="parent5-items "><img src="./8.svg" alt="" class="parent5-items-img img2"></div><br>
            <div class="parent5-items"><img src="./9.svg" alt="" class="parent5-items-img "></div>
            <div class="parent5-items"><img src="./10.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./11.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./12.svg" alt="" class="parent5-items-img"></div><br>
            <div class="parent5-items"><img src="./13.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./14.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./15.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./16.svg" alt="" class="parent5-items-img"></div><br>
            <div class="parent5-items"><img src="./17.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./18.svg" alt="" class="parent5-items-img"></div>
            <div class="parent5-items"><img src="./19.svg" alt="" class="parent5-items-img"></div>
            <h2 class="parent5-title"><span class="parent5-p">These are just a few of the big names.</span> There have been many <br> hundreds of thousands of apps created with Rails since its inception.</h2>
        </div>
    </div>
        <div class="parent6">
            <h1 class="parent6-title">Building it together.</h1>
            <h2 class="parent6-p">Over six thousand people have<a href="" class="parent6-p-b-link"> contributed code to Rails,</a>and <br>many more have served the community through evangelism,<br> documentation, and  bug reports. Join us!</h2>
        </div>
        <div class="parent7">
            <div class="parent7-index">
                <h1 class="parent7-title">Everything you need.</h1>
                <span class="parent7-p">
                    <h4 class="parent7-p-b">Rails is a full-stack framework.</h4>
                    It ships with all the tools needed to build amazing web apps on both the front and back end.
                </span>
                <p class="parent7-p font2" >Rendering HTML templates, updating databases, sending and receiving emails, maintaining live pages via WebSockets, enqueuing jobs for asynchronous work, storing uploads in the cloud, providing solid security protections for common attacks. Rails does it all and so much more.</p>
            </div>
        </div>
        <div class="parent8">
            <div class="parent8-index">
                <div class="parent8-left"><img src="./d1.png" alt=""><h1>Active Records make modeling easy.</h1><span>Databases come to life with business logic encapsulated in rich objects. <br> Modeling associations between tables, providing callbacks when saved, <br> encrypting sensitive data seamlessly, and expressing SQL queries <br> beautifully.</span></div>
                <div class="parent8-right"><img src="./d2.png" alt="">
                <h1>Action Controllers handle all requests.</h1>
            <span>Controllers expose the domain model to the web, process incoming <br> parameters, set caching headers, and render templates, responding with <br> either HTML or JSON. </span></div>
            <div class="parent8-left-b"><img src="./d3.png" alt=""><h1>Action Views mix Ruby and HTML.</h1>
            <span>Templates can use the full versatility of Ruby, excessive code <br> is  extracted into helpers, and the domain model is used directly and <br> interwoven with the HTML. </span></div>
            <div class="parent8-right-b"><img src="./d3.png" alt=""><h1>Action Dispatch routes URLs.</h1><span>Configure how URLs connect to the controllers using the routing domain language. Routes <br> expose the bundle of actions that go together <br> as a resource: index, show, new, create, edit, update, destroy.</span></div>
            </div>
        </div>
        <div class="parent9">
            <div class="parent9-index">
                <h1>Optimized for happiness.</h1>
                <span>Rails has united and cultivated a strong tribe around a <p> wide set of heretical thoughts about the </p> <br> nature of programming and programmers. Understanding these thoughts will help you <br>understand the design of the framework.</span>
                <h2><a href="#">Read the Rails Doctrine > </a></h2>
            </div>
        </div>
        <div class="parent10">
            <h1>Let’s get started.</h1>
        </div>
        <div class="finished">
            <div class="son son1"><div class="headerfinish">Learning ></div><a href="#">Read the guides. </a> <p>Learn what the frameworks can do and how
                they fit together.</p></div>
            <div class="son son2"><div class="headerfinish">Contributing ></div><a href="#">Contribute on GitHub.</a><p>File bug reports and make pull-requests.</p></div>
            <div class="son son3"><div class="headerfinish">Keeping up ></div><a href="#">See what’s new.</a> <p>The latest releases and updates on
                development.</p></div>
        </div>
        <div class="parent11">
            <h2>Learn more about <a href="#">Hotwire </a> , the default front-end framework for Rails.</h2>
            <span> <p>Stay up to date </p>with Rails on <a href="#"> <img src="./icon-twitter.svg" alt=""> Twitter,</a> <a href="#"> <img src="./icon-youtube.svg" alt=""> YouTube </a>, and <br>  <a href="#" > <img src="./icon-world.svg" alt="">This Week in Rails. </a></span>
        </div>
        <div class="parent12"><div class="parent12-index"><img src="./logo.svg" alt=""></div>
            <a href="#" class="parent12-link">Conduct</a>
            <a href="#" class="parent12-link">Maintenance</a>
            <a href="#" class="parent12-link"> Security</a>
            <a href="#" class="parent12-link">Trademarks</a>
            <a href="#" class="parent12-link"> License</a>
        </div>
</body>
</html >
