
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giitam Music Software</title>
    <link rel="stylesheet" href="Style.css">
</head>

<body>
    <nav>
        <ul>
            <li class="brand"><img src="Logo2.jpg" alt="Giitam">Gittam</li>
            <i class="fa-regular fa-user"></i>
            <li>Home</li>
            <li>About</li>
        </ul>
    </nav>

    <div class="container">
        <div class="Songlist">
            <h1>Latest Launch only for You !!</h1>
            <div class="songitemcontainer">
                <div class="songitem">
                    <img src="cover/1.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/2.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/3.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/4.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/5.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/6.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/7.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/8.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/9.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/10.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/11.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/12.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/13.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/14.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>
                <div class="songitem">
                    <img src="cover/15.jpg" alt="1">
                    <span class="songName"> Sugar Baby</span>
                    <span class="songlistplay"><span class="timestamp">05:34 <i
                                class="fa-regular songItemplay fa-circle-play"> </i></span></i></span>
                </div>

            </div>
        </div>
        <div class="songBanner"></div>
    </div>

    <div class="bottom">
        <input type="range" name="range" id="myProgressBar" min="0" value="0" max="100">
        <div class="icons">
            <!--fontawesome icons-->
            <i class="fa-solid fa-3x fa-backward"></i>
            <i class="fa-regular fa-3x fa-circle-play" id="masterPlay"></i>
            <i class="fa-solid fa-3x fa-forward"></i>

        </div>
        <div class="songinfo">
            <img src="playing.gif" id="gif" width="42px"> Sugar Baby 
        </div>

    </div>
    <script src="https://kit.fontawesome.com/94ebfc53bb.js" crossorigin="anonymous"></script>
    <script src="function.js"></script>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Varela+Round&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap');

body {
    background-color: rgb(0, 0, 0);
}

* {
    margin: 0;
    padding: 0;
}

nav {
    font-family: 'Ubuntu', sans-serif;
}

nav ul {
    display: flex;
    align-items: center;
    list-style-type: none;
    height: 65px;
    background-color: black;
    color: azure;
    position: fixed;
    overflow: hidden;
    top: 0;
    width: 100%;
}

nav ul li {
    padding: 0 12px;
    align-items: center;
}

.brand img {
    width: 65px;
    padding: 0 8px;
}

.brand {
    display: flex;
    align-items: center;
    font-weight: bolder;
    font-size: 2.3rem;
    font-family: 'Montserrat';
}

.container {
    min-height: 75vh;
    background-color: rgba(127, 126, 57, 0.145);
    color: rgb(72, 72, 72);
    font-family: 'Dancing Script', cursive;
    align-items: baseline;
    display: flex;
    width: 96%;
    margin: 37px auto;
    border-radius: 12px;
    padding: 34px;
    font-size: 34px;
    background-image: url(cover/Cover.jpg);
}

.bottom {
    position: sticky;
    height: 135px;
    background-color: black;
    color: aliceblue;
    bottom: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.icons {
    margin-top: 14px;
}

.icons i {
    cursor: pointer;
}

#myProgressBar {
    width: 80vw;
    text-align: center;
    color: aqua;
    cursor: pointer;
}

.songitemcontainer {
    margin-top: 60px;
}

.songitem {
    height: 144px;
    display: inline-grid;
    background-color: rgba(180, 153, 90, 0.016)12;
    cursor: pointer;
    color: rgb(217, 206, 206);
    margin: 12px 0;
    justify-content: center;
    align-items: center;
    border-radius: 34px;
}

.songitem img {
    width: 250px;
    margin: 50px 55px 0;
    border-radius: 34px;
    box-shadow: aliceblue;

}

.timestamp {
    margin: 0 23px;

}

.timestamp i {
    cursor: pointer;
    padding: 0 10px;
}

.songinfo {
    position: absolute;
    left: 10vw;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.songinfo img {
    opacity: 0;
    transition: opacity 0.4s ease-in;
}

