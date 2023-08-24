
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Odisej - Mljet Island Hotel</title>

    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="./android-chrome-192x192.png" type="image/x-icon">

    <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css"
  />

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.css">


    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">


</head>
<body>

    <div id="cursor"></div>
    <div id="nav">
        <div id="part1">
            <div class="line"></div>
            <div class="line"></div>
            <div class="line"></div>
        </div>
        <div id="part2">
            <button id="first">online-check-in</button>
            <button id="second">book now</button>

        </div>
    </div>


    <div id="main">

        <div id="loader">
            <h1>0%</h1>
        </div>

        <div id="landingpage">

            <svg class="u-icon u-icon--logo js-navigation-logo" viewBox="0 0 312 91" xmlns="http://www.w3.org/2000/svg">
                <path class="u-icon__main" d="M40.8 12.6V11.4H29.4V12.6C31.92 12.6 32.4 14.28 32.4 17.16V27.96H10.8V17.16C10.8 14.28 11.28 12.6 13.8 12.6V11.4H2.4V12.6C4.92 12.6 5.4 14.28 5.4 17.16V45.24C5.4 48.12 4.92 49.8 2.4 49.8V51H13.8V49.8C11.28 49.8 10.8 48.12 10.8 45.24V30.36H32.4V45.24C32.4 48.12 31.92 49.8 29.4 49.8V51H40.8V49.8C38.28 49.8 37.8 48.12 37.8 45.24V17.16C37.8 14.28 38.28 12.6 40.8 12.6ZM42.5672 36C42.5672 44.1 47.6672 51.6 57.5672 51.6C67.4672 51.6 72.5672 44.1 72.5672 36C72.5672 27.9 67.4672 20.4 57.5672 20.4C47.6672 20.4 42.5672 27.9 42.5672 36ZM48.0272 37.2C47.1272 29.88 49.1072 23.76 55.9472 22.92C62.7872 22.08 66.2072 27.6 67.1072 34.8C68.0072 42.12 66.0272 48.24 59.1872 49.08C52.3472 49.92 48.9272 44.4 48.0272 37.2ZM88.4555 47.1C88.3355 48.42 87.7955 49.2 86.4155 49.2C83.8955 49.2 83.3555 46.62 83.3555 40.8V23.4H88.8155C90.6155 23.4 90.6155 22.2 90.6155 21H83.3555V11.4H80.9555C80.9555 19.08 78.2555 20.4 74.3555 21V23.4H77.9555V42.24C77.9555 50.22 82.2155 51.6 85.8755 51.6C88.3955 51.6 90.8555 51 92.0555 48.3L88.4555 47.1ZM114.521 41.28C115.121 46.86 112.121 49.2 107.141 49.2C101.801 49.2 97.4813 45.12 97.4813 37.2V36.24C105.401 38.76 120.281 38.52 120.281 29.22C120.281 23.94 115.721 20.4 108.281 20.4C98.9213 20.4 92.0813 26.58 92.0813 36.78C92.0813 45.18 96.4613 51.6 107.741 51.6C116.381 51.6 120.521 45.48 119.921 40.08L114.521 41.28ZM108.281 22.8C112.721 22.8 114.881 25.26 114.881 28.56C114.881 34.14 109.541 36.72 97.7213 33.72C98.6213 27.48 101.981 22.8 108.281 22.8ZM129.867 11.4C129.867 8.1 127.347 7.8 125.067 7.8H121.467V9C123.987 9 124.467 10.68 124.467 13.56V45.24C124.467 48.12 123.987 49.8 121.467 49.8V51H132.867V49.8C130.347 49.8 129.867 48.12 129.867 45.24V11.4ZM149.067 31.2C149.067 42.9 156.267 51.6 167.967 51.6C179.667 51.6 186.867 42.9 186.867 31.2C186.867 19.5 179.667 10.8 167.967 10.8C156.267 10.8 149.067 19.5 149.067 31.2ZM154.587 32.82C153.207 22.02 157.167 14.4 165.147 13.44C174.387 12.3 180.027 18.72 181.347 29.58C182.727 40.38 178.767 48 170.787 48.96C161.547 50.1 155.907 43.68 154.587 32.82ZM190.465 36C190.465 45.84 196.525 51.6 204.565 51.6C209.425 51.6 213.445 48.78 215.065 44.64H215.665V47.4C215.665 50.64 218.605 50.94 220.465 51H224.065V49.8C221.545 49.8 221.065 48.12 221.065 45.24V11.4C221.065 8.1 218.545 7.8 216.265 7.8H212.665V9C215.185 9 215.665 10.68 215.665 13.56V27.36H215.065C213.445 23.22 209.425 20.4 204.565 20.4C196.525 20.4 190.465 26.16 190.465 36ZM196.465 36C196.465 28.86 199.225 22.8 205.765 22.8C212.305 22.8 215.065 28.86 215.065 36C215.065 43.14 212.305 49.2 205.765 49.2C199.225 49.2 196.465 43.14 196.465 36ZM231.752 17.04C233.372 17.04 234.872 15.66 234.872 13.86C234.872 12.24 233.372 10.8 231.752 10.8C230.072 10.8 228.632 12.24 228.632 13.86C228.632 15.66 230.072 17.04 231.752 17.04ZM234.872 24.42C234.872 21.24 232.772 21 230.072 21H226.472V22.2C228.992 22.2 229.472 23.88 229.472 26.76V45.24C229.472 48.12 228.992 49.8 226.472 49.8V51H237.872V49.8C235.352 49.8 234.872 48.12 234.872 45.24V24.42ZM240.858 28.74C240.858 34.68 245.838 35.82 253.818 37.92C258.378 39.36 261.198 39.9 261.198 43.92C261.198 46.98 258.738 49.2 254.298 49.2C249.378 49.2 243.678 47.82 246.078 40.02L240.678 38.82C238.278 48.96 246.258 51.6 254.238 51.6C260.718 51.6 266.598 49.26 266.598 42.66C266.598 36.12 261.138 34.62 253.818 32.7C248.598 31.14 246.258 30.9 246.258 27.18C246.258 25.02 248.118 22.8 253.158 22.8C256.878 22.8 261.978 24.18 259.578 29.58L264.978 30.78C267.378 23.04 259.998 20.4 253.218 20.4C246.138 20.4 240.858 22.74 240.858 28.74ZM291.453 41.28C292.053 46.86 289.053 49.2 284.073 49.2C278.733 49.2 274.413 45.12 274.413 37.2V36.24C282.333 38.76 297.213 38.52 297.213 29.22C297.213 23.94 292.653 20.4 285.213 20.4C275.853 20.4 269.013 26.58 269.013 36.78C269.013 45.18 273.393 51.6 284.673 51.6C293.313 51.6 297.453 45.48 296.853 40.08L291.453 41.28ZM285.213 22.8C289.653 22.8 291.813 25.26 291.813 28.56C291.813 34.14 286.473 36.72 274.653 33.72C275.553 27.48 278.913 22.8 285.213 22.8ZM304.19 17.04C305.81 17.04 307.31 15.66 307.31 13.86C307.31 12.24 305.81 10.8 304.19 10.8C302.51 10.8 301.07 12.24 301.07 13.86C301.07 15.66 302.51 17.04 304.19 17.04ZM302.51 21H298.91V22.2C301.43 22.2 301.91 23.88 301.91 26.76V51C301.91 55.56 301.31 60.6 297.83 61.8L298.43 64.2C303.71 63 307.31 59.22 307.31 51V24.42C307.31 21.3 304.79 21 302.51 21Z"></path>
                <path class="u-icon__secondary" d="M137.84 73.18V72.78L136.64 72.8C136.02 72.82 135 73.04 134.18 74.8L129.48 85.08L124.6 74.8C123.7 72.92 123.24 72.8 122 72.8H120.8V73.2C121.64 73.2 121.8 73.76 121.8 74.72V84.08C121.8 85.04 121.64 85.6 120.8 85.6V86H123.6V85.6C122.76 85.6 122.6 85.04 122.6 84.08V74.8L127.94 86H129.94L135.04 74.8V84.08C135.04 85.04 134.88 85.6 134.04 85.6V86H137.84V85.6C137 85.6 136.84 85.04 136.84 84.08V74.72C136.84 73.76 137 73.2 137.84 73.18ZM150.302 83.16C150.082 84.84 149.482 85.2 148.522 85.2H143.842V74.72C143.842 73.76 144.002 73.2 144.842 73.2V72.8H141.042V73.2C141.882 73.2 142.042 73.76 142.042 74.72V84.08C142.042 85.04 141.882 85.6 141.042 85.6V86H150.342L150.402 85.6L150.682 83.22L150.302 83.16ZM157.442 72.8H153.642V73.2C154.482 73.2 154.642 73.76 154.642 74.72V86C154.642 87.52 154.442 89.2 153.282 89.6L153.482 90.4C155.242 90 156.442 88.74 156.442 86V74.72C156.442 73.76 156.602 73.2 157.442 73.2V72.8ZM169.908 83.16C169.688 84.84 169.088 85.2 168.128 85.2H163.448V79.7H166.208C167.168 79.7 167.728 79.86 167.728 80.7H168.128V77.9H167.728C167.728 78.74 167.168 78.9 166.208 78.9H163.448V73.6H167.928C168.888 73.6 169.488 73.96 169.708 75.64L170.088 75.58L169.808 73.2L169.748 72.8H160.648V73.2C161.488 73.2 161.648 73.76 161.648 74.72V84.08C161.648 85.04 161.488 85.6 160.648 85.6V86H169.948L170.008 85.6L170.288 83.22L169.908 83.16ZM184.488 73.2L184.428 72.8H173.628L173.568 73.2L173.288 75.58L173.668 75.64C173.888 73.96 174.488 73.6 175.448 73.6H178.128V84.08C178.128 85.04 177.967 85.6 177.128 85.6V86H180.928V85.6C180.088 85.6 179.928 85.04 179.928 84.08V73.6H182.608C183.568 73.6 184.168 73.96 184.388 75.64L184.768 75.58L184.488 73.2Z"></path>
            </svg>


            <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/209/ALH_Odisej_exterior_aerial_07-scaled-1920x0.jpg" alt="">

    
        </div>

        <div id="page2">
            <svg class="u-icon u-icon--shape-1 js-bg-shape-animation-svg" viewBox="0 0 1397 716" fill="none" xmlns="http://www.w3.org/2000/svg">
                <defs>
                    <linearGradient id="shape1" x1="4.00008" y1="341.5" x2="1190.809728" y2="273.628" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#667250"></stop>
                        <stop offset="1" stop-color="#535D41"></stop>
                    </linearGradient>
                </defs>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M843.62 403.193C837.933 360.187 817.505 296.154 699.368 318.557C649.448 328.024 608.465 369.617 564.245 414.495C503.818 475.821 437.347 543.282 333.764 543.282C313.715 543.282 293.819 537.875 274.307 533.916C233.289 525.172 186.156 515.125 153.449 527.101C134.2 534.15 116.867 564.085 96.8711 598.62C72.9566 641.135 45.1672 691.151 0 714.21L0 0H133.984C50.8607 102.09 203.423 242.51 306.5 134.5C330.967 108.862 353.28 65.4195 377.498 18.2695C380.599 12.2306 383.732 6.13089 386.905 0H1341.41C1346.87 24.2232 1349.75 49.4226 1349.75 75.2949C1349.75 114.571 1326.55 146.119 1303.67 177.249C1275.89 215.034 1248.57 252.203 1263.72 301.828C1273.89 335.145 1304.52 350.223 1333.85 364.663C1366.22 380.592 1397 395.745 1397 433.753C1397 506.617 1337.98 565.685 1265.18 565.685C1219.01 565.685 1206.74 576.887 1211.71 600.535C1213.88 610.865 1218.19 616.08 1222.36 621.119C1229.5 630.046 1232.85 638.676 1232.85 650.321C1232.85 686.066 1203.9 715.043 1168.19 715.043C1132.47 715.043 1103.52 686.066 1103.52 650.321C1103.52 624.84 1094.99 624.633 1076.09 624.174C1071.01 624.051 1065.17 623.909 1058.55 623.252C1027.1 620.13 1012.28 607.027 997.247 593.736C976.518 575.411 955.385 556.729 889.73 563.358C854.016 563.358 817.505 544.176 817.505 508.432C817.505 492.535 823.795 478.469 830.28 463.967C838.377 445.861 846.778 427.073 843.62 403.193Z" fill="url(#shape1)"></path>
            </svg>

           

            <div id="text-container">
                
                   <h2>  Set within the</h2>
                   <h2> verdant pine and</h2>
                    <h2> oak tree forest of</h2>
                    <h2> Mljet National Park,</h2>
                     <h2>Hotel Odisej Mljet is</h2>
                     <h2>just two hours by </h2>
                     <h2> passenger or car</h2>
                     <h2> ferry from</h2>
                    <h2>Dubrovnik.</h2>

            </div>


            <svg id="svg2" class="u-icon u-icon--separator-main js-section-separator-main" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg">
                <path d="M-174.61 -157V-116.765C-174.61 15.4344 -112.186 139 -3.49988 139C111 139 138.787 62.2189 249.697 62.2189C360.606 62.2189 356 156.175 533.698 156.175C683 156.175 698.557 75.6322 817.699 62.2189C930.436 49.5265 988.565 138.856 1101.7 138.856C1214.83 138.856 1274.79 62.2189 1385.7 62.2189C1496.61 62.2189 1556.57 138.856 1669.7 138.856C1782.84 138.856 1842.79 62.2189 1953.7 62.2189C2064.61 62.2189 2124.57 138.856 2237.7 138.856C2350.84 138.856 2408.57 62.2188 2521.7 62.2189C2634.84 62.2189 2694.8 138.856 2805.71 138.856C2916.61 138.856 2976.57 62.2189 3089.71 62.2189C3202.84 62.2188 3260.57 138.856 3373.71 138.856C3486.84 138.856 3546.8 62.2189 3657.71 62.2189C3768.62 62.2189 3867.02 222.761 3941.71 108.856C3998.61 22.0779 3941.71 -157 3941.71 -157H-174.61Z"></path>
            </svg>



            <svg id="svg3" class="u-icon u-icon--separator-secondary js-section-separator-secondary" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg">
                <path d="M-196.61 0V21.1232C-196.61 90.5281 -148.913 67.6768 -101.5 115.09C-14.9999 201.59 116.787 115.09 227.697 115.09C338.606 115.09 400.788 152.442 511.698 152.442C622.607 152.442 676.557 122.132 795.699 115.09C908.436 108.426 966.566 155.325 1079.7 155.325C1192.83 155.325 1252.79 115.09 1363.7 115.09C1474.61 115.09 1534.57 155.325 1647.7 155.325C1760.84 155.325 1820.79 115.09 1931.7 115.09C2042.61 115.09 2102.57 155.325 2215.7 155.325C2328.84 155.325 2386.57 115.09 2499.7 115.09C2612.84 115.09 2672.8 155.325 2783.71 155.325C2894.61 155.325 2954.57 115.09 3067.71 115.09C3180.84 115.09 3238.57 155.325 3351.71 155.325C3464.84 155.325 3524.8 115.09 3635.71 115.09C3746.62 115.09 3845.02 185.125 3919.71 125.325C3976.61 79.7659 3919.71 0 3919.71 0H-196.61Z"></path>
                </svg>


        </div>

        <div id="page3">
            <h2>Sweeping view of the  </h2>
            <h2> Adriatic in your Room</h2>

           <div id="section">
            <div id="left">
                <p>Many rooms have balconies that beckon you to <br> breathe in the pure Mediterranean air of the island. <br> All rooms are air conditioned and feature an <br> elegant ensuite bathroom with shower.

                </p>

                <div id="smalltext">
                    <h3>Explore Rooms</h3>
                    <div id="icon">
                        <i class="ri-arrow-right-line"></i>
                    </div>

                </div>

                <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/211/ALH_Odisej_Rosemary_suite_05-scaled-800x0.jpg" alt="">
            </div>
            <div id="right">
                <img  id = "img1"src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/213/ALH_Odisej_deluxe_seaview_balcony_double_01-scaled-800x0.jpg" alt="">



                <img id="img2" src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/215/ALH_Odisej_deluxe_seaview_balcony_double_02-scaled-800x0.jpg" alt="">
            </div>

           </div>
              
        </div>

        <div id="page4">

            <div class="elem">
                <div id="first">
                    <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/560/Classic-room-2-480x0.jpeg" alt="">
                </div>
                <div id="second">
                    <div class="text">
                        <h3>classic room</h3>
                        <p>comfortable room with impressive views</p>


                    </div>

                    <div class="icon">
                        01
                    </div>

                </div>
    
            </div>
            

            <div class="elem">
                <div id="first">
               <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/532/Superior-room-1-480x0.jpeg" alt="">
                </div>
                <div id="second">
                    <div class="text">
                        <h3>superior room</h3>
                        <p>beautifully blue sea views are the centerpiece of <br> every superior room</p>


                    </div>

                    <div class="icon">
                        02
                    </div>

                </div>
    
            </div>


            <div class="elem">
                <div id="first">
                <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/538/Deluxe-room-1-480x0.jpeg" alt="">
                </div>
                <div id="second">
                    <div class="text">
                        <h3>deluxe room</h3>
                        <p>beyond the tree, a mismering view of the, <br> adriatic, draws the eye in a deluxe room</p>


                    </div>

                    <div class="icon">
                        01
                    </div>

                </div>
    
            </div>



            <div class="elem">
                <div id="first">
                    <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/542/Family-room-1-480x0.jpeg" alt="">
                </div>
                <div id="second">
                    <div class="text">
                        <h3>family room</h3>
                         <p>a balcony facing the sea or the rush parkland <br> surrounding the hotel creates  a calming <br>connection with nature in a family room</p>



                    </div>

                    <div class="icon">
                        01
                    </div>

                </div>
    
            </div>


            
            <div class="elem">
                <div id="first">
                  <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/552/Executive-suite-1-480x0.jpeg" alt="">
                </div>
                <div id="second">
                    <div class="text">
                        <h3>executive suite</h3>
                         <p>a glorious Sweeping view of the adrinatic from <br> your private secutiy </p>




                    </div>

                    <div class="icon">
                        01
                    </div>

                </div>
    
            </div>




        </div>


        <div id="page5">
            
            <div class="swiper mySwiper">
                <div class="swiper-wrapper">
                  <div class="swiper-slide">
                    <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/213/ALH_Odisej_deluxe_seaview_balcony_double_01-scaled-2880x0.jpg" alt="">
                  </div>
                  <div class="swiper-slide">
                    <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/211/ALH_Odisej_Rosemary_suite_05-scaled-2880x0.jpg" alt="">
                  </div>
                  <div class="swiper-slide">
                    <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/209/ALH_Odisej_exterior_aerial_07-scaled-2880x0.jpg" alt="">
                  </div>
                  <div class="swiper-slide"></div>
    
                </div>
                <div class="swiper-pagination"></div>
                <div class="swiper-button-prev">
                    <i class="ri-arrow-left-line"></i>
                </div>
                <div class="swiper-button-next">
                    <i class="ri-arrow-right-line"></i>
                </div>
              </div>
        </div>


        <div id="page6">
            <svg id="svgfirst" class="u-icon u-icon--separator-main js-section-separator-main" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg" style="translate: none;  scale: none; transform: translate(-492.667px, 0px);">
                <path d="M-174.61 -157V-116.765C-174.61 15.4344 -112.186 139 -3.49988 139C111 139 138.787 62.2189 249.697 62.2189C360.606 62.2189 356 156.175 533.698 156.175C683 156.175 698.557 75.6322 817.699 62.2189C930.436 49.5265 988.565 138.856 1101.7 138.856C1214.83 138.856 1274.79 62.2189 1385.7 62.2189C1496.61 62.2189 1556.57 138.856 1669.7 138.856C1782.84 138.856 1842.79 62.2189 1953.7 62.2189C2064.61 62.2189 2124.57 138.856 2237.7 138.856C2350.84 138.856 2408.57 62.2188 2521.7 62.2189C2634.84 62.2189 2694.8 138.856 2805.71 138.856C2916.61 138.856 2976.57 62.2189 3089.71 62.2189C3202.84 62.2188 3260.57 138.856 3373.71 138.856C3486.84 138.856 3546.8 62.2189 3657.71 62.2189C3768.62 62.2189 3867.02 222.761 3941.71 108.856C3998.61 22.0779 3941.71 -157 3941.71 -157H-174.61Z"></path>
        </svg>



        <svg  id="svgsecond" class="u-icon u-icon--separator-secondary js-section-separator-secondary" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg" style="translate: none; scale: none; transform: translate(-246.333px, 0px);">
            <path d="M-196.61 0V21.1232C-196.61 90.5281 -148.913 67.6768 -101.5 115.09C-14.9999 201.59 116.787 115.09 227.697 115.09C338.606 115.09 400.788 152.442 511.698 152.442C622.607 152.442 676.557 122.132 795.699 115.09C908.436 108.426 966.566 155.325 1079.7 155.325C1192.83 155.325 1252.79 115.09 1363.7 115.09C1474.61 115.09 1534.57 155.325 1647.7 155.325C1760.84 155.325 1820.79 115.09 1931.7 115.09C2042.61 115.09 2102.57 155.325 2215.7 155.325C2328.84 155.325 2386.57 115.09 2499.7 115.09C2612.84 115.09 2672.8 155.325 2783.71 155.325C2894.61 155.325 2954.57 115.09 3067.71 115.09C3180.84 115.09 3238.57 155.325 3351.71 155.325C3464.84 155.325 3524.8 115.09 3635.71 115.09C3746.62 115.09 3845.02 185.125 3919.71 125.325C3976.61 79.7659 3919.71 0 3919.71 0H-196.61Z"></path>
    </svg>



    <div id="center-text">
        
        <h3>Dining options with </h3>
        <h3>  regional specialities</h3>

            <p id="center-para">A romantic sunset dinner, a quick afternoon snack, a relaxed family  <br>meal – our contemporary restaurants suit most occasions - and all  <br> with spectacular sea views.

            </p>
    </div>

    <div class="image-text" id="first-image-text">
        <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/381/alh1-800x0.jpg" alt="">

        <h3>Restaurant Odisej</h3>

        <p>The picture perfect panorama of Pomena <br> Bay from the terrace draws a steady crowd <br> to Restaurant Odisej. Every day a buffet <br> breakfast is served, while the dinner menu is <br> focused on regional seafood specialities.

        </p>
    </div>

    

    <div class="image-text" id="second-image-text">
       <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/383/alh2-800x0.jpg" alt="">
     
       <h3>Levanat Pizzeria</h3>

      <p>Overlooking the neatly lined boats at the <br> very pretty Pomena marina, Levanat Pizzeria <br> has enchanting views over the crystal-clear <br> Adriatic. Sample from a menu of fresh pizza, <br> lasagne, salads, and other Italian classics, not <br> the least, delicious gelato.</p>

        </p>
    </div>



    <div class="image-text" id="third-image-text">
        <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/383/alh2-800x0.jpg" alt="">
      
        <h3>Vista Mare Beach </h3>
 
       <p>Overlooking the neatly lined boats at the <br> very pretty Pomena marina, Levanat Pizzeria <br> has enchanting views over the crystal-clear <br> Adriatic. Sample from a menu of fresh pizza, <br> lasagne, salads, and other Italian classics, not <br> the least, delicious gelato.</p>
 
         </p>
     </div>

   
    </div>


    <div id="page6-part2">
        <div id="navigate-text">
            <h2>Dining Locations
            </h2>
            <div id="button">
                <i class="ri-arrow-right-line"></i>
            </div>
        </div>



        <svg id="firstsvg" class="u-icon u-icon--separator-main js-section-separator-main" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg" style="translate: none; rotate: none; scale: none; transform: translate(-492.667px, 0px);">
            <path d="M-174.61 -157V-116.765C-174.61 15.4344 -112.186 139 -3.49988 139C111 139 138.787 62.2189 249.697 62.2189C360.606 62.2189 356 156.175 533.698 156.175C683 156.175 698.557 75.6322 817.699 62.2189C930.436 49.5265 988.565 138.856 1101.7 138.856C1214.83 138.856 1274.79 62.2189 1385.7 62.2189C1496.61 62.2189 1556.57 138.856 1669.7 138.856C1782.84 138.856 1842.79 62.2189 1953.7 62.2189C2064.61 62.2189 2124.57 138.856 2237.7 138.856C2350.84 138.856 2408.57 62.2188 2521.7 62.2189C2634.84 62.2189 2694.8 138.856 2805.71 138.856C2916.61 138.856 2976.57 62.2189 3089.71 62.2189C3202.84 62.2188 3260.57 138.856 3373.71 138.856C3486.84 138.856 3546.8 62.2189 3657.71 62.2189C3768.62 62.2189 3867.02 222.761 3941.71 108.856C3998.61 22.0779 3941.71 -157 3941.71 -157H-174.61Z"></path>
    </svg>


    <svg id="secondsvg" class="u-icon u-icon--separator-secondary js-section-separator-secondary" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg" style="translate: none; rotate: none; scale: none; transform: translate(-246.333px, 0px);">
        <path d="M-196.61 0V21.1232C-196.61 90.5281 -148.913 67.6768 -101.5 115.09C-14.9999 201.59 116.787 115.09 227.697 115.09C338.606 115.09 400.788 152.442 511.698 152.442C622.607 152.442 676.557 122.132 795.699 115.09C908.436 108.426 966.566 155.325 1079.7 155.325C1192.83 155.325 1252.79 115.09 1363.7 115.09C1474.61 115.09 1534.57 155.325 1647.7 155.325C1760.84 155.325 1820.79 115.09 1931.7 115.09C2042.61 115.09 2102.57 155.325 2215.7 155.325C2328.84 155.325 2386.57 115.09 2499.7 115.09C2612.84 115.09 2672.8 155.325 2783.71 155.325C2894.61 155.325 2954.57 115.09 3067.71 115.09C3180.84 115.09 3238.57 155.325 3351.71 155.325C3464.84 155.325 3524.8 115.09 3635.71 115.09C3746.62 115.09 3845.02 185.125 3919.71 125.325C3976.61 79.7659 3919.71 0 3919.71 0H-196.61Z"></path>
</svg>
        
    </div>


    <div id="page7">
        <h3>Surrender yourself</h3>
        <h3>to the silent solitude
        </h3>
        <h3>of the wild, or set off</h3>
        <h3>on an adventure</h3>
        <h3>through the lush</h3>
        <h3>forest of the National
        </h3>
        <h3>Park.
        </h3>

    </div>


    <div id="page8">
        <div id="part1" class="part"></div>
        <div id="text-div">
            <h2>Relaxing <br> treatments
            </h2>

            <p>Massage, sauna sessions, beauty treatments such <br> as pedicures and manicures, a fitness room, an <br> outdoor children's pool filled with sea water or a <br> sun terrace to relax on.

            </p>

            <div id="bottom">
                <h3>explore welness</h3>
                <div id="btn"><i class="ri-arrow-right-line"></i></div>
            </div>
        </div>
        <div id="part2" class="part"></div>

    </div>

    <div id="page9">
        <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/394/ALH-Odisej-Lakes-1920x0.jpg" alt="">
        <svg id="svg1" class="u-icon u-icon--separator-main js-section-separator-main" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg" style="translate: none; rotate: none; scale: none; transform: translate(-492.667px, 0px);">
            <path d="M-174.61 -157V-116.765C-174.61 15.4344 -112.186 139 -3.49988 139C111 139 138.787 62.2189 249.697 62.2189C360.606 62.2189 356 156.175 533.698 156.175C683 156.175 698.557 75.6322 817.699 62.2189C930.436 49.5265 988.565 138.856 1101.7 138.856C1214.83 138.856 1274.79 62.2189 1385.7 62.2189C1496.61 62.2189 1556.57 138.856 1669.7 138.856C1782.84 138.856 1842.79 62.2189 1953.7 62.2189C2064.61 62.2189 2124.57 138.856 2237.7 138.856C2350.84 138.856 2408.57 62.2188 2521.7 62.2189C2634.84 62.2189 2694.8 138.856 2805.71 138.856C2916.61 138.856 2976.57 62.2189 3089.71 62.2189C3202.84 62.2188 3260.57 138.856 3373.71 138.856C3486.84 138.856 3546.8 62.2189 3657.71 62.2189C3768.62 62.2189 3867.02 222.761 3941.71 108.856C3998.61 22.0779 3941.71 -157 3941.71 -157H-174.61Z"></path>
    </svg>


    <svg id="svg2" class="u-icon u-icon--separator-main js-section-separator-main" viewBox="0 0 3876 160" xmlns="http://www.w3.org/2000/svg" style="translate: none; rotate: none; scale: none; transform: translate(-492.667px, 0px);">
        <path d="M-174.61 -157V-116.765C-174.61 15.4344 -112.186 139 -3.49988 139C111 139 138.787 62.2189 249.697 62.2189C360.606 62.2189 356 156.175 533.698 156.175C683 156.175 698.557 75.6322 817.699 62.2189C930.436 49.5265 988.565 138.856 1101.7 138.856C1214.83 138.856 1274.79 62.2189 1385.7 62.2189C1496.61 62.2189 1556.57 138.856 1669.7 138.856C1782.84 138.856 1842.79 62.2189 1953.7 62.2189C2064.61 62.2189 2124.57 138.856 2237.7 138.856C2350.84 138.856 2408.57 62.2188 2521.7 62.2189C2634.84 62.2189 2694.8 138.856 2805.71 138.856C2916.61 138.856 2976.57 62.2189 3089.71 62.2189C3202.84 62.2188 3260.57 138.856 3373.71 138.856C3486.84 138.856 3546.8 62.2189 3657.71 62.2189C3768.62 62.2189 3867.02 222.761 3941.71 108.856C3998.61 22.0779 3941.71 -157 3941.71 -157H-174.61Z"></path>
</svg>



    </div>


    <div id="page10">
        
        <div id="text">
            <h3>Oak tree forest of 
            </h3>
        
            <h3>   Mljet National Park    </h3>
        
                <p>Surrounded by the tranquil blue-green waters of the Adriatic, Mljet <br> is Croatia’s greenest and most gloriously untamed island, with much <br> magic to explore and enjoy.
        
                </p>
        </div>


        <div id="images">
            <img class="comman" id="img1" src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/326/ALH_Hotel_Supetar_Cavtat_Pool26-800x0.jpg" alt="">


            <img class="comman"  id="img2" src="
            https://hotelodisej.com/wp-content/uploads/bf-advanced-images/324/ALH_Hotel_Supetar_Cavtat_Pool18-800x0.jpg" alt="">


            <img class="comman" id="img3" src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/322/ALH_Hotel_Supetar_Cavtat_Pool17-800x0.jpg" alt="">
        </div>

        <div class="bottom-navigate">
            <h3>discover mljet</h3>
            <div id="btn">
                <i class="ri-arrow-right-line"></i>
            </div>
        </div>

       
    </div>



    <div id="page11">
          <div id="text11">
            <h3>beyond the hotel</h3>
            <p>Discover the history and uniqueness of Mljet, <br> which goes all the way back to ancient Greece.</p>
          </div>

          <div id="contents">
                <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/399/ALH_Hotel_Supetar_Cavtat_Pool9-800x0.jpg" alt="">

            <div id="textright">
                <h3>A Bead in My Palm
                </h3>
                <p>An exhibition of traditional Croatian <br> beaded jewellery and jewellery making <br> workshop on the island of Mljet

                </p>
                <div id="btn11">
                     <h3>read more</h3>
                     <div id="icon11">
                        <i class="ri-arrow-right-line"></i>
                     </div>
                    </div>
            </div>

          </div>

          <div id="content2">
            <div id="text-left">
                <h3>The Island of <br> Ulysses
                </h3>

                <p>Have you heard about Ulysses, the great  <br>mythical Greek hero and king of Ithaca? <br>According to legends, Odysseus was  <br>shipwrecked on the island of Mljet and lured  <br>by the nymph Calypso into a cave where he  <br>became her hostage.

                </p>


                <div id="btn12">
                    <h3>read more</h3>
                  
                    <div id="icon12">
                        <i class="ri-arrow-right-line"></i>
                    </div>

                </div>
            </div>

            <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/397/ALH_Hotel_Supetar_Cavtat_Pool10-800x0.jpg" alt="">
          </div>
    </div>


    <div id="page12">
        <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/394/ALH-Odisej-Lakes-2880x0.jpg" alt="">

        <div class="overlay-elem">
            <h3>Get back to nature
            </h3>

             <div id="part2">
                <p>Book your stay</p>

                <div id="btn13">
                    <i class="ri-arrow-right-line"></i>
                </div>
             </div>

        </div>
    </div>


 <div id="footerpage">

    <div id="logos">
        <svg class="u-icon u-icon--logo-footer" viewBox="0 0 312 96" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M41.0367 12.6V11.4H29.6367V12.6C32.1567 12.6 32.6367 14.28 32.6367 17.16V27.96H11.0367V17.16C11.0367 14.28 11.5167 12.6 14.0367 12.6V11.4H2.63673V12.6C5.15672 12.6 5.63673 14.28 5.63673 17.16V45.24C5.63673 48.12 5.15672 49.8 2.63673 49.8V51H14.0367V49.8C11.5167 49.8 11.0367 48.12 11.0367 45.24V30.36H32.6367V45.24C32.6367 48.12 32.1567 49.8 29.6367 49.8V51H41.0367V49.8C38.5167 49.8 38.0367 48.12 38.0367 45.24V17.16C38.0367 14.28 38.5167 12.6 41.0367 12.6ZM42.8039 36C42.8039 44.1 47.9039 51.6 57.8039 51.6C67.7039 51.6 72.8039 44.1 72.8039 36C72.8039 27.9 67.7039 20.4 57.8039 20.4C47.9039 20.4 42.8039 27.9 42.8039 36ZM48.2639 37.2C47.3639 29.88 49.3439 23.76 56.1839 22.92C63.0239 22.08 66.4439 27.6 67.3439 34.8C68.2439 42.12 66.2639 48.24 59.4239 49.08C52.5839 49.92 49.1639 44.4 48.2639 37.2ZM88.6922 47.1C88.5722 48.42 88.0322 49.2 86.6522 49.2C84.1322 49.2 83.5922 46.62 83.5922 40.8V23.4H89.0522C90.8522 23.4 90.8522 22.2 90.8522 21H83.5922V11.4H81.1922C81.1922 19.08 78.4922 20.4 74.5922 21V23.4H78.1922V42.24C78.1922 50.22 82.4522 51.6 86.1122 51.6C88.6322 51.6 91.0922 51 92.2922 48.3L88.6922 47.1ZM114.758 41.28C115.358 46.86 112.358 49.2 107.378 49.2C102.038 49.2 97.718 45.12 97.718 37.2V36.24C105.638 38.76 120.518 38.52 120.518 29.22C120.518 23.94 115.958 20.4 108.518 20.4C99.158 20.4 92.318 26.58 92.318 36.78C92.318 45.18 96.698 51.6 107.978 51.6C116.618 51.6 120.758 45.48 120.158 40.08L114.758 41.28ZM108.518 22.8C112.958 22.8 115.118 25.26 115.118 28.56C115.118 34.14 109.778 36.72 97.958 33.72C98.858 27.48 102.218 22.8 108.518 22.8ZM130.104 11.4C130.104 8.1 127.584 7.8 125.304 7.8H121.704V9C124.224 9 124.704 10.68 124.704 13.56V45.24C124.704 48.12 124.224 49.8 121.704 49.8V51H133.104V49.8C130.584 49.8 130.104 48.12 130.104 45.24V11.4ZM149.304 31.2C149.304 42.9 156.504 51.6 168.204 51.6C179.904 51.6 187.104 42.9 187.104 31.2C187.104 19.5 179.904 10.8 168.204 10.8C156.504 10.8 149.304 19.5 149.304 31.2ZM154.824 32.82C153.444 22.02 157.404 14.4 165.384 13.44C174.624 12.3 180.264 18.72 181.584 29.58C182.964 40.38 179.004 48 171.024 48.96C161.784 50.1 156.144 43.68 154.824 32.82ZM190.702 36C190.702 45.84 196.762 51.6 204.802 51.6C209.662 51.6 213.682 48.78 215.302 44.64H215.902V47.4C215.902 50.64 218.842 50.94 220.702 51H224.302V49.8C221.782 49.8 221.302 48.12 221.302 45.24V11.4C221.302 8.1 218.782 7.8 216.502 7.8H212.902V9C215.422 9 215.902 10.68 215.902 13.56V27.36H215.302C213.682 23.22 209.662 20.4 204.802 20.4C196.762 20.4 190.702 26.16 190.702 36ZM196.702 36C196.702 28.86 199.462 22.8 206.002 22.8C212.542 22.8 215.302 28.86 215.302 36C215.302 43.14 212.542 49.2 206.002 49.2C199.462 49.2 196.702 43.14 196.702 36ZM231.989 17.04C233.609 17.04 235.109 15.66 235.109 13.86C235.109 12.24 233.609 10.8 231.989 10.8C230.309 10.8 228.869 12.24 228.869 13.86C228.869 15.66 230.309 17.04 231.989 17.04ZM235.109 24.42C235.109 21.24 233.009 21 230.309 21H226.709V22.2C229.229 22.2 229.709 23.88 229.709 26.76V45.24C229.709 48.12 229.229 49.8 226.709 49.8V51H238.109V49.8C235.589 49.8 235.109 48.12 235.109 45.24V24.42ZM241.095 28.74C241.095 34.68 246.075 35.82 254.055 37.92C258.615 39.36 261.435 39.9 261.435 43.92C261.435 46.98 258.975 49.2 254.535 49.2C249.615 49.2 243.915 47.82 246.315 40.02L240.915 38.82C238.515 48.96 246.495 51.6 254.475 51.6C260.955 51.6 266.835 49.26 266.835 42.66C266.835 36.12 261.375 34.62 254.055 32.7C248.835 31.14 246.495 30.9 246.495 27.18C246.495 25.02 248.355 22.8 253.395 22.8C257.115 22.8 262.215 24.18 259.815 29.58L265.215 30.78C267.615 23.04 260.235 20.4 253.455 20.4C246.375 20.4 241.095 22.74 241.095 28.74ZM291.69 41.28C292.29 46.86 289.29 49.2 284.31 49.2C278.97 49.2 274.65 45.12 274.65 37.2V36.24C282.57 38.76 297.45 38.52 297.45 29.22C297.45 23.94 292.89 20.4 285.45 20.4C276.09 20.4 269.25 26.58 269.25 36.78C269.25 45.18 273.63 51.6 284.91 51.6C293.55 51.6 297.69 45.48 297.09 40.08L291.69 41.28ZM285.45 22.8C289.89 22.8 292.05 25.26 292.05 28.56C292.05 34.14 286.71 36.72 274.89 33.72C275.79 27.48 279.15 22.8 285.45 22.8ZM304.426 17.04C306.046 17.04 307.546 15.66 307.546 13.86C307.546 12.24 306.046 10.8 304.426 10.8C302.746 10.8 301.306 12.24 301.306 13.86C301.306 15.66 302.746 17.04 304.426 17.04ZM302.746 21H299.146V22.2C301.666 22.2 302.146 23.88 302.146 26.76V51C302.146 55.56 301.546 60.6 298.066 61.8L298.666 64.2C303.946 63 307.546 59.22 307.546 51V24.42C307.546 21.3 305.026 21 302.746 21Z" fill="#E3E3C4"></path>
            <path d="M141.158 78.18V77.78L139.958 77.8C139.338 77.82 138.318 78.04 137.498 79.8L132.798 90.08L127.918 79.8C127.018 77.92 126.558 77.8 125.318 77.8H124.118V78.2C124.958 78.2 125.118 78.76 125.118 79.72V89.08C125.118 90.04 124.958 90.6 124.118 90.6V91H126.918V90.6C126.078 90.6 125.918 90.04 125.918 89.08V79.8L131.258 91H133.258L138.358 79.8V89.08C138.358 90.04 138.198 90.6 137.358 90.6V91H141.158V90.6C140.318 90.6 140.158 90.04 140.158 89.08V79.72C140.158 78.76 140.318 78.2 141.158 78.18ZM153.621 88.16C153.401 89.84 152.801 90.2 151.841 90.2H147.161V79.72C147.161 78.76 147.321 78.2 148.161 78.2V77.8H144.361V78.2C145.201 78.2 145.361 78.76 145.361 79.72V89.08C145.361 90.04 145.201 90.6 144.361 90.6V91H153.661L153.721 90.6L154.001 88.22L153.621 88.16ZM160.76 77.8H156.96V78.2C157.8 78.2 157.96 78.76 157.96 79.72V91C157.96 92.52 157.76 94.2 156.6 94.6L156.8 95.4C158.56 95 159.76 93.74 159.76 91V79.72C159.76 78.76 159.92 78.2 160.76 78.2V77.8ZM173.226 88.16C173.006 89.84 172.406 90.2 171.446 90.2H166.766V84.7H169.526C170.486 84.7 171.046 84.86 171.046 85.7H171.446V82.9H171.046C171.046 83.74 170.486 83.9 169.526 83.9H166.766V78.6H171.246C172.206 78.6 172.806 78.96 173.026 80.64L173.406 80.58L173.126 78.2L173.066 77.8H163.966V78.2C164.806 78.2 164.966 78.76 164.966 79.72V89.08C164.966 90.04 164.806 90.6 163.966 90.6V91H173.266L173.326 90.6L173.606 88.22L173.226 88.16ZM187.806 78.2L187.746 77.8H176.946L176.886 78.2L176.606 80.58L176.986 80.64C177.206 78.96 177.806 78.6 178.766 78.6H181.446V89.08C181.446 90.04 181.286 90.6 180.446 90.6V91H184.246V90.6C183.406 90.6 183.246 90.04 183.246 89.08V78.6H185.926C186.886 78.6 187.486 78.96 187.706 80.64L188.086 80.58L187.806 78.2Z" fill="#F7F7EE"></path>
        </svg>


        <img src="https://hotelodisej.com/wp-content/uploads/bf-advanced-images/349/logo-negative-1-1-200x0.png" alt="">
    </div>

    <div class="elem" class="elem1">
        <a href="">
            POMENA 16, 20226, POMENA, CROATIA
            </a>

            <a id="secondtag" href="">RESERVATIONS@ALH.HR
            </a>

            <a href="">+385 20 300 300</a>

    </div>


    <div class="elem2"  class="elem">
        <a href="">
                FACEBOOK
            </a>

            <a href="">INSTAGRAM
            </a>

            <a href="">PINTEREST </a>

    </div>



    <div class="elem3"  class="elem">
        <a href="">
            CONTACT US
            </a>

            <a href="">PRIVACY POLICY AND COOKIES
            </a>



    </div>



    <div class="footer">
        <p>ALH GROUP MEDIA All Rights Reserved</p>
       <p>Design & Developement by BORNFIGHT STUDIO®</p>
    </div>

 </div>

    </div>






  <script src="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.js"></script>


    <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>



<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js" integrity="sha512-16esztaSRplJROstbIIdwX3N97V1+pZvV33ABoG1H2OyTttBxEGkTsoIVsiP1iaTtM8b3+hu2kB6pQ4Clr5yug==" 
crossorigin="anonymous" referrerpolicy="no-referrer"></script>



<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js" integrity="sha512-Ic9xkERjyZ1xgJ5svx3y0u3xrvfT/uPkV99LBwe68xjy/mGtO+4eURHZBW2xW4SZbFrF1Tf090XqB+EVgXnVjw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

    <script src="script.js"></script>
</body>
</html>




*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

@font-face {
    font-family:  regular;
    src: url(./PPWoodland-Regular.ttf);
}

html,body{
    width: 100%;
    height: 100%;
}


body{
    cursor: none;
}
#cursor{
    position: absolute;
    width: 20px;
    height: 20px;
    border-radius: 50px;
    background-color:rgb(54, 33, 33);
    mix-blend-mode: color-burn;
    z-index: 999;
    transition: all cubic-bezier(0.19, 1 , 0.22 , 1) 1s;
    /* transition: all linear 1s; */
}
#main #loader {
    position: absolute;
    width: 100%;
    height: 100vh;
    background-color: #033A56;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #F7F7EE;
    font-family: Poppins;
    font-size: 2vw;
    font-weight: lighter;
    /* z-index: 9999; */
}



