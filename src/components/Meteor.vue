<template>
  <div>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
  </div>
</template>

<script setup>
</script>

<style scoped>
/* 背景图 */
div{
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: url('@/assets/Meteor.jpg');
  background-size: cover;
  animation: donghua1 50s linear infinite;
}
/* 背景图动画 */
/* @keyframes donghua1 {
  0%,100%{
    transform: scale(1);
  }
  50%{
    transform: scale(1.2);
  }
} */
span{
  position: absolute;
  left: 30%;
  top: 30%;
  width: 6px;
  height: 6px;
  background-color: #fff;
  border-radius: 50%;
  box-shadow: 0 0 0 4px rgba(255,255,255,0.1),
  0 0 0 2px rgba(255,255,255,0.1),
  0 0 20px rgba(255,255,255,1);
  animation: donghua2 3s linear infinite;
  transform: rotate(330deg);
}
@keyframes donghua2{
  0%{
    transform: rotate(330deg) translateX(0);
    opacity: 1;
  }
  25%{
    opacity: 0;
  }
  50%{
    opacity: 1;
  }
  100%{
    transform: rotate(330deg) translateX(-900px);
    opacity: 0;
  }
}
span::before{
  content: '';
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 300px;
  height: 1px;
  /* linear-gradient() 函数用于创建一个表示两种或多种颜色线性渐变的图片。 */
  /* 渐变轴为90度 */
  background:linear-gradient(90deg,#fff,transparent);
}
span:nth-child(1){
  top: 0;
  right: 0;
  /* animation-delay CSS属性定义动画于何时开始 */
  animation-delay: 0s;
  /* animation-duration属性指定一个动画周期的时长。 */
  animation-duration: 3s;
}
span:nth-child(2){
  top: 20px;
  right: 50px;
  animation-delay: 0.1s;
  animation-duration: 4s;
}
span:nth-child(3){
  top: 41px;
  right: 54px;
  animation-delay: 0.4s;
  animation-duration: 8s;
}
span:nth-child(4){
  top: 300px;
  right: 233px;
  animation-delay: 0.2s;
  animation-duration: 5s;
}
span:nth-child(5){
  top: 100px;
  right: 10px;
  animation-delay: 0.1s;
  animation-duration: 12s;
}
span:nth-child(6){
  top: 600px;
  right: 700px;
  animation-delay: 0.4s;
  animation-duration: 5s;
}
span:nth-child(7){
  top: 100px;
  right: 432px;
  animation-delay: 0s;
  animation-duration: 9s;
}
span:nth-child(8){
  top: 500px;
  right: 345px;
  animation-delay: 0.2s;
  animation-duration: 8s;
}
span:nth-child(9){
  top: 60px;
  right: 1000px;
  animation-delay: 0.4s;
  animation-duration: 10s;
}
</style>