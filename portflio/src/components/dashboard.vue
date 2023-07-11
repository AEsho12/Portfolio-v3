<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
    
</script>

<template>
    <!-- Main Container -->
    <div class="main-container">
        <!-- title Container -->
        <div class="title-container">
            <!-- Heading-text Container -->
            <div class="heading-container">
                <h1>Ayo Esho</h1>
            </div>
            <!-- subtitle text Container -->
            <div class="subtitle-container">
                <h2>Developer</h2>
            </div>
            <!-- info Container -->
            <div class="info-container">
                <p>Computer Science Student at the University of Liverpool</p>
            </div>
            <!-- icons Container -->
            <div class="icons-container">
                
            </div> 
        </div>
        <!-- AboutContainer -->
        <div class="about-container">
            <div> 
                <h4 class="about">ABOUT</h4>
            </div> 
            <div> 
                <p2 class="about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi sint eligendi consectetur laborum nihil recusandae quo corrupti, debitis repellendus odio.</p2>
            </div>    
        </div>
        
    </div>
</template>

<style scoped>
*{
    margin: 0;
    padding: 0;
    border: none;
}

.main-container {
    margin: 40px;
}
.title-container{
    color: rgb(226 232 240/var(--tw-text-opacity));
    letter-spacing: -.025em;
    line-height: 2.5rem;
    font-family: "Helvetica"var(--font-inter),ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-feature-settings: "ss03","cv02","cv11";
}
h1{
    font-weight: 700;
    font-size: 40px;
}
h2{
    font-weight: 700;
    font-size: 20px;
}
p{
    max-width: 20rem;
    line-height: 1.5;
    margin-top: 1rem;
}
h4 {
    margin-top: 100px;
    font-weight: 700;
    font-size: 12px;
}

</style>
