<script setup>
const model_arch = './airuni_arch.png'
</script>
<template>
  <el-divider />
  <el-row justify="center">
      <h1 class="section-title">AirUni Architecture</h1>
  </el-row>
    <el-row justify="center" style="margin-top: 20px;">
      <el-col :xs="24" :sm="24" :md="20" :lg="16" :xl="12" >
        <el-container class="video-container">
          <!-- <img src="./cover.png" alt="cover" style="width: 100%; height: auto;"> -->
          <el-image :src="model_arch" style="width: 100%; height: auto;" fit="cover" />
        </el-container>
      </el-col>
    </el-row>
    <el-row justify="center">
      <el-col 
      :xs="24" :sm="24" :md="20" :lg="16" :xl="12"
      class="caption-container"
    >
      <p>
        Overview of the AirUniNav architecture. The model is trained on a large-scale 
        joint indoor–outdoor dataset containing 2.4M samples. It receives multimodal 
        inputs, including textual instructions, historical visual observations, 
        and the current visual frame, and outputs a sequence of predicted actions 
        for the next k time steps.
      </p>
    </el-col>
    </el-row>

</template>
