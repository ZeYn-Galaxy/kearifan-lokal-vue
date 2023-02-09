<script>

export default {
    data() {
        return {
        }
    },

    props: {
        Title: String
    }
}
</script>

<template>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container-fluid h-100">
            <a class="navbar-brand" href="/kearifan-lokal-vue/">KALIMANTAN <span>TIMUR</span></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link active" href="/kearifan-lokal-vue/">Home</a>
                    <a class="nav-link" href="#/rumah-adat">Rumah Adat</a>
                    <a class="nav-link" href="#/wisata">Wisata</a>
                    <a class="nav-link" href="#/makanan-khas">Makanan Khas</a>
                    <a class="nav-link" href="#/suku">Suku</a>
                </div>
            </div>
        </div>
    </nav>
</template>