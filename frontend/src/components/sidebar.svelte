<script>
</script>

<div class="sidebar">
	<div class="sidebar-components">
		<div class="sidebar-title">
			<img class="logo" src="/images/logo.png" alt="site logo" />
			<h1>EASY KODI</h1>
			<hr />
		</div>

		<div class="sidebar-nav">
			<ul>
				<li>
					<a href={''}>
						<img class="nav-icon" src="/images/Dashboard.png" alt="dashboard" /> DASHBOARD</a
					>
				</li>
				<li>
					<a href={''}> <img class="nav-icon" src="/images/People.png" alt="people" />TENANTS</a>
				</li>
				<li>
					<a href={''}> <img class="nav-icon" src="/images/Account.png" alt="account" />PROFILE</a>
				</li>
				<li>
					<a href={''}> <img class="nav-icon" src="/images/Logout.png" alt="logout" />SIGN OUT</a>
				</li>
			</ul>
		</div>

		<div class="sidebar-footer">
			<p>All Rights Reserved. Copyright &copy;</p>

			<div class="socials">
				<a href={''}><i class="fab fa-twitter" /></a>
				<a href={''}><i class="fab fa-facebook" /></a>
				<a href={''}><i class="fab fa-instagram" /></a>
			</div>
		</div>
	</div>
</div>

<style>
	.sidebar {
		background-color: #0c407a;
		color: #fff;
		height: 100vh;
		text-align: center;
	}

	.logo {
		width: 40px;
	}

	li img {
		width: 20px;
	}

	.sidebar-title {
		padding: 20px;
		text-align: center;
	}

	hr {
		width: 100%;
	}

	.sidebar li {
		margin-left: 75px;
		padding: 10px;
		list-style-type: none;
	}

	.sidebar li:nth-child(4) {
		position: fixed;
		bottom: 90px;
	}

	.sidebar-nav a {
		display: flex;
		align-self: center;
		color: #fff;
		text-decoration: none;
		font-weight: bold;
	}

	.sidebar-nav a:hover {
		color: #60aaff;
	}

	.sidebar-footer {
		position: fixed;
		bottom: 0;
		text-align: center;
	}

	.sidebar-footer p {
		font-size: 0.9em;
		padding: 10px;
	}

	.socials i {
		color: #fff;
		font-size: 20px;
		padding: 0 6px;
	}

	.socials i:hover {
		color: #60aaff;
	}
</style>
