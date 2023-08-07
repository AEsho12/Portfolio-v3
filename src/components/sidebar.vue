<!-- eslint-disable vue/multi-word-component-names -->

<script setup lang="ts">
import { Icon } from '@iconify/vue';



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
                        <p>Computer Science Student at the<span class="liverpool"> University of Liverpool</span> </p>

                    </div>
                    <div class="navbar">
                        <div class="tech-stack">Tech Stack<span class="arrow">
                                <Icon icon="mdi:arrow-up" width="15" height="30" :rotate="1" />
                            </span></div>
                        <div class="icons">
                            <Icon icon="logos:javascript" width="30" height="30" />
                            <Icon icon="devicon:java-wordmark" width="30" height="30" />
                            <Icon icon="devicon:typescript" width="30" height="30" />
                            <Icon icon="skill-icons:react-dark" width="30" height="30" />
                            <Icon icon="logos:mysql" width="30" height="30" />
                            <Icon icon="ph:file-sql" width="30" height="30" />
                            <Icon icon="devicon:postgresql" width="30" height="30" />
                            <Icon icon="devicon:python" width="30" height="30" />
                            <Icon icon="devicon:tailwindcss" width="30" height="30" />
                            <Icon icon="logos:bootstrap" width="30" height="30" />
                            <Icon icon="devicon:git" width="30" height="30" />
                            <Icon icon="devicon:html5" width="30" height="30" />
                            <Icon icon="skill-icons:vuejs-dark" width="30" height="30" />
                            <Icon icon="skill-icons:nextjs-dark" width="30" height="30" />
                            <Icon icon="skill-icons:spring-dark" width="30" height="30" />
                        </div>
                        <div class="socials">
                            <a href="https://github.com/AEsho12"  target="_blank" >
                                <Icon icon="mdi:github" width="30" height="30" class="github" />
                            </a>
                            <a  href="https://www.linkedin.com/in/ayo-esho-5279a31bb/"  target="_blank" >
                                <Icon icon="line-md:linkedin" width="30" height="30" class="linkedin" />
                            </a>
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


.main-container {
    z-index: 100;

    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    line-height: 1.625;

    padding: 0 24px;
    top: 0;
}
a{
    background-color: #0f182d;
    color: rgb(148 163 184/var(--tw-text-opacity));
    text-decoration: none;
}
a:hover{
    background-color: #0f182d;
    text-decoration: none;
}

.liverpool:hover {
    color: white;
    transition: .6s;
    cursor: pointer;

}

.arrow {
    position: relative;
    top: 10px;
    left: 8px;
    cursor: pointer;
    color: rgb(100 116 139/var(--tw-text-opacity));
}

.tech-stack:hover {
    color: white;

    .arrow:hover {
        position: relative;
        left: 18px;
        transition: .6s;
        color: white;
    }

}

.title-container {
    color: rgb(226 232 240/var(--tw-text-opacity));
    letter-spacing: -.025em;
    line-height: 3.5rem;
    font-family: "Helvetica" var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    margin-bottom: 1.5rem;
}

.icons {
    display: flex;
    gap: 10px;
    margin-bottom: 4rem;
    width: 400px;

}

.socials {
    display: flex;
    gap: 10px;
    position: relative;
    bottom: 0rem;
    margin-bottom: 4rem;

}

.github {
    transition: .6s;
    cursor: pointer;
}

.linkedin {
    transition: .6s;
    cursor: pointer;
}

.github:hover {
    transform: translate(0, -10px);
    color: white;
}

.linkedin:hover {
    transform: translate(0, -10px);
    color: white;
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

.long {
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

}

.short1:hover {
    width: 10.6rem;
    transition: ease-in-out;
}

.short2:hover {
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

    .socials {
        position: relative;
        bottom: -120px;
    }
}



@media (min-width: 650px) {
    .info-container {
        padding-right: 0;
    }

}</style>
