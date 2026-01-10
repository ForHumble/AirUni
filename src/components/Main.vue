<script>
import Title from './sections/Title.vue'
import Abstract from './sections/Abstract.vue'
import Markdown from './sections/Markdown.vue'
import BibTeX from './sections/BibTeX.vue'
import Carousel from './sections/Carousel.vue'
import Video from './sections/Video.vue'
import ImageSlider from './sections/ImageSlider.vue'
import ImageSliderInner from './sections/ImageSliderInner.vue'
import ImageSelector from './sections/ImageSelector.vue'
import Echart from './sections/Echart.vue'
import Table from './sections/Table.vue'
import Collapse from './sections/Collapse.vue'
import SeletionForComparison from './sections/SeletionForComparison.vue'
import Comment from './sections/Comment.vue'
import Latex from './sections/Latex.vue'
import Model3D from './sections/Model3D.vue'
import GaussianSplats3D from './sections/GaussianSplats3D.vue'
import AirUniArchitecture from './sections/AirUniArchitecture.vue'
import DataSet from './sections/DataSet.vue'
import R2RVideo from './sections/R2RVideo.vue'
import RxRVideo from './sections/RxRVideo.vue'
import Experiment from './sections/Experiment.vue'
import RealExperiment from './sections/RealExperiment.vue'
import AerialVideo from './sections/AerialVideo.vue'
  
  
export default {
  components: {
    Title,
    Abstract,
    Markdown,
    BibTeX,
    // Carousel,
    R2RVideo,
    RxRVideo,
    AerialVideo,
    AirUniArchitecture,
    DataSet,
    Experiment,
    RealExperiment,
    // Echart,
    // Collapse,
    // Table,
    // SeletionForComparison,
    // Comment,
    // Latex,
    // Model3D,
    // GaussianSplats3D
  }
}
</script>

<template>
  <Title/>
  <Abstract/>
  <AirUniArchitecture/>
  <DataSet/>
  <R2RVideo/>
  <RxRVideo/>
  <AerialVideo/>
  <Experiment/>
  <RealExperiment/>
  <BibTeX/>
</template>
