<script>
import Navbar from './Navbar.vue';

export default {
    components: {
        Navbar
    }
}
</script>

<template>
    <Navbar />
    <section class="slide">
        <div class="home-row">
            <div class="home-col animate__animated animate__fadeInLeft">
                <div class="home-title">
                    <div class="top">Apa itu <span class="text-yellow">Kearifan Lokal?</span></div>
                </div>
                <p class="subheading">
                    Kearifan lokal adalah identitas atau kepribadian budaya sebuah bangsa yang menyebabkan bangsa
                    tersebut mampu menyerap, bahkan mengolah kebudayaan yang berasal dari luar/bangsa lain menjadi
                    watak dan kemampuan sendiri.
                </p>
                <p class="subheading">
                    Kearifan lokal juga merupakan ciri khas etika dan nilai budaya dalam masyarakat lokal yang
                    diturunkan dari generasi ke generasi. Di Indonesia, Kesadaran akan kearifan lokal mulai tumbuh
                    subur pasca jatuhnya rezim Presiden Soeharto pada tahun 1998.

                </p>
            </div>
            <div class="home-col-2 animate__animated animate__fadeInRight">
                <div class="card-cs">
                    <img src="../assets/images/Rumah-Lamin.jpg" alt="">
                </div>
            </div>
        </div>
    </section>
</template>