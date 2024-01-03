# -<!DOCTYPE html>
<html>
	<head>
		<style>
			body {
				height: 100vh;
				display: flex;
				justify-content: center;
				align-items: center;
				margin: 0;
				background: #424242;
			}
			ul {
				font-family: 'Roboto Condensed', sans-serif;
				display: flex;
			}
			li {
				list-style: none;
				margin: 0 5px;
			}
			.fa-brands {
				color: #262626;
				font-size: 40px;
				line-height: 80px;
				transition: .5s;
				padding-right: 14px;
			}
			a {
				width: 210px;
				height: 80px;
				background: #fff;
				text-decoration: none;
				display: block;
				text-align: left;
				padding-left: 20px;
				transform: rotate(-30deg) skew(25deg) translate(0, 0);
				box-shadow: -20px 20px 10px #00000080;
			}
			a span {
				color: #262626;
				padding: 0;
				margin: 0;
				position: absolute;
				top: 30px;
				letter-spacing: 4px;
				transition: .5s;
			}
			a::before {
				content: '';
				position: absolute;
				height: 100%;
				width: 20px;
				background: #b1b1b1;
				top: 10px;
				left: -20px;
				transform: rotate(0deg) skewY(-45deg);
			}
			a:after {
				content: '';
				position: absolute;
				height: 20px;
				width: 100%;
				background: #b1b1b1;
				bottom: -20px;
				left: -10px;
				transform: rotate(0deg) skewX(-45deg);
			}
			a:hover {
				transform: rotate(-30deg) skew(25deg) translate(20px, -15px);
				box-shadow: -50px 50px 50px #00000080;
			}
			li:hover .fa-brands,
			li:hover span {
				color: #fff;
			}
			li:hover:nth-child(1) {
				& a {
					background: #3b5998;

					&::before {
						background: #365492;
					}

					&::after {
						background: #4a69ad;
					}
				}
			}
			li:hover:nth-child(2) {
				& a {
					background: #00aced;

					&::before {
						background: #097aa5;
					}

					&::after {
						background: #53b9e0;
					}
				}
			}
			li:hover:nth-child(3) {
				& a {
					background: #dd4b39;

					&::before {
						background: #b33a2b;
					}

					&::after {
						background: #b33a2b;
					}
				}
			}
			li:hover:nth-child(4) {
				& a {
					background: #a1249b;

					&::before {
						background: #a1249b;
					}

					&::after {
						background: #a1249b;
					}
				}
			}
			</style>
		</head>
		<body>
			<ul>
				<li>
					<a href="https://vk.com/radi_nee_axmed1337">
						<i class="fa-brands fa-VK-Vkontakte"></i>
						<span> - Vkontakte</span>
					</a>
				</li>
				<li>
					<a href="https://web.telegram.org/a/">
						<i class="fa-brands fa-tg-Telegram"></i>
						<span> - Telegram</span>
					</a>
				</li>
				<li>
					<a href="https://www.youtube.com/channel/UCRXACQp9SvEGiBhvxooi_ow">
						<i class="fa-brands fa-Youtube"></i>
						<span> - YouTube</span>
					</a>
				</li>
				<li>
					<a href="https://www.twitch.tv/radi_nee_axmed1337">
						<i class="fa-brands fa-Twitch"></i>
						<span> - Twitch</span>
					</a>
				</li>
			</ul>
		</body>
	</html>
