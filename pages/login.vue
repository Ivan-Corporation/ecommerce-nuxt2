<template>
	<v-container class="login-container">
		<h1>Login</h1>

		<UserAuthForm buttonText="Login" :submitForm="loginUser" />
	</v-container>
</template>

<script>
import UserAuthForm from '@/components/UserAuthForm'

export default {
	components: {
		UserAuthForm
	},
	methods: {
		loginUser(logininfo) {
			// this.$auth.loginWith('local', {
			// 	data: logininfo
			// })
			alert('You pressed a button')

		}
	}
}
</script>

<style lang="scss" scoped>
.login-container {
	margin-top: 10%;
	width: 50%;
}
</style>