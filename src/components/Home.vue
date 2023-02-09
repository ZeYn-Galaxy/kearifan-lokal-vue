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
    <section class="home">

        <div class="container-fluid h-100">
            <div class="row h-100">
                <div class="col-lg-6 overflow-break-word animate__animated animate__fadeInLeft">
                    <h1 class="heading color-h">Apa itu <span>Kearifan Lokal?</span></h1>
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
                    <p class="subheading">
                        Lebih lanjut kearifan lokal juga didefinisikan sebagai kemampuan beradaptasi, menata, dan
                        menumbuhkan pengaruh alam serta budaya lain yang menjadi motor penggerak transformasi dan
                        penciptaan keanekaragaman budaya Indonesia yang luar biasa.
                    </p>
                    <p class="subheading">
                        Ini juga bisa menjadi suatu bentuk pengetahuan, kepercayaan, pemahaman atau persepsi beserta
                        kebiasaan atau etika adat yang menjadi pedoman perilaku manusia dalam kehidupan ekologis dan
                        sistemik.
                    </p>
                </div>
                <div class="col-lg-6 animate__animated animate__fadeInRight">
                    <div class="card">
                        <img src="../images/Rumah-Lamin.JPG" class="card-img-top" alt="...">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>