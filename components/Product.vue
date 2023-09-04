<template>
	<div>
		<div
			class="lg:h-[20rem] lg:w-[15rem] bg-emerald-500 relative">
			<img :src="image" class="absolute bottom-0" alt="" srcset="" />
		</div>
        <div>
            Price
        </div>
	</div>
</template>

<script setup lang="ts">

    const props = defineProps<{
        image : string, 
        color : string
    }>(); 
</script>

<style scoped></style>