#nav{
    width: 100vw;
    /* background-color: red; */
    color: white;
    padding: 35px 55px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: fixed;
    z-index: 999;

}

#nav #part1 {
    width: 5vw;
    height: 2vh;
    /* background-color: royalblue; */
    position: relative;
}
#nav  #part1  .line {
    width:  60%;
    height: 10%;
    /* background-color: black; */
    background-color: #434B34;
    margin-bottom: 5px;
}


#nav #first{
color: #434B34;
background-color: white;
border: none;
border-radius: 50px;
padding: 8px 19px;
font-size: 17px;
text-transform: capitalize;
margin-right: 20px;
border: 1px solid #434B34;
}

#nav #second {
 background-color: #434B34;color: white;
border: none;
border-radius: 50px;
padding: 8px 19px;
font-size: 17px;
text-transform: capitalize;
}
#main{
    position: relative;

}


body{
    overflow-x: hidden;
}


#landingpage{
    width: 100%;
    height: 100vh;
    position: relative;
  /* background-color: red; */
  /* padding-top: 0px; */
  overflow: hidden;
}

#landingpage svg{
    scale:0.22;
    fill: #434B34;
    position: relative;
    bottom: 6.5vw;
    z-index: 99;
    

}


#landingpage img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    position: absolute;
    top: 0%;
    left: 0%;

}



