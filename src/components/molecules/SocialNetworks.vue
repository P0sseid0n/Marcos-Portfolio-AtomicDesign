<template>
	<div class="social-networks">
		<SocialLink icon="facebook" to="https://facebook.com" />
		<SocialLink icon="github" to="https://github.com" />
		<SocialLink icon="twitter" to="https://twitter.com" />
	</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
	components: { SocialLink },
})
</script>

<style scoped>
</style>