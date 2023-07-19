<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">


</script>
    

<template>
    <!-- Main Container -->
    <div class="main-container">
        <!-- Experience Container -->
        <div class="experience-container">
            <div class="experience-colum ">
                <div class="experience-title">
                    experience
                </div>
                <div class="timeline">
                    <div class="present">
                        <div class="date">
                            JULY - PRESENT
                        </div>
                        
                        <div class="colum">
                            <div class="risidio">   
                                <div class="content">
                                    <h2>Frontend Developer - Risidio</h2>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus voluptatum nesciunt sit voluptates mollitia. Omnis, accusantium. Ad repellat sequi distinctio?</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="present">
                        <div class="date">
                            2020 - 2024 
                        </div>
                        
                        <div class="colum">
                            <div class="university">   
                                <div class="content">
                                    <h2>Computer Science W/ Software Development - University of Liverpool</h2>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus voluptatum nesciunt sit voluptates mollitia. Omnis, accusantium. Ad repellat sequi distinctio?</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="present">
                        <div class="date">
                            Summer 2022
                        </div>
                        
                        <div class="colum">
                            <div class="risidio">   
                                <div class="content">
                                    <h2>Software Specialism - QA BootCamp</h2>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus voluptatum nesciunt sit voluptates mollitia. Omnis, accusantium. Ad repellat sequi distinctio?</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="present">
                        <div class="date">
                            2017 - 2020
                        </div>
                        <div class="colum">
                            <div class="risidio">   
                                <div class="content">
                                    <h2>Information Technology - Palmers College</h2>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus voluptatum nesciunt sit voluptates mollitia. Omnis, accusantium. Ad repellat sequi distinctio?</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
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



.experience-container{
    display: block;
    font-family: var(--font-inter),ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-feature-settings: "ss03","cv02","cv11";
    -webkit-font-smoothing: antialiased;
    line-height: 1.625;
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    -tw-bg-opacity: 1;
    transition-property: all;
    transition-timing-function: cubic-bezier(.4,0,.2,1);
    transition-duration: .15s;
    padding-bottom: 0.25rem;
    margin-top: 3.2rem;
}
@media (min-width: 1025px) {
    .experience-container {
        position: relative;
        bottom: 370px;
        left: 600px;
    }
}
.experience-title{
    display: none;
}

.date{
    text-transform: uppercase;
    letter-spacing: .025em;
    --tw-text-opacity: 1;
    color: rgb(100 116 139/var(--tw-text-opacity));
    font-weight: 600;
    font-size: .75rem;
    line-height: 1rem;
    margin-top: 1.25rem;
    margin-bottom: 2.5rem;
    z-index: 10;
    -webkit-font-smoothing: antialiased;
    font-family: var(--font-inter),ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-feature-settings: "ss03","cv02","cv11";
    
}
.present{
    padding: 5px;
}

.present:hover{
    background-color: rgba(30,41,59,.5);
    box-shadow: var(--tw-ring-offset-shadow,0 0 #0000),var(--tw-ring-shadow,0 0 #0000),var(--tw-shadow);
    filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
    border-radius: .375rem;
    --tw-shadow: inset 0 1px 0 0 rgba(148,163,184,.1);
    --tw-shadow-colored: inset 0 1px 0 0 var(--tw-shadow-color);
    --tw-drop-shadow: drop-shadow(0 10px 8px rgba(0,0,0,.04)) drop-shadow(0 4px 3px rgba(0,0,0,.1));
    cursor: pointer;
    
}



h2 {
    font-weight: 500;
    font-size: 20px;
    position: relative;
    top: -30px;
    text-align: -webkit-match-parent;
    --tw-text-opacity: 1;
    color: rgb(226 232 240/var(--tw-text-opacity));
    line-height: 1.375;
    margin: 0;
    font-size: inherit;
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    
}

p {
    line-height: 1.5;
    font-size: .875rem;
    margin-top: 0.5rem;
    margin: 0;
    text-align: -webkit-match-parent;
    list-style: none;
    font-family: var(--font-inter),ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-feature-settings: "ss03","cv02","cv11";
}



.content{
    transition-property: all;
    transition-timing-function: cubic-bezier(.4,0,.2,1);
    transition-duration: .15s;
    padding-bottom: 4.25rem;
    display: grid;
    position: relative;
    font-family: var(--font-inter),ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-feature-settings: "ss03","cv02","cv11";
    padding: 5px;
}
@media (max-width: 1025px) {
    .experience-title {
        
        
        line-height: 1.625;
        --tw-bg-opacity: 1;
        text-transform: uppercase;
        display: block;
        font-size: small;
        font-weight: 700;
        color: white;
        margin-bottom: 1.2rem;
    }
}

</style>
