<template>
    <div id="welcome-container">
        <img
            id="profile-image"
            src="https://via.placeholder.com/500png?text=Profile+Picture"
            alt="Profile Picture"
        />
        <div id="welcome-header-container">
            <h1>Hi, I'm Steven</h1>
        </div>
    </div>
    <div id="profile-paragraph-container">
        <p id="profile-paragraph">
            BSc. Informatie- en Communicatietechnologie (ICT) behaald aan de
            Hogeschool Windesheim in Almere in juli 2022. Vijf stages succesvol
            afgerond bij VMI Care, Clappform, DAT.Mobility en het
            Flevoziekenhuis. HAVO diploma behaald in juni 2017. Internationaal
            georiënteerd en cultureel bewust door jeugd in VS, VK en Singapore.
        </p>
    </div>
    <div id="experience-container">
        <h1>Experience</h1>
        <hr />
        <job-content
            name="Junior .NET Developer"
            company="Capgemini"
            location="Utrecht"
            duration="Oct. 2022 - Nov. 2022"
        >
        </job-content>
        <job-content
            name="Stagiar C# Ontwikkelaar"
            company="VMI Care"
            location="Almere"
            duration="Oct. 2022 - Nov. 2022"
        >
        </job-content>
        <job-content
            name="Stagiar Vue.js Ontwikkelar"
            company="Clappform"
            location="Amstelveen"
            duration="Sept. 2021 - Jan. 2021"
        >
        </job-content>
        <job-content
            name="Stagiar Angular Ontwikkelaar"
            company="DAT.Mobility"
            location="Deventer"
            duration="Sept. 2020 - Jun. 2020"
        >
        </job-content>
        <job-content
            name="Stagiar C# Ontwikkelaar"
            company="VMI Care"
            location="Almere"
            duration="Sept. 2020 - Jun. 2020"
        >
        </job-content>
        <job-content
            name="Stagiar ICT Afdeling"
            company="Flevoziekenhuis"
            location="Almere"
            duration="Sept. 2019 - Jan. 2020"
        >
        </job-content>
    </div>
    <div id="education-container">
        <h1>Education</h1>
        <hr />
        <job-content
            name="BSc. Informatie- en Communicatietechnologie (ICT)"
            company="Hogeschool Windesheim"
            location="Almere"
            duration="Sept. 2018 - 2022"
        ></job-content>
        <job-content
            name="Minor Inleiding in de Toegepaste Psychologie"
            company="Hogeschool Utrecht"
            location="Utrecht"
            duration="Feb. 2021 - Jul. 2021"
        ></job-content>
        <job-content
            name="MBO Niveau 4 Applicatie Ontwikkelaar"
            company="ICT Campus"
            location="Hilversum"
            duration="Sept. 2012 - Jul. 2017"
        ></job-content>
        <job-content
            name="HAVO Natuur \& Techniek"
            company="Alberdink Thijm College"
            location="Hilversum"
            duration="Sept. 2012 - Jul. 2017"
        ></job-content>
    </div>
    <div id="project-container">
        <h1>Projecten</h1>
        <h2>BSc. Informatie- en Communicatietechnologie (ICT</h2>
        <ul>
            <li>
                Applicatie voor fietsenwinkels waarin bijgehouden kan worden
                welke fietsen in welke winkels op voorraad zijn (C\# .NET)
            </li>
            <li>
                Administrative applicatie voor een studentenhuis waarin de
                gebruikers\\kunnen aangeven welk voorwerp is toegekend aan welke
                bewoner\\(PHP Laravel)
            </li>
            <li>
                Chat-applicatie met verschillende kanalen voor
                ICT-gerelateerde\\onderwerpen (PHP Laravel)
            </li>
            <li>item Webshop voor CD's en LP's (PHP Lumen)</li>
            <li>
                Quiz website waar de gebruiker een quiz over HTML, CSS en
                Javascript kan doen (HTML/CSS/Javascript)
            </li>
        </ul>

        <h2>MBO Niveau 4 Applicatie Ontwikkelaar</h2>
        <ul>
            <li>
                Games website gemaakt met Pac Man, Pong, Flappy Bird, Tetris en
                Memory (HTML/CSS/Javascript)
            </li>
        </ul>
    </div>
</template>

<script>
import JobContent from "./JobContent.vue";

export default {
    components: {
        JobContent
    }
};
</script>

<style lang="scss" scoped>
#welcome-container {
    margin: 20px;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;

    border: 2px solid black;
    padding: 5px;

    #welcome-header-container {
        display: flex;
        flex-direction: column;
        justify-content: center;

        h1 {
            font-size: 2em;
        }
    }
    #profile-image {
        width: 10em;
    }
}

#profile-paragraph-container {
    padding: 20px;
    background-color: lightgray;
    border-radius: 20px;
    margin: 20px;

    #profile-paragraph {
        font-size: 2em;
        font-weight: bold;
    }
}

#experience-container {
    margin: 20px;
}
</style>
