<template>
  <v-container>
    <v-row>
      <v-col lg="6">
        <h2 class="title1">Apapun Keluhanmu</h2>
        <h2 class="title2">Periksain Siap Membantu</h2>
        <p style="color: #002996">
          Kami siap memberikan pelayanan terbaik untukmu <br />
          pilih layanan kesehatan sesuai kebutuhan
        </p>
      </v-col>
      <v-col lg="6">
        <img width="100%" src="./../assets/header.png" alt="" />
      </v-col>
      <v-col lg="1"></v-col>
      <v-col lg="10">
        <div class="main">
          <p class="title3">Kategori Pemeriksaan</p>
          <v-row>
            <v-col lg="3" v-for="item in Mykategori.data" :key="item.id">
              <div class="urine">
                <img
                  :src="item.iconUrl"
                  alt=""
                  width="25%"
                  height="55%"
                  style="margin-top: 22px; margin-left: 20px"
                />
                <p class="darah">{{ item.name }}</p>
              </div>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <v-col lg="1"></v-col>
      <v-col lg="12"></v-col>
      <v-col lg="1"></v-col>
      <v-col lg="2">
        <v-btn depressed large style="border-radius: 10px">
          <v-icon style="margin-right: 10px">mdi-sort</v-icon>
          Urutkan
        </v-btn>
      </v-col>
      <v-col lg="2">
        <v-btn depressed large style="border-radius: 10px; margin-left: -30px">
          <v-icon style="margin-right: 10px">mdi-filter-outline</v-icon>
          Filter
        </v-btn>
      </v-col>
      <v-col lg="3"></v-col>
      <v-col lg="2">
        <div class="search">
          <v-icon large style="margin-top: 8px; margin-left: 7px"
            >mdi-magnify</v-icon
          >
          <div class="input">
            <v-text-field placeholder="Cari Pemeriksaan"></v-text-field>
          </div>
        </div>
      </v-col>
      <v-col lg="12"></v-col>
      <v-col lg="3" v-for="items in Myresponse.data" :key="items.id">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <div class="promo2">Terkoneksi PeduliLindungi</div>
            <p class="text-h5 text--primary">{{ items.name }}</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP {{ items.marginPrice }}
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  :src="items.laboratoryLogo"
                  alt=""
                  height="40"
                  width="50"
                />
              </v-col>
              <v-col lg="3">
                <div class="map">
                  <img
                    src="./../assets/maps.png"
                    alt=""
                    width="30"
                    height="30"
                    style="margin-top: 2px"
                  />
                </div>
              </v-col>
              <v-col lg="6">
                <p class="loc">{{ items.city }}</p>
              </v-col>
            </v-row>
          </v-card-text>
          <v-card-actions>
            <v-btn text color="blue darken-1"> Lihat Detail </v-btn>
            <v-btn
              depressed
              rounded
              small
              class="btn-1"
              style="margin-left: 75px"
            >
              <v-icon color="white">mdi-cart</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col lg="12"></v-col>
      <v-col lg="12">
        <v-btn x-large rounded class="btn-s">Selanjutnya</v-btn>
      </v-col>
      <v-col lg="12"></v-col>
      <v-col lg="12"></v-col>
      <v-col lg="12" class="footer">
        <v-row>
          <v-col lg="3">
            <div class="bag1">
              <p style="margin-bottom: 30px">Informasi</p>
              <p>Tentang Periksain</p>
              <p style="margin-top: -10px">Layanan</p>
              <p style="margin-top: -10px">Kontak</p>
              <p style="margin-top: -10px">Artikel & Berita</p>
            </div>
          </v-col>
          <v-col lg="3">
            <div class="bag1">
              <p style="margin-bottom: 30px">GabungMitra</p>
              <p>Mitra Plebotomist</p>
              <p style="margin-top: -10px">Mitra Laboratorium</p>
              <p style="margin-top: -10px">Partner</p>
            </div>
          </v-col>
          <v-col lg="3">
            <div class="bag1">
              <p style="margin-bottom: 30px">Pusat Bantuan</p>
              <p>+62 812-3867-772</p>
              <p style="margin-top: -10px">(031)999-220-22</p>
              <p style="margin-top: 30px">Stay Connect</p>
              <img src="./../assets/ig.png" width="40" height="40" alt="" />
              <img
                src="./../assets/fb.png"
                width="35"
                height="35"
                alt=""
                style="margin-left: 10px; margin-bottom: 2px"
              />
            </div>
          </v-col>
          <v-col lg="3">
            <div class="bag1">
              <p style="margin-bottom: 30px">Available on</p>
              <img
                src="./../assets/android.png"
                width="150"
                height="100"
                alt=""
              />
              <p>Metode Pembayaran</p>
              <img
                src="./../assets/mandiri.png"
                width="70"
                height="70"
                alt=""
                style="
                  background-color: white;
                  border-radius: 10px 0px 0px 10px;
                "
              />
              <img
                src="./../assets/bca.png"
                width="90"
                height="70"
                alt=""
                style="
                  background-color: white;
                  border-radius: 0px 10px 10px 0px;
                "
              />
            </div>
          </v-col>
          <div>
            <p style="margin-left: 60px">
              Copyright@PT.Wahana Mediatek Indonesia. All Rights Reserved
            </p>
          </div>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
