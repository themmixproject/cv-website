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
</template>

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
</style>
