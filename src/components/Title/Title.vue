<template>
    <span class="subtitle">{{ title }}</span>
</template>

<script>
    export default {

        props:{
            title: {
                type: String,
                required: true
            }
        }
        
    }
</script>

<style>
.subtitle{
    font-size: 1.2em;
    color: var(--primary-color);
    font-weight: 500;
    font-family: var(--primary-font);
}

@media (max-width: 550px) {
    .subtitle{
        font-size: 24px;
        max-width: 121px;
    }
}
</style>