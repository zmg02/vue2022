<template>
	<div id="app">
		<MHeader />
		<MSearch />
		<MTab />
		<MBanner />
		<MContent />
		<MFooter />
		<MAside />
	</div>
</template>

<script>
import MHeader from "./components/MHeader"
import MSearch from "./components/MSearch"
import MTab from "./components/MTab"
import MBanner from "./components/MBanner"
import MContent from "./components/MContent"
import MFooter from "./components/MFooter"
import MAside from "./components/MAside"

export default {
  name:'App',
  components:{MHeader,MSearch,MTab,MBanner,MContent,MFooter,MAside},
  
}
</script>

<style>
*{
	margin: 0px;
	padding: 0px;
	list-style: none;
}
</style>