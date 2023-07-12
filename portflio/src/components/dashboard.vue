<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">


</script>
    

<template>
    <!-- Main Container -->
    <div class="main-container">
        <div ClassName="sidebar">
            <div ClassName="content-wrapper">
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
                <!-- About Container -->
                <div class="about-container">
                    <div>
                        <h4 class="about">ABOUT</h4>
                    </div>
                    <div>
                        <p2 class="about">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi sint eligendi
                            consectetur
                            laborum nihil recusandae quo corrupti, debitis repellendus odio.</p2>
                    </div>
                </div>
            </div>
        </div>

        <!-- Experience Container -->
        <div class="experience-container">
            <div class="experience-colum ">
                <div class="experience-title">
                    EXPERIENCE
                </div>
                <div class="timeline">
                    <div class="present">
                        JULY - PRESENT
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
                        2020 - 2024  
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
                        Summer 2022
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
                        2017 - 2020
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

.sidebar {
    width: 50%;
    margin: 20px;
}

.sidebar .content-wrapper {
    height: 200px;
    width: 200px;
    margin-bottom: 20px;

}

.main-container {
    margin: 40px;
}

.title-container {
    color: rgb(226 232 240/var(--tw-text-opacity));
    letter-spacing: -.025em;
    line-height: 2.5rem;
    font-family: "Helvetica" var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
}

h1 {
    font-weight: 700;
    font-size: 40px;
}

h2 {
    font-weight: 700;
    font-size: 20px;
}

p {
    max-width: 20rem;
    line-height: 1.5;
    margin-top: 1rem;
    color: rgb(100 116 139/var(--tw-text-opacity));
    letter-spacing: .025em;
    font-weight: 600;
}

h4 {
    margin-top: 100px;
    font-weight: 700;
    font-size: 12px;
}

.about {
    padding-top: 1.25rem;
    padding-bottom: 1.25rem;

    padding-right: 1.5rem;

    margin-bottom: 1rem;

    z-index: 20;
}
.experience-title{
    padding-top: 4.25rem;
}
.timeline{
    column-count: 1;
    
}
.colum{
    display: inline-flex;
    margin: 20px;
    

}
.content{
    margin-left: 8.5rem; 
    margin-bottom: 3.5rem;
}
</style>
