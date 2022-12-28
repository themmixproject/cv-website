<template>
    <div class="experience-container">
        <div>
            <h2 class="experience-title">
                <slot name="experience-name"></slot>
            </h2>
        </div>
        <div>
            <slot name="experience-company"></slot>
        </div>
        <div>
            <slot name="experience-location"></slot>
        </div>
        <div>
            <slot name="experience-duration"></slot>
        </div>
        <hr/>
    </div>
</template>
