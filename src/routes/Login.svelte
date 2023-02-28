<script>
</script>

<div class="content">
	<img alt="top_left" src="/Vector.svg" class="top_left" />
	<img alt="top_right" src="/Top Right Blob.svg" class="top_right" />
	<img alt="bot_left" src="/Bottom Left Blob.svg" class="bot_left" />
	<img alt="bot_right" src="/Bottom Right Blob.svg" class="bot_right" />
	<h2 class="header">SemScape</h2>
	<div class="flexbox">
		<div class="login_side">
			<section class="q">Are you a contributor?</section>
			<div class="login_border">
				<div class="Login">
					<h2 style="font-size:2vw">Login</h2>
					<section class="details">
						<!-- svelte-ignore a11y-label-has-associated-control -->
						<label>Username</label><br />
						<input placeholder="Enter your Username" type="text" />
						<br /><br />
						<!-- svelte-ignore a11y-label-has-associated-control -->
						<label>Password</label><br />
						<input placeholder="Enter your Password" type="password" />
						<p>Forgot your Password? <a href="#page">Click Here!</a></p>
						<p>Want to Contribute? <a href="#page">Contact Us!</a></p>
						<button>Login</button>
					</section>
				</div>
			</div>
		</div>
		<div class="login_blob">
			<img alt="login blob" src="/Login Blob.svg" />
		</div>
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@300;700&display=swap');
	.content {
		font-family: 'Manrope', sans-serif;
		font-weight: 700;
		padding: 0% 10% 2% 15%;
	}
	.top_left {
		position: absolute;
		left: -1%;
		top: -1%;
		width: 10vw;
	}
	.top_right {
		position: absolute;
		right: -1%;
		top: -1%;
		width: 10vw;
	}
	.bot_left {
		position: absolute;
		left: -1%;
		bottom: -1%;
		width: 20vw;
	}

	.bot_right {
		position: absolute;
		right: -1%;
		bottom: -1%;
		width: 20vw;
	}
	.content > .header {
		font-size: 3vw;
		font-weight: 700;
	}
	.flexbox {
		display: flex;
	}
	.login_side {
		padding-top: 2%;
	}
	.login_side > .q {
		font-size: 1.5vw;
		font-weight: 700;
		padding: 2% 5% 3% 0%;
	}
	.login_side > .login_border {
		border: solid;
		border-radius: 30px;
		margin-left: 8%;
	}
	.login_side > .login_border > .Login {
		padding: 0vw 7vw 3vw 2.5vw;
	}
	.details {
		padding: 0vw 2vw 0vw 2vw;
	}
	.Login > .details > input {
		margin-top: 3%;
		width: 20vw;
		height: 2vw;
		border: 3px solid black;
		border-radius: 15px;
		padding-left: 5%;
	}
	.details > p {
		font-weight: 500;
	}
	.details > p > a {
		text-decoration: none;
		color: #ffa675;
	}
	.details > button {
		background-color: #ffa675;
		border-radius: 2vw;
		font-size: 1.5vw;
		vertical-align: middle;
		font-weight: 600;
		padding: 3% 7% 3% 7%;
	}
	.login_blob > img {
		width: 33vw;
		padding: 10%;
	}
</style>
