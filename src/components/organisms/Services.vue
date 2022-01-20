<template>
	<div class="services">
		<Service
			title="Front end"
			description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eos, blanditiis. Accusamus quia ipsam, omnis quam, nemo
		eaque minima dolore non et modi ut recusandae quis quibusdam commodi quae veniam consectetur."
		/>
		<Service
			title="Back end"
			description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eos, blanditiis. Accusamus quia ipsam, omnis quam, nemo
		eaque minima dolore non et modi ut recusandae quis quibusdam commodi quae veniam consectetur."
		/>
		<Service
			title="Manutenção"
			description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eos, blanditiis. Accusamus quia ipsam, omnis quam, nemo
		eaque minima dolore non et modi ut recusandae quis quibusdam commodi quae veniam consectetur."
		/>
	</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
	components: { Service },
})
</script>

<style scoped>
.services {
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	grid-gap: 5rem;
}
</style>