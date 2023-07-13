<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">


</script>
    

<template>
    <!-- Main Container -->
    <div class="main-container">
        <!-- About Container -->
        <div class="about-container">
            <div>
                <p class="about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi sint eligendi consectetur laborum nihil recusandae quo corrupti, debitis repellendus odio.</p>
                <p class="about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi sint eligendi consectetur laborum nihil recusandae quo corrupti, debitis repellendus odio.</p>
                <p class="about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi sint eligendi consectetur laborum nihil recusandae quo corrupti, debitis repellendus odio.</p>
            </div>
        </div>

    </div>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
    border: none;
}

.main-container {
    margin: 40px;

}
.about-container{
    position: relative;
    left: 600px;
    bottom: 200px;
}

p {

    margin-top: 1rem;
    color: rgb(100 116 139/var(--tw-text-opacity));
    letter-spacing: .025em;
    font-weight: 600;
}


.about {
    padding-right: 1.5rem;
    z-index: 20;
}
</style>
