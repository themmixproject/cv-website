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
            afgerond bij VMI Care, Clappform, DAT.Mobility en het Flevoziekenhuis.
            HAVO diploma behaald in juni 2017. Internationaal georiënteerd en
            cultureel bewust door jeugd in VS, VK en Singapore.
        </p>
    </div>
    <div id="experience-container">
        <h1>Experience</h1>
        <hr/>
        <experience-content>
            <template v-slot:experience-name>Junior .NET Developer</template>
            <template v-slot:experience-company>Capgemini</template>
            <template v-slot:experience-location>Utrecht</template>
            <template v-slot:experience-duration>Oct. 2022 - Nov. 2022</template>
        </experience-content>
        <experience-content>
            <template v-slot:experience-name>Stagiar C# Ontwikkelaar</template>
            <template v-slot:experience-company>VMI Care</template>
            <template v-slot:experience-location>Almere</template>
            <template v-slot:experience-duration>Feb. 2022 - Jul. 2022</template>
        </experience-content>
        <experience-content>
            <template v-slot:experience-name>Stagiair Vue.js Ontwikkelaar</template>
            <template v-slot:experience-company>Clappform</template>
            <template v-slot:experience-location>Amstelveen</template>
            <template v-slot:experience-duration>Sept. 2021 - Jan. 2022</template>
        </experience-content>
        <experience-content>
            <template v-slot:experience-name>Stagiair C# Ontwikkelaar</template>
            <template v-slot:experience-company>VMI Care</template>
            <template v-slot:experience-location>Almere</template>
            <template v-slot:experience-duration>Jan. 2020 - Jun. 2020</template>
        </experience-content>
        <experience-content>
            <template v-slot:experience-name>Stagiair ICT Afdeling</template>
            <template v-slot:experience-company>Flevoziekenhuis</template>
            <template v-slot:experience-location>Almere</template>
            <template v-slot:experience-duration>Sept. 2021 - Jan. 2022</template>
        </experience-content>
    </div>
</template>

<script>
import experienceContent from "./ExperienceContent.vue";

export default {
    components: {
        experienceContent
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
    padding : 20px;
    background-color: lightgray;
    border-radius: 20px;
    margin: 20px;

    #profile-paragraph {
        font-size: 2em;
        font-weight: bold;
    }

}

#experience-container{
    margin: 20px;
}
</style>
