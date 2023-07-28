<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">


</script>
    

<template>
    <!-- Main Container -->
    <div class="main-container">
        <!-- Experience Container -->
        <div class="experience-container " id="projects">
            <div class="experience-colum ">
                <div class="experience-title">
                    projects
                </div>
                <div class="timeline">
                    <div class="present">
                        <div class="date">
                            Frontend
                            <div class="tech-items">Live View</div>
                            <div class="tech-items">Code</div>
                        </div>

                        <div class="colum">
                            <div class="risidio">
                                <div class="content">
                                    <h2>Space Rocks</h2>
                                    <p>A web based game implemented with JavaScript. The game consists of three
                                        stages, setup, play and end. During the play stage the game proceeds in rounds. The
                                        game is played on a grid with 5 x 5 cells. The game involves red pieces controlled
                                        by the user, black pieces controlled by your program, and blocks that are placed on
                                        the
                                        grid and do not move. The user has to navigate throughout the grid and eliminate its
                                        enemy using key functions</p>
                                    <div class="technologies">
                                        <div class="tech-items">JavaScript</div>
                                        <div class="tech-items">HTML</div>
                                        <div class="tech-items">CSS</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="present">
                        <div class="date">
                            Full Stack
                        </div>
                        <div class="colum">
                            <div class="university">
                                <div class="content">
                                    <h2>Gym Booking System </h2>
                                    <p>A Full-Stack web-based application that allows members
                                        of the gym to book its fitness classes. The systems makes sure that bookings are
                                        only possible on a
                                        Saturday or Sunday for classes during the following week. Each class is given a time
                                        and day of the week as classes may reoccur throughout the week.
                                        The system is designed to only accommodate a
                                        certain number of participants, as classes have a max limit of people that are
                                        allowed to attend. </p>
                                    <div class="technologies">
                                        <div class="tech-items">PHP</div>
                                        <div class="tech-items">JavaScript</div>
                                        <div class="tech-items">MySQL</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="present">
                        <div class="date">
                            Full Stack
                        </div>
                        <div class="colum">
                            <div class="risidio">
                                <div class="content">
                                    <h2>Student Management System </h2>
                                    <p>A Full-Stack web application built for final project that allows users to track
                                        student progression as their BootCamp has been completed. The range of details are
                                        added for each student including email, job position etc. The frontend creates calls
                                        request that takes the data from the backend and displays the users into a table
                                        based view.
                                    </p>
                                    <div class="technologies">
                                        <div class="tech-items">Java</div>
                                        <div class="tech-items">Spring</div>
                                        <div class="tech-items">React JS</div>
                                        <div class="tech-items">MySQL</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="present">
                        <div class="date">
                            Full Stack
                        </div>
                        <div class="colum">
                            <div class="risidio">
                                <div class="content">
                                    <h2>Vending Machine</h2>
                                    <p>Covered the foundations of Information Technology, while learning about systems and
                                        Linux Development. Built Web applications with DreamWeaver. Landed number 1 spot for
                                        a competition for the creation of web application for a client of the College . </p>
                                    <div class="technologies">
                                        <div class="tech-items">DreamWeaver</div>
                                        <div class="tech-items">Python</div>
                                        <div class="tech-items">Linux</div>
                                    </div>
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



.experience-container {
    display: flex;
    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    -webkit-font-smoothing: antialiased;
    line-height: 1.625;
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    -tw-bg-opacity: 1;
    transition-property: all;
    transition-timing-function: cubic-bezier(.4, 0, .2, 1);
    transition-duration: .15s;
    padding-bottom: .25rem;
    margin-top: 3.2rem;
}

@media (min-width: 1025px) {
    .experience-container {
        position: relative;
        bottom: 550px;
        left: 580px;
    }

    .content {
        width: 390px;
    }

}

.experience-title {
    display: none;
}

.technologies {
    display: flex;
    gap: 10px;

    align-items: center;
    text-align: center;
}

.tech-items {
    font-size: .75rem;
    font-weight: 500;
    line-height: 1.25rem;


    border-radius: 35px;
    --tw-text-opacity: 1;
    color: rgb(94 234 212/var(--tw-text-opacity));

    align-items: center;





}

.date {
    text-transform: uppercase;
    letter-spacing: .025em;
    --tw-text-opacity: 1;
    color: rgb(100 116 139/var(--tw-text-opacity));
    font-weight: 700;
    font-size: .80rem;
    line-height: 1rem;
    z-index: 10;
    -webkit-font-smoothing: antialiased;
    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    width: 120px;

}

.present {
    padding: 20px;
    margin-bottom: 30px;
    display: flex;


}


.present:hover {
    background-color: rgba(30, 41, 59, .5);
    box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
    filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
    border-radius: .375rem;
    --tw-shadow: inset 0 1px 0 0 rgba(148, 163, 184, .1);
    --tw-shadow-colored: inset 0 1px 0 0 var(--tw-shadow-color);
    --tw-drop-shadow: drop-shadow(0 10px 8px rgba(0, 0, 0, .04)) drop-shadow(0 4px 3px rgba(0, 0, 0, .1));
    cursor: pointer;

}



h2 {
    font-weight: 500;
    font-size: 20px;
    position: relative;
    top: -20px;
    text-align: -webkit-match-parent;
    --tw-text-opacity: 1;
    color: rgb(226 232 240/var(--tw-text-opacity));
    line-height: 1.375;

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
    --tw-text-opacity: 1;
    color: rgb(148 163 184/var(--tw-text-opacity));
    text-align: -webkit-match-parent;
    list-style: none;
    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    margin-top: 0.5rem;
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;


}



.content {
    transition-property: all;
    transition-timing-function: cubic-bezier(.4, 0, .2, 1);
    transition-duration: .15s;
    padding-bottom: 4.25rem;
    display: flex-inline;
    position: relative;
    font-family: var(--font-inter), ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-feature-settings: "ss03", "cv02", "cv11";
    height: 200px;


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

    .present {
        display: block;
    }

    .date {
        margin-bottom: 30px;
    }

    .technologies {
        display: grid;
        grid-gap: 9px;
        grid-template-columns: 0fr .2fr .3fr;
    }
}

@media (min-width: 550px) {
    .technologies {
        display: flex;
        gap: 10px;

        align-items: center;
        text-align: center;

    }
}</style>