import kategori from "../assets/json/KategoriPemeriksaan.json";
import response from "../assets/json/ResponsePemeriksaan.json";
export default {
  name: "Content",
  data() {
    return {
      Mykategori: kategori,
      Myresponse: response,
    };
  },
};
</script>
<style scoped>
.title1 {
  font-size: 40px;
  margin-top: 100px;
  color: #002ea8;
}
.title2 {
  font-size: 40px;
  margin-bottom: 30px;
  margin-top: -10px;
  color: #002585;
}
.title3 {
  padding-top: 15px;
  margin-left: 30px;
  font-weight: bold;
  font-size: 18px;
}
.main {
  box-shadow: 0px 0px 5px 0px rgba(186, 186, 186, 0.5);
  background-color: white;
  border-radius: 20px;
  height: 20vh;
}
.title4 {
  margin-top: -36px;
  margin-left: 80px;
}
.darah {
  margin-top: -36px;
  margin-left: 70px;
}
.anti {
  margin-top: -36px;
  margin-left: 70px;
}
.urine {
  border-radius: 15px;
  border: 1px solid #dfdfdf;
  width: 12vw;
  height: 9vh;
  margin-left: 20px;
}
.search {
  width: 18vw;
}
.input {
  margin-top: -55px;
  margin-left: 50px;
}
.promo {
  background-color: #002999;
  width: 4vw;
  border-radius: 4px 0px;
  color: white;
  text-align: center;
  margin-top: -16px;
  margin-left: -16px;
  margin-bottom: 20px;
}
.promo2 {
  background-color: #4f6dc0;
  width: 12vw;
  border-radius: 4px 0px;
  color: white;
  text-align: center;
  margin-top: -42px;
  margin-left: 45px;
  margin-bottom: 20px;
  border-radius: 0px 0px 10px 5px;
  border: 0px solid #ffffff;
}
.btn-s {
  background: -webkit-linear-gradient(to right, #182848, #4b6cb7);
  background: linear-gradient(to right, #182848, #4b6cb7);
  color: white;
  margin-left: 500px;
}
.footer {
  background: -webkit-linear-gradient(to right, #182848, #4b6cb7);
  background: linear-gradient(to right, #182848, #4b6cb7);
  color: white;
  height: 57vh;
}
.bag1 {
  padding-top: 50px;
  margin-left: 55px;
  font-size: 20px;
  font-weight: normal;
}
.btn-1 {
  background: -webkit-linear-gradient(to left, #edde5d, #f09819);
  background: linear-gradient(to left, #edde5d, #f09819);
}
.disc {
  background-color: #b2ebf2;
  width: 2vw;
  height: 3vh;
  text-align: center;
  border-radius: 5px;
}
.map {
  background-color: #f5f5f5;
  width: 2vw;
  height: 5vh;
  text-align: center;
  border-radius: 5px;
}

.loc {
  font-size: 15px;
  margin-left: -20px;
  margin-top: 5px;
}
</style>
