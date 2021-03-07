<template>
	<router-view />
</template>

<style lang="scss">
	@import url('https://fonts.googleapis.com/css2?family=Jura:wght@400;700&display=swap');

	* {
		box-sizing: border-box;
	}

	html, body {
		width: 100%;
		height: 100%;
		margin: 0;
		padding: 0;
		font-family: 'Jura', sans-serif!important;
	}

	::-webkit-scrollbar {
		width: 4px;
	}

	/* Track */
	::-webkit-scrollbar-track {
		box-shadow: inset 0 0 5px grey; 
		border-radius: 5px;
	}
	
	/* Handle */
	::-webkit-scrollbar-thumb {
		background: black; 
		border-radius: 5px;
	}

	/* Handle on hover */
	::-webkit-scrollbar-thumb:hover {
		background: gray; 
	}
</style>
