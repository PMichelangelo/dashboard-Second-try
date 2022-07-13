<script setup>
import HeaderItem from './components/HeaderItem.vue'
import AsideItem from './components/AsideItem.vue'
import MainItem from './components/MainItem.vue';
import MetricCard from './components/MetricCard.vue';
import Heatmap from './components/Heatmap.vue';
import ChartCardWIcon from './components/ChartCardWIcon.vue';
import ChartCard from './components/ChartCard.vue';

</script>

<template>
  <header>
    <HeaderItem>
    </HeaderItem>
  </header>

  <main class="main-app">
    <AsideItem></AsideItem>
    <div class="main-bar">
      <MainItem></MainItem>
      <div class="main-content">
        <div class="main-content-column">
          <div class="main-metricCard">
            <MetricCard></MetricCard>
            <MetricCard></MetricCard>
          </div>
          <Heatmap></Heatmap>
        </div>
        <div class="main-content-column">
          <ChartCardWIcon></ChartCardWIcon>
          <ChartCard></ChartCard>
        </div>
      </div>
    </div>
  </main>


</template>

<style>
html,
body {
  margin: 0;
  padding: 0;
  max-width: 100%;
}

header {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  padding: 0 24px;
  gap: 24px;
  height: 80px;
  background-color: #f2f9ff;
  backdrop-filter: blur(64px);
  border-bottom: 1px solid #E1E3E6;
}

.main-app {
  display: flex;
  flex-direction: row;
  margin: 24px;
  gap: 24px;
  max-width: 1300px;

}

.main-bar {
  max-width: fit-content;

  display: flex;
  flex-direction: column;
}

.main-metricCard {
  display: flex;
  flex-direction: row;
  gap: 24px;
}

.main-content {
  display: flex;
  flex-direction: row;
  gap: 24px;
  margin-top: 24px;

}

.main-content-column {
  display: flex;
  flex-direction: column;
  gap: 24px;
}
</style>
