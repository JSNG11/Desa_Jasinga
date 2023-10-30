<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi dan Misi Desa Jasinga</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Mewujudkan Masyarakat Desa Jasinga yang Bertaqwa, Kreatif, Cerdas, Bermartabat, Berdaya dan Berbudaya, Maju, Mandiri dan Sejahtera”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Mengamalkan dan melaksanakan ajaran agama dalam kehidupan sehari-hari dengan mengedepankan iman, taqwa, jujur, adil, dan berakhlaqul karimah;
        </li>
        <li>
          2. Meningkatkan kehidupan yang harmonis, toleran, saling menghormati dalam berbudaya beragama di Desa Jasinga;
        </li>
        <li>
          3. Mewujudkan keamanan dan ketertiban dilingkungan Desa Jasinga;
        </li>
        <li>
          4. Meningkatkan kinerja Aparatur Desa yang berkualitas, Profesional dan berjiwa pelayanan prima tanpa membeda-bedakan status sosial masyarakat;
        </li>
        <li>
          5. Meningkatkan sarana dan prasarana penunjang baik dari segi fisik, ekonomi, pendidikan, kesehatan, olah raga dan kebudayaan yang mendukung dalam kehidupan sehari-hari;
        </li>
        <li>
          6. Mengupayakan kemandirian masyarakat dalam melaksanakan otonomi yang berbasis pada potensi Desa;
        </li>
        <li>
          7. Meningkatkan pemberdayaan masyarakat melalui partisipasi aktif dalam membangun maupun kegiatan ekonomi produktif untuk meningkatkan taraf hidup masyarakat;
        </li>
        <li>
          8. Meningkatkan kesehatan, kebersihan Desa serta mewujudkan program Desa Siaga dan mengusahakan Jaminan kesehatan masyarakat melalui program Pemerintah;
        </li>
        <li>
          9. Meningkatkan kesejahteraan masyarakat Desa dengan mewujudkan Badan Usaha Milik Desa (BUMDES) dan program lain untuk membuka lapangan kerja dan menyalurkan tenaga kerja bagi masyarakat Desa, serta meningkatkan produksi rumahan/UMKM;
        </li>
        <li>
          10. Melanjutkan dan melaksanakan RPJMDes berdasarkan musyawarah dan gotong royong;
        </li>
        <li>
          11. Sabar, Tawakal dan tetap berusaha dengan segala potensi Desa untuk mewujudkan Indeks Desa membangun yang maju, mandiri dan sejahtera.
        </li>
        <li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