#page2 {
    width: 100%;
    min-height: 190vh;
    background-color: #5F6A4A;
    position: relative;
    overflow: hidden;
    display: flex;
    align-items: top;
    justify-content: center;
    overflow-x: hidden;

}


#page2 svg{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    object-position: center;
}


#page2 #text-container {
    position: absolute;
    z-index: 99;
    text-align: center;
    top: 15%;
}


#text-container h2{
    font-family: regular;
    font-size: 6vw;
    font-weight: 600;
    position: relative;
    line-height: 7vw;
    color: #434B34;

}


#text-container h2 span{
    font-family: regular;
    
}

#page2 #svg2 {
    position: absolute;
    bottom: -45%;
    width: 300vw;
    fill:#5F6A4A;
    z-index: 99;
}


#page2 #svg3{
    position: absolute;
    bottom: -50%;
    left: -50vw;
    width: 300vw;
    fill:#E3E3C4;    

}

#page3 {
    width: 100%;
    min-height: 180vh;
    position: relative;
    background-color: #F7F7EE;
   padding-top: 12vw;
}



#page3 h2 {
    position: relative;
    font-family: regular;
    font-size: 5vw;
    line-height: 5.5vw;
    text-align: center;
    font-weight: 200;
    color: #E3E3C4;


}

