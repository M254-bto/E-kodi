<script>
	import Sidebar from '../components/sidebar.svelte';
</script>

<div class="container">
	<div class="side">
		<Sidebar />
	</div>
	<div class="content">
		<div class="form">
			<div class="form_head">
				<h2>Edit Profile</h2>
			</div>
			<form action="" class="edit">
				<input type="text" name="first_name" id="first" placeholder="First name" />

				<input type="text" name="first_name" id="last" placeholder="Last name" />

				<input type="text" name="first_name" id="email" placeholder="email" />

				<input type="text" name="first_name" id="contact" placeholder="contact" />

				<input type="submit" value="Save" class="button" />
			</form>
			<div class="form_head">
				<h2>Reset Password</h2>
			</div>
			<form action="" class="pass">
				<input type="password" name="pass" id="pass" placeholder="password" />

				<input type="password" name="pass2" id="pass2" placeholder="confirm password" />

				<input type="submit" value="Reset" class="button" />
			</form>
		</div>
		<div class="profile_pic">
			<img src="/images/default.png" alt="" srcset="" />
			<h3>Edit</h3>
		</div>
	</div>
</div>

<style>
	.container {
		margin: 0;
		width: 100vw;
		height: 100vh;
		overflow: hidden;
		display: grid;
		grid-template-columns: 22% 78%;
	}
	.side {
		height: 100vh;
		left: 0;
	}

	.content {
		height: 100vh;
		overflow: hidden;
		background-color: #d2e0fb;
		display: grid;
		grid-template-columns: 60% 19%;
		justify-content: space-around;
	}
	.form {
		height: 100vh;
	}

	.form_head {
		height: 45px;
		width: 280px;
		text-align: center;
		padding: 0%;
		margin: auto;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 300;
		font-size: 25px;
		line-height: 48px;
	}

	.profile_pic {
		height: 200px;
		text-align: center;
	}

	input {
		display: block;
		gap: 30px;
		width: 70%;
		margin: 20px auto;
		height: 40px;
		background-color: rgb(255, 255, 255);
		border-radius: 10px;
		color: #6598ff;
		border: 0;
		font-size: 20px;
		padding-left: 10px;
		text-align: center;
	}

	.button {
		width: 30%;
		background-color: #0c407a;
		color: #d2e0fb;
	}
	img {
		height: 90%;
		width: 90%;
		margin: auto;
	}
</style>
