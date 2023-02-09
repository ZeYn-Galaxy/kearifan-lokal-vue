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
        <div class="column">
            <div class="card-cs animate__animated animate__slideInLeft">
                <div class="text-cs">
                    <p><span class="text-yellow">Amplang</span> adalah sebuah makanan ringan tradisional yang terbuat dari ikan yang disajikan di
                        Samarinda, Indonesia dan kemudian terkenal di Kalimantan Timur, Kalimantan Utara dan
                        pesisir timur Sabah, Malaysia. Amplang terbuat dari ikan tenggiri, yang dicampur
                        dengan tepung kanji dan bahan-bahan lainnya, dan kemudian digoreng.</p>
                </div>
                <img src="../images/amplang.JPG" alt="">
            </div>
            <div class="card-cs animate__animated animate__slideInUp">
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
                <img src="../images/ayam-cincane.JPG" alt="">
            </div>
            <div class="card-cs animate__animated animate__slideInRight">
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
                <img src="../images/nasi-bekepor.JPG" alt="">
            </div>
        </div>
    </section>
</template>


<style>
.text-cs{
    display: flex;
    width: 100%;
    height: 40%;
    justify-content: center;
    align-items: center;
    font-size: 1.25rem;
    color: #FFFFFF;
}

.text-cs p {
    text-align: center;
}

.column {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-between;
}

.column img {
    height: 40%;
    max-width: 80%;
    border-radius: 15px;
}

.card-cs {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 30%;
    height: 100%;
}
</style>