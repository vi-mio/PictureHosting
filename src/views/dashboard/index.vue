<template>
	<div class="dashboard-container">
    <div><h2  style="color: red">使用手册:</h2>
      <h3>本站仅供个人学习使用，禁止用于商业用途，因传播者的原因造成法律纠纷的，由传播者自行负责。</h3>
      <h3>本站上传的图片使用的是国内的CND加速服务，禁止上传(露骨/血腥/暴力/吸毒/R18)违法图片，否则将永久封禁，请遵守中华人民共和国相关法律法规，做一个爱国爱党，遵纪守法的中国公民。</h3>
    </div>
	</div>
</template>

<script>
	export default {
		name: 'Dashboard',

	}


</script>

<style lang="scss" scoped>
	.dashboard {
		&-container {
			margin: 30px;
		}

		&-text {
			font-size: 30px;
			line-height: 46px;
		}
	}

   h2,
   h3 {
     display: inline-block;
   }
</style>
