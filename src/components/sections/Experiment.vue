<script setup>
const experient_implemention = './experient_implemention.png'
</script>
<template>
  <el-divider />
  <el-row justify="center">
      <h1 class="section-title">Data Distribute</h1>
  </el-row>
    <el-row justify="center">
      <el-col 
      :xs="24" :sm="24" :md="20" :lg="16" :xl="12"
      class="caption-container"
    >
      <p>
        We employed the SU17 UAV developed by AMOVLAB as the embodied platform.
        The vehicle integrates a gimbal-mounted forward-facing camera (configured at 1280 × 780 resolution) with an omnidirectional vision system, 
        and is controlled via the PX4 autopilot. A Wi-Fi signal module and a wireless receiver were mounted on top of the UAV to establish communication with the server, 
        while a grayscale camera was coupled with the SU17 to enable waypoint control through its API. To comprehensively assess its generalization capability, 
        we evaluate AirUni across a wide spectrum of real-world environments, covering both indoor (e.g., offices, bedrooms) and outdoor (e.g., industrial areas) scenarios.
      </p>
    </el-col>
    </el-row>
    <el-row justify="center" style="margin-top: 20px;">
      <el-col :xs="24" :sm="24" :md="20" :lg="16" :xl="12" >
        <el-container class="video-container">
          <!-- <img src="./cover.png" alt="cover" style="width: 100%; height: auto;"> -->
          <el-image :src="experient_implemention" style="width: 100%; height: auto;" fit="cover" />
        </el-container>
      </el-col>
    </el-row>
    

</template>
