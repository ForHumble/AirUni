<script setup>
const model_arch = './data_distribute.png'
</script>
<template>
  <el-divider />
  <el-row justify="center">
      <h1 class="section-title">Data Distribute</h1>
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
        We collect and construct a joint indoor–outdoor navigation (ION) dataset comprising 2.4M samples. 
        Built under a video-based multimodal paradigm, each sample contains a natural-language navigation instruction, 
        an egocentric image sequence (video frames), and the corresponding future action sequence.
      </p>
    </el-col>
    </el-row>

</template>
