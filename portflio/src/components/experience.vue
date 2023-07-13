<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">


</script>
    

<template>
    <!-- Main Container -->
    <div class="main-container">
        <!-- Experience Container -->
        <div class="experience-container">
            <div class="experience-colum ">
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


.experience-container{
    position: relative;
    left: 630px;
    top: -30px;
}
.present{
   padding: 20px;
}

.present:hover{
    background-color: rgba(30,41,59,.5);
    box-shadow: var(--tw-ring-offset-shadow,0 0 #0000),var(--tw-ring-shadow,0 0 #0000),var(--tw-shadow);
    filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
    border-radius: .375rem;
    --tw-shadow: inset 0 1px 0 0 rgba(148,163,184,.1);
    --tw-shadow-colored: inset 0 1px 0 0 var(--tw-shadow-color);
    --tw-drop-shadow: drop-shadow(0 10px 8px rgba(0,0,0,.04)) drop-shadow(0 4px 3px rgba(0,0,0,.1));


   
}



h2 {
    font-weight: 700;
    font-size: 20px;
    position: relative;
    top: -30px;
}

p {
    max-width: 20rem;
    line-height: 1.5;
    margin-top: 1rem;
    color: rgb(100 116 139/var(--tw-text-opacity));
    letter-spacing: .025em;
    font-weight: 600;
    position: relative;
    top: -30px;
}



.content{
    margin-left: 8.5rem; 
    margin-bottom: 4.5rem;
    
}
</style>
