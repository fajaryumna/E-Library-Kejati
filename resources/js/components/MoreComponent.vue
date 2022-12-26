<template>

    <head>
        <!-- <link rel="stylesheet" href="resources/css/app.css"> -->
    </head>

    <body>
        <div>
            <div class="no-margin">
                <div class="top-page">
                    <div class="text-shadow display-flex-between ">
                        <div>
                            <!-- <img src="./images/Logo Kejati.png" height="50px"> -->
                            <h2>GAMBAR</h2>
                        </div>
                        <div>
                            <a>Beranda</a>
                            <a>Peminjaman</a>
                            <a>FAQ</a>
                            <a>Login</a>
                        </div>

                    </div>
                </div>
            </div>

            <div>
                <h2 class="text-center">KOLEKSI <span>BUKU</span></h2>
                <div class="text-center">
                    <div class="display-flex-center">
                        <div>
                            <h4>Judul Buku:</h4>
                            <input type="text" placeholder="Judul Buku">
                        </div>
                        <div>
                            <h4>Pengarang:</h4>
                            <input type="text" placeholder="Pengarang">
                        </div>
                        <div>
                            <h4>Penerbit:</h4>
                            <input type="text" placeholder="Penerbit">
                        </div>
                        <div>
                            <h4>Tahun Terbit:</h4>
                            <input type="text" placeholder="Tahun Terbit">
                        </div>
                        <button>Cari</button>
                    </div>

                </div>
            </div>

            <div class="tabel-buku">
                <div>

                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
                <div class="display-flex-center">
                    <h5>BUKU X</h5>
                </div>
            </div>


            <footer class="no-margin">

                <div class="footer-content">
                    <h3>Tentang Kami</h3>
                    <h3 class="text-center">Perpustakaan Kejaksaan Tinggi Jawa Tengah</h3>
                    <div class="display-flex-center">
                        <div class="footer-equalwidth footer-content-left">
                            <!-- <img src="./images/top-background.jpg" width="200%"> -->
                            <h2>GAMBAR</h2>
                        </div>
                        <div class="footer-equalwidth footer-content-right">
                            <h3 class="footer-right-margin">Alamat: </h3>
                            <h3 class="footer-right-margin">No Telp: </h3>
                            <h3 class="footer-right-margin">Fax: </h3>
                        </div>
                    </div>
                </div>
            </footer>
        </div>

    </body>
</template>

<script>
export default {
    name: 'MoreComponent'
}
</script>

<style>
body {
    margin: 0;
    background-color: beige;
}

footer {
    padding: 5px 0;
    background-color: #067322;
}

.top-page {
    margin: 0;
    /* border: 2px solid rgba(0, 0, 0, 0); */
    padding: 0 0 300px 0;
    background-image: url("/assets/images/top-background.jpg");
    background-size: cover;
}

.text-shadow {
    /* text-shadow: 0px 0px 20px white; */
    margin: inherit;

    color: black;
    background-color: #f6f6f699;
    padding: 20px 5%;
}

.tabel-buku {
    margin: 0 20%;
}

.footer-content {
    margin: 0 5%;
    padding-bottom: 2%;
}

.footer-equalwidth {
    width: 50%;
}

.footer-content-left {
    margin-right: 20px;
}

.footer-content-right {
    margin-left: 20px;
    padding: 2% 0 2% 20%;
}

.footer-right-margin {
    margin: 0 0 5% 0;
    color: white;
}

.text-center {
    text-align: center;
}

.no-margin {
    margin: 0px;
}

.display-flex-center {
    display: flex;
    justify-content: center;
    margin: 0 20%;
}

.display-flex-between {
    display: flex;
    justify-content: space-between;
}

.border-checker {
    border: 2px dotted red;
}
</style>