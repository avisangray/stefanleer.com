<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/svelte-logo.svg';
	import github from '$lib/images/github.svg';
</script>
<div id="preloader-active">
	<div class="preloader d-flex align-items-center justify-content-center">
		<div class="preloader-inner position-relative">
			<div class="preloader-circle"></div>
			<div class="preloader-img pere-text">
				<span style="color:#000;font-size:3rem;font-weight:bold;text-decoration: underline; text-decoration-color: #e98a79;">Stefan Leer</span>
			</div>
		</div>
	</div>
</div>
<!-- Preloader Start -->
<header>
	<!-- Header Start -->
	<div class="header-area">
		<div class="main-header header-sticky">
			<div class="container-fluid">
				<div class="menu-wrapper d-flex align-items-center justify-content-between">
					<!-- Logo -->
					<div class="logo">
						<a href="index.html">
							<span style="color:#000;font-size:3rem;font-weight:bold;text-decoration: underline; text-decoration-color: #e98a79;">Stefan Leer</span>
						</a>
					</div>
					<!-- Main-menu -->
					<div class="main-menu f-right d-none d-lg-block">
						<nav>
							<ul id="navigation">
								<li><a href="/">Home</a></li>
								<li><a href="/#contact-me">About</a></li>
								<!--li><a href="services.html">Services</a></li-->
								<li><a href="/#contact-me">Contact</a></li>
							</ul>
						</nav>
					</div>          
					<!-- Header-btn -->
					<div class="header-btns d-none d-lg-block f-right">
						<a href="tel:+12102591648" class="border-btn"><i class="fas fa-phone"></i>+1 (210) 259-1648</a>
					</div>
					<!-- Mobile Menu -->
					<div class="col-12">
						<div class="mobile_menu d-block d-lg-none"></div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<!-- Header End -->
</header>