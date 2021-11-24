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
            <v-col lg="3">
              <div class="urine">
                <img
                  src="https://content.periksain.id/display-group/2a959fe0-7ef1-4cc4-b08c-b9930a1cdf41/230180.png"
                  alt=""
                  width="25%"
                  height="55%"
                  style="margin-top: 14px; margin-left: 20px"
                />
                <p class="darah">DARAH</p>
              </div>
            </v-col>
            <v-col lg="3">
              <div class="gula">
                <img
                  src="https://content.periksain.id/display-group/3741f88e-8022-417e-85c8-26bfeff17f63/PCR2 (1).png"
                  alt=""
                  width="20%"
                  height="55%"
                  style="margin-top: 14px; margin-left: 20px"
                />
                <p class="title4">SWAB PCR</p>
              </div>
            </v-col>
            <v-col lg="3">
              <div class="antigen">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/layout/home/pcr-removebg-preview.png"
                  alt=""
                  width="45%"
                  height="55%"
                  style="margin-top: 14px"
                />
                <p class="anti">ANTIGEN</p>
              </div>
            </v-col>
            <v-col lg="3">
              <div class="paru">
                <img
                  src="https://content.periksain.id/display-group/c1fc0754-8a11-46fb-b308-8d17f502744b/kissclipart-urine-test-png-clipart-clinical-urine-tests-comput-defb38fcbc7d6ecf.png"
                  alt=""
                  width="30%"
                  height="55%"
                  style="margin-top: 14px; margin-left: 20px"
                />
                <p class="title4">URIN</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <div class="promo2">Terkoneksi PeduliLindungi</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 310000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/12/lab-logo/lab 7 logo.png"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <div class="promo2">Terkoneksi PeduliLindungi</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 310000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="4">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/2/lab-logo/lab 2 logo.jpeg"
                  alt=""
                  height="40"
                  width="100"
                />
              </v-col>
              <v-col lg="4">
                <div class="map2">
                  <img
                    src="./../assets/maps.png"
                    alt=""
                    width="30"
                    height="30"
                    style="margin-top: 2px"
                  />
                </div>
              </v-col>
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 315000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="4">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/4/lab-logo/lab 4 logo.png"
                  alt=""
                  height="40"
                  width="100"
                />
              </v-col>
              <v-col lg="4">
                <div class="map2">
                  <img
                    src="./../assets/maps.png"
                    alt=""
                    width="30"
                    height="30"
                    style="margin-top: 2px"
                  />
                </div>
              </v-col>
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 340000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/14/lab-logo/lab 9 logo.png"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 365000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="4">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/16/lab-logo/lab 13 logo.png"
                  alt=""
                  height="40"
                  width="100"
                />
              </v-col>
              <v-col lg="4">
                <div class="map2">
                  <img
                    src="./../assets/maps.png"
                    alt=""
                    width="30"
                    height="30"
                    style="margin-top: 2px"
                  />
                </div>
              </v-col>
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 305000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="4">
                <img
                  src="https://content.periksain.id/laboratory/20/lab-logo/mIhVIED04X1630909828.png"
                  alt=""
                  height="40"
                  width="100"
                />
              </v-col>
              <v-col lg="4">
                <div class="map2">
                  <img
                    src="./../assets/maps.png"
                    alt=""
                    width="30"
                    height="30"
                    style="margin-top: 2px"
                  />
                </div>
              </v-col>
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">Antigen SARS-CoV-2</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 145000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="4">
                <img
                  src="https://content.periksain.id/laboratory/19/lab-logo/xUimqbKLnQ1630469318.jpg"
                  alt=""
                  height="40"
                  width="100"
                />
              </v-col>
              <v-col lg="4">
                <div class="map2">
                  <img
                    src="./../assets/maps.png"
                    alt=""
                    width="30"
                    height="30"
                    style="margin-top: 2px"
                  />
                </div>
              </v-col>
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">PCR Covid-19</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 345000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://content.periksain.id/laboratory/24/lab-logo/naraya2.jpg"
                  alt=""
                  height="40"
                  width="60"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">SGOT</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 72000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/14/lab-logo/lab 9 logo.png"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">Total Cholesterol</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 72000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/14/lab-logo/lab 9 logo.png"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">Urine Lengkap</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 72000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/14/lab-logo/lab 9 logo.png"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
      <v-col lg="3">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div class="promo">Promo</div>
            <p class="text-h5 text--primary">Lekosit</p>
            <p class="text-h5 text--primary" style="font-weight: bold">
              RP 54000
            </p>
            <p class="disc">50%</p>
            <v-row>
              <v-col lg="3">
                <img
                  src="https://storage.googleapis.com/periksain-legacy/laboratory/14/lab-logo/lab 9 logo.png"
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
              <v-col lg="4">
                <p class="loc">Surabaya</p>
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
export default {
  name: "Content",
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
  width: 9vw;
  height: 9vh;
  margin-left: 30px;
}
.antigen {
  border-radius: 15px;
  border: 1px solid #dfdfdf;
  width: 10vw;
  height: 9vh;
  margin-left: 30px;
}
.gula {
  border-radius: 15px;
  border: 1px solid #dfdfdf;
  width: 12vw;
  height: 9vh;
  margin-left: 10px;
}
.paru {
  border-radius: 15px;
  border: 1px solid #dfdfdf;
  width: 9vw;
  height: 9vh;
  margin-left: 10px;
}
.search {
  /* border: 1px solid #dfdfdf; */
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
.map2 {
  background-color: #f5f5f5;
  width: 2vw;
  height: 5vh;
  text-align: center;
  border-radius: 5px;
  margin-left: 20px;
}
.loc {
  font-size: 20px;
  margin-left: -20px;
  margin-top: 5px;
}
</style>
