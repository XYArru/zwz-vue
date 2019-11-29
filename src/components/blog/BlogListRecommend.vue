<template>
  <div id="blog-list">
    <el-row>
      <el-col :span="16">
        <h3 style="float: left;font-family:yahei;padding-top:10px"><strong>Multi-channel higher-order local autocorrelation for object detection on satellite images</strong></h3>
        <div style="height:50px"></div>
        <div style="float: left;padding-top:10px">
          <el-tag label = "lalala">Uehara Kazuki</el-tag>
          <el-tag type="success">Nosato Hirokazu</el-tag>
          <el-tag type="info">Murakawa Masahiro </el-tag>
          <el-tag type="warning">Nakamura Ryosuke</el-tag>
          <el-tag type="danger">Miyamoto Hiroki</el-tag>
          <el-button type="primary" style="margin-left:180px;float:right"><a href="https://www.tandfonline.com/doi/full/10.1080/01431161.2019.1648904">Full-text</a></el-button>
        </div>
        <div style="height:110px"></div>
        <div>
          <el-card body-style="padding-left:10px;padding-top:0px" >
            <div style="float:left;font-family:yahei">
              <h3><Strong>Abstract</strong></h3>
            </div>
          </el-card>
          <el-card class="box-card">
            <div style="text-align:justify">
              <h4>An automatic object-detection method is necessary to facilitate the efficient analysis of satellite images consisting of multispectral images. Considering that the relationship between spectrums is important for discriminating objects in multispectral images. This paper proposes a feature extraction method that can capture both spatial and spectral relationships of the multispectral images. Moreover, image preprocessing and dimensionality reduction procedures are introduced for stable feature extraction. In this study, we conducted experiments for detecting two types of objects by using Landsat 8 images. The proposed method improved the detection performance relative to other image features.</h4>
            </div>
          </el-card>
        </div>
        <el-card body-style="padding-left:10px;padding-top:0px">
          <h4 style="float:left;font-family:yahei"><strong>Uncontrolled terms:</strong></h4>
          <h5 style="padding-top:14px"><font color='#007398'>Detection performance -  Dimensionality reduction -  Efficient analysis -  Feature extraction methods</font></h5>
        </el-card>
        <el-card body-style="padding-left:10px;padding-top:0px">
          <h4 style="float:left;font-family:yahei"><strong>Classification code:</strong></h4>
          <h5 style="padding-top:14px;"><font color='#007398'>723.2 Data Processing and Image Processing  -  802.3 Chemical Operations</font></h5>
        </el-card>
      </el-col>
      <el-col :span="7" style="margin-left:30px;margin-top:20px">
        <el-card class="box-card" style="background-color:#909399">
          <div style="color:#F5F5F5">
            <h3><strong>Related Documents</strong></h3>
          </div>
        </el-card>
        <el-card>
          <div style="width:100%;margin:0 auto">
            <font color='#007398'>VHR object detection based on structural feature extraction and query expansion</font><br>
            <font color='#007398'>Bai, Xiao ; Zhang, Huigang ; Zhou, Jun</font><br>
            <font>(2014) IEEE Transactions on Geoscience and Remote Sensing</font><br>
            <font>Database: Compendex</font><br>
            <font color='#007398'>Multi-scale geospatial object detection based on shallow-deep feature extraction</font><br>
            <font color='#007398'>AL-Alimi, Dalal ; Shao, Yuxiang ; Feng, Ruyi ; Al-Qaness, Mohammed A.A. ; Elaziz, Mohamed Abd ; Kim, Sunghwan</font><br>
            <font>(2019) Remote Sensing</font><br>
            <font>Database: Compendex</font><br>
            <font color='#007398'>Real-time object detection-based affordance feature extraction system using deep learning model</font><br>
            <font color='#007398'>Ko, KwangEun ; Sim, Kwee-Bo</font><br>
            <font>(2017) Journal of Institute of Control, Robotics and Systems</font><br>
            <font>Database: Compendex</font>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: 'BlogListRecommend',
  data () {
    return {
      currentPage: 1,
      pagesize: 10,
      blogList: []
    }
  },
  created: function () {
    this.handleBlogList()
  }
}
</script>

<style scoped>
  .text {
    font-size: 14px;
  }
  .box-card {
    width: 100%;
  }
</style>