#page3 h2 span{
    font-family: regular;

}


#section {
    width: 100%;
    height: 100vh;
    position: relative;
    /* background-color: red; */
    display: flex;
}


#section #left {
    width: 50%;
    height: 100%;
    position: relative;
    /* background-color: green; */
    padding-left: 8vw;
    padding-top: 5vw;

}

#section #left p {
    font-family: regular;
    font-size: 1vw;
    font-family: 800;
    width: 70%;
    opacity: 0;
}


#section h3 {
    font-family: regular;
    color: #5F6A4A;
    font-size: 2vw;
    font-weight: 100;

}

#section #smalltext {
    width: 20vw;
    margin-top: 3vw;
    height: 10vh;
    display: flex;
    align-items: center;
    justify-content:center ;
    gap: 2vw;
    opacity: 0;

  
}
#section #icon 
{
    width: 4vw;
    height: 2vw;
    position: relative;
    background-color: #5F6A4A;
    border-radius: 50px;
    color: #E3E3C4;
   display: flex;
   align-items: center;
   justify-content: center;
}

#icon i {
    font-size: 1.5vw;
    transition: all ease 1s;

}

#smalltext #icon:hover i {
    /* background-color: red; */
    display: none;
    cursor: pointer;

}
#section #right {
    width: 50%;
    height: 100%;
    position: relative;
    /* background-color: orange; */
    
}

