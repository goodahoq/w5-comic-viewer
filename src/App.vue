<template>
	<div id="app">
		<PageHeader/>
		<transition name="fade" mode="out-in" appear>
			<router-view style="padding:60px 0 40px 0" :key="$route.fullPath" />
		</transition>
		<PageFooter/>
	</div>
</template>
 
<script>
import PageFooter from '@/components/PageFooter'
import PageHeader from '@/components/PageHeader'
export default {
  name: 'App',
  components: {
    PageFooter,
    PageHeader
  }
}
</script>

<style lang="scss" src="./assets/style/main.scss">
</style>
