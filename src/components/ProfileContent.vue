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
