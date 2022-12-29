<template>
    <div class="experience-container">
        <div>
            <h2 class="experience-title">
                {{ name }}
            </h2>
        </div>
        <div>
            {{ company }}
        </div>
        <div>
            {{ location }}
        </div>
        <div>
            {{ duration }}
        </div>
        <hr />
    </div>
</template>

<script>
export default {
    props: ["name", "company", "location", "duration"]
};
</script>
