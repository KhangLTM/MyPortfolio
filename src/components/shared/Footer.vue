<template>
	<div class="container mx-auto pt-20 sm:pt-40 pb-8">
		<div class="flex flex-col justify-center items-center mb-12 sm:mb-28">
			<p
				class="text-3xl sm:text-4xl font-semibold text-primary-dark dark:text-primary-light mb-5"
			>
				Follow me
			</p>
			<ul class="flex gap-4 sm:gap-8">
				<a
					target="_blank"
					href="https://github.com/KhangLTM"
					class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm∫ p-4"
				>
					<i data-feather="github" class="w-6 sm:w-8 h-6 sm:h-8"></i>
				</a>
				<a
					href="#"
					target="__blank"
					class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm∫ p-4"
				>
					<i data-feather="twitter" class="w-6 sm:w-8 h-6 sm:h-8"></i>
				</a>
				<a
					href="#"
					target="__blank"
					class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm∫ p-4"
				>
					<i
						data-feather="instagram"
						class="w-6 sm:w-8 h-6 sm:h-8"
					></i>
				</a>
				<a
					href="#"
					target="__blank"
					class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm∫ p-4"
				>
					<i data-feather="feather" class="w-6 sm:w-8 h-6 sm:h-8"></i>
				</a>
			</ul>
		</div>
		
	</div>
</template>

<script>
import feather from 'feather-icons';
export default {
	mounted() {
		feather.replace();
	},
	updated() {
		feather.replace();
	},
};
</script>

<style scoped></style>
