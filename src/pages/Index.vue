<template>
  <q-page>
    <div class="">
      <div class="row q-pa-md">
        <div class="col-md-6 col-sm-12 col-xs-12 q-pl-xl q-mt-xl gt-xs">
          <div class="text-h2 text-white text-weight-bold q-mt-xl">
            <div class="text-primary">EASIEST PAYMENT</div>
            METHOD EVER
          </div>
          <div class="text-h6 text-grey-5 text-weight-light q-mt-lg">
            {{ lorem }}<br />{{ lorem1 }}
          </div>
          <q-btn class="text-subtitle1 q-mr-md text-weight-light q-mt-lg" rounded color="primary" label="Get Started" />
          <q-btn class="text-h6 text-weight-light q-mt-lg text-white bg-transparent" rounded label="Contact Us" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 q-pl-md q-mt-md lt-sm">
          <div class="text-h4 text-white text-weight-bold q-mt-md">
            <div class="text-primary">EASIEST PAYMENT</div>
            METHOD EVER
          </div>
          <div class="text-h6 text-grey-5 text-weight-light q-mt-lg">
            {{ lorem }}<br />{{ lorem1 }}
          </div>
          <q-btn class="text-subtitle1 q-mr-md text-weight-light q-mt-lg" rounded color="primary" label="Get Started" />
          <q-btn class="text-h6 text-weight-light q-mt-lg text-white bg-transparent" rounded label="Contact Us" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 gt-xs q-pl-xl">
          <q-img width="600px" class="q-mt-xl" src="~assets/home-img-big@2x-e1609121743866.png">
            <q-img src="~assets/Efficiencydark-1.png" width="300px" style="margin-left: 300px" />
          </q-img>
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 lt-sm">
          <q-img width="310px" class="q-mt-xl" src="~assets/home-img-big@2x-e1609121743866.png">
            <q-img src="~assets/Efficiencydark-1.png" width="150px" style="margin-left: 130px" />
          </q-img>
        </div>
      </div>
      <!-- ------------------------- -->
      <div class="row q-col-gutter-lg q-pa-md">
        <div class="col-md-6 col-sm-12 col-xs-12 gt-xs">
          <q-img class="q-mr-lg q-mt-xl" width="600px" src="~assets/app-mockup-2-a@2x-e1610431074808.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 lt-sm q-pt-lg">
          <q-img class="" width="320px" src="~assets/app-mockup-2-a@2x-e1610431074808.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 q-mt-xl gt-xs">
          <div class="text-h2 text-white text-weight-medium">
            Manage Everything in Your Hand
          </div>
          <div class="text-subtitle1 text-grey-5 text-weight-light q-mt-lg">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae
            ab illo inventore veritatis et quasi architecto beatae vitae dicta
            sunt explicabo.
          </div>

          <div class="row" v-for="product in product" :key="product">
            <div class="col-2">
              <q-icon class="bg-primary q-mt-lg q-pa-md text-grey-4" size="50px" :name="product.icon"
                style="border-radius: 50px" />
            </div>
            <div class="col-7 q-mt-lg">
              <div class="text-h5 text-primary">{{ product.name }}</div>
              <div class="text-subtitle1 text-grey-5">
                {{ product.lorem }}
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 q-mt-xl lt-sm">
          <div class="text-h4 text-white text-weight-medium">
            Manage Everything in Your Hand
          </div>
          <div class="text-subtitle1 text-grey-5 text-weight-light q-mt-lg">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae
            ab illo inventore veritatis et quasi architecto beatae vitae dicta
            sunt explicabo.
          </div>

          <div class="row" v-for="product in product" :key="product">
            <div class="col-3">
              <q-icon class="bg-primary q-mt-lg q-pa-md text-grey-4" size="30px" :name="product.icon"
                style="border-radius: 50px" />
            </div>
            <div class="col-9 q-mt-lg">
              <div class="text-h5 text-primary">{{ product.name }}</div>
              <div class="text-subtitle1 text-grey-5">
                {{ product.lorem }}
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- --------------------------->
      <div class="row q-pa-md q-mt-xl">
        <div class="col-md-6 col-sm-12 col-xs-12 gt-xs">
          <div class="text-h2 text-weight-bold text-white" style="margin-top: 200px">
            Enjoy Various Merchant's Promos
          </div>
          <div class="text-subtitle1 q-mt-lg text-grey-5">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium,<br /> totam rem aperiam, eaque ipsa quae
            ab illo inventore veritatis et quasi architecto beatae vitae dicta
            sunt explicabo.
          </div>
          <q-btn class="text-subtitle1 q-mr-md text-weight-light q-mt-lg" rounded color="primary" label="Get Started" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 lt-sm">
          <div class="text-h4 text-weight-bold text-white">
            Enjoy Various Merchant's Promos
          </div>
          <div class="text-subtitle1 q-mt-lg text-grey-5">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium,<br /> totam rem aperiam, eaque ipsa quae
            ab illo inventore veritatis et quasi architecto beatae vitae dicta
            sunt explicabo.
          </div>
          <q-btn class="text-subtitle1 q-mr-md text-weight-light q-mt-lg" rounded color="primary" label="Get Started" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 gt-xs">
          <q-img width="600px" src="~assets/shopping-girl-home1@2x.jpg" style="border-radius: 20px">
            <q-img class="bg-transparent" src="~assets/shape-1@2x.png"> </q-img>
          </q-img>
          <q-img src="~assets/Last-Costslast-cost.png" width="250px" style="margin-top: -150px" />
          <q-img class="bg-transparent" width="300px" style="margin-top: -620px; margin-left: 50px"
            src="~assets/shopping-icon-home@2x.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 lt-sm q-mt-lg">
          <q-img width="320px" src="~assets/shopping-girl-home1@2x.jpg" style="border-radius: 20px">
            <q-img class="bg-transparent" src="~assets/shape-1@2x.png"> </q-img>
          </q-img>
          <q-img src="~assets/Last-Costslast-cost.png" width="150px" style="margin-top: -150px" />
          <q-img class="bg-transparent" width="150px" style="margin-top: -320px; margin-left: 170px"
            src="~assets/shopping-icon-home@2x.png" />
        </div>
      </div>
    </div>
    <!-- ------------------------- -->
    <q-img class="q-mt-md" width="100%" height="870px" src="~assets/bg-halftone@2x.png">
      <div class="absolute-top bg-transparent q-mt-md" style="text-align: center">
        <div class="text-h3 text-weight-medium">Our Service</div>
        <div class="text-subtitle1 text-weight-light q-mt-lg">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit
          <br />
          aut fugit, sed quia consequuntur magni dolores eos qui ratione.
        </div>
        <!-- ----card---- -->
        <div class="row q-mt-xs text-white q-col-gutter-md gt-xs" style="text-align:left">
          <div class="col-md-4 col-sm-6 col-xs-12" v-for="item in user" :key="item">
            <q-card class="my-card q-pa-md bg-negative text-white">
              <q-icon class="q-mb-xs q-pl-md" size="50px" :name="item.icon" />
              <q-card-section>
                <div class="text-h6">{{ item.name }}</div>
              </q-card-section>
              <q-card-section>
                <div class="text-subtitle2">{{ item.lorem }}</div>
              </q-card-section>
              <q-card-section class="text-h6 q-pa-md">
                Learn
                <q-icon name="fas fa-arrow-right" />
              </q-card-section>
            </q-card>
          </div>
          <div class="col-4" style="text-align: center">
            <div class="text-body1 text-weight-light q-mt-xl">
              We have a lot of powerful service that you <br />
              can get. Check for more of our available <br />
              services in our product.
            </div>
            <q-btn class="q-mt-md text-subtitle1" color="primary" label="VIEW MORE" style="border-radius: 20px" />
          </div>
        </div>
        <div class="row q-mt-xs text-white lt-sm" style="text-align:center">
          <div class="col-md-4 col-sm-6 col-xs-12" v-for="item in user" :key="item">
            <q-card class="my-card q-pa-md bg-negative text-white">
              <q-icon class="q-mb-xs q-pl-md" size="50px" :name="item.icon" />
              <q-card-section>
                <div class="text-h6">{{ item.name }}</div>
              </q-card-section>
              <q-card-section>
                <div class="text-subtitle2">{{ item.lorem }}</div>
              </q-card-section>
              <q-card-section class="text-h6 q-pa-md">
                Learn
                <q-icon name="fas fa-arrow-right" />
              </q-card-section>
            </q-card>
          </div>
          <!-- <div class="col-4" style="text-align: center">
            <div class="text-body1 text-weight-light q-mt-xl">
              We have a lot of powerful service that you <br />
              can get. Check for more of our available <br />
              services in our product.
            </div>
            <q-btn class="q-mt-md text-subtitle1" color="primary" label="VIEW MORE" style="border-radius: 20px" />
          </div> -->
        </div>
        <!-- -------- -->
      </div>
    </q-img>
    <!-- ------------------------- -->
    <div class="q-pa-lg q-mb-xl gt-xs" style="text-align: center">
      <q-img src="~assets/quoite-left-black@2x.png" width="100px" color="primary" text-color="white"
        style="z-index: 1" />
      <q-img class="bg-primary" src="~assets/halftone-subs-white@2x.png"
        style="border-radius: 10px 100px 10px 100px; margin-top: -30px">
        <div class="row bg-transparent">
          <div class="col-5" style="padding-left: 150px; padding-top: 50px">
            <q-avatar size="100px">
              <q-img src="~assets/testi-foto@2x@2x-e1610431253715.jpg"></q-img>
            </q-avatar>
            <div class="text-h6 text-dark">Jane Daya</div>
            <div class="text-body1 text-white">Customer</div>
          </div>
          <div class="col-1" style="margin-top: 40px; border-right: 2px solid white"></div>
          <div class="col-6" style="padding-top: 50px">
            <div class="text-subtitle1">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque<br />
              laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
              veritatis et quasi<br />
              architecto beatae vitae dicta sunt explicabo.
            </div>
          </div>
        </div>
      </q-img>
    </div>
    <!-- ------------------------- -->
    <div class="q-pa-md q-mb-xl lt-sm" style="text-align: center">
      <q-img src="~assets/quoite-left-black@2x.png" width="40px" color="primary" text-color="white"
        style="z-index: 1" />
      <q-img height="120px" class="bg-primary" src="~assets/halftone-subs-white@2x.png"
        style="border-radius: 5px 80px 5px 80px; margin-top: -10px">
        <div class="row bg-transparent q-pl-md">
          <div class="col-4">
            <q-avatar size="50px">
              <q-img src="~assets/testi-foto@2x@2x-e1610431253715.jpg"></q-img>
            </q-avatar>
            <div class="text-caption text-dark">Jane Daya</div>
            <div class="text-body2 text-white">Customer</div>
          </div>
          <div class="col-1" style="border-right: 2px solid white; height: 80px;"></div>
          <div class="col-7" style="padding-top: 10px">
            <div class="text-white" style="font-size: 10px">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque<br />
              laudantium, totam rem aperiam, eaque
            </div>
          </div>
        </div>
      </q-img>
    </div>
    <!-- ------------------------- -->
    <div class="q-pa-md">
      <div class="row gt-xs">
        <div class="col-md-6 col-sm-12 col-xs-12" style="margin-top: 100px">
          <div class="text-h2 text-white text-weight-medium">
            Support Payment<br />
            From Every Plartform
          </div>
          <div class="text-subtitle1 text-grey-5 text-weight-light q-mt-lg">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae
            ab illo inventore veritatis et quasi architecto beatae vitae dicta
            sunt explicabo.
          </div>
          <div class="text-h6 q-mt-md text-white">Support Payment :</div>
          <div class="row q-mt-md text-white">
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-mastercard" />
            </div>
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-visa" />
            </div>
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-paypal" />
            </div>
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-stripe" />
            </div>
          </div>
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div class="col-6">
            <q-img width="650px" src="~assets/payment-img@2x.jpg">
              <q-img class="bg-transparent" src="~assets/shape-img2@2x.png">
              </q-img>
            </q-img>
            <q-img src="~assets/Last-Operation1.png" width="250px" style="margin-top: -300px" />
            <q-img class="bg-transparent" width="300px" style="margin-top: -720px; margin-left: 50px"
              src="~assets/payment-icon-home@2x.png" />
          </div>
        </div>
      </div>
      <div class="row lt-sm">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div class="text-h4 text-white text-weight-medium">
            Support Payment<br />
            From Every Plartform
          </div>
          <div class="text-subtitle1 text-grey-5 text-weight-light q-mt-lg">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae
            ab illo inventore veritatis et quasi architecto beatae vitae dicta
            sunt explicabo.
          </div>
          <div class="text-h6 q-mt-md text-white">Support Payment :</div>
          <div class="row q-mt-md text-white">
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-mastercard" />
            </div>
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-visa" />
            </div>
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-paypal" />
            </div>
            <div class="col-md-2 col-sm-2 col-xs-3">
              <q-icon color="primary" size="60px" name="fab fa-cc-stripe" />
            </div>
          </div>
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12 q-mt-lg">
          <q-img width="300px" src="~assets/payment-img@2x.jpg">
            <q-img class="bg-transparent" src="~assets/shape-img2@2x.png">
            </q-img>
          </q-img>
          <q-img class="bg-transparent" width="100px" style="margin-top: -360px; margin-left: 30px"
            src="~assets/payment-icon-home@2x.png" />
          <q-img src="~assets/Last-Operation1.png" width="100px" style="margin-top: -450px; margin-left: 70px;" />
        </div>
      </div>
      <!-- ------------------------- -->
      <q-img class="q-mt-xl bg-primary gt-xs" src="~assets/halftone-subs-white@2x.png"
        style="border-radius: 100px 20px 100px 20px">
        <div class="row bg-transparent" style="padding: 100px">
          <div class="col-6">
            <div class="text-h2 text-weight-bold">
              Keep Updated About Our Product
            </div>
          </div>
          <div class="col-6">
            <q-input class="bg-white" v-model="text" outlined rounded type="text" placeholder="Your E-mail Address"
              style="width: 590px; border-radius: 28px">
              <q-btn class="text-body1 q-mt-xs" color="primary" label="SUBMIT"
                style="width: 160px; height: 50px; border-radius: 28px" />
            </q-input>
          </div>
        </div>
      </q-img>
      <q-img height="110px" class="q-mt-xl bg-primary lt-sm" src="~assets/halftone-subs-white@2x.png"
        style="border-radius: 60px 5px 60px 5px">
        <div class="row bg-transparent">
          <div class="col-md-6 col-sm-12 col-xs-12">
            <div class="text-subtitle1 text-weight-bold q-ml-lg">
              Keep Updated About Our Product
            </div>
          </div>
          <div class="col-md-6 col-sm-12 col-xs-12">
            <q-input dense class="bg-white" v-model="text" outlined rounded type="text"
              placeholder="Your E-mail Address" style="width: 300px; border-radius: 28px">
              <q-btn dense class="text-body1 q-mt-xs" color="primary" label="SUBMIT"
                style="width: 80px; height: 20px; border-radius: 28px" />
            </q-input>
          </div>
        </div>
      </q-img>
      <!-- ------------------------- -->
      <div class="row q-my-xl">
        <div class="col-md-4 col-sm-4 col-xs-12">
          <q-img src="~assets/logo-new@2x.png" width="150px" />
          <div class="text-subtitle1 q-mt-lg text-grey-5">
            One Application for Every Payment
          </div>
          <div class="row q-mt-lg text-primary">
            <div class="col">
              <q-icon size="40px" name="fab fa-apple"></q-icon>
            </div>
            <div class="col">
              <q-icon size="40px" name="fab fa-google-play"></q-icon>
            </div>
            <div class="col">
              <q-icon size="40px" name="fab fa-app-store-ios"></q-icon>
            </div>
          </div>
        </div>
        <!-- -------------- -->
        <div class="col-md-2 col-sm-4 col-xs-6 q-mt-md">
          <div class="text-h6 text-primary">Other Pages</div>
          <div class="text-subtitle1 text-grey-5">Home</div>
          <div class="text-subtitle1 text-grey-5">About Us</div>
          <div class="text-subtitle1 text-grey-5">Service</div>
          <div class="text-subtitle1 text-grey-5">Contact</div>
        </div>
        <!-- -------------- -->
        <div class="col-md-2 col-sm-4 col-xs-6 q-mt-md">
          <div class="text-h6 text-primary">QuicK Links</div>
          <div class="text-subtitle1 text-grey-5">Privacy Policy</div>
          <div class="text-subtitle1 text-grey-5">Term Of Service</div>
          <div class="text-subtitle1 text-grey-5">Disclaimer</div>
          <div class="text-subtitle1 text-grey-5">Credits</div>
        </div>
        <!-- -------------- -->
        <div class="col-md-2 col-sm-4 col-xs-12 q-mt-md">
          <div class="text-h6 text-primary">Social Media</div>
          <div class="text-subtitle1 text-grey-5">
            Our Support and Sales team is available 24 /7 to answer your queries
          </div>
          <div class="row q-mt-lg">
            <div class="col-3">
              <q-icon color="primary" name="fab fa-facebook" size="20px" />
            </div>
            <div class="col-3">
              <q-icon color="primary" name="fab fa-instagram" size="20px" />
            </div>
            <div class="col-3">
              <q-icon color="primary" name="fab fa-linkedin" size="20px" />
            </div>
            <div class="col-3">
              <q-icon color="primary" name="fab fa-twitter" size="20px" />
            </div>
          </div>
        </div>
      </div>
      <!-- ------------------------- -->
      <hr />
      <!-- ------------------------- -->
      <div class="row q-my-sm q-pt-sm">
        <div class="col-md-3 col-sm-3 col-xs-6">
          <div class="text-subtitle2 text-weight-bold text-grey-5">
            P o w e r S o f t
          </div>
        </div>
        <div class="col-md-6 col-sm-3 col-xs-5"></div>
        <div class="col-md-3 col-sm-3 col-xs-7">
          <div class="text-caption text-grey-5">
            Copyright © 2022. All rights reserved.
          </div>
        </div>
      </div>
      <!-- ------------------------- -->
    </div>
  </q-page>
</template>
<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      text: ref(""),
      slide: ref(1),
      lorem:
        "Sed ut perspiciatis unde omnis iste natus error sit",
      lorem1: "voluptatem accusantium doloremque laudantium, totam rem aperiam.",
      user: [
        {
          icon: "fas fa-money-check-alt",
          name: "Payment Management",
          lorem:
            "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.",
        },
        {
          icon: "fas fa-chart-line",
          name: "Personal Dashboard",
          lorem:
            "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.",
        },
        {
          icon: "fas fa-closed-captioning",
          name: "Integrated Payments",
          lorem:
            "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.",
        },
        {
          icon: "fas fa-business-time",
          name: "Business Tracking",
          lorem: "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.",
        },
        {
          icon: "fas fa-credit-card",
          name: "Credit & Debit Card",
          lorem: "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.",
        },
      ],
      product: [
        {
          icon: "fas fa-mobile-alt",
          name: "User Friendly",
          lorem:
            "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.",
        },
        {
          icon: "fas fa-headset",
          name: "Best Support",
          lorem:
            "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.",
        },
        {
          icon: "fas fa-lock",
          name: "Secure",
          lorem:
            "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.",
        },
      ],
    };
  },
};
</script>
