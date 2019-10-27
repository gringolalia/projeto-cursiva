<template lang="pug">

#app

	i-navbar._sticky-top.with.dignity(variant='light')
		i-navbar-brand(to='/' style="font-size: 20px;") 
			i.fas.fa-chess-knight.fa-2x
			| &nbsp;&nbsp;Engenho Novo LLC
		i-navbar-items
			i-nav
				i-nav-item(:to='{ name: \'index\' }') In Principio
				i-nav-item(:to='{ name: \'about\' }') In Media Res
				i-nav-item(:to='{ name: \'contact\' }') Nobres e Pobres

	router-view

</template>

<style lang="less">

#app {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
#nav {
	padding: 30px;
	a {
		font-weight: bold;
		color: #2c3e50;
		&.router-link-exact-active {
			color: #42b983;
		}
	}
}

</style>
