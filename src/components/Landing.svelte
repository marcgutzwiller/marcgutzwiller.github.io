
<div id="landing-focus">
    <p id="marc">MARC</p>
    <br>
    <p id="gutzwiller">GUTZWILLER</p>
    <br>
    <p id="creative-developer">Creative Developer</p>
    <div class="icon-scroll"></div>
</div>

<style>

    @media (min-width: 768px) {
        #landing-focus {
            position: absolute;
            top: 5vh;
            height: 90vh;
            width: 75vw;
            left: 11.5vw;
            border-radius: 20px;
            background: linear-gradient(rgba(61, 70, 99, 0.1), rgba(29, 28, 54, 0.1));
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-top: 2px solid rgba(148, 165, 217, 0.3);
            border-left: 2px solid rgba(148, 165, 217, 0.3);
            box-shadow: 20px 20px 20px rgba(9, 9, 9, 0.1);

        }

        #marc {
            position: inherit;
            font-family: 'Josefin Sans', sans-serif;
            font-weight: 700;
            color: #d85a31;
            font-size: 8vw;
            top: 8vw;
            left: 7%;
        }

        #gutzwiller {
            position: inherit;
            font-family: 'Josefin Sans', sans-serif;
            font-weight: 700;
            z-index: 2;
            color: #e35b38;
            font-size: 8vw;
            top: 13.7vw;
            left: 11.74%;
        }

        #creative-developer {
            position: inherit;
            font-family: 'Josefin Sans', sans-serif;
            font-weight: 70;
            z-index: 2;
            color: #e15b38;
            font-size: 4vw;
            top: 26vw;
            left: 16%;
        }

        .icon-scroll,
        .icon-scroll:before {
            position: absolute;
            left: 50%;
            bottom: 2vw;
        }
        .icon-scroll {
            width: 2vw;
            height: 4vw;
            box-shadow: inset 0 0 0 3px rgba(57, 57, 57, 0.8);
            border-radius: 25px;
        }
        .icon-scroll:before {
            content: '';
            width: 1vw;
            height: 1vw;
            background: rgb(207, 89, 42);
            margin-left: -0.5vw;
            top: 0.5vw;
            border-radius: 50%;
            animation-duration: 1.5s;
            animation-iteration-count: infinite;
            animation-name: scroll;
        }
        @keyframes scroll {
            0% {
                opacity: 1;
            }
            100% {
                opacity: 0;
                transform: translateY(2vw);
            }
        }
    }


/*smaller than 768px **************************************************************************************************/
    @media (max-width: 767px) {

        #landing-focus {
            writing-mode: vertical-lr;
            text-orientation: upright;

            position: absolute;
            top: 5svh;
            height: 90svh;
            width: 90%;
            left: 5%;
            border-radius: 10px;
            background: linear-gradient(rgba(61, 70, 99, 0.1), rgba(29, 28, 54, 0.1));
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-top: 1px solid rgba(148, 165, 217, 0.3);
            border-left: 1px solid rgba(148, 165, 217, 0.3);
            box-shadow: 10px 10px 10px rgba(9, 9, 9, 0.3);
        }

        #marc {
            position: inherit;
            font-family: 'Josefin Sans', sans-serif;
            font-weight: 700;
            color: #d85a31;
            font-size: 2.5em;
            top: 50px;
            left: 30px;
        }

        #gutzwiller {
            position: inherit;
            font-family: 'Josefin Sans', sans-serif;
            font-weight: 700;
            z-index: 2;
            color: #e35b38;
            font-size: 2.5em;
            top: 50px;
            left: 70px;
        }

        #creative-developer {
            position: inherit;
            font-family: 'Josefin Sans', sans-serif;
            font-weight: 70;
            z-index: 2;
            color: #e15b38;
            font-size: 1.5em;
            top: 50px;
            left: 160px;
        }

        .icon-scroll,
        .icon-scroll:before {
            position: absolute;
            left: 50%;
            bottom: 2vw;
        }

        .icon-scroll {
            width: 2vw;
            height: 4vw;
            box-shadow: inset 0 0 0 3px rgba(57, 57, 57, 0.8);
            border-radius: 25px;
        }

        .icon-scroll:before {
            content: '';
            width: 1vw;
            height: 1vw;
            background: rgb(207, 89, 42);
            margin-left: -0.5vw;
            top: 0.5vw;
            border-radius: 50%;
            animation-duration: 1.5s;
            animation-iteration-count: infinite;
            animation-name: scroll;
        }

        @keyframes scroll {
            0% {
                opacity: 1;
            }
            100% {
                opacity: 0;
                transform: translateY(2vw);
            }
        }
    }
    hr {
        border-top: 1px solid #A9E5BB;
        border-radius: 20px;
        opacity: 0.3;
    }
</style>
