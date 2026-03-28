<script setup>

</script>

<template>
<h1>Work</h1>
<hr>
<p>Lulusan Teknik Informatika tahun 2022 yang memiliki ketertarikan dan pengalaman di bidang produksi visual, khususnya sebagai cameraman. Berawal dari pengalaman bekerja di bagian studio TV Batam, saya mendapatkan kesempatan untuk terlibat langsung dalam membantu tugas kameramen saat dibutuhkan. Dari pengalaman tersebut, saya mengembangkan kemampuan dalam pengoperasian kamera serta memahami angle dan komposisi pengambilan gambar untuk kebutuhan foto dan video. Saya dikenal sebagai pribadi yang cepat tanggap, cekatan, menyukai tantangan, dan mampu beradaptasi dengan baik di lingkungan kerja yang baru.</p>
<hr>
<p>Mengabadikan setiap detail, ekspresi, dan atmosfer yang penuh makna
karena setiap frame punya cerita yang lebih dari sekadar panggung.</p>
<div class="galeri">
                <img src="/public/foto/f1.jpg" alt="">
                <img src="/public/foto/f2.jpg" alt="">
                <img src="/public/foto/f3.jpg" alt="">
                <img src="/public/foto/f4.jpg" alt="">
                <img src="/public/foto/f5.jpg" alt="">
                <img src="/public/foto/f6.jpg" alt="">
                <img src="/public/foto/f7.jpg" alt="">
                <img src="/public/foto/f8.jpg" alt="">
                <img src="/public/foto/f9.jpg" alt="">
            </div>
</template>

<style scoped>
h1{
    padding: 25px;
}
p{
    text-align: justify;
}
.galeri {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 kolom */
    gap: 15px;
}

.galeri img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}
</style>