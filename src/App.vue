<template>
  <v-app>
    <v-main>
      <!-- Hero Section -->
      <v-container fluid class="hero-section pa-4 pa-sm-15">
        <v-row align="center" justify="center" class="text-center">
          <v-col cols="12" md="8">
            <h1 class="text-h2 font-weight-bold mb-6">
              <span class="gradient-text">Transform Customer Feedback</span><br>
              Into Growth Opportunities
            </h1>
            <p class="text-h6 mb-8">
              Smart QR-based feedback system that turns unhappy customers into loyal ones
              and happy customers into Google reviewers
            </p>
            <v-btn
              size="x-large"
              color="primary"
              class="text-uppercase mb-4"
            >
              Start Free Trial
            </v-btn>
            <p class="text-caption">Only $10/month - Including 2 Elegant Tabletop Signs</p>
          </v-col>
        </v-row>

        <!-- Features Grid -->
        <v-row class="mt-16">
          <v-col cols="12" md="4">
            <v-card class="pa-4 h-100" elevation="0" rounded="lg">
              <v-icon size="48" color="primary" class="mb-4">mdi-qrcode</v-icon>
              <h3 class="text-h5 mb-4">Smart QR Codes</h3>
              <p>Elegant tabletop signs with QR codes that intelligently route customer feedback</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card class="pa-4 h-100" elevation="0" rounded="lg">
              <v-icon size="48" color="primary" class="mb-4">mdi-google</v-icon>
              <h3 class="text-h5 mb-4">Google Reviews Boost</h3>
              <p>Happy customers are guided to leave Google reviews, improving your online presence</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card class="pa-4 h-100" elevation="0" rounded="lg">
              <v-icon size="48" color="primary" class="mb-4">mdi-chart-bar</v-icon>
              <h3 class="text-h5 mb-4">Live Dashboard</h3>
              <p>Real-time insights into customer satisfaction with actionable KPIs</p>
            </v-card>
          </v-col>
        </v-row>

        <!-- How It Works Section -->
        <v-row class="mt-16 pt-16">
          <v-col cols="12" class="text-center mb-8">
            <h2 class="text-h3 font-weight-bold">
              <span class="gradient-text">How It Works</span>
            </h2>
          </v-col>
          <v-col cols="12" md="3">
            <v-card class="pa-4 h-100 text-center" elevation="0" rounded="lg">
              <v-icon size="64" color="primary" class="mb-4">mdi-table-furniture</v-icon>
              <h3 class="text-h6 mb-4">Place QR Signs</h3>
              <p>Set up elegant tabletop signs with smart QR codes</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="3">
            <v-card class="pa-4 h-100 text-center" elevation="0" rounded="lg">
              <v-icon size="64" color="primary" class="mb-4">mdi-cellphone-message</v-icon>
              <h3 class="text-h6 mb-4">Collect Feedback</h3>
              <p>Customers scan and share their experience</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="3">
            <v-card class="pa-4 h-100 text-center" elevation="0" rounded="lg">
              <v-icon size="64" color="primary" class="mb-4">mdi-star</v-icon>
              <h3 class="text-h6 mb-4">Route Reviews</h3>
              <p>Happy customers are guided to Google Reviews</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="3">
            <v-card class="pa-4 h-100 text-center" elevation="0" rounded="lg">
              <v-icon size="64" color="primary" class="mb-4">mdi-trending-up</v-icon>
              <h3 class="text-h6 mb-4">Grow Business</h3>
              <p>Monitor KPIs and improve customer satisfaction</p>
            </v-card>
          </v-col>
        </v-row>

        <!-- Testimonials Section -->
        <v-row class="mt-16 pt-16">
          <v-col cols="12" class="text-center mb-8">
            <h2 class="text-h3 font-weight-bold">
              <span class="gradient-text">What Restaurants Say</span>
            </h2>
          </v-col>
          <v-col cols="12" md="4">
            <v-card class="pa-6 h-100" elevation="1" rounded="lg">
              <v-rating
                model-value="5"
                color="amber"
                density="compact"
                readonly
                class="mb-4"
              ></v-rating>
              <p class="text-body-1 mb-4">"This system has transformed how we handle customer feedback. Our Google reviews increased by 40% in just two months!"</p>
              <p class="text-subtitle-1 font-weight-bold">Sarah Chen</p>
              <p class="text-caption">Owner, The Golden Spoon</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card class="pa-6 h-100" elevation="1" rounded="lg">
              <v-rating
                model-value="5"
                color="amber"
                density="compact"
                readonly
                class="mb-4"
              ></v-rating>
              <p class="text-body-1 mb-4">"The elegant QR stands fit perfectly with our decor, and the customer insights have been invaluable for our service improvement."</p>
              <p class="text-subtitle-1 font-weight-bold">Michael Rodriguez</p>
              <p class="text-caption">Manager, Bistro 301</p>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card class="pa-6 h-100" elevation="1" rounded="lg">
              <v-rating
                model-value="5"
                color="amber"
                density="compact"
                readonly
                class="mb-4"
              ></v-rating>
              <p class="text-body-1 mb-4">"The reward system keeps customers coming back, and we've built a great email list for our promotions. Best investment ever!"</p>
              <p class="text-subtitle-1 font-weight-bold">Emma Thompson</p>
              <p class="text-caption">Owner, Café Delight</p>
            </v-card>
          </v-col>
        </v-row>

        <!-- FAQ Section -->
        <v-row class="mt-16 pt-16">
          <v-col cols="12" class="text-center mb-8">
            <h2 class="text-h3 font-weight-bold">
              <span class="gradient-text">Frequently Asked Questions</span>
            </h2>
          </v-col>
          <v-col cols="12" md="8" offset-md="2">
            <v-expansion-panels>
              <v-expansion-panel>
                <v-expansion-panel-title>What's included in the $10/month subscription?</v-expansion-panel-title>
                <v-expansion-panel-text>
                  You get 2 premium tabletop QR code stands, access to the live dashboard, unlimited feedback collection, and customer email collection feature.
                </v-expansion-panel-text>
              </v-expansion-panel>
              <v-expansion-panel>
                <v-expansion-panel-title>How do the QR codes work?</v-expansion-panel-title>
                <v-expansion-panel-text>
                  Customers scan the QR code with their smartphone camera. They're then guided through a simple feedback process that routes positive reviews to Google Maps and negative feedback directly to management.
                </v-expansion-panel-text>
              </v-expansion-panel>
              <v-expansion-panel>
                <v-expansion-panel-title>Can I customize the reward discounts?</v-expansion-panel-title>
                <v-expansion-panel-text>
                  Yes! You can set custom discount amounts and terms through your dashboard. This helps you control your promotion strategy.
                </v-expansion-panel-text>
              </v-expansion-panel>
            </v-expansion-panels>
          </v-col>
        </v-row>

        <!-- CTA Section -->
        <v-row class="mt-16 pt-16 pb-16">
          <v-col cols="12" md="8" offset-md="2" class="text-center">
            <h2 class="text-h3 font-weight-bold mb-6">
              Ready to Transform Your Customer Feedback?
            </h2>
            <v-btn
              size="x-large"
              color="primary"
              class="text-uppercase mb-4"
            >
              Start Your Free Trial Today
            </v-btn>
            <p class="text-caption">No credit card required • 14-day free trial</p>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
// Component logic here
</script>

<style>
.gradient-text {
  background: linear-gradient(45deg, #2196F3, #FF4081);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-section {
  background: linear-gradient(to bottom, #f8f9fa, #ffffff);
  min-height: 100vh;
}

.v-card {
  transition: transform 0.3s ease;
  border: 1px solid #eee;
}

.v-card:hover {
  transform: translateY(-5px);
}

.v-expansion-panels {
  background: transparent !important;
}

.v-expansion-panel {
  background: white !important;
  margin-bottom: 16px !important;
  border: 1px solid #eee !important;
}

.v-expansion-panel-title {
  font-size: 1.1rem !important;
  font-weight: 500 !important;
}
</style>
