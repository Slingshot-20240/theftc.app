<head>
	<title>The FTC App | 20240 Slingshot</title>
</head>

<main>
	<img id="logo" src="/logo.png" alt="FTC Team 20240 Slingshot Logo" />

	<img id="ss" src="/ss.png" alt="DECODE™ Scorer presented by 20240 Slingshot App Home Screen" />

	<h1>One app for <b>everything</b> FTC</h1>

	<h3>September 1</h3>

	<a
		id="waitlist"
		href="mailto:beta@theftc.app?subject=Beta%20Waitlist%20Request%20for%20the%20FTC%20App%20presented%20by%2020240%20Slingshot&body=Please%20use%20your%20Apple%20Account%20(formerly%20Apple%20ID)%20email%20address%20if%20you%20use%20an%20iPhone%20or%20iPad.%0AFor%20Android%20users%2C%20use%20your%20primary%20Google%20Account%20email%20address.%0A%0AThis%20is%20an%20automatically%20generated%20request.%0A%0ABy%20sending%20this%20email%20request%2C%20you%20agree%20to%20receive%20further%20email%20communications%20from%20beta%40theftc.app%20regarding%20the%20FTC%20App%20presented%20by%2020240%20Slingshot%20development%20and%20beta%20program."
		><span>Join the beta waitlist</span></a
	>

	<div>
		<a class="link" href="https://ftcscoring.app" target="_blank">DECODE™ Scorer ↗</a>
    <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
		<a class="link" href="https://itd.ftcscoring.app" target="_blank">INTO THE DEEP℠ Scorer ↗</a>
	</div>
</main>

<style>
	:global(:root, body) {
		margin: 0;
		padding: 0;
		width: 100vw;
		height: 100vh;
		background-color: #f4e3c5;
		background-image: url('/bg.png');
		background-size: 100%;
	}

	*,
	a,
	span {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: Inter, sans-serif;
		text-decoration: none;
	}

	main {
		width: 100vw;
		height: 100vh;
		padding: 2rem;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;

		#logo {
			margin: 0 0 calc(min(12rem, 40%) / 16) 0;
			width: min(12rem, 40%);
		}

		#ss {
			width: min(48rem, 100%);
		}

		h1 {
			margin: calc(min(2.8rem, 8vw) / 3) 0 0.2rem 0;
			font-size: min(2.8rem, 8vw);
			font-weight: 300;
			text-align: center;

			b {
				font-weight: 600;
			}
		}

		h3 {
			margin: calc(min(1.6rem, 5vw) / 3) 0 0.2rem 0;
			font-size: min(1.6rem, 5vw);
			font-weight: 300;
		}

		#waitlist {
			margin: min(1.2rem, 4vw) 0 0.2rem 0;
			padding: calc(min(1.2rem, 4vw) / 3) calc(min(1.2rem, 4vw) / 2);
			background: linear-gradient(180deg, #1f1f1f 0%, #0f0f0f 100%);
			border-radius: calc(min(1.2rem, 4vw) / 2);
			transition: filter 0.2s;

			span {
				font-size: min(1.2rem, 4vw);
				font-weight: 600;
				color: transparent;
				background: linear-gradient(90deg, #e5ae32 0%, #ea572e 25%, #92dbac 50%, #598290 100%);
				background-clip: text;
			}

			&:hover {
				filter: invert();

				span {
					filter: invert();
				}
			}
		}

		div {
			display: flex;

			* {
				margin: min(1.2rem, 4vw) 0 0.2rem 0;
				font-size: min(0.8rem, 3vw);
				color: #876;
				transition: color 0.2s;

				&.link:hover {
					color: #000;
				}
			}
		}
	}
</style>
