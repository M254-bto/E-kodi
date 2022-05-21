<script>




	
</script>

<main>
	<div class="sidebar">

	</div>
	<div class="container">
	<div class="heading">
		<div class="name">
			<h1 class="ap_name">Appartment Name</h1>
			<p class="loc">location</p>
		</div>
		<div class="photo">
			<img src="/png.png" alt="Display">
			<div class="name_cont"><p class="photo_name">Robin Mwaura</p></div>
			
		</div>
	</div>
	<hr>

	<div class="dash">
		<div class="number dd">
			<h3>Tenants</h3>
			<p class="ddn">444</p>
		</div>
		<div class="paid dd">
			<h3>Paid</h3>
			<p class="ddn">444</p>
		</div>
		<div class="pending dd">
			<h3>pending</h3>
			<p class="ddn">444</p>
		</div>
	</div>
	<h2>Tenants</h2>
<div class="tenants">
	<div class="search-add">
		<div class="search">
			<div class="con">
				<div class="sh">
				<p class="ss">Search...</p>
			</div>
				<div class="s-icon">
				<img src="/search.png" alt="">
				</div>
			</div>
		</div>
		<div class="add">
			<button class="button"><p class="btn-txt">Add New</p></button>
		</div>
	</div>
	
	<div class="ten-1 ten">
		<div class="ten-name">Name</div>
		<div class="ten-num">Unit Number</div>
		<div class="ten-stat">Status</div>
	</div>
	<div class="ten-2 ten">
		<div class="ten-name">Robin Mwaura</div>
		<div class="ten-num">024</div>
		<div class="ten-stat">Paid</div>
	</div>
	<div class="ten-3 ten">
		<div class="ten-name">Robin Mwaura</div>
		<div class="ten-num">024</div>
		<div class="ten-stat">Paid</div>
	</div>
	<div class="ten-4 ten">
		<div class="ten-name">Robin Mwaura</div>
		<div class="ten-num">024</div>
		<div class="ten-stat">Paid</div>
	</div>

</div>
</div>


</main>

<style>
	.ddn{
		margin-top:-20px;
	}
	main {
		
		overflow-x: hidden;
		padding: 0;
		max-width: 100vw;
		max-height: 100vh;
		margin: 0;
		background-color: #D2E1FA;
		display: grid;
		grid-template-columns: 320px  auto;
	}
	.container{
		overflow-x: hidden;
		display: flex;
		flex-direction: column;
	}
	.sidebar{
		height: 100vh;
		left: 0px;
		top: 0px;
		overflow-y: hidden;
		background: #0C407A;
	}
	.sh{
		height:100%;
		align-items: center;
		margin-top: -25px;
	}
	.heading{
		height: 100px;
		width: 100%;
		grid-template-columns: 7fr 1fr;
		
	}
	.name{
		
		text-align: center;
		width: 675px;
		height: 90px;
		top: 20px;
		margin-left:60px;
		background: #0C407A;
		border-radius: 39px;
		margin: auto;
	}


	h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 32px;
		line-height: 39px;
		/* identical to box height */


		color: #FFFFFF;
	}

	.photo{
		position: absolute;
		width: 90px;
		height: 90px;
		right: 60px;
		top: 20px;
	
	}
	.name_cont{
		position: absolute;
		width: 181px;
		height: 24px;
		text-align: center;
		padding:0;
		margin: 0;
	}
	.photo_name{
		font-family: 'Inter';
		font-style: normal;
		font-weight: 600;
		font-size: 15px;
		line-height: 24px;

		color: #0C407A;

	}
	img{
		height: 80%;
		width: 80%;
	}
	.loc{
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 20px;
		line-height: 24px;
		color: #FFFFFF;
		top:-20px;
	}
	.dash{
		width:80%;
		margin: auto;
		text-align: center;
		display: grid;
		grid-template-columns: 260px 260px 260px;
		column-gap: 40px;
		margin-top: 30px;
	}
	.dd{	

		padding-bottom:30px;
		height: 80px;
		background: #B7BED3;
		border-radius: 38px;
		
		
	}


	h3{
	font-family: 'Inter';
font-style: normal;
font-weight: 700;
font-size: 24px;

/* identical to box height */


color: #0C407A;
}

.ddn{
	font-family: 'Inter';
font-style: normal;
font-weight: 700;
font-size: 36px;

/* identical to box height */


color: #0C407A;

}

.tenants{
	display: flex;
	flex-direction: column;
	width: 90%;
	margin: auto;
	padding: 10px;
	border: 2px solid #B7BED3;
}

.search-add{
	display: grid;
	grid-template-columns: 5fr 1fr;
	column-gap: 20px;
}

h2{
	
	margin-left: 100px;
	font-family: 'jost';
	font-style: normal;
	font-weight: 700;
	font-size: 25px;
	line-height: 44px;
	/* identical to box height */

	text-transform: uppercase;

	color: #0C407A;
}
.search{
	border: 3px solid black;
	border-radius: 10px;
	height: 45px;
	background-color: #fff;
	align-items: center;
	
}
.con{
	display: grid;
	grid-template-columns: 5fr 1fr;
}
.ss{

	font-family: 'jost';
	font-style: normal;
	font-size: 26px;
	text-transform: capitalize;
	color: #000000;
}

.s-icon{
	height: 35px;
	width: 35px;
}
.ten{
	padding: 10px;
	margin: auto;
	width: 90%;
	height: 35px;
	background-color: #B7BED3;
	border-radius: 10px;
	margin-top: 10px;
	display: grid;
	grid-template-columns: 2fr 1fr 1fr;
	text-align: justify;
	text-align: center;
	align-items: center;

}

.button{
	width: 162px;
    height: 60px;
	background: #0C407A;
    border-radius: 12px;
	text-align: center;
	align-items: center;
}
.btn-txt{
	font-family: 'jost';
font-style: normal;
font-size: 20px;

/* identical to box height */

text-transform: capitalize;

color: #FFFFFF;
}



	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>