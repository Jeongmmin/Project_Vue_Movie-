<template>
    <router-link to="/" class="logo"> <span>JMDbAPI</span>.COM </router-link>
</template>

<style lang="scss" scoped>
@import "../scss/main";
.logo {
    font-family: "Oswald", sans-serif;
    font-size: 20px;
    color: $black;
    text-decoration: none;
    &:hover {
        color: $black;
    }
    span {
        color: $primary;
    }
}
</style>