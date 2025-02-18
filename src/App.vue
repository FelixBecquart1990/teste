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
</style>
