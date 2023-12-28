<template>
    <section class="section-projects">
        <h2>Projects</h2>
        <div class="projects-content">
            <div class="min-menu">
                <div class="content-text-frontend">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 15 15" fill="none">
                        <mask id="mask0_41_105" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="0" y="1" width="15" height="13">
                            <path d="M12.8125 2.5H2.1875C1.66973 2.5 1.25 2.91973 1.25 3.4375V11.5625C1.25 12.0803 1.66973 12.5 2.1875 12.5H12.8125C13.3303 12.5 13.75 12.0803 13.75 11.5625V3.4375C13.75 2.91973 13.3303 2.5 12.8125 2.5Z" stroke="white" stroke-width="1.66667" stroke-linejoin="round"/>
                            <path d="M1.25 3.4375C1.25 3.18886 1.34877 2.9504 1.52459 2.77459C1.7004 2.59877 1.93886 2.5 2.1875 2.5H12.8125C13.0611 2.5 13.2996 2.59877 13.4754 2.77459C13.6512 2.9504 13.75 3.18886 13.75 3.4375V6.25H1.25V3.4375Z" fill="white" stroke="white" stroke-width="1.66667"/>
                            <path d="M2.5 4.375C2.5 4.02982 2.77982 3.75 3.125 3.75C3.47018 3.75 3.75 4.02982 3.75 4.375C3.75 4.72018 3.47018 5 3.125 5C2.77982 5 2.5 4.72018 2.5 4.375Z" fill="black"/>
                            <path d="M4.375 4.375C4.375 4.02982 4.65482 3.75 5 3.75C5.34518 3.75 5.625 4.02982 5.625 4.375C5.625 4.72018 5.34518 5 5 5C4.65482 5 4.375 4.72018 4.375 4.375Z" fill="black"/>
                        </mask>
                        <g mask="url(#mask0_41_105)">
                            <path d="M0 0H15V15H0V0Z" fill="#00121B" fill-opacity="0.8"/>
                        </g>
                    </svg>
                    <p class="text-frontend">Frontend</p>
                </div>
                <div class="content-text-backend">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="21" viewBox="0 0 20 21" fill="none">
                        <path d="M16.6666 3.83331H3.33329C2.89127 3.83331 2.46734 4.00891 2.15478 4.32147C1.84222 4.63403 1.66663 5.05795 1.66663 5.49998V15.5C1.66663 15.942 1.84222 16.3659 2.15478 16.6785C2.46734 16.9911 2.89127 17.1666 3.33329 17.1666H16.6666C17.5833 17.1666 18.3333 16.4166 18.3333 15.5V5.49998C18.3333 5.05795 18.1577 4.63403 17.8451 4.32147C17.5326 4.00891 17.1087 3.83331 16.6666 3.83331ZM16.6666 15.5H3.33329V7.16665H16.6666V15.5ZM15 14.6666H9.99996V13H15V14.6666ZM6.24996 14.6666L5.07496 13.4916L7.22496 11.3333L5.06663 9.17498L6.24996 7.99998L9.58329 11.3333L6.24996 14.6666Z" fill="#00121B"/>
                    </svg>
                    <p class="text-backend">Backend</p>
                </div>
            </div>
            <SectionProjectsProjects></SectionProjectsProjects>
        </div>
    </section>  
</template>

<script setup>
import SectionProjectsProjects from './SectionProjectsProjects.vue';
</script>

<style scoped lang="scss">
.section-projects {
    display: flex;
    padding: 80px 0px 120px 0px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 60px;
    align-self: stretch;
}
.projects-content {
    display: flex;
    padding: 80px 0px 120px 0px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 60px;
    align-self: stretch;
    background: var(--foundation-red-light-active, #F78B59);
}
.min-menu {
    display: flex;
    justify-content: center;
    align-items: flex-end;
    gap: 30px;
}
.content-text-frontend {
    display: flex;
    padding: 0px 10px 3px 10px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    border-bottom: 4px solid var(--Foundation-Orange-Normal, #FF5349);
}
.text-frontend {
    color: var(--foundation-blue-dark-active, #00121B);
    font-family: InterBold;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}
.content-text-backend {
    display: flex;
    padding: 0px 10px 3px 10px;
    justify-content: center;
    align-items: center;
    gap: 10px;
}
</style>