<!--
	* 页面标题描述
	* by linpeiwei
	* to 2020.03.03
-->
<template>
	<div class="hello">
		<h1>{{title}}</h1>
	</div>
</template>

<script>
	export default {
		name: 'hello',
		data () {
			return {
				title: '这是一个测试的数据标题',
			}
		},
		//页面加载后是执行
		created() {
			
		}
	}
</script>

<style scoped lang="scss">
    .hello{
        height: 100px;
    }
</style>