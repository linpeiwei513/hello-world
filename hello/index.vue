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

<style>
    .hello{
        height: 100px;
    }
</style>