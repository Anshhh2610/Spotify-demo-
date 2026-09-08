<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify - Web Player: Music for everyone</title>
    <link rel="shortcut icon" href="https://open.spotifycdn.com/cdn/images/favicon32.b64ecc03.png" type="image/x-icon">
    <link rel="stylesheet" href="src/spotify.css">
    <link rel="stylesheet" href="src/utility.css">
    <link rel="stylesheet" href="src/font-styles.css">
    <link rel="stylesheet" href="src/colors.css">
    <link rel="stylesheet" href="src/animation.css">
    <link rel="stylesheet" href="src/responsive.css">
</head>

<body class="ds" oncontextmenu="return false;">
    <div class="container dflex">
        <nav class="navbar">
            <div class="leftnav">
                <img src="svg/logo2.svg" id="logo" class="logo invert m-8l" alt="Logo">
                <div class="bg-grey2 homebg bg-trans" id="home">
                    <img src="svg/home.svg" class="home invert" alt="Home">
                </div>
                <div class="search-container m-8l fac bg-grey2">
                    <img src="svg/search.svg" class="invert cp" height="24px" alt="Search">
                    <input type="search" class="bg-grey2 outline-n" id="searcht"
                        placeholder="What do you want to play?">
                    <div class="line"></div>
                    <img src="svg/sbox.svg" class="invert cp" height="24px" alt="sbox">
                </div>
            </div>
            <div class="rightnav">
                <ul>
                    <div class="rightnav-left-sec fac ">
                        <li class="nav-text rightnav-scale m-5">Premium</li>
                        <li class="nav-text rightnav-scale m-5">Support</li>
                        <li class="nav-text rightnav-scale m-5">Download</li>
                    </div>
                    <div class="line"></div>
                    <li class="fac r">
                        <img src="svg/install.svg" class="invert" alt="Install"    <!-- <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="20" height="20" color="currentColor" fill="#000000" stroke="#000000" 
                        class="invert" >
                        <path
                            d="M4.995 8.745a.75.75 0 0 1 1.06 0L7.25 9.939V4a.75.75 0 0 1 1.5 0v5.94l1.195-1.195a.75.75 0 1 1 1.06 1.06L8 12.811l-.528-.528-.005-.005-2.472-2.473a.75.75 0 0 1 0-1.06">
                        </path>
                        <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13"></path>
                    </svg> -->
                        <span class="nav-text2 rightnav-scale m-5">
                            Install App
                        </span>
                    </li>
                    <li>
                        <span class="nav-text2 rightnav-scale">
                            Sign Up
                        </span>
                    </li>
                    <li>
                        <button type="button" class="login-btn  cp all-btn">
                            <span class="black-text">Log in</span>
                        </button>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="in-container">
            <div class="left bg-grey br-8"
                <div class="yourlibrary dflex jcsb align-c">
                    <span>
                        <b class="main-text1">
                            Your Library
                        </b>
                    </span>
                    <button class="create-btn bg-grey2 cp hover-bg-color bg-trans" type="button">
                        <img class="invert" src="svg/plus.svg" height="16px" alt="Plus">
                        <span class="main-text1" style="color: white;">
                            Create
                        </span>
                    </button>
                </div>

                <div class="left-two-box-cont">

                    <div class="dual-cont br-grey2">

                        <div class="inner-cont">

                            <div class="in-inner-cont">
                                <span class="main-text1 m-5">
                                    Create your first playlist
                                </span>
                                <span class="main-text2 m-5">
                                    It's easy, We'll help you
                                </span>
                                <button type="button" class="create-playlist-btn cp all-btn lbtn-mar">
                                    <span class="sblack-text">
                                        Create playlist
                                    </span>
                                </button>
                            </div>
                        </div>


                        <div class="inner-cont">
                            <div class="in-inner-cont">
                                <span class="main-text1 m-5">
                                    Let's find some podcasts to follow
                                </span>
                                <span class="main-text2 m-5">
                                    We'll keep you updated on new episodes
                                </span>
                                <button type="button" class="create-playlist-btn cp all-btn lbtn-mar">
                                    <span class="sblack-text">
                                        Browse podcasts
                                    </span>
                                </button>
                            </div>
                        </div>
                    </div>



                </div>


                <div class="link-container ">
                    <div class="links ">
                        <div class="links-items">
                            <a class="link-text " href="https://www.spotify.com/in-en/legal/" id="">
                                <span class="bottom-text">Legal</span>
                            </a>
                        </div>

                        <div class="links-items">
                            <a class="link-text " href="https://www.spotify.com/in-en/safetyandprivacy/" id="">
                                <span class="bottom-text">Safety &amp; Privacy Center</span>
                            </a>
                        </div>

                        <div class="links-items">
                            <a class="link-text" href="https://www.spotify.com/in-en/legal/privacy-policy/" id="">
                                <span class="bottom-text">Privacy Policy</span>
                            </a>
                        </div>

                        <div class="links-items">
                            <a class="link-text" href="https://www.spotify.com/in-en/legal/cookies-policy/" id="">
                                <span class="bottom-text">Cookies</span>
                            </a>
                        </div>

                        <div class="links-items">
                            <a class="link-text" href="https://www.spotify.com/in-en/legal/privacy-policy/#s3" id="">
                                <span class="bottom-text">About Ads</span>
                            </a>
                        </div>

                        <div class="links-items">
                            <a class="link-text " href="https://www.spotify.com/in-en/accessibility/" id="">
                                <span class="bottom-text">Accessibility</span>
                            </a>
                        </div>
                    </div>

                    <a draggable="false" class="link-text links-items cus-p cookies"
                        href="https://www.spotify.com/legal/cookies-policy/" target="_blank" rel="noopener">
                        <span class="bottom-text2">Cookies</span>
                    </a>

                </div>


                <div class="lang-btn-cont ">
                    <button type="button" class="lang-btn cp bg-grey ">
                        <img src="svg/lang-btn.svg" class="invert" height="16px" alt="Globe">
                        <span class="eng-text">
                            English
                        </span>
                    </button>
                </div>


            </div>


            <div class="right bg-grey br-8">


                <div class="header">
                    <span class="head-text">
                        Trending Songs
                    </span>
                </div>





                <div class="card-cont">



                    <!-- <div class="card-bg cp" onclick="playSong()">
                    <div class="card">
                         <div class="play-svg fac none ">
                            <img src="play.svg" alt="" height="24">
                        </div>
                        <div class="play-svg fac none">
                           <img src="pause.svg" alt="" height="24">
                        </div> 
                        <img src="https://i.scdn.co/image/ab67616d0000b273a7fdc721f4ac2c0415593273" alt="IMG">
                        <p class="card-text">
                            DXB
                        </p>
                        <p class="card-n-text">
                            Cheema Y
                        </p>
                    </div>
                  </div> -->





                </div>


                <div class="player-cont">

                    <div class="horizontal-rule">

                    </div>

                    <div class="player-in  bg-any bg-grey2">


                        <div class="playbar-bg bg-grey2 ">

                            <div class="song-info ds">
                                <p class="song-name main-text1">Lorem, ipsum dolor.</p>
                                <p class="artist-name nav-text2 ">Lorem, ipsum.</p>
                            </div>

                            <div class="btns ds">

                                <div class="previous cp playbar-svg fac" id="previous">
                                    <img src="svg/previous.svg" alt="">
                                    </svg>
                                </div>

                                <div class="playbar cp fac" id="play">
                                    <div class="playbar-svg fac">
                                        <img src="svg/play.svg" alt="">
                                    </div>
                                </div>


                                <div class="next cp playbar-svg fac" id="next">
                                    <img src="svg/next.svg" alt="">
                                    </svg>
                                </div>


                            </div>

                            <div class="vol-controls cp fac ">

                                <img src="svg/vol-ful.svg" alt="">
                                <input type="range" min="0" max="1" step="0.01" value="1" class=" cp volume-slider">

                            </div>




                            <div class="song-time ds nav-text2">
                                00 / 00
                            </div>

                        </div>


                        <div class="seekbar">
                            <div class="circle onSelectc">

                            </div>

                        </div>


                    </div>





                </div>


            </div>






        </div>



        <div class="bottom-footer mqhide align-c jcsb">
            <div class="bf-text m-5">
                <span class="bottom-textf">
                    Preveiw of Spotify
                </span>
                <span class="bottom-text3">
                    Sign up to get unlimited songs and podcasts with occasional ads. No credit card needed.
                </span>
            </div>

            <div class="bf-btn">
                <button type="button" class="bf-signup cp all-btn ">
                    <span class="black-text">
                        Sign up free
                    </span>
                </button>
            </div>

        </div>

    </div>


    <audio id="audioPlayer"></audio>
    <!-- <script src="spotify.js"></script> -->
    <script src="spotify.js"></script>
</body>

</html>
