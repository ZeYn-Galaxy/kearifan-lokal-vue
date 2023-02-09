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
    <section class="home-cs">
        <div class="column">
            <div class="baris animate__animated animate__slideInLeft padding-3">
                <div class="text-cs">
                    <p><span class="text-yellow">Amplang</span> adalah sebuah makanan ringan tradisional yang terbuat dari ikan yang disajikan di
                        Samarinda, Indonesia dan kemudian terkenal di Kalimantan Timur, Kalimantan Utara dan
                        pesisir timur Sabah, Malaysia. Amplang terbuat dari ikan tenggiri, yang dicampur
                        dengan tepung kanji dan bahan-bahan lainnya, dan kemudian digoreng.</p>
                </div>
                <img src="../assets/images/amplang.jpg" alt="">
            </div>
            <div class="baris animate__animated animate__slideInRight padding-3">
                <div class="text-cs">
                    <p>
                        <span class="text-yellow">Ayam cincane</span> menjadi makanan khas Samarinda yang dimasak dengan bumbu khas sehingga
                        rasanya jadi berbeda.

                        Ayam cincane dibuat dari ayam kampung yang dibumbui dengan kemiri, jahe, lengkuas, serta
                        rempah lainnya.

                        Setelah ayam dilumuri hingga rata, ayam tersebut direbus terlebih dahulu.

                        Jadi, bumbunya meresap hingga ke bagian dalam daging.

                        Setelah direbus, barulah ayam dibakar hingga matang.

                        Selain dibakar, ayam cincane bisa digoreng sebentar hingga kulitnya sedikit kecokelatan.
                    </p>
                </div>
                <img class="cs-img" src="../assets/images/ayam-cincane.jpeg" alt="">
            </div>
            <div class="baris animate__animated animate__slideInLeft padding-3">
                <div class="text-cs">
                    <p>
                        <span class="text-yellow">Nasi bekepor</span> sebenarnya adalah nasi rames alias nasi campur ala Samarinda.

                        Jadi nasi bekepor dibuat dari nasi putih yang disajikan dengan aneka lauk-pauk.

                        Lauk pauk untuk nasi bekepor berupa ikan asin, telur, tumisan sayur, daun kemangi, tahu
                        goreng, hingga sambal raja.

                        Nasi bekepor dulunya hanya disantap atau dinikmati oleh kalangan raja dan bangsawan di
                        Kalimantan Timur.

                        Hal ini karena lauk-pauknya terbilang cukup mewah.

                        Namun, seiring berjalannya waktu, makanan khas Samarinda ini bisa dinikmati oleh semua
                        orang.
                    </p>
                </div>
                <img src="../assets/images/nasi-bekepor.jpg" alt="">
            </div>
        </div>
    </section>
</template>