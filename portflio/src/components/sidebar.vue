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
                        <p>Computer Science Student at the University of liverpool </p>
                        
                    </div>
                    <div class="navbar">
                        <nav>
                            <li><a>About</a></li>
                            <li><a>Experience</a></li>
                            <li><a>Project</a></li>
                        </nav>
                    </div>
                    <!-- icons Container -->
                    <div class="icons-container">

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


.main-container {
    z-index: 100;
    top: 150px;
    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    line-height: 1.625;

}

.title-container {
    color: rgb(226 232 240/var(--tw-text-opacity));
    letter-spacing: -.025em;
    line-height: 2.5rem;
    font-family: "Helvetica" var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    margin-bottom: 1.5rem;
    

}

h1 {
    font-weight: 700;
    font-size: 40px;
}


p {
    max-width: 20rem;
    line-height: 1.5;
    margin-top: 1rem;
    color: rgb(100 116 139/var(--tw-text-opacity));
    letter-spacing: .025em;
    font-weight: 600;
}

.navbar {
    display: none;
    text-decoration: none;
    list-style-type: none;
    
    position: relative;
    top: 100px;
}

.info-container {
    display: flex;
    gap: 4px;
    margin-top: 1rem;
    
    --font-inter: "__inter_20b187","__inter_Fallback_20b187";
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    line-height: 1.5;
    max-width: 20rem;
}

.liverpool:hover {
    color: #44b879;
    background-color: #1c393e;
    cursor: pointer;
}

@media (min-width: 1024px) {
    .main-container {
        padding-top: 6rem;
        padding-bottom: 6rem;
        justify-content: space-between;
 
        max-height: 100vh;
        top: 0;
        position: sticky;
    }
}

@media (min-width: 1025px) {
    .navbar {
        display: block;
        font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
        font-feature-settings: "ss03", "cv02", "cv11";
        --font-inter: "__inter_20b187", "__inter_Fallback_20b187";
        --tw-text-opacity: 1;
        color: rgb(148 163 184/var(--tw-text-opacity));
        line-height: 1.625;
        --tw-bg-opacity: 1;
        cursor: pointer;
    }

}
@media (min-width: 650px) {
    .info-container {
        padding-right: 0;    
}
}
</style>
