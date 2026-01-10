<script setup>
const experient_implemention = './experient_implemention.png'
</script>
<template>
  <el-divider />
  <el-row justify="center">
      <h1 class="section-title">Real-world experiments</h1>
  </el-row>
    <el-row justify="center">
      <el-col 
      :xs="24" :sm="24" :md="20" :lg="16" :xl="12"
      class="caption-container"
    >
      <p>
       For real-world validation, we employed the SU17 UAV developed by AMOVLAB and the Owl UAV as the embodied platform. Both UAVs integrate a gimbal-mounted forward-facing camera with an omnidirectional vision system, and is controlled via the PX4 autopilot. A Wi-Fi signal module and a wireless receiver were mounted on top of the UAV to establish communication with the server, while a grayscale camera was coupled with the UAV to enable waypoint control through its API.
      </p>
    </el-col>
    </el-row>
    

</template>