#section #left img{
    width: 90%;
    height: 60%;
    object-fit: cover;
    object-position: center;
    border-radius: 30px;
    margin-top: 4vw;
    opacity: 0;
}

#section #right #img1 {
    width: 85%;
    height: 60%;
    object-fit: cover;
    object-position: center;
    border-radius: 30px;
    margin-top: 5vw;
    opacity: 0;
}


#section #right #img2 {
    width: 40%;
    height: 40%;
    object-fit: cover;
    object-position: center;
    border-radius: 30px;
    margin-top: 3vw;
    opacity: 0;
}
#page4 {
    position: relative;
    width: 100%;
    height: 130vh;
    background-color: #F7F7EE;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    
}

#page4 .elem {
    width: 90vw;
    height: 25vh;
    border-bottom: 1px solid #434b34df;
    border-left: 1px solid #434B34;
    border-right: 1px solid #434B34;
    position: relative;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  overflow: hidden;
  opacity: 0;

}


#page4 .elem:nth-child(1){
    border-top: 1px solid #434B34;
    border-left: 1px solid #434B34;
    border-right: 1px solid #434B34;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;

}

#page4 .elem:nth-last-child(1){
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
}

#page4 .elem #first {
    width: 25%;
    height: 100%;
    background-color: rebeccapurple;
    position: absolute;
    left: 0%;
    top: 0%;
   transform: translateX(-100%);
   /* z-index: 9; */
}


#page4 .elem #first img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    transition: all ease .2s;

}


#page4 .elem #second {
    width: 100%;
    height: 100%;
    /* background-color: red; */
    transition: all ease  .3s;    
    color:#5F6A4A;
     /* position: absolute; */
     display: flex;
     align-items: center;
     justify-content: space-between;
     padding: 0 5vw;

}



#page4 .elem:hover #first{
    transform: translateX(0%);

}

#page4 .elem:hover #second {
    width: 75%;
    background-color: #5F6A4A;
    color: #E3E3C4;
    
}


#page4 .elem:hover .icon{
    background-color: white;
    color: #434B34;
    transition: all ease .2s;
}

.elem #second .text  h3 {
    font-size: 2.2vw;
   text-transform: capitalize;
   font-weight: 600;
   font-family: regular;
   transition: all ease .2s;

}

.elem #second .text p {
    font-size: 1vw;
    margin-top: 1.1vw;
    text-transform: capitalize;
    transition: all ease .2s ;

}

.elem #second .icon {
    width: 4vw;
    height: 2vw;
    background-color: #434B34;
    border-radius: 50px;
   display: flex;
   align-items: center;
   justify-content: center;
   color: #E3E3C4;
   font-family: "gilroy";
   font-size: 1.5vw;

}

