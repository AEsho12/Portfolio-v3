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
                        <div class="short1" href="#about">
                            <div class="border-short1" ></div>
                            <div class="nav-about">About</div>
                        </div>
                        <div class="long" href="#experience">
                            <div class="border-long"></div>
                            <div class="nav-experience ">Experience</div>
                        </div>
                        <div class="short2">
                            <div class="border-short2"></div>
                            <div class="nav-projects">Project</div>
                        </div>
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

    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    line-height: 1.625;

    padding: 0 24px;
    top: 0;
}

.title-container {
    color: rgb(226 232 240/var(--tw-text-opacity));
    letter-spacing: -.025em;
    line-height: 3.5rem;
    font-family: "Helvetica" var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    margin-bottom: 1.5rem;



}

h1 {
    font-weight: 700;
    font-size: 50px;
}

.short1 {
    display: flex;
    width: 100px;
}
.short2 {
    display: flex;
    width: 100px;
}
.long{
    display: flex;
}


.border-long {
    width: 50px;
    background-color: white;
    height: 1px;
    position: relative;
    top: 10px;
    margin-right: 20px;
}


.border-short1 {
    width: 50px;
    background-color: white;
    height: 1px;
    position: relative;
    top: 10px;
    margin-right: 20px;
}
.border-short2 {
    width: 50px;
    background-color: white;
    height: 1px;
    position: relative;
    top: 10px;
    margin-right: 20px;

}.short1:hover{
    width:  10.6rem;
    transition: ease-in-out;
}
.short2:hover{
    width: 10.6rem;
    transition: ease-in-out;
}

p {
    max-width: 20rem;
    line-height: 1.5;
    margin-top: 1rem;
    color: rgb(100 116 139/var(--tw-text-opacity));
    letter-spacing: .025em;
    font-weight: 600;
    position: relative;
    bottom: 30px;
}

.navbar {
    display: none;
    text-decoration: none;
    list-style-type: none;
    position: relative;
    top: 30px;
    text-transform: uppercase;
    color: rgb(100 116 139/var(--tw-text-opacity));
    font-size: small;
    letter-spacing: 1.3px;
}

.nav-about {
    margin-bottom: 10px;
    font-weight: 700;
}

.nav-experience {
    margin-bottom: 10px;
    font-weight: 700;
}

.nav-projects {
    margin-bottom: 10px;
    font-weight: 700;
}


.nav-about:hover {
    color: white;
    text-decoration: none;
}

.nav-experience:hover {
    color: white;
    text-decoration: none;
}

.nav-projects:hover {
    color: white;
    text-decoration: none;
}


.info-container {
    display: flex;
    gap: 4px;
    margin-top: 1rem;

    --font-inter: "__inter_20b187", "__inter_Fallback_20b187";
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    line-height: 1.5;
    max-width: 20rem;
}


@media (min-width: 1024px) {
    .main-container {
        padding-top: 6rem;
        padding-bottom: 6rem;
        justify-content: space-between;

        max-height: 100vh;
        top: 0;
        position: sticky;
        margin-left: 40px;
    }
}



@media (min-width: 650px) {
    .info-container {
        padding-right: 0;
    }
}
</style>
