<template>
	<div>
		<div class="nv-navbar">
			<ul class="nav">
				<li><router-link :to="{ name: 'blogs' }">Blogs</router-link></li>
				<li><router-link :to="{ name: 'users' }">Users</router-link></li>
				<li><router-link :to="{ name: 'login' }">Login</router-link></li>
				<li><router-link :to="{ name: 'blogs' }">Blogs</router-link></li>
			</ul>
			<div class="clearfix" />
		</div>
	</div>
</template>
<script>
export default {};
</script>
<style scoped>
.nv-navbar {
	background-color: rgb(202, 224, 231);
	width: 100%;
	padding: 10px 0px 10px 0px;
}
.nv-navbar .nav {
	list-style: none;
	margin: 0;
	padding: 0;
	float: left;
}
.nv-navbar .nav li {
	float: left;
}
.nv-navbar .nav li a {
	padding: 10px;
	text-decoration: none;
	color: rgb(24, 22, 22);
	font-weight: bold;
}
.nv-navbar .nav li a:hover {
	padding: 10px;
	text-decoration: none;
	color: rgb(4, 39, 39);
}
.nv-navbar .nav li a.router-link-active {
	background-color: rgb(150, 212, 214);
	color: rgb(4, 53, 53);
}
.clearfix {
	clear: left;
}
</style>
