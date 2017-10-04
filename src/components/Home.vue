<template>
	<div>
		<p>Yours Funds: {{ funds | currency }}</p>
	</div>
</template>

<script>
	export default {
	    computed: {
	        funds() {
                return this.$store.getters.funds;
            }
		}
	}
</script>

<style>
</style>