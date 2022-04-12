<template>
  <div class="home">
				<div class="header">
						<h2 class="title">Hi <b>Jack!</b> </h2>
						<div class="input">
								<input type="text" class="" placeholder="Find what you want">
								<div class="icon-input">
										<box-icon name='search' color="lightgrey"></box-icon>
								</div>
						</div>
						<div class="combo-header">
								<div class="text">
								<h2>Combo Cheese</h2>
								<p> Cheese Burger x2 <br/> New Users</p>
								</div>
								<div class="img">
										<img src="https://pngimg.com/uploads/burger_sandwich/burger_sandwich_PNG4115.png">
								</div>
						</div>
						<div class="scroll-main"> 
								<div class="scroll-content">
										<div class="avatar">
										</div>
								</div>
						</div>
				</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  }
}
</script> 

<style lang="less">

.home {
		margin: 20px;
}
.header {
		.scroll-main {}
		.combo-header {
				margin-top: 20px;
				background-color: orange;
				color: white;
				padding: 20px;
				border-radius: 20px;
				display: flex;
				.img {
						width: 50%;
						object-fit: cover;
						img {
								width:100%;
						}
				}
				.text {
						margin: auto;
						width: 50%;
						h2 {
								font-size: 7.7vw;
								font-family:'Rubik Moonrocks', cursive;;
								font-weight: 400;
						}
						p {
								font-size: 4vw;
						}
				}
		}
		.input {
				margin-top: 15px;
				display: flex;
				position: relative;
				align-items: center;
				input {
						width: 100%;
						background-color: rgba(250,248,248);
						border: 0px;
						outline: none;
						padding: 10px;
						padding-left: 30px;
						border-radius: 10px;
				}
				.icon-input {
						position: absolute;
						margin-right: 8px;
						margin-top: 6px;
						margin-left: 4px;
				}
		}

		.title {
				font-weight: 350;
		}
}
</style>

