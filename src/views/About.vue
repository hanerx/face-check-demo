<template>
  <div class="about">
    <h1>参数</h1>
    <h2>image</h2>
    <p>String 需要对比的人脸图像url</p>
    <h2>limit-time</h2>
    <p>Number 最大比对次数 默认1000</p>
    <h2>pass-rate</h2>
    <p>Number 识别通过的欧几里得距离 默认0.4</p>
    <h2>delay</h2>
    <p>Number 每次识别之间的间隔（毫秒） 默认100</p>
    <h2>model-delay</h2>
    <p>Number 加载模型的延时（毫秒），过低可能导致模型未加载报错 默认300</p>
    <h2>camera-style</h2>
    <p>String 显示框样式</p>
    <h2>label-style</h2>
    <p>String 提示框样式</p>
    <h1>函数</h1>
    <h2>onCheckSuccess(distance)</h2>
    <p>验证成功回调函数 参数distance-最后一次欧几里得距离</p>
    <h2>onCheckFailed(distance)</h2>
    <p>验证失败回调函数 参数distance-最后一次欧几里得距离</p>
  </div>
</template>
