
<div id="about-section">

    <h1 id="about">ABOUT</h1>

    <div class="lists">

        <div class="free-time">
            <h5>HOW I BECAME A DEVELOPER</h5>
            <hr>
            <p>
                After it became obvious that I didn't want to remain an electrician, I had to decide what my future career path should look like. Even in
                my childhood, I loved to design, tinker and create new things. I really wanted to integrate this passion into my professional life.
                Nevertheless, it was important to me not to lose the technical aspect. The iCompetence degree course at the University of Applied Sciences
                Switzerland was the perfect choice for me. This broad-based computer science program has a special focus on design and
                thus gave me the opportunity to develop my creative streak further while at the same time satisfying my technical interest. Thanks to
                the focus on practical work in this education, I have, even though I am fresh out of school, gained quite a bit of experience in various projects.
            </p>
        </div>

        <div class="skills">
            <h5>WHAT I LIKE TO DO</h5>
            <hr>
            <span class="badge_about">UI/UX DESIGN</span>
            <span class="badge_about">EXTENDED REALITY</span>
            <span class="badge_about">MOBILE APPS</span>
            <span class="badge_about">GRAPHIC DESIGN</span>
            <span class="badge_about">3D MODELLING</span>
        </div>
    </div>
</div>

<style>
    hr {
        border-top: 1px solid #A9E5BB;
        border-radius: 20px;
        opacity: 0.3;
        margin-top: 3vh;
        margin-bottom: 3vh;
    }
    @media (min-width: 768px) {
        h1 {
            line-height: 1.1;
            font-family: 'Josefin Sans', sans-serif;
            font-size: 6vw;
            font-weight: 200;
            color: #d85a31;
        }

        h5 {
            line-height: 1.1;
            font-family: 'Josefin Sans', sans-serif;
            font-size: 2vw;
            font-weight: 200;
            color: #d85a31;
            margin-bottom: 0;
            margin-top: 0;
        }

        #about-section {
            position: relative;
            margin-bottom: 15vw;
        }

        .badge_about {
            display: inline-block;
            padding: 10px;
            background-color: #e15b38;
            color: #1d1c36;
            border-radius: 10px;
            margin: 5px;
            font-size: 1em;
        }

        .lists {
            position: relative;
            display: flex;
            width: 100%;
            gap: 10vw;
        }

        .free-time {
            position: relative;
            width: 90vw;
            text-align: left;
        }

        .skills {
            position: relative;
        }
    }

    @media (max-width: 767px) {
        h1 {
            line-height: 1.1;
            font-family: 'Josefin Sans', sans-serif;
            font-size: 3em;
            font-weight: 200;
            color: #d85a31;
        }
        h5{
            text-align: center;
            line-height: 1.1;
            font-family: 'Josefin Sans', sans-serif;
            font-size: 1.5em;
            font-weight: 200;
            color: #d85a31;
            margin-bottom: 0;
            margin-top: 0;
        }
        #about-section{
            margin-bottom: 15vw;
        }
        .badge_about{
            display: inline-block;
            padding: 8px;
            background-color: #e15b38;
            color: #1d1c36;
            border-radius: 8px;
            margin: 5px;
            font-size: 1em;
        }
        .lists{
            left: 5%;
        }
        .free-time{
            text-align: left;
            margin-bottom: 15svh;
        }
        .skills{
            position: relative;
            text-align: center;
            margin-bottom: 15svh;
        }
    }
</style>
