<template>
	<div style="overflow: auto">
		<div id="navbar">
			<p style="font-size: 20px"><b>
				<ul>
					<li><img src="~/assets/TempLogo.svg" width=50 height=50/></li>
					<li>Home</li>
					<li>Tutorials</li>
					<li>About</li>
				</ul>
			</b></p>
		</div>
		<br>
	</div>
</template>

<style>
	#navbar {
		overflow-x: hidden;
	}
	#navbar ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		width: 80%;
		align-items: stretch;
		display: flex;
		justify-content: space-between;
		position: relative;
		left: 50%;
	}
	#navbar ul li {
		position: relative;
		left: -50%;
		text-align: center;
		display: block;
		flex: 0 0 auto;
	}
</style>