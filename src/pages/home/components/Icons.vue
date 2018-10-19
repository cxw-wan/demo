<template>
  <div class="icons">
    <div class="icon" v-for="item in iconList" :key="item.id">
      <div class="icon_img">
        <img class="icon_img_style" :src="item.imgUrl" alt="">
      </div>
      <p class="icon_desc">{{item.desc}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeIcons',
  data: function () {
    return {
      iconList: [
        {
          id: '1001',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },
        {
          id: '1002',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/4c/eac47dd8def8de02.png',
          desc: '去赏花'
        },
        {
          id: '1003',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },
        {
          id: '1004',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },
        {
          id: '1005',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },
        {
          id: '1006',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },

        {
          id: '1007',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        },
        {
          id: '1008',
          imgUrl: 'http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png',
          desc: '景点门票'
        }
      ]
    }
  }
}
</script>

<style scoped>
.icons{
  width: 100%;
  height: 0;
  padding-bottom: 50%;

}
.icon{
  width: 25%;
  height: 0;
  padding-bottom: 25%;
  float: left;
  background: red;
  position: relative;
}
.icon_img{
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0.44rem;
}
.icon_img_style{
  height: 100%;
  margin: 0 auto;
}
.icon_desc{
  position: absolute;
  left:5px;
  right: 0;
  bottom: 0;
  padding-bottom: 5%;
}
</style>