.elem:hover p{
    color: white;
}


#page5 {
    width: 100%;
    height: 100vh;
    position: relative;
    background-color: #F7F7EE;
}


.swiper {
    width: 100%;
    height: 100%;
  }

  .swiper-slide {
    text-align: center;
    font-size: 18px;
    /* background: #fff; */
    display: flex;
    justify-content: center;
    align-items: center;
    transition: all linear 1s;
  }

  .swiper-slide img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    border-radius: 20px;
    transform: scale(0.5) translateX(-150px)  translateY(160px);
  }


  .swiper-slide {
    width: 75%;
  }

  .swiper-slide:nth-child(4n) {
    width: 20%;
  }

  .swiper-slide-active  img{
    /* background-color: red;/ */
    transform: scale(1) translateX(0px);

  }

  .swiper-slide-active{
padding: 100px 70px;
  }

  .swiper-button-prev{
    background-color: #434B34;
    color:#F7F7EE;
    /* height: 1px; */
    padding: 0px 30px;
    border-radius: 50px;
    color: #F7F7EE;

  }

  .swiper-button-prev::after{
    content: "";
  }

  .swiper-button-prev i {
    color: #F7F7EE;
  }

  .swiper-button-next{
    background-color: #434B34;
    color:#F7F7EE;
    height: 10px;
    padding: 0px 30px;
    border-radius: 50px;
    color: #F7F7EE;
  }

  .swiper-button-next::after{
    content: "";
    display: none;
    
  }


  .swiper-button-next i {
    color: #F7F7EE;
    font-size: 20px;
  }

  
  .swiper-button-prev i {
    color: #F7F7EE;
    font-size: 20px;
  }

  .swiper-button-prev::after{
    content: "";
    display: none;
    
  }


  .swiper-pagination{
    /* background-color: red; */
    font-family: "gilroy";
    font-size: 20px;
     margin-bottom: 6vh; 
     
  }


#page6 {
    width: 100%;
    height: 220vh;
    position: relative;
    background-color:#03364F;
    overflow: hidden;
}


#page6 #svgfirst {
    fill:#F7F7EE;
    transform: rotate(180deg);
    width: 250vw;
    position: absolute;
    z-index: 99;
}


#page6 #svgsecond {
    fill: #03364F;
    width: 300vw;
    z-index: 9;
    top: 0%;
    left: -50vw;

}

#page6 #center-text {
    margin-top: 20vh;
    text-align: center;

}

#center-text h3 {
    color: #043F5D;
    font-size: 5vw;
    font-family: regular;
}


#center-text p {
    color: white;
    font-size: 1.2vw;
    font-family: mediumm;
   margin-top: 40px;
   opacity: 0;
}

#page6 .image-text {

color: #F7F7EE;
margin-left: 5vw;
margin-top: 15vw;
opacity: 0;
}


#page6 .image-text  img{
    width: 330px;
    height: 230px;
    object-fit: cover;
    object-position: center;
    border-radius: 20px;
}

#page6 .image-text h3 {
    font-family:regular;
    font-size: 2.8vw;
    color: #E3E3C4;
    font-weight: 200;
    margin-top: 30px;
}

#page6 .image-text p {
    font-size:1.2vw;
    margin-top: 5px;
    font-family: regular;
}


#page6  #second-image-text {
    margin-left: 45vw;
    position: relative;
    bottom: 27%;

}

#page6  #third-image-text {
    margin-left: 73vw;
    position: relative;
    bottom: 70%;

}


#page6-part2{
    position: relative;
    width: 100%;
    height: 40vh;
    background-color: #03364F;
    display: flex;
    justify-content: center;

}


#page6-part2  #navigate-text{
   
    color: #F7F7EE;
    display: flex;
    align-items: center;
    gap: 30px;
    position: absolute;
    top: 35%;
    opacity: 0;
}

#page6-part2 #navigate-text h2 {
    font-size: 2vw;
    font-family: regular;
    font-weight: 200;
}


#page6-part2 #navigate-text #button{
    width: 55px;
    height: 30px;
    background-color: #F7F7EE;
    border-radius: 50px;
   display: flex;
   justify-content: center;
   align-items: center;
   padding:2px 0px;
   color: black;
}


#page6-part2 #navigate-text #button i {
    font-size: 20px;
}


 #page6-part2 #firstsvg{
    position: absolute;
    width: 300vw;
    top:85%;
    fill:#E3E3C4;
   z-index:9;
   left: 20vw;
} 

#page6-part2 #secondsvg{
    position: absolute;
    z-index: 99;
    width: 300vw;
    top: 65%;
    fill:#03364F;
}


#page7 {
    width: 100%;
    height: 170vh;
    position: relative;
    background-color: #F7F7EE;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
   text-align: center;
}


#page7 h3 {
    color: #434B34;
    font-family: regular;
    font-size: 4.5vw;
    position: relative;
    top: 5%;
    font-weight: 300;
}


#page8{
    width: 100%;
    height: 100vh;
    position: relative;
    background-color: #F7F7EE;
    display: flex;
    align-items: center;

}


#page8  #part1{

    width: 40%;
    height: 70%;
    position: relative;
    /* background-color: red; */
    background-image: url(https://hotelodisej.com/wp-content/uploads/bf-advanced-images/230/ALH_Odisej_outsidepool_01-scaled-480x0.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 25px;

}

#page8 #text-div{
    width: 20%;
    height: 80%;
    position: relative;
    /* background-color: royalblue; */
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    opacity: 0;
    transition: opacity ease .1s;

}

#page8 #text-div h2 {
    font-family: regular;
    font-size: 5vw;
    color: #5F6A4A;
    line-height: 1;
    font-weight: 400;


}

#page8 #text-div p{
    font-size: 18px;
    font-family: gilroy;
    margin: 60px 0px;
    font-weight: 300;

}



#page8 #text-div #bottom {
    display: flex;
    align-items: center;
    gap: 30px;
    margin-top: 100px;
    opacity: 0;
}


#page8 #text-div #bottom h3{
    color:#646A57;
    font-family: regular;
    font-weight: 500;
    text-transform: capitalize;
    font-size: 2vw;

}

#page8 #text-div #bottom #btn{
    background-color: #646A57;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50px;
    padding: 5px 20px;
    color: #F7F7EE;


}
#page8  #part2{

    width: 40%;
    height: 70%;
    position: relative;
    /* background-color: green; */
    background-image: url(https://hotelodisej.com/wp-content/uploads/bf-advanced-images/388/alh-img-2-480x0.jpeg);
    background-size: cover;
    background-position: center;
    border-radius: 25px;

}


#page9{
    width: 100%;
    height: 100vh;
    position: relative;
    /* overflow: hidden; */
}


#page9 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    z-index: 1000;
}

#page9 #svg1 {
    width: 300vw;
    position: absolute;
    bottom: -25%;
    fill: #E3E3C4;
  z-index: 999;
}


/* #page9 #svg2{
    width: 300vw;
    position: absolute;
    bottom: -5%;
    fill:#5B6647;
    z-index: 999;
    display: none;
} */
#page10{
    width: 100%;
    height: 230vh;
    position: relative;
    background-color: #F7F7EE;
    background-color: #5B6647;
    padding: 20vw 30vw;
    text-align: center;
}



#page10 #text {
    display: flex;
    flex-direction: column;
   text-align: center;
}


#page10 #text h3 {
    font-size: 5vw;
    white-space: nowrap;
    color: #434B34;
    font-family: regular;
    font-weight: 100;
    line-height: 1.2;
}


#page10 #text p {
    color:#F7F7EE;
    margin-top: 80px;
    font-size: 20px;
    opacity: 0;
}


#page10 #images {
    display: flex;
    justify-content: center;
    align-items: end;
    gap: 30px;
    position: relative;
    margin-top: 100px;
}

#page10 #images #img1 {
    width: 400px;
    height: 400px;
    object-fit: cover;
    object-position: center;
    border-radius: 20px;
    opacity: 0;

}


#page10 #images #img2 {
    width: 500px;
    height: 700px;
    object-fit: cover;
    object-position: center;
    border-radius: 20px;
    opacity: 0;
}


#page10 #images #img3 {
    width: 400px;
    height:400px;
    object-fit: cover;
    object-position: center;
    border-radius: 20px;
    position: relative;
    bottom: 300px;
    left: 10px;
    opacity: 0;
}


#page10 #images .comman{
    transition: all linear .5s;
}



#page10 .bottom-navigate {
display: flex;
align-items: center;
justify-content: center;
gap: 30px;
position: absolute;
bottom: 8%;
left: 50%;
transform: translateX(-50%);
opacity: 0;
transform: all linear .3s;

}

#page10 .bottom-navigate h3 {
    font-size: 1.7vw;
    text-transform: capitalize;
    font-family: Poppins;
    font-weight: 300;
    color: #F7F7EE;
    
}


#page10 .bottom-navigate #btn{
    background-color: #F7F7EE;
    width: 50px;
    height: 25px;
    border-radius: 50px;
    color: #5F6A4A;
    display: flex;
    align-content: center;
    justify-content: center;
    
}

#page10 .bottom-navigate #btn i {
    font-size: 20px;
    position: relative;
    top: 2px;
    font-weight: bold;
}



#page11 {
    width: 100%;
    height: 255vh;
    position: relative;
    background-color: #F7F7EE;
}



#text11 {
   position: absolute;
   top: 13%;
   left: 50%;
   transform: translate(-50%,-50%);
   text-align: center;
}


#text11 h3 {
    font-size: 5vw;
    text-transform: capitalize;
    color: #434B34;
    font-family: regular;
    font-weight: 200;
    opacity: 0;

}

#text11 p {
    font-size: 1vw;
    font-family: regular;
    margin-top: 20px;
    opacity: 0;
}

#page11 #contents {
    width: 100%;
    display: flex;
    position: relative;
    top: 550px;
    align-items: center;
    /* justify-content: space-between; */
    padding: 0vw 50px;
    gap: 300px;
}


#page11 img{
    width: 40%;
    height: 600px;
    object-fit: cover;
    object-position:top;
    border-radius: 16px;
    opacity: 0;
}

#page11 #contents #textright h3{
    
    color: #434B34;
    font-family: regular;
    font-size: 2.5vw;
    font-weight: 200;
    opacity: 0;
}

