<template>
  <div class="q-pa-md row items-start q-gutter-md">
    <q-card class="my-card" flat bordered>
          <q-card
          class="my-card text-white"
          style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)"
        >
          <q-card-section>
            <div class="text-h6">Aplikasi Penjualan DVD Film</div>
            <div class="text-subtitle2">by Sholeha</div>
          </q-card-section>

          <q-card-section class="q-pt-none">
            {{ lorem }}
          </q-card-section>
          </q-card>
    </q-card>
  </div>
</template>
<script>
export default {
  data () {
    return {
      lorem: 'Aplikasi penjualan DVD Film berbasis web ini menjual berbagai film dengan kualitas tinggi yang banyak diminati oleh penggemar semua kalangan baik dari luar negeri maupun dalam negeri, DVD film yang kami jual juga merupakan Film original dimana para penggemar akan merasa lebih nyaman dan tertarik dalam menonton nya'
    }
  }
}
</script>
