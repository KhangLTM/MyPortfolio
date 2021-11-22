<template>
	
	<section class="pt-20 sm:pt-28">
		<div class="text-center">
			<p
				class="text-2xl sm:text-5xl font-semibold mb-3 text-ternary-dark dark:text-ternary-light"
			>
				Projects Portfolio
			</p>
			<p class="text-md sm:text-xl text-gray-500 dark:text-ternary-light">
				Some of the projects I have successfully completed
			</p>
		</div>

		<div class="grid grid-cols-1 sm:grid-cols-3 mt-16 sm:gap-10">
			<div
				to="/projects/single-project"
				class="rounded-3xl shadow-lg hover:shadow-xl cursor-pointer mb-10 sm:mb-0 bg-secondary-light dark:bg-ternary-dark"
			>
				<div>
					<a 
					target="_blank"
					href="https://vuepomodoro.netlify.app/">
						<img
							src="../../assets/images/ui-project-2.png"
							alt=""
							class="rounded-t-3xl border-none"
						/>
					</a>
				</div>
				<div class="text-center px-4 py-6">
					<p
						class="text-2xl text-ternary-dark dark:text-ternary-light font-semibold mb-2"
					>
						Vue Doro
					</p>
					<span
						class="text-lg text-ternary-dark dark:text-ternary-light"
						>Timer Application</span
					>
				</div>
			</div>
			<div
				class="rounded-3xl shadow-lg hover:shadow-xl cursor-pointer mb-10 sm:mb-0 bg-secondary-light dark:bg-ternary-dark"
			>
				<div>
					<a 
					target="_blank"
					href="https://vueflix-khangltm.netlify.app/">
						<img
							src="../../assets/images/ui-project-1.png"
							alt=""
							class="rounded-t-3xl border-none"
						/>
					</a>
				</div>
				<div class="text-center px-4 py-6">
					<p
						class="text-2xl text-ternary-dark dark:text-ternary-light font-semibold mb-2"
					>
						VueFlix
					</p>
					<span
						class="text-lg text-ternary-dark dark:text-ternary-light"
						>NetFlix Clone</span
					>
				</div>
			</div>
			<div
				class="rounded-3xl shadow-lg hover:shadow-xl cursor-pointer mb-10 sm:mb-0 bg-secondary-light dark:bg-ternary-dark"
			>
				<div>
					<a 
					target="_blank"
					href="https://vuemmerce-khangltm.netlify.app/">
					<img
						src="../../assets/images/ui-project(1)-3.png"	
						alt=""
						class="rounded-t-3xl border-none"
					/>
					</a>
				</div>
				<div class="text-center px-4 py-6">
					<p
						class="text-2xl text-ternary-dark dark:text-ternary-light font-semibold mb-2"
					>
						Vuemmerce
					</p>
					<span
						class="text-lg text-ternary-dark dark:text-ternary-light"
						>  UI/Ecommerce</span
					>
				</div>
			</div>
			
			
			
		</div>
		
	</section>
</template>

<script>
import feather from 'feather-icons';

export default {
	name: 'Projects',
	mounted() {
		feather.replace();
	},
	updated() {
		feather.replace();
	},
};
</script>

<style scoped></style>
