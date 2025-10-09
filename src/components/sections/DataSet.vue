<script setup>
const data_distribute = './data_distribute.png'
const data_structure = './data_structure.png'
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
        We constructed a unified dataset of unprecedented scale, 
        comprising approximately 1.15M indoor samples and 1.25M outdoor samples, yielding a total of 2.4M navigation instances. 
        Built under a video-based multimodal paradigm, each sample contains a natural-language navigation instruction, 
        an egocentric image sequence (video frames), and the corresponding future action sequence.
      </p>
    </el-col>
    </el-row>
    <el-row justify="center" style="margin-top: 20px;">
      <el-col :xs="24" :sm="24" :md="20" :lg="16" :xl="12" >
        <el-container class="video-container">
          <!-- <img src="./cover.png" alt="cover" style="width: 100%; height: auto;"> -->
          <el-image :src="data_distribute" style="width: 100%; height: auto;" fit="cover" />
        </el-container>
      </el-col>
    </el-row>
    <el-row justify="center" style="margin-top: 20px;">
      <el-col :xs="20" :sm="20" :md="16" :lg="12" :xl="8" >
        <el-container class="video-container">
          <!-- <img src="./cover.png" alt="cover" style="width: 100%; height: auto;"> -->
          <el-image :src="data_structure" style="width: 100%; height: auto;" fit="cover" />
        </el-container>
      </el-col>
    </el-row>
    

</template>
