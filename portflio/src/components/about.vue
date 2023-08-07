<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">


</script>
    

<template>
    <!-- Main Container -->
    <section id="section1">
    <div class="main-container">
        <!-- About Container -->
        <div class="about-container" id="about">
            <div class="about-title">About</div>
            <div>
                <p class="about">
                    I'm a dedicated student at the University of Liverpool, pursuing my degree in Computer Science with a focus on Software Development. Throughout my academic journey, I've had the pleasure of exploring a diverse range of modules that cover various exciting aspects of the field, including Object-Oriented Programming, Software Engineering, Data Structures, and Algorithms, among others. </p>
                <p class="about">Programming has always been my driving force and remains a true passion of mine. I find immense joy in dedicating countless hours to the creation and design of systems, even during my leisure time.</p>
                <p class="about">When I'm not engrossed in code, I absolutely cherish every opportunity to watch football matches alongside my beloved family and friends. It's a shared experience that brings us all closer together and fills my heart with happiness.</p>
            </div>
        </div>

    </div>
</section>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
    border: none;
}

.main-container {
    z-index: 100;
    font-family: var(--font-inter),ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    line-height: 1.625;
    transition-property: all;
    transition-timing-function: cubic-bezier(.4,0,.2,1);
    transition-duration: .15s;
    


}
.about-container{
    display: grid;
    position: relative;
}
.about-title{
    display: none;
  
    
}

p {

    margin-top: 1rem;
    letter-spacing: .025em;
    font-weight: 600;
    line-height: inherit;
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
}


.about {
    padding-right: 1.5rem;
    z-index: 20;

}
@media (min-width: 768px) {
    .main-container{
        gap: 1rem;
        
    }
}
@media (min-width: 640px) {
    .main-container{
        grid-template-columns:  repeat(8,minmax(0,1fr)); ;
        
    }
}
@media (max-width: 1025px) {
    .about-title {
        
        
        line-height: 1.625;
        --tw-bg-opacity: 1;
        text-transform: uppercase;
        display: block;
        font-size: small;
        font-weight: 700;
        color: white;
    }

}
@media (min-width: 1025px) {
    .about-container {
        position: relative;
        bottom: 570px;
        left: 600px;
        width: 550px;
    }
}
</style>
