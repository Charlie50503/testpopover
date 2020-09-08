<template>
  <div class="home">
	<span v-b-popover.hover.bottom="required_label">
		test
	</span>
	<span v-b-popover.hover.bottom="required_label">
		test
	</span>
	<span v-b-popover.hover.bottom="required_label">
		test
	</span>
	<span v-b-popover.hover.bottom="required_label">
		test
	</span>
  </div>
</template>

<script>
	export default {
		data() {
			return {
				required_label:'required',
			}
		},
		methods:{
			// jumpToNext() {
			// 	this.$router.push({
			// 		path: '/Next'
			// 	})
			// },
		},
		beforeDestroy(){
			console.log("beforeDestroy")
		},
	}
</script>
