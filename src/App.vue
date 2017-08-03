<template>
  <div id="app">
  	<page-header></page-header>
  	<div class="tab">
  		<div class="tab-item">商品</div>
  		<div class="tab-item">评论</div>
  		<div class="tab-item">商家</div>
  	</div>
  	<div class="content">
  		I am the Content
  	</div>
  </div>
</template>

<script>
	import pageHeader from './components/pageHeader/pageHeader.vue';
	
	export default{
		components: {
			pageHeader
		}
	};
</script>

<style>
	.tab{
		display: flex;
		width: 100%;
		height: 40px;
		line-height: 40px;
	}
	.tab-item{
		flex: 1;
		text-align: center ;
	}
</style>