#page11 #contents #textright p {
    font-size: 1vw;
    color: #434B34;
    font-family: regular;
    margin-top: 30px;
    opacity: 0;
}


#page11 #contents #textright #btn11  {
    display: flex;
     gap: 30px;
    align-items: center; 
    /* justify-content: center;   */
    margin-top: 35px;
    opacity: 0;
}

#page11 #contents #textright #btn11 h3 {
    color: #5B6647;
    font-family: regular;
    font-size: 1.7vw;
    text-transform: capitalize;
}


#page11 #contents #textright #btn11 #icon11{
    margin-bottom: 35px;
}
#page11 #contents #textright #btn11 i{
    background-color: #434B34;
    border-radius: 50px;
    padding: 5px 20px;
   color:#F7F7EE;
   transition: all line cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

#page11 #contents #textright #btn11 i:hover{
    color: black;
}


#page11 #content2{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content:flex-end;
    gap: 300px;
    position: relative;
    top: 30%;
    padding: 0vw 50px;

}

#page11 #content2 img{
        width: 40%;
        height: 600px;
        object-fit: cover;
        object-position:top;
        border-radius: 16px;
       opacity: 0;
}


#page11 #content2 #text-left h3 {
    color: #434B34;
    font-size: 2.8vw;
    font-family: regula;
    font-weight: 300;
    opacity: 0;
}


#page11 #content2 #text-left p {
    color: #434B34;
    font-family: regular;
    font-weight: 200;
    margin-top: 20px;
   opacity: 0;
}

#page11 #content2 #text-left #btn12{
    display: flex;
    align-items: center;
    /* justify-content: center; */
    gap: 30px;
    margin-top: 35px;
    opacity: 0;
    height: 100px;
}

#page11 #content2 #text-left #btn12 h3 {
    font-size: 1.6vw;
    font-family: regular;
    text-transform: capitalize;
    font-weight:500;
    opacity: 0;
}


#page11 #content2 #text-left #btn12 #icon12 {
    display: flex;
    align-content: center;
    background-color: #434B34;
    border-radius: 50px;
    padding: 5px 20px;
    color: #F7F7EE;
    margin-bottom: 33px;
}



#page12 {
    width: 100%;
    height: 110vh;
    position: relative;
    overflow: hidden;
    background-color: #F7F7EE;

}

#page12 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
}



#page12 .overlay-elem{
    width: 90%;
    height: 25%;
    position: absolute;
    background-color:#5B6647;
    bottom: 10%;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 20px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    opacity: 0;
}

#page12 .overlay-elem h3 {
    font-size: 4vw;
    color: #E3E3C4;
    font-family: regular;
    font-weight: 200;
}


.overlay-elem #part2 {
    display: flex;
    gap: 30px;
    align-items: center;
}

.overlay-elem #part2 p {
    color: #F7F7EE;
    font-size: 1.4vw;
    /* text-transform: capitalize; */
    font-family:Poppins;
}

.overlay-elem #part2 #btn13 {
    background-color: #F7F7EE;
    color:#434B34;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50px;
    padding: 5px 20px;
    border: none;
}


.overlay-elem #part2 #btn13 i {
    font-size: 20px;
}




#footerpage{
    width: 100%;
    height: 100vh;
    position: relative;
    background-color:#033A56;
    padding-top: 5vw ;
    padding-right: 4vw;
}



#footerpage #logos{
    position: relative;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-end;
   /* background-color: red; */
   height: 20%;
   margin-bottom: 50px;

}

#footerpage svg{
    scale: 0.2;
}

#footerpage #logos img{
    height: 50px;
}




#footerpage .elem{
    width: 95%;
    height: 10%;
    /* background-color: red; */
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    border-bottom: 1px solid #226c91c6;
    display: flex;
    justify-content: space-between;
    padding: 0px 6px;
    padding-top: 33px;
}

#footerpage .elem a {
    text-decoration: none;
    color: #F7F7EE;
    font-size: 20px;
    text-transform: uppercase;
    font-family: Poppins;
}


#footerpage .elem #secondtag{
    /* background-color: red; */
    position: relative;
    right: 65px;
}

#footerpage .elem2{
    /* background-color: red; */
    margin-top: 200px;
    width: 95%;
    height: 10%;
    /* background-color: red; */
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    border-bottom: 1px solid #226c91c6;
    display: flex;
    justify-content: space-between;
    padding: 0px 6px;
    padding-top: 33px;
}


#footerpage .elem2 a {
    text-decoration: none;
    color: #F7F7EE;
    font-size: 20px;
    text-transform: uppercase;
    font-family: Poppins;
}



#footerpage  .elem3{
      /* background-color: red; */
      margin-top: 240px;
      width: 95%;
      height: 10%;
      /* background-color: red; */
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      /* border-bottom: 1px solid #226c91c6; */
      display: flex;
      justify-content: flex-start;
      gap: 450px;
      padding: 0px 6px;
      padding-top: 50px;
}

#footerpage .elem3 a {
    text-decoration: none;
    color: #F7F7EE;
    font-size: 20px;
    text-transform: uppercase;
    font-family: Poppins;
}


#footerpage .footer {
    width: 100%;
    position: absolute;
    bottom: 3%;
    display:flex;
    justify-content: space-between;
    padding: 0px 45px;
}

#footerpage .footer p {
    color: #F7F7EE ;
    font-family: Poppins;
    font-size: 12px;
    opacity: .8;
    
}




function loader() {
    var a = 0;
    setInterval(function () {
        a = a + Math.floor(Math.random() * 20);
        if (a < 100) {
            document.querySelector("#main #loader  h1").innerHTML = a + "%";
        }

        else {
            a = 100;
            document.querySelector("#main #loader  h1 ").innerHTML = a + "%";
        }

    }, 200)
}

loader();

var load = gsap.timeline();

load.to("#loader h1", {
    scale: 2,
    onstart: loader(),
    ease: Power3,
})


load.to("#loader ", {
    transform: "translateY(-100vh)",
    ease: Power3,
    delay: 2,
    backgroundColor: "#5F6A4A",

})


function locomotive(){
    gsap.registerPlugin(ScrollTrigger);

// Using Locomotive Scroll from Locomotive https://github.com/locomotivemtl/locomotive-scroll

const locoScroll = new LocomotiveScroll({
  el: document.querySelector("#main"),
  smooth: true
});
// each time Locomotive Scroll updates, tell ScrollTrigger to update too (sync positioning)
locoScroll.on("scroll", ScrollTrigger.update);

// tell ScrollTrigger to use these proxy methods for the ".smooth-scroll" element since Locomotive Scroll is hijacking things
ScrollTrigger.scrollerProxy("#main", {
  scrollTop(value) {
    return arguments.length ? locoScroll.scrollTo(value, 0, 0) : locoScroll.scroll.instance.scroll.y;
  }, // we don't have to define a scrollLeft because we're only scrolling vertically.
  getBoundingClientRect() {
    return {top: 0, left: 0, width: window.innerWidth, height: window.innerHeight};
  },
  // LocomotiveScroll handles things completely differently on mobile devices - it doesn't even transform the container at all! So to get the correct behavior and avoid jitters, we should pin things with position: fixed on mobile. We sense it by checking to see if there's a transform applied to the container (the LocomotiveScroll-controlled element).
  pinType: document.querySelector("#main").style.transform ? "transform" : "fixed"
});



// each time the window updates, we should refresh ScrollTrigger and then update LocomotiveScroll. 
ScrollTrigger.addEventListener("refresh", () => locoScroll.update());

// after everything is set up, refresh() ScrollTrigger and update LocomotiveScroll because padding may have been added for pinning, etc.
ScrollTrigger.refresh();

}

locomotive();

function page1animation() {

    // var tl = gsap.timeline()

    load.from("#landingpage svg", {
        opacity: 0,
        y: -50,
        duration: .5,
    })


    load.from("#landingpage img", {
        scale: 0.4,
        duration: .7,
        ease: Power2.easeIn,
        delay: -1,
    })


    load.from("body  #nav ", {
        opacity: 0,
        y: -50,
        duration: .7,
        delay: -.1,
        ease: Power2.easeOut,

    })
}

function page2animation() {
    var h2 = document.querySelectorAll("#page2 #text-container h2");
    h2.forEach(function (elem) {
        var textdata = elem.textContent;


        var splittedtext = textdata.split("")
        var clutter = "";

        splittedtext.forEach(function (val) {
            clutter += `<span>${val}</span>`

        });

        elem.innerHTML = clutter;
    })

    gsap.to("#page2 #text-container h2 span ", {
        color: "#E3E3C4",
        stagger: .1,
        duration: .2,
        ease: Power2.easeIn,


        scrollTrigger: {
            trigger: "#text-container h2 span ",
            scroller: "#main",
            // markers :true,
            start: "top 25%",
            end: "top 5%",
            scrub: 4,
        }
    })

    gsap.to("#page2 #svg2, #page2 #svg3", {
        transform: "translateX(-100vw)",
        duration: 0.3,
        ease: Power4,

        scrollTrigger: {
            trigger: "#page2",
            scroller: "#main",
            scrub: 5,
        }

    })
}

function page3animation() {
    var h2 = document.querySelectorAll("#page3 h2");
    h2.forEach(function (elem) {
        var textdata = elem.textContent;


        var splittedtext = textdata.split("")
        var clutter = "";

        splittedtext.forEach(function (val) {
            clutter += `<span>${val}</span>`

        });

        elem.innerHTML = clutter;
    })


    gsap.to("#page3 h2 span", {

        color: "#434B34",
        stagger: .1,
        duration: .2,
        ease: Power2.easeIn,

        scrollTrigger: {
            trigger: "#page3 h2 span",
            scroller: "#main",
            scrub: 2,
        }

    })


    var tl2 = gsap.timeline(
        {
            scrollTrigger: {
                trigger: "#section #left ",
                scroller: "body",
                // markers:true,
                start: "top 10%",
                end: "top 0%",
                scrub: 3,

            }
        }
    );

    tl2.to("#section #left p ", {
        opacity: 1,
        y: -10,
        ease: Power2.easeIn,


    }, 'a')


    tl2.to("#section #left #smalltext ", {
        opacity: 1,
        y: -10,
        ease: Power2.easeIn,
    })


    tl2.to("#section #left img", {
        opacity: 1,
        y: -20,
        ease: Power2.easeIn,
    }, 'b')



    tl2.to("#section #right #img1", {
        opacity: 1,
        y: -20,
        ease: Power2.easeIn,
        stagger: .2,
    }, 'a')


    tl2.to(" #section #right #img2", {
        opacity: 1,
        y: -20,
        ease: Power2.easeIn,
        stagger: .2,
    }, 'b')
}

