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
        <!-- Rumah Lamin -->
        <div class="title">
            <div class="top animate__animated animate__fadeInDown">RUMAH LAMIN</div>
        </div>
        <div class="row-custom">
            <div class="baris">
                <img class="animate__animated animate__fadeInLeft" src="../images/Rumah-Lamin-1.JPG" alt="">
                <img class="animate__animated animate__zoomIn" src="../images/Rumah-Lamin.JPG" alt="">
                <img class="animate__animated animate__fadeInRight" src="../images/Rumah-Lamin-2.JPG" alt="">
            </div>
        </div>
        <div class="animate__animated animate__slideInUp">
            <div class="text pd-2">
                <p> <span class="text-yellow">Rumah Lamin</span> adalah rumah adat dari Kalimantan Timur. Rumah Lamin
                    adalah
                    identitas masyarakat Dayak di
                    Kalimantan Timur. Rumah Lamin mempunyai panjang sekitar 300 meter, lebar 15 meter, dan tinggi kurang
                    lebih 3 meter. Rumah Lamin juga dikenal sebagai rumah panggung yang panjang dari sambung
                    menyambung.Rumah ini dapat ditinggal oleh beberapa keluarga karena ukuran rumah yang cukup besar.
                    Salah satu rumah Lamin yang berada di Kalimantan Timur bahkan dihuni oleh 12 sampai 30 keluarga.
                    Rumah Lamin dapat menampung kurang lebih 100 orang. Pada tahun 1967, rumah Lamin diresmikan oleh
                    pemerintah Indonesia.</p>
            </div>
            <div class="sub-title pd-2"><span>CIRI KHAS</span></div>
            <div class="text pd-2">
                <p>
                    <span class="text-yellow">Rumah lamin</span> menggunakan kayu ulin sebagai dasar kontruksinya.

                    Kayu ulin ini hanya bisa kamu dapatkan di hutan Kalimantan.

                    Kayu ini terbaik dari sisi bahannya dan bersifat sangat kuat serta tidak mudah lapuk.

                    Bila terkena air, justru kayu ulin akan bertambah keras dan kuat layaknya besi.

                    Oleh karena itu, masyakarat di sana banyak yang menjulukinya dengan sebutan kayu besi.

                    Efektif sekali bila digunakan untuk penyangga lantai dan dinding.

                    Selain itu, rumah lamin yang berbentuk persegi panjang memiliki atap seperti pelana.

                    Atap rumah lamin diberikan tiang-tiang penyangga yang dibagi dua yaitu, untuk atap dan menopang
                    lantai-lantai rumah.
                </p>
            </div>
            <div class="text pd-2">
                <p>
                    Ciri khas dari rumah adat lamin di Kalimantan Timur ini adalah ukiran-ukiran etnik indah yang berupa
                    gambar bermakna.
                    Gambar-gambar ini memiliki motif makhluk hidup seperti, tampilan wajah manusia, tumbuhan, hewan, dan
                    lain-lain.

                    Menurut kepercayaan orang sana, ukiran yang terdapat pada rumah lamin dapat menjaga anggota keluar
                    dari
                    bahay ilmu hitam yang sewaktu-waktu bisa saja menyerang.
                </p>
            </div>
            <div class="text pd-2">
                <p>
                    Rumah lamin memiliki ciri khas yang didesain kontras dan mampu menghiasi dasar dinding.

                    Warna-warna yang ada seperti, <span class="text-yellow">kuning</span>, <span
                        class="text-red">merah</span>, <span class="text-black">hitam</span>, <span
                        class="text-blue">biru</span>, dan putih.
                    Warna di atas selalu digunakan dalam arsitektur rumah lamin.
                    Dalam makna filosofis, merah berarti keberanian, kunin adalah simbol kewibawaan, putih adalah
                    kebersihan
                    jiwa, dan hitam adalah simbol keteduhan.
                </p>
            </div>
        </div>
        <!-- SOURCE -->
        <!-- https://www.ruparupa.com/blog/macam-rumah-adat-kalimantan-timur-dan-ciri-khas/ -->
    </section>
</template>

<style>
:root {
    --hitam: #000000;
    --putih: #FFFFFF;
    --Montserrat: 'Montserrat', sans-serif;
    --Roboto: 'Roboto', sans-serif;
    --Merriweather: 'Merriweather', sans-serif;
    --Background: #06051b;
    --Primary: #F7D716;
    --merah: #fe2e2e;
    --biru: #001be7;
}

.text-red {
    color: var(--merah);
}

.text-blue {
    color: var(--biru);
}

.text-black {
    color: var(--hitam);
    text-shadow: 0px 0px 5px white;
}

.home-cs {
    width: 100%;
    height: 150vh;
    background-color: var(--Background);
}

.row-custom {
    display: grid;
    grid-template-areas: 1fr 1fr 1fr;
    justify-content: center;
}

.baris {
    display: flex;
    gap: 15px;
}

.baris img {
    border-radius: 15px;
    max-width: 350px;
}

.title {
    width: 100%;
    height: 10%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.sub-title {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: var(--Merriweather);
}

.sub-title span {
    font-size: 2.5rem;
    color: #FFFFFF;
    font-weight: 400;
}

.p-2 {
    padding-top: 2rem;
}


.text {
    overflow-wrap: break-word;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.25rem;
    color: #FFFFFF;
    font-family: var(--Merriweather);
    font-weight: normal;
}

.text p {
    width: 80%;
    text-align: center;
}

.text ul li {
    width: 80%;
}

.title .top {
    font-size: 3rem;
    color: #FFFFFF;
    font-family: var(--Merriweather);
    font-weight: 400;
}

ul>li {
    list-style: none;
}

.text-yellow {
    color: var(--Primary);
}
</style>