function page4animation() {

    gsap.to("#page4 .elem", {
        opacity: 1,
        y: -30,
        stagger: .1,


        scrollTrigger: {
            trigger: "#page4 .elem",
            scroller: "#main",
            // markers:true,
            start: "top 5%",
            end: "top -5%",
            scrub: 3,

        }

    })

}

page1animation();
page2animation();
page3animation();
page4animation();


(function page5swiper() {
    var swiper = new Swiper(".mySwiper", {
        slidesPerView: "1.4",
        pagination: {
            el: ".swiper-pagination",
            //   clickable: true,
            type: "fraction",
        },

        navigation: {
            nextEl: ".swiper-button-next",
            prevEl: ".swiper-button-prev",
        },
    });
})()




function page6animation() {
    gsap.to("#page6 #svgfirst, #page6 #svgsecond", {
        left: "-100vw",
        duration: 1,
        ease: Power3,
        stagger: .1,

        scrollTrigger: {
            trigger: "#page6",
            scroller: "#main",
            // markers : true,
            start: "top 50%",
            end: "top 15%",
            scrub: 5,
        }
    })



    var data = document.querySelectorAll("#page6 h3");
    data.forEach(function (elem) {
        var textdata = elem.textContent;
        var splittedtext = textdata.split("")
        var clutter = "";

        splittedtext.forEach(function (val) {
            clutter += `<span>${val}</span>`

        });


        elem.innerHTML = clutter;
    })


    var tl = gsap.timeline();
    tl.to("#page6 h3 span", {
        color: "#E3E3C4",
        stagger: .1,
        ease: Power4,

        scrollTrigger: {
            trigger: "#page6 h3 span ",
            scroller: "#main",
            // markers :true,
            start: "top 25%",
            end: "top 5%",
            scrub: 4,
        }

    })


    tl.to("#page6 #center-para ", {

        y: 30,
        stagger: 1,
        opacity: 1,
        duration: 0.5,
        ease: Expo.ease,
        scrollTrigger: {
            trigger: "#page6 #center-text p  ",
            scroller: "#main",
            // markers:true,
            start: "top 25%",
            end: "top 0%",
            scrub: 2,
        }

    })



    tl.to("#page6 #first-image-text ", {
        opacity: 1,
        duration: 0.5,
        y: 30,
        ease: Power3,



        scrollTrigger: {
            trigger: "#page6 #first-image-text ",
            scroller: "#main",
            scrub: 3,
        }

    }, 't')


    tl.to("#page6 #second-image-text ", {
        opacity: 1,
        duration: 0.5,
        y: 30,
        ease: Power3,

        scrollTrigger: {
            trigger: "#page6  #second-image-text",
            scroller: "#main",
            scrub: 3,
        }

    }, 't')



    tl.to("#page6 #third-image-text ", {
        opacity: 1,
        duration: 0.5,
        y: 30,
        ease: Power3,


        scrollTrigger: {
            trigger: "#page6 #third-image-text  ",
            scroller: "#main",
            scrub: 3,

        }

    }, 't')


    tl.to("#page6-part2 #navigate-text", {
        opacity: 1,
        y: -30,
        duration: 1,
        ease: Power3,
        yoyo: true,
        repeat: -1,

    })
}
page6animation()





function page6part2animate() {


    gsap.to("#page6-part2 #firstsvg, #page6-part2 #secondsvg", {
        transform: "translateX(-100vw)",
        duration: 1,
        ease: Power3.easeIn,

        scrollTrigger: {
            trigger: "#page6-part2",
            scroller: "#main",
            // markers:true,
            start: "top 45%",
            end: "top 15%",
            scrub: 3,
        }
    })
}

page6part2animate()




function page7animate() {
    var data = document.querySelectorAll("#page7 h3");
    data.forEach(function (elem) {
        var textdata = elem.textContent;
        var splittedtext = textdata.split("")
        var clutter = "";

        splittedtext.forEach(function (val) {
            clutter += `<span>${val}</span>`

        });

        elem.innerHTML = clutter;
    })


    var tl = gsap.timeline();
    tl.to("#page7 h3 span", {
        color: "#E3E3C4",
        stagger: .1,
        ease: Power4,

        scrollTrigger: {
            trigger: "#page7 h3 span ",
            scroller: "#main",
            // markers :true,
            start: "top 25%",
            end: "top 5%",
            scrub: 4,
        }

    })
}

page7animate()



function page8animation() {
    var tl8 = gsap.timeline({
        scrollTrigger: {
            trigger: "#page8",
            scroller: "#main",
            // markers:true,
            start: "top 25%",
            end: "top -5%",
            // pin:true,
            scrub: 4,

        }
    });
    tl8.to("#page8 #part1", {
        transform: "translateX(-30%)",
        duration: .5,
        ease: Power3,

    }, 'n')


        .to("#page8 #part2", {
            transform: "translateX(30%)",
            duration: .5,
            ease: Power3,
        }, 'n')

        .to("#page8 #text-div", {
            width: "40%",
            duration: .5,
            ease: Power3,
            opacity: 1,

        }, 'n')


        .to("#page8 #text-div #bottom", {
            y: -30,
            opacity: 1,
            duration: .5,
            ease: Power2,

        })

}
page8animation()



function page9animate() {

    gsap.to("#page9 #svg1 , #pqge9 #svg2", {
        transform: "translateX(-100vw)",
        duration: 1,
        ease: Power3,
        stagger: .1,

        scrollTrigger: {
            trigger: "#page9",
            scroller: "#main",
            start: "bottom 50%",
            end: "bottom 0%",
            scrub: 3,

        }
    })
}

page9animate()





function page10animate() {
    var data = document.querySelectorAll("#page10 #text h3");
    data.forEach(function (elem) {
        var textdata = elem.textContent;
        var splittedtext = textdata.split("")
        var clutter = "";

        splittedtext.forEach(function (val) {
            clutter += `<span>${val}</span>`

        });

        elem.innerHTML = clutter;
    })


    var tl = gsap.timeline(
        {
            scrollTrigger: {
                trigger: "#page10 #text h3 span ",
                scroller: "#main",
                // markers :true,
                start: "top 40%",
                end: "top 20%",
                scrub: 4,
            }
        }
    );
    tl.to("#page10 #text h3 span", {
        color: "#E3E3C4",
        stagger: .1,
        ease: Power4,


    })


    tl.to("#page10 #text p ", {
        opacity: 1,
        y: -50,
        duration: 1,
        ease: Power3,

    })



    tl.to("#page10 #images #img3 ", {
        y: 10,
        opacity: 1,
        ease: Power3,
        duration: .5

    })


    tl.to(" #page10 #images #img2 ", {
        y: 10,
        opacity: 1,
        ease: Power3,
        duration: .5,
    })



    tl.to(" #page10 #images #img1 ", {
        y: 20,
        opacity: 1,
        ease: Power3,
        duration: .5,
    })


    tl.to(".bottom-navigate", {
        opacity: 1,
        y: -20,
        duration: 0.5,
        ease: Power3,
    })



}
page10animate()




function page11animation() {



    var tl11 = gsap.timeline();

    tl11.to("#text11 h3, #text11 p", {
        opacity: 1,
        duration: .5,
        ease: Power3,
        y: -35,
        stagger: .1,
        scrollTrigger: {
            trigger: "#text11",
            scroller: "#main",
            // markers :true,
            start: "top 15%",
            end: "top 0",
            scrub: 3,
        }

    })

        .to("#contents img", {
            opacity: 1,
            duration: .5,
            ease: Power3,
            y: -35,



            scrollTrigger: {
                trigger: "#contents img",
                scroller: "#main",
                // markers :true,
                start: "top 20%",
                end: "top 5%",
                scrub: 3,
            }

        }, 'r')

        .to("#contents #textright h3, #contents #textright p, #contents  #textright #btn11", {

            opacity: 1,
            duration: .5,
            ease: Power3,
            y: -20,
            stagger: .1,



            scrollTrigger: {
                trigger: "#textright",
                scroller: "#main",
                // markers :true,
                start: "top 20%",
                end: "top 5%",
                scrub: 3,
            }

        }, 'r')


        .to("#content2 img", {
            opacity: 1,
            duration: .5,
            ease: Power3,
            y: -35,



            scrollTrigger: {
                trigger: "#content2 img",
                scroller: "#main",
                // markers :true,
                start: "top 35%",
                end: "top 10%",
                scrub: 3,
            }
        }, 'm')

        .to("#content2 #text-left h3, #content2 #text-left p, #content2  #text-left #btn12", {

            opacity: 1,
            duration: .5,
            ease: Power3,
            y: -20,
            stagger: .1,


            scrollTrigger: {
                trigger: "#content2 img",
                scroller: "#main",
                // markers :true,
                start: "top 35%",
                end: "top 10%",
                scrub: 3,
            }

        }, 'm')
}
page11animation();



function page12() {
    gsap.to("#page12 .overlay-elem", {
        opacity: 1,
        y: "-30",
        ease: Power4,


        scrollTrigger: {
            trigger: ".overlay-elem",
            scroller: "#main",
            // markers :true,
            start: "bottom 110%",
            end: "top 40%",
            scrub: 3,

        }
    })
}
page12();




function cursormove(){
    var cursor = document.querySelector("#cursor");
var body = document.querySelector("body");

body.addEventListener("mousemove", function(dets){

    cursor.style.top   = dets.clientY + "px";
    cursor.style.left   = dets.clientX + "px";

})


}
cursormove();




function scollmousewheeleventhandling(){
    
    document.addEventListener("wheel", function(dets){

        if(dets.offsetY > 600){
           if(dets.deltaY > 0){
               gsap.to("#nav", {
                   opacity : 0,
                   ease:Power3,
       
               })
           }
        }
   
       if(dets.deltaY < 0){
           gsap.to("#nav", {
               opacity:1,
               backgroundColor : "F7F7EE",
               ease:Power3,
           })
       }
   
   })
}

scollmousewheeleventhandling();




