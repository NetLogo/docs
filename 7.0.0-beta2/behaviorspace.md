<!DOCTYPE html>
<html lang="en">
	<head>
		<script src="script.js" type="module"></script>
		<meta charset="UTF-8" />
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1">
		<title>NetLogo 7.0.0-beta2 — User Manual</title>
		<link rel="stylesheet" href="netlogo.css" type="text/css"/>
		<link rel="icon" type="image/png" href="favicon/favicon-96x96.png" sizes="96x96" />
		<link rel="icon" type="image/svg+xml" href="favicon/favicon.svg" />
		<link rel="shortcut icon" href="favicon/favicon.ico" />
		<link rel="apple-touch-icon" sizes="180x180" href="favicon/apple-touch-icon.png" />
		<meta name="apple-mobile-web-app-title" content="Docs" />
		<link rel="manifest" href="favicon/site.webmanifest" />
	</head>
	<body>
<!------------  NAV  ------------>
<nav class="navbar">
	<input id="menu-toggle" type="checkbox" hidden />
	<div class="navbar__row">
		<div class="navbar__anchor">
			<label class="hamburger" for="menu-toggle"> <span></span><span></span><span></span> </label>
			<a href="/7.0.0-beta2/" class="navbar__brand"
				><svg width="261" height="50" viewBox="0 0 261 50" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path
						d="M76.6661 13V-0.340001H79.4261L86.2861 8.9L85.3261 10.9V-0.340001H88.3061V13H85.8661L78.8861 3.88L79.6461 2.42V13H76.6661ZM95.6188 13.3C94.6054 13.3 93.7054 13.0933 92.9188 12.68C92.1454 12.2533 91.5388 11.6533 91.0988 10.88C90.6721 10.0933 90.4588 9.16 90.4588 8.08C90.4588 6.32 90.8921 4.96 91.7588 4C92.6388 3.02667 93.8921 2.54 95.5188 2.54C96.6388 2.54 97.5388 2.78 98.2188 3.26C98.9121 3.74 99.4188 4.44 99.7388 5.36C100.059 6.28 100.212 7.4 100.199 8.72H92.4988L92.1788 6.82H97.7388L97.2988 7.76C97.2854 6.68 97.1321 5.92 96.8388 5.48C96.5454 5.04 96.0654 4.82 95.3988 4.82C95.0254 4.82 94.6854 4.91333 94.3788 5.1C94.0854 5.28667 93.8521 5.6 93.6788 6.04C93.5188 6.46667 93.4388 7.06 93.4388 7.82C93.4388 8.78 93.6654 9.52 94.1188 10.04C94.5854 10.56 95.3254 10.82 96.3388 10.82C96.7121 10.82 97.0788 10.78 97.4388 10.7C97.8121 10.6067 98.1588 10.5 98.4788 10.38C98.7988 10.26 99.0721 10.1533 99.2988 10.06V12.62C98.8188 12.82 98.2788 12.98 97.6788 13.1C97.0921 13.2333 96.4054 13.3 95.6188 13.3ZM106.409 13.4C105.236 13.4 104.363 13.1267 103.789 12.58C103.216 12.02 102.929 11.2333 102.929 10.22V5.16H101.449V2.88H102.929V0.0999992H106.049V2.88H108.269V5.16H106.049V9.84C106.049 10.1867 106.123 10.4467 106.269 10.62C106.416 10.78 106.663 10.86 107.009 10.86C107.209 10.86 107.429 10.82 107.669 10.74C107.909 10.66 108.109 10.56 108.269 10.44V13C107.989 13.1467 107.683 13.2467 107.349 13.3C107.029 13.3667 106.716 13.4 106.409 13.4ZM110.631 13V-0.340001H113.871V10.46H119.671V13H110.631ZM126.185 13.3C124.478 13.3 123.191 12.8467 122.325 11.94C121.471 11.02 121.045 9.67333 121.045 7.9C121.045 5.99333 121.478 4.62667 122.345 3.8C123.225 2.96 124.505 2.54 126.185 2.54C127.318 2.54 128.265 2.73333 129.025 3.12C129.798 3.49333 130.378 4.07333 130.765 4.86C131.165 5.64667 131.365 6.66 131.365 7.9C131.365 9.67333 130.918 11.02 130.025 11.94C129.131 12.8467 127.851 13.3 126.185 13.3ZM126.185 10.92C126.678 10.92 127.085 10.8067 127.405 10.58C127.738 10.34 127.985 10 128.145 9.56C128.318 9.10667 128.405 8.55333 128.405 7.9C128.405 7.15333 128.318 6.56667 128.145 6.14C127.985 5.7 127.738 5.38667 127.405 5.2C127.071 5 126.665 4.9 126.185 4.9C125.678 4.9 125.265 5 124.945 5.2C124.625 5.4 124.385 5.72 124.225 6.16C124.078 6.58667 124.005 7.16667 124.005 7.9C124.005 8.91333 124.178 9.67333 124.525 10.18C124.885 10.6733 125.438 10.92 126.185 10.92ZM137.302 13.3C136.382 13.2467 135.588 13.0333 134.922 12.66C134.268 12.2867 133.755 11.74 133.382 11.02C133.022 10.2867 132.842 9.36667 132.842 8.26C132.842 7.14 132.982 6.21333 133.262 5.48C133.542 4.73333 133.928 4.15333 134.422 3.74C134.928 3.32667 135.535 3.03333 136.242 2.86C136.948 2.68667 137.735 2.6 138.602 2.6C139.442 2.6 140.175 2.70667 140.802 2.92C141.428 3.13333 141.915 3.44 142.262 3.84C142.608 4.24 142.782 4.73333 142.782 5.32V13.12C142.782 13.8267 142.668 14.4467 142.442 14.98C142.215 15.5267 141.875 15.98 141.422 16.34C140.982 16.7133 140.442 16.9933 139.802 17.18C139.175 17.3667 138.448 17.46 137.622 17.46C136.728 17.46 135.962 17.3933 135.322 17.26C134.695 17.14 134.215 16.9867 133.882 16.8V14.18C134.082 14.26 134.375 14.3667 134.762 14.5C135.148 14.6333 135.582 14.74 136.062 14.82C136.542 14.9133 137.022 14.96 137.502 14.96C138.128 14.96 138.608 14.8733 138.942 14.7C139.288 14.5267 139.528 14.2933 139.662 14C139.795 13.7067 139.862 13.3733 139.862 13V11.36L140.442 11.78C140.228 12.0867 139.975 12.3533 139.682 12.58C139.388 12.8067 139.042 12.98 138.642 13.1C138.255 13.2333 137.808 13.3 137.302 13.3ZM138.062 11.06C138.408 11.06 138.728 11.0267 139.022 10.96C139.315 10.88 139.595 10.7667 139.862 10.62V5.98C139.862 5.7 139.782 5.48667 139.622 5.34C139.462 5.19333 139.262 5.09333 139.022 5.04C138.782 4.98667 138.528 4.96 138.262 4.96C137.648 4.96 137.162 5.09333 136.802 5.36C136.455 5.62667 136.202 6 136.042 6.48C135.895 6.94667 135.822 7.48 135.822 8.08C135.822 9 136.028 9.72667 136.442 10.26C136.855 10.7933 137.395 11.06 138.062 11.06ZM149.837 13.3C148.13 13.3 146.844 12.8467 145.977 11.94C145.124 11.02 144.697 9.67333 144.697 7.9C144.697 5.99333 145.13 4.62667 145.997 3.8C146.877 2.96 148.157 2.54 149.837 2.54C150.97 2.54 151.917 2.73333 152.677 3.12C153.45 3.49333 154.03 4.07333 154.417 4.86C154.817 5.64667 155.017 6.66 155.017 7.9C155.017 9.67333 154.57 11.02 153.677 11.94C152.784 12.8467 151.504 13.3 149.837 13.3ZM149.837 10.92C150.33 10.92 150.737 10.8067 151.057 10.58C151.39 10.34 151.637 10 151.797 9.56C151.97 9.10667 152.057 8.55333 152.057 7.9C152.057 7.15333 151.97 6.56667 151.797 6.14C151.637 5.7 151.39 5.38667 151.057 5.2C150.724 5 150.317 4.9 149.837 4.9C149.33 4.9 148.917 5 148.597 5.2C148.277 5.4 148.037 5.72 147.877 6.16C147.73 6.58667 147.657 7.16667 147.657 7.9C147.657 8.91333 147.83 9.67333 148.177 10.18C148.537 10.6733 149.09 10.92 149.837 10.92Z"
						fill="black"
					/>
					<path
						d="M83.9923 44.28C81.6776 44.28 79.8763 43.5987 78.5883 42.236C77.319 40.8733 76.6843 38.9227 76.6843 36.384V25.324H78.7003V36.496C78.7003 38.4933 79.1483 39.9773 80.0443 40.948C80.9403 41.9 82.2563 42.376 83.9923 42.376C85.7283 42.376 87.0536 41.9 87.9683 40.948C88.883 39.9773 89.3403 38.4933 89.3403 36.496V25.324H91.3003V36.384C91.3003 38.0827 91.011 39.52 90.4323 40.696C89.8536 41.872 89.023 42.768 87.9403 43.384C86.8576 43.9813 85.5416 44.28 83.9923 44.28ZM101.083 44.28C100.15 44.28 99.3564 44.2147 98.703 44.084C98.0497 43.9533 97.4617 43.7667 96.939 43.524C96.4163 43.2813 95.847 43.0013 95.231 42.684V40.5C95.8283 41.004 96.631 41.452 97.639 41.844C98.647 42.236 99.823 42.432 101.167 42.432C102.586 42.432 103.612 42.1333 104.247 41.536C104.9 40.92 105.227 40.1453 105.227 39.212C105.227 38.428 105.012 37.8027 104.583 37.336C104.154 36.8507 103.603 36.4587 102.931 36.16C102.259 35.8427 101.55 35.544 100.803 35.264C100.168 35.04 99.5337 34.8067 98.899 34.564C98.283 34.3027 97.723 33.9853 97.219 33.612C96.715 33.22 96.3137 32.7253 96.015 32.128C95.7163 31.512 95.567 30.7467 95.567 29.832C95.567 29.328 95.6603 28.796 95.847 28.236C96.0523 27.676 96.3697 27.1533 96.799 26.668C97.247 26.1827 97.835 25.7907 98.563 25.492C99.3097 25.1933 100.215 25.044 101.279 25.044C102.007 25.044 102.623 25.1 103.127 25.212C103.65 25.3053 104.144 25.4547 104.611 25.66C105.078 25.8467 105.6 26.08 106.179 26.36V28.432C105.694 28.152 105.227 27.9 104.779 27.676C104.35 27.4333 103.864 27.2467 103.323 27.116C102.8 26.9667 102.156 26.892 101.391 26.892C100.476 26.892 99.739 27.0227 99.179 27.284C98.6377 27.5453 98.2363 27.8907 97.975 28.32C97.7323 28.7493 97.611 29.2067 97.611 29.692C97.611 30.4573 97.779 31.064 98.115 31.512C98.4697 31.96 98.955 32.3333 99.571 32.632C100.206 32.912 100.934 33.192 101.755 33.472C102.408 33.696 103.062 33.948 103.715 34.228C104.368 34.4893 104.956 34.8253 105.479 35.236C106.02 35.628 106.45 36.132 106.767 36.748C107.103 37.3453 107.271 38.092 107.271 38.988C107.271 39.828 107.084 40.6587 106.711 41.48C106.338 42.2827 105.703 42.9547 104.807 43.496C103.911 44.0187 102.67 44.28 101.083 44.28ZM111.042 44V25.324H122.83V27.228H113.058V33.668H121.654V35.628H113.058V42.096H122.83V44H111.042ZM127.032 44V25.324H134.704C136.533 25.324 137.905 25.7813 138.82 26.696C139.753 27.6107 140.22 28.964 140.22 30.756C140.22 31.8387 139.996 32.8 139.548 33.64C139.1 34.48 138.474 35.1427 137.672 35.628C136.869 36.1133 135.926 36.356 134.844 36.356L135.684 35.796L141.06 44H138.68L133.136 35.432L134.144 36.468H129.048V44H127.032ZM129.048 34.564H133.78C135.329 34.564 136.449 34.256 137.14 33.64C137.849 33.0053 138.204 32.0907 138.204 30.896C138.204 29.776 137.942 28.8893 137.42 28.236C136.897 27.564 135.917 27.228 134.48 27.228H129.048V34.564ZM152.257 44V25.324H154.441L161.357 35.936L159.985 36.244L167.293 25.324H169.477V44H167.461V27.34H168.357L160.657 38.148L153.545 27.564L154.273 26.528V44H152.257ZM172.141 44L179.589 25.324H181.605L189.025 44H186.869L180.401 27.2L180.821 27.144L174.325 44H172.141ZM175.417 38.176L176.285 36.244H185.441L185.581 38.176H175.417ZM191.674 44V25.324H193.97L205.618 41.76L205.114 42.544V25.324H207.13V44H204.862L192.766 26.948L193.69 26.08V44H191.674ZM218.909 44.28C216.594 44.28 214.793 43.5987 213.505 42.236C212.235 40.8733 211.601 38.9227 211.601 36.384V25.324H213.617V36.496C213.617 38.4933 214.065 39.9773 214.961 40.948C215.857 41.9 217.173 42.376 218.909 42.376C220.645 42.376 221.97 41.9 222.885 40.948C223.799 39.9773 224.257 38.4933 224.257 36.496V25.324H226.217V36.384C226.217 38.0827 225.927 39.52 225.349 40.696C224.77 41.872 223.939 42.768 222.857 43.384C221.774 43.9813 220.458 44.28 218.909 44.28ZM228.887 44L236.335 25.324H238.351L245.771 44H243.615L237.147 27.2L237.567 27.144L231.071 44H228.887ZM232.163 38.176L233.031 36.244H242.187L242.327 38.176H232.163ZM248.419 44V25.324H250.435V42.04H259.983V44H248.419Z"
						fill="black"
					/>
					<g clip-path="url(#clip0_1_80)">
						<g clip-path="url(#paint0_angular_1_80_clip_path)" data-figma-skip-parse="true">
							<g transform="matrix(0.0191234 -0.00861445 0.00861444 0.0191234 24.5732 8.78025)">
								<foreignObject x="-1071.43" y="-1071.43" width="2142.86" height="2142.86"
									><div
										xmlns="http://www.w3.org/1999/xhtml"
										style="
											background: conic-gradient(
												from 90deg,
												rgba(200, 2, 0, 1) 0deg,
												rgba(195, 0, 0, 1) 0.0794891deg,
												rgba(191, 0, 0, 1) 116.448deg,
												rgba(223, 24, 0, 1) 127.48deg,
												rgba(223, 24, 0, 1) 235.378deg,
												rgba(255, 22, 0, 1) 240.998deg,
												rgba(243, 21, 0, 1) 359.438deg,
												rgba(200, 2, 0, 1) 360deg
											);
											height: 100%;
											width: 100%;
											opacity: 1;
										"
									></div
								></foreignObject>
							</g>
						</g>
						<path
							d="M43.6966 0.165806L10.8397 0.178574L21.1584 10.3186L21.9154 24.7658L43.6966 0.165806Z"
							data-figma-gradient-fill="{&#34;type&#34;:&#34;GRADIENT_ANGULAR&#34;,&#34;stops&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;stopsVar&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;transform&#34;:{&#34;m00&#34;:38.246723175048828,&#34;m01&#34;:17.228889465332031,&#34;m02&#34;:-3.1645612716674805,&#34;m10&#34;:-17.228891372680664,&#34;m11&#34;:38.246719360351562,&#34;m12&#34;:-1.7286592721939087},&#34;opacity&#34;:1.0,&#34;blendMode&#34;:&#34;NORMAL&#34;,&#34;visible&#34;:true}"
						/>
					</g>
					<g clip-path="url(#clip1_1_80)">
						<g clip-path="url(#paint1_angular_1_80_clip_path)" data-figma-skip-parse="true">
							<g transform="matrix(0.0191234 -0.00861445 0.00861444 0.0191234 35.8408 33.4802)">
								<foreignObject x="-1071.43" y="-1071.43" width="2142.86" height="2142.86"
									><div
										xmlns="http://www.w3.org/1999/xhtml"
										style="
											background: conic-gradient(
												from 90deg,
												rgba(200, 2, 0, 1) 0deg,
												rgba(195, 0, 0, 1) 0.0794891deg,
												rgba(191, 0, 0, 1) 116.448deg,
												rgba(223, 24, 0, 1) 127.48deg,
												rgba(223, 24, 0, 1) 235.378deg,
												rgba(255, 22, 0, 1) 240.998deg,
												rgba(243, 21, 0, 1) 359.438deg,
												rgba(200, 2, 0, 1) 360deg
											);
											height: 100%;
											width: 100%;
											opacity: 1;
										"
									></div
								></foreignObject>
							</g>
						</g>
						<path
							d="M54.9642 24.8658L22.1072 24.8785L32.4259 35.0185L33.183 49.4657L54.9642 24.8658Z"
							data-figma-gradient-fill="{&#34;type&#34;:&#34;GRADIENT_ANGULAR&#34;,&#34;stops&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;stopsVar&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;transform&#34;:{&#34;m00&#34;:38.246723175048828,&#34;m01&#34;:17.228889465332031,&#34;m02&#34;:8.1030168533325195,&#34;m10&#34;:-17.228891372680664,&#34;m11&#34;:38.246719360351562,&#34;m12&#34;:22.971292495727539},&#34;opacity&#34;:1.0,&#34;blendMode&#34;:&#34;NORMAL&#34;,&#34;visible&#34;:true}"
						/>
					</g>
					<g clip-path="url(#clip2_1_80)">
						<g clip-path="url(#paint2_angular_1_80_clip_path)" data-figma-skip-parse="true">
							<g transform="matrix(0.012641 -0.00569436 0.00569436 0.012641 9.15805 30.5895)">
								<foreignObject x="-1071.43" y="-1071.43" width="2142.86" height="2142.86"
									><div
										xmlns="http://www.w3.org/1999/xhtml"
										style="
											background: conic-gradient(
												from 90deg,
												rgba(200, 2, 0, 1) 0deg,
												rgba(195, 0, 0, 1) 0.0794891deg,
												rgba(191, 0, 0, 1) 116.448deg,
												rgba(223, 24, 0, 1) 127.48deg,
												rgba(223, 24, 0, 1) 235.378deg,
												rgba(255, 22, 0, 1) 240.998deg,
												rgba(243, 21, 0, 1) 359.438deg,
												rgba(200, 2, 0, 1) 360deg
											);
											height: 100%;
											width: 100%;
											opacity: 1;
										"
									></div
								></foreignObject>
							</g>
						</g>
						<path
							d="M21.7991 24.8951L0.0798187 24.9035L6.90073 31.6063L7.40114 41.1563L21.7991 24.8951Z"
							data-figma-gradient-fill="{&#34;type&#34;:&#34;GRADIENT_ANGULAR&#34;,&#34;stops&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;stopsVar&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;transform&#34;:{&#34;m00&#34;:25.282018661499023,&#34;m01&#34;:11.388715744018555,&#34;m02&#34;:-9.1773138046264648,&#34;m10&#34;:-11.388717651367188,&#34;m11&#34;:25.282012939453125,&#34;m12&#34;:23.6428222656250},&#34;opacity&#34;:1.0,&#34;blendMode&#34;:&#34;NORMAL&#34;,&#34;visible&#34;:true}"
						/>
					</g>
					<g clip-path="url(#clip3_1_80)">
						<g clip-path="url(#paint3_angular_1_80_clip_path)" data-figma-skip-parse="true">
							<g transform="matrix(0.012641 -0.00569436 0.00569436 0.012641 53.6131 9.85192)">
								<foreignObject x="-1071.43" y="-1071.43" width="2142.86" height="2142.86"
									><div
										xmlns="http://www.w3.org/1999/xhtml"
										style="
											background: conic-gradient(
												from 90deg,
												rgba(200, 2, 0, 1) 0deg,
												rgba(195, 0, 0, 1) 0.0794891deg,
												rgba(191, 0, 0, 1) 116.448deg,
												rgba(223, 24, 0, 1) 127.48deg,
												rgba(223, 24, 0, 1) 235.378deg,
												rgba(255, 22, 0, 1) 240.998deg,
												rgba(243, 21, 0, 1) 359.438deg,
												rgba(200, 2, 0, 1) 360deg
											);
											height: 100%;
											width: 100%;
											opacity: 1;
										"
									></div
								></foreignObject>
							</g>
						</g>
						<path
							d="M66.2541 4.15756L44.5349 4.166L51.3558 10.8688L51.8562 20.4187L66.2541 4.15756Z"
							data-figma-gradient-fill="{&#34;type&#34;:&#34;GRADIENT_ANGULAR&#34;,&#34;stops&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;stopsVar&#34;:[{&#34;color&#34;:{&#34;r&#34;:0.76470589637756348,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.00022080302005633712},{&#34;color&#34;:{&#34;r&#34;:0.75082629919052124,&#34;g&#34;:0.0,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.32346612215042114},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.35411190986633301},{&#34;color&#34;:{&#34;r&#34;:0.87450981140136719,&#34;g&#34;:0.094117648899555206,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.65382820367813110},{&#34;color&#34;:{&#34;r&#34;:1.0,&#34;g&#34;:0.086419761180877686,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.66943931579589844},{&#34;color&#34;:{&#34;r&#34;:0.95294117927551270,&#34;g&#34;:0.082352943718433380,&#34;b&#34;:0.0,&#34;a&#34;:1.0},&#34;position&#34;:0.99844002723693848}],&#34;transform&#34;:{&#34;m00&#34;:25.282016754150391,&#34;m01&#34;:11.388714790344238,&#34;m02&#34;:35.277732849121094,&#34;m10&#34;:-11.388716697692871,&#34;m11&#34;:25.282012939453125,&#34;m12&#34;:2.9052729606628418},&#34;opacity&#34;:1.0,&#34;blendMode&#34;:&#34;NORMAL&#34;,&#34;visible&#34;:true}"
						/>
					</g>
					<defs>
						<clipPath id="paint0_angular_1_80_clip_path">
							<path d="M43.6966 0.165806L10.8397 0.178574L21.1584 10.3186L21.9154 24.7658L43.6966 0.165806Z" />
						</clipPath>
						<clipPath id="paint1_angular_1_80_clip_path">
							<path d="M54.9642 24.8658L22.1072 24.8785L32.4259 35.0185L33.183 49.4657L54.9642 24.8658Z" />
						</clipPath>
						<clipPath id="paint2_angular_1_80_clip_path">
							<path d="M21.7991 24.8951L0.0798187 24.9035L6.90073 31.6063L7.40114 41.1563L21.7991 24.8951Z" />
						</clipPath>
						<clipPath id="paint3_angular_1_80_clip_path">
							<path d="M66.2541 4.15756L44.5349 4.166L51.3558 10.8688L51.8562 20.4187L66.2541 4.15756Z" />
						</clipPath>
						<clipPath id="clip0_1_80">
							<rect width="36" height="36" fill="white" transform="translate(6.23242 -2.69995) rotate(-24.25)" />
						</clipPath>
						<clipPath id="clip1_1_80">
							<rect width="36" height="36" fill="white" transform="translate(17.5 22) rotate(-24.25)" />
						</clipPath>
						<clipPath id="clip2_1_80">
							<rect width="24" height="24" fill="white" transform="translate(-3.10001 22.95) rotate(-24.25)" />
						</clipPath>
						<clipPath id="clip3_1_80">
							<rect width="20" height="20" fill="white" transform="translate(44 3.21437) rotate(-24.25)" />
						</clipPath>
					</defs>
				</svg>
			</a>
		</div>
		<div class="visible-lg">
		<div class="navbar__links">
	<!-- Intro -->
	<div class="navbar__item">
		<a href="/7.0.0-beta2/">Home</a>
	</div>
	<!-- Learning -->
	<div class="navbar__item">
		<a href="whatis.html">Learning NetLogo</a>
		<div class="dropdown__menu">
			<a href="whatis.html">What is NetLogo?</a>
			<a href="sample.html">Tutorial #0: Sample Model</a>
			<a href="tutorial1.html">Tutorial #1 Models</a>
			<a href="tutorial2.html">Tutorial #2 Commands</a>
			<a href="tutorial3.html">Tutorial #3 Procedures</a>
		</div>
	</div>
	<!-- Reference -->
	<div class="navbar__item">
		<a href="interface.html">Documentation</a>
		<div class="dropdown__menu">
			<a href="dictionary.html">NetLogo Dictionary</a>
			<a href="interface.html">Interface Guide</a>
			<a href="interfacetab.html">Interface Tab Guide</a>
			<a href="infotab.html">Info Tab Guide</a>
			<a href="codetab.html">Code Tab Guide</a>
			<a href="programming.html">Programming Guide</a>
			<a href="transition.html">Transition Guide</a>
			<a href="scaladoc">Scaladoc</a>
		</div>
	</div>
	<!-- Features -->
	<div class="navbar__item">
		<a href="extension-manager.html">Advanced Tools</a>
		<div class="dropdown__menu" style="column-count: 2; column-gap: 1rem; row-gap: 0.5rem">
			<a href="extension-manager.html">Extension Manager</a>
			<a href="shapes.html">Shapes Editor</a>
			<a href="behaviorspace.html">BehaviorSpace</a>
			<a href="systemdynamics.html">System Dynamics</a>
			<a href="hubnet.html">HubNet</a>
			<a href="hubnet-authoring.html">HubNet Authoring</a>
			<a href="logging.html">Logging</a>
			<a href="controlling.html">Controlling</a>
			<a href="mathematica.html">Mathematica Link</a>
			<a href="3d.html">NetLogo 3D</a>
			<a href="modelingcommons.html">Save to Modeling Commons</a>
		</div>
	</div>
	<!-- Extensions -->
	<div class="navbar__item">
		<a href="extensions.html">Extensions</a>
		<div class="dropdown__menu" style="column-count: 2; column-gap: 1rem; row-gap: 0.5rem">
			<a href="extensions.html">Extensions Guide</a>
			<a href="arduino.html">Arduino</a>
			<a href="array.html">Array</a>
			<a href="bitmap.html">Bitmap</a>
			<a href="csv.html">CSV</a>
			<a href="gis.html">GIS</a>
			<a href="gogo.html">GoGo</a>
			<a href="ls.html">LevelSpace</a>
			<a href="matrix.html">Matrices</a>
			<a href="nw.html">Networks</a>
			<a href="palette.html">Palette</a>
			<a href="profiler.html">Profiler</a>
			<a href="py.html">Python</a>
			<a href="r.html">R</a>
			<a href="resource.html">Resource</a>
			<a href="rnd.html">Rnd</a>
			<a href="sound.html">Sound</a>
			<a href="table.html">Table</a>
			<a href="time.html">Time</a>
			<a href="vid.html">Vid</a>
			<a href="view2.5d.html">View2.5D</a>
		</div>
	</div>
	<!-- FAQ -->
	<div class="navbar__item"><a href="faq.html">FAQ</a></div>
</div>
		</div>
		<div class="navbar__actions">
			<!-- Version / Actions -->
			<select id="version-select" class="version-select" aria-label="Select version">
				<option selected value="this">7.0.0-beta2</option>
				<option value="6.4.0">6.4</option>
				<option value="6.3.0">6.3.0</option>
				<option value="6.2.2">6.2.2</option>
				<option value="6.1.1">6.1.1</option>
				<option value="6.0.4">6.0.4</option>
				<option value="6.0-BETA1">6.0beta</option>
				<option value="5.3.1">5.3.1</option>
				<option value="5.2.1">5.2.1</option>
				<option value="5.1.0">5.1.0</option>
				<option value="5.0">5.0</option>
				<option value="4.1">4.1</option>
				<option value="4.0">4.0</option>
				<option value="3.1">3.1</option>
				<option value="3.0">3.0</option>
				<option value="2.1">2.1</option>
				<option value="2.0">2.0</option>
				<option value="1.2">1.2</option>
				<option value="1.1">1.1</option>
				<option value="1.0">1.0</option>
			</select>
			<button class="navbar__action hidden" id="searchBtn" aria-label="Search (⌘K)">
				<!-- Search icon -->
				<svg viewBox="0 0 24 24">
					<path
						d="M10 2a8 8 0 0 1 5.29 13.93l5.4 5.4-1.42 1.42-5.4-5.4A8 8 0 1 1 10 2m0 2a6 6 0 1 0 0 12A6 6 0 0 0 10 4z"
					/>
				</svg>
			</button>
			<a class="navbar__action" href="https://github.com/NetLogo/NetLogo" aria-label="GitHub" target="_blank">
				<!-- GitHub logo -->
				<svg viewBox="0 0 24 24">
					<path
						d="M12 .5a12 12 0 0 0-3.79 23.4c.6.11.82-.26.82-.58v-2.04c-3.34.72-4.04-1.61-4.04-1.61-.55-1.4-1.34-1.77-1.34-1.77-1.09-.74.08-.73.08-.73 1.2.08 1.83 1.23 1.83 1.23 1.07 1.84 2.8 1.31 3.48 1.01.11-.78.42-1.31.76-1.61-2.67-.3-5.47-1.34-5.47-5.96 0-1.32.47-2.4 1.23-3.24-.12-.3-.53-1.52.12-3.17 0 0 1.01-.32 3.3 1.23a11.32 11.32 0 0 1 6 0c2.3-1.55 3.3-1.23 3.3-1.23.65 1.65.24 2.87.12 3.17.77.84 1.23 1.92 1.23 3.24 0 4.63-2.8 5.66-5.47 5.96.43.38.81 1.12.81 2.25v3.34c0 .32.22.7.83.58A12 12 0 0 0 12 .5z"
					/>
				</svg>
			</a>
		</div>
	</div>
	<div class="navbar__links__mobile hidden-lg">
		<div class="navbar__links">
	<!-- Intro -->
	<div class="navbar__item">
		<a href="/7.0.0-beta2/">Home</a>
	</div>
	<!-- Learning -->
	<div class="navbar__item">
		<a href="whatis.html">Learning NetLogo</a>
		<div class="dropdown__menu">
			<a href="whatis.html">What is NetLogo?</a>
			<a href="sample.html">Tutorial #0: Sample Model</a>
			<a href="tutorial1.html">Tutorial #1 Models</a>
			<a href="tutorial2.html">Tutorial #2 Commands</a>
			<a href="tutorial3.html">Tutorial #3 Procedures</a>
		</div>
	</div>
	<!-- Reference -->
	<div class="navbar__item">
		<a href="interface.html">Documentation</a>
		<div class="dropdown__menu">
			<a href="dictionary.html">NetLogo Dictionary</a>
			<a href="interface.html">Interface Guide</a>
			<a href="interfacetab.html">Interface Tab Guide</a>
			<a href="infotab.html">Info Tab Guide</a>
			<a href="codetab.html">Code Tab Guide</a>
			<a href="programming.html">Programming Guide</a>
			<a href="transition.html">Transition Guide</a>
			<a href="scaladoc">Scaladoc</a>
		</div>
	</div>
	<!-- Features -->
	<div class="navbar__item">
		<a href="extension-manager.html">Advanced Tools</a>
		<div class="dropdown__menu" style="column-count: 2; column-gap: 1rem; row-gap: 0.5rem">
			<a href="extension-manager.html">Extension Manager</a>
			<a href="shapes.html">Shapes Editor</a>
			<a href="behaviorspace.html">BehaviorSpace</a>
			<a href="systemdynamics.html">System Dynamics</a>
			<a href="hubnet.html">HubNet</a>
			<a href="hubnet-authoring.html">HubNet Authoring</a>
			<a href="logging.html">Logging</a>
			<a href="controlling.html">Controlling</a>
			<a href="mathematica.html">Mathematica Link</a>
			<a href="3d.html">NetLogo 3D</a>
			<a href="modelingcommons.html">Save to Modeling Commons</a>
		</div>
	</div>
	<!-- Extensions -->
	<div class="navbar__item">
		<a href="extensions.html">Extensions</a>
		<div class="dropdown__menu" style="column-count: 2; column-gap: 1rem; row-gap: 0.5rem">
			<a href="extensions.html">Extensions Guide</a>
			<a href="arduino.html">Arduino</a>
			<a href="array.html">Array</a>
			<a href="bitmap.html">Bitmap</a>
			<a href="csv.html">CSV</a>
			<a href="gis.html">GIS</a>
			<a href="gogo.html">GoGo</a>
			<a href="ls.html">LevelSpace</a>
			<a href="matrix.html">Matrices</a>
			<a href="nw.html">Networks</a>
			<a href="palette.html">Palette</a>
			<a href="profiler.html">Profiler</a>
			<a href="py.html">Python</a>
			<a href="r.html">R</a>
			<a href="resource.html">Resource</a>
			<a href="rnd.html">Rnd</a>
			<a href="sound.html">Sound</a>
			<a href="table.html">Table</a>
			<a href="time.html">Time</a>
			<a href="vid.html">Vid</a>
			<a href="view2.5d.html">View2.5D</a>
		</div>
	</div>
	<!-- FAQ -->
	<div class="navbar__item"><a href="faq.html">FAQ</a></div>
</div>
	</div>
</nav>
<!-- ------------ SEARCH MODAL ------------ -->
<section class="search-modal" id="searchModal" role="dialog" aria-modal="true" aria-label="Search">
	<div class="search-box">
		<input type="text" placeholder="Type to search… Esc to close" autofocus />
	</div>
</section>
<!-- ------------ END NAVBAR ------------ -->
<footer class="nl-container-full mt-5 landing px-standard gap-3 hidden-important">
	<div class="nl-col nl-col-lg-4 px-1 py-2">
		<div class="nl-col nl-col-lg-3 flex flex-col align-items-left">
			<img class="h-fit mt-0 mx-0" src="images/user-manual-logo.png" alt="User Manual Logo" style="max-width: 300px" />
			<hr />
			<p>
				NetLogo is a programmable modeling environment for simulating natural and social phenomena. It was authored by
				Uri Wilensky in 1999 and has been in continuous development ever since at the Center for Connected Learning and
				Computer-Based Modeling.
			</p>
		</div>
	</div>
	<div class="nl-col nl-col-lg-3 px-1 py-2">
		<div>
			<h5 class="mt-0">Related Links</h5>
			<ul>
				<li>
					<a href="https://ccl.northwestern.edu/netlogo/">NetLogo Home</a>
				</li>
				<li>
					<a href="https://ccl.northwestern.edu/">Center for Connected Learning</a>
				</li>
				<li>
					<a href="https://www.netlogoweb.org/">NetLogo Web</a>
				</li>
				<li>
					<a href="https://ccl.northwestern.edu/nettangoweb/">NetTango Web</a>
				</li>
				<li>
					<a href="3d.html">NetLogo 3D</a>
				</li>
				<li>
					<a href="https://www.behaviorsearch.org/">BehaviorSearch</a>
				</li>
				<li>
					<a href="contact.html">Contact Us</a>
				</li>
			</ul>
		</div>
	</div>
	<div class="nl-col nl-col-lg-5 px-1 py-2">
		<p id="copyright" class="mt-2">
			Copyright © 1999- Uri Wilensky and the
			<a href="https://ccl.northwestern.edu/">Center for Connected Learning and Computer-Based Modeling</a> at
			<a href="https://www.northwestern.edu/">Northwestern University</a>. All rights reserved.
		</p>
		<p>
			This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public
			License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any
			later version.
		</p>
		<p>
			Commercial licenses are also available. To inquire about commercial licenses, please contact Uri Wilensky at
			<a href="mailto:netlogo-commercial-admin@ccl.northwestern.edu">netlogo-commercial-admin@ccl.northwestern.edu</a>.
		</p>
		<p>For more information, visit the <a href="https://ccl.northwestern.edu/netlogo">NetLogo website</a>.</p>
	</div>
</footer>
		<script src="scripts/highlight-nl.min.js" type="text/javascript"></script>
		<script>
			(function() {
				document.addEventListener("DOMContentLoaded", function() {
					const highlightNL = require('highlight-nl');
					let codeElems   = Array.from(document.querySelectorAll('pre code'));
					codeElems = codeElems.concat(
						Array.from(document.querySelectorAll('pre')).filter(
							(elem) => elem.children.length === 0 && elem.innerText.trim() !== ''
						)
					);
					codeElems.forEach((elem) => {
						let html = highlightNL(elem.innerText);
						elem.innerHTML = html;
					});
				});
			})()
		</script>
  </body>
</html>

<main class="prose">



This guide has three parts:

- [**What is BehaviorSpace?**](#what-is-behaviorspace): A general description of the tool,
  including the ideas and principles behind it.
- [**How It Works**](#how-it-works): Walks you through how to use the tool and highlights
  its most commonly used features.
- [**Advanced Usage**](#advanced-usage): How to use BehaviorSpace from the command
  line, or from your own Java code.

A number of new features were introduced in NetLogo 6.4:

- [**Subexperiment syntax**](#subexperiment-syntax): A syntax for allowing parameter
 combinations to be run separately, rather than being expanded combinatorically.
- [**Run metrics when**](#run-metrics-when): A reporter can be used to conditionally record
measurements.
- [**Pre experiment commands**](#pre-experiment-commands): Commands can be run before
the experiment begins.
- [**Post experiment commands**](#post-experiment-commands): Commands can be run after
the experiment ends.
- [**Statistics output**](#statistics-output): The mean and standard deviation
of data from repetitions can be saved in an output file.
- [**Lists output**](#lists-output): List data can be output in a file with one list
 element per cell.
- [**Importing and exporting**](#importing-and-exporting): Experiments can now be exported to
an XML file that can be used when running headlessly. Experiments can also be imported into a
 model.
- [**Paused experiments**](#paused-experiments): Experiments can now be paused and resumed.
- [**Run options: update plots and monitors**](#run-options-update-plots-and-monitors):
Reduction in memory usage when box is unchecked.


More about changes to BehaviorSpace in NetLogo 6.4:

- Experiments created in versions prior to 6.4 can still be opened, but experiments
created using new features are not backwards compatible.
- For information on format changes to output files see
[**Output File Changes**](#output-file-changes).
- The Experiment dialog now uses tooltips rather than text below each input element see
[**Creating an experiment setup**](#creating-an-experiment-setup).
- Experiments using the new features can be found in the model
Sample Models=>Biology=>Wolf Sheep Predation, with with additional notes in the Info tab.
- Additional minor changes can be found by searching this page for *(Since 6.4)*.

## What is BehaviorSpace?

BehaviorSpace is a software tool integrated with NetLogo that allows you to
perform experiments with models.

BehaviorSpace runs a model many times, systematically varying the model's
settings and recording the results of each model run. This process is sometimes
called "parameter sweeping". It lets you explore the model's "space" of possible
behaviors and determine which combinations of settings cause the behaviors of
interest.

If your computer has multiple processor cores, you can specify how many model runs will
happen in parallel. Using multiple runs in parallel will increase the memory used
by BehaviorSpace.

### Why BehaviorSpace?

The need for this type of experiment is revealed by the following observations.
Models often have many settings, each of which can take a range of values.
Together they form what in mathematics is called a parameter space for the
model, whose dimensions are the number of settings, and in which every point is
a particular combination of values. Running a model with different settings (and
sometimes even the same ones) can lead to drastically different behavior in the
system being modeled. So, how are you to know which particular configuration of
values, or types of configurations, will yield the kind of behavior you are
interested in? This amounts to the question of where in its huge,
multi-dimension parameter space does your model perform best?

For example, suppose you want speedy synchronization from the agents in the
Fireflies model. The model has four sliders -- number, cycle-length,
flash-length and flashes-to-reset -- that have approximately 2000, 100, 10 and 3
possible values, respectively. That means there are 2000 * 100 * 10 * 3 =
6,000,000 possible combinations of slider values! Trying combinations one at a
time is hardly an efficient way to learn which one will evoke the speediest
synchronization.

BehaviorSpace offers you a much better way to solve this problem by sampling the
model's parameter space -- not exhaustively, but enough so that you will be able
to see relationships form between different slider values and the behavior of the
system. One way to do this is to specify a subset of values from the ranges of each
slider. See [**Combinatorial syntaxes**](#combinatorial-syntaxes). BehaviorSpace
will run the model with each possible combination of those values and, during each
model run, record the results. Since NetLogo 6.4 it has been possible to specify
 non-combinatorial sets of slider values. See
  [**Subexperiment syntax**](#subexperiment-syntax). After all the runs are
over, a dataset is generated which you can open in a different tool, such as a
spreadsheet, database, or scientific visualization application, and explore.

By enabling you to explore the entire "space" of behaviors a model can exhibit,
BehaviorSpace can be a powerful assistant to the modeler.

## How It Works

To begin using BehaviorSpace, open your model, then choose the BehaviorSpace
item on NetLogo's Tools menu.

### Managing experiment setups

The dialog that opens lets you create, edit, duplicate, delete, import, export,
and run experiment setups. Experiments are listed by name and total number of model
runs.

Experiment setups are considered part of a NetLogo model and are saved as part
of the model, but can be also be exported as individual files. See
[**Importing and exporting**](#importing-and-exporting) (*Since 6.4*).

To create a new experiment setup, press the "New" button. To edit an existing
experiment setup, press the "Edit" button. The same dialog is used in both cases,
what differs is the information that is already filled in. The dialog is
non-blocking, which is useful if you want to copy something from the Code Tab,
or view sliders in the Interface Tab (*Since 6.4*).

### Creating an experiment setup

The information that can be included in the Experiment dialog is detailed below.
Note that it is not necessary to specify everything; some parts can be left blank
or with their default values. If a property's name is underlined, you can hover over
it to read more info about the property and how it is used, so you don't have to
revisit this page as often *(Since 6.4)*.

**Experiment name:** Experiments in the same model must have different names. If
you open a model that contains experiments with duplicate names, the conflicting
names will be altered to ensure that all experiment names remain unique *(Since 6.4)*.

**Vary variables as follows:** This is where you specify which settings you want
varied, and what values you want them to take. Variables can include sliders,
switches, choosers, and any global variables in your model. You may notice that
the view and plots do not correspond to the values in the widgets once the experiment is completed.
This is because the globals that are controlled by widgets are reset to their initial state at
the end of the experiment. To synchronize your view and plots with the widgets, run your procedure
that initializes the view.

Variables can also include [[max-pxcor|max-pcor]], [[min-pxcor|min-pcor]],
[[max-pycor|max-pcor]] and [[min-pycor|min-pcor]], [[world-width|world-dim]],
[[world-height|world-dim]] and [[random-seed]]. These are not variables, strictly
speaking, but BehaviorSpace lets you vary them as if they were.
Varying the world dimensions lets you explore the effect of world size upon your
model. Setting  [[world-width|world-dim]] and [[world-height|world-dim]] is
valid under two circumstances. 1) If the origin is centered in width or height
BehaviorSpace will keep it centered in that dimension. This requires that the
corresponding value(s) [[world-width|world-dim]] and/or [[world-height|world-dim]]
must be odd. 2) If one of
the bounds is zero it will remain zero and the other bound will move. For example,
if you start with a world with `min-pxcor = 0`, `max-pxcor = 10` and you vary
`world-width` like this:

> `["world-width" [11 1 14]]`

[[min-pxcor|min-pcor]] will remain zero and [[max-pxcor|max-pcor]] will be set to 11,
12, and 13 for successive runs. If neither of these conditions is true you cannot
you cannot vary [[world-height|world-dim]] or [[world-width|world-dim]] directly but
must vary [[max-pxcor|max-pcor]], [[max-pycor|max-pcor]], [[min-pxcor|min-pcor]]
and [[min-pycor|min-pcor]] instead.

Varying [[random-seed]] lets you repeat runs by using a known seed for the
NetLogo random number generator. Note that you're also free to use the
[[random-seed]] command in your experiment's setup commands. For more
information on random seeds, see the
[Random Numbers](programming.html#random-numbers) section of the Programming
Guide.

#### Combinatorial syntaxes
You may specify values either by listing the values you want used, or by
specifying that you want to try every value within a given range. For example,
to give a slider named `number` every value from 100 to 1000 in increments of
50, you would enter:

> `["number" [100 50 1000]]`

Or, to give it only the values of 100, 200, 400, and 800, you would enter:

> `["number" 100 200 400 800]`

Be careful with the brackets here. Note that there are fewer square brackets in
the second example. Including or not including this extra set of brackets is how
you tell BehaviorSpace whether you are listing individual values, or specifying
a range.

Also note that the double quotes around the variable names are required.

All combinations of the specified values will be run. For example, if you have two
 values for a variable `a` and three values of a variable `b` six runs will result.

> `["a" 1 2]`

> `["b" 2 4 10]`

This would create six runs, organized as follows:

| a   | b   |
| ---: | ---: |
| 1   |  2  |
| 1   |  4  |
| 1   | 10  |
| 2   |  2  |
| 2   |  4  |
| 2   | 10  |

**Run combinations in sequential order checkbox** This box is checked by default,
and causes variables specified later to vary more quickly than those specified earlier.
When the box is unchecked, non-sequential order results, with variables specified earlier
 varying more quickly than those specified later.
The non-sequential order for the variable specification above is:

| a   | b   |
| ---: | ---: |
| 1   |  2  |
| 2   |  2  |
| 1   |  4  |
| 2   |  4  |
| 1   | 10  |
| 2   | 10  |

#### Subexperiment syntax
*(Since 6.4)*

For more advanced users, there is a third available syntax
for varying parameters, the subexperiment syntax.  For example, in the Wolf Sheep Predation model, if you wanted to try
two values for the `grass-regrowth-time` variable, each with its own values for the `initial-number-sheep` and
`initial-number-wolves` variables, you could write it as follows:

> `[["grass-regrowth-time" 30]["initial-number-sheep" 116]["initial-number-wolves" 107]]`

> `[["grass-regrowth-time" 40]["initial-number-sheep" 100]["initial-number-wolves" 77]]`

Note the use of doubly nested square brackets to separate each variable within a
subexperiment. This would create two runs, organized as follows:

| grass-regrowth-time   | initial-number-sheep   | initial-number-wolves   |
| ---: | ---: | ---: |
| 30  | 116 | 107 |
| 40  | 100 | 77  |

The subexperiment syntax also allows you to define constants using the standard
syntax, which will be applied to each subexperiment where they are not overwritten.
To add to the example above, if you wanted to try those combinations of `initial-number-sheep` and
`initial-number-wolves` but with the same value for `grass-regrowth-time`, you could write it as follows:

> `["grass-regrowth-time" 30]`

> `[["initial-number-sheep" 116]["initial-number-wolves" 107]]`

> `[["initial-number-sheep" 100]["initial-number-wolves" 77]]`

This would set `grass-regrowth-time` to 30 for both subexperiments, resulting in the following runs:

| grass-regrowth-time   | initial-number-sheep   | initial-number-wolves   |
| ---: | ---: | ---: |
| 30  | 116 | 107 |
| 30  | 100 | 77  |

You can also override a constant in a subexperiment, as in the following example:

> `["grass-regrowth-time" 30]`

> `[["initial-number-sheep" 116]["initial-number-wolves" 107]]`

> `[["grass-regrowth-time" 40]["initial-number-sheep" 100]["initial-number-wolves" 77]]`

> `[["initial-number-sheep" 80]["initial-number-wolves" 153]]`

This would produce three runs with the following combinations:

| grass-regrowth-time   | initial-number-sheep   | initial-number-wolves   |
| ---: | ---: | ---: |
| 30  | 116 | 107 |
| 40  | 100 | 77  |
| 30  | 80  | 153 |

Note that all constants must be defined before any subexperiments.

You can vary as many settings as you want, including just one, or none at all.
Any settings that you do not vary will retain their current values. Not varying
any settings is useful if you just want to do many runs with the current
settings.

The order in which you list the variables determines the run order. All values
for a later variable will be tried before moving to the next
value for an earlier variable. So for example if you vary both x and y from 1 to
3, and x is listed first, then the order of model runs will be: x=1 y=1,
x=1 y=2, x=1 y=3, x=2 y=1, and so on.

**Repetitions:** Sometimes the behavior of a model can vary a lot from run to
run even if the settings don't change, if the model uses random numbers. If you
want to run the model more than once at each combination of settings, enter a
higher number.
With sequential ordering repetitions occur in sequential runs:

| a   | b   |
| ---: | ---: |
| 1   |  2  |
| 1   |  2  |
| 2   |  2  |
| 2   |  2  |
| 1   |  6  |
| 1   |  6  |
| 2   |  6  |
| 2   |  6  |
| 1   | 10  |
| 1   | 10  |
| 2   | 10  |
| 2   | 10  |

With non-sequential ordering repetitions occur as a second group of runs:

| a   | b   |
| ---: | ---: |
| 1   |  2  |
| 2   |  2  |
| 1   |  6  |
| 2   |  6  |
| 1   | 10  |
| 2   | 10  |
| 1   |  2  |
| 2   |  2  |
| 1   |  6  |
| 2   |  6  |
| 1   | 10  |
| 2   | 10  |

**Measure runs using these reporters:** This is where you specify what data you
want to collect from each run. For example, if you wanted to record how the
population of turtles rose and fell during each run, you would enter:

> `count turtles`

You can enter one reporter, or several, or none at all. If you enter several,
each reporter must be on a line by itself, for example:

> `count frogs`
> `count mice`
> `count birds`

If you don't enter any reporters, the runs will still take place. This is useful
if you want to record the results yourself your own way, such as with the
[[export-world|export-cmds]] command. You can use reporters you have
 defined in the Code tab. Reporters appear as column headers. If you prefer compact
 headers you could replace `count patches with [ pcolor = red ]` with a reporter `red-patches`
 defined in the Code tab.

**Run metrics every step:** Normally NetLogo will measure model runs at
every step, using the reporters you entered in the previous box. If you're doing
very long model runs, you might not want all that data. Uncheck this box if you
want to either only measure model runs at the end of the run or
if you want to specify certain conditions when measurements should be taken.

#### Run metrics when
*(Since 6.4)*

This reporter will be used to determine when measurements
should be recorded if they are not being recorded at every step. Measurements
will be always be taken at the end of each model run, even if this text box is
 empty as was previously the case when the *Measure runs at every step*
 (now *Run metrics every step*) was unchecked.  For example *ticks mod 10 = 0*
  would record every tenth tick, as well as the last tick. Multiple reporters
   can be combined using *and* and *or*.

##### Pre experiment commands
These commands will be run once, before the experiment begins.

**Setup commands:** These commands will be used to begin each model run.
Typically, you will enter the name of a procedure that sets up the model,
typically `setup`. But it is also possible to include other commands as well.
 If you want the same
results each time you run an experiment, you could use something like
`random-seed 473 setup` or to have different results for repetitions
`random-seed (474 + behaviorspace-run-number) setup`

**Go commands:** These commands will be run over and over again to advance to
the model to the next "step". Typically, this will be the name of a procedure,
such as `go`, but you may include any commands you like.

**Stop condition:** This lets you do model runs of varying length, ending each
run when a certain condition becomes true. For example, suppose you wanted each
run to last until there were no more turtles. Then you would enter:

> `not any? turtles`

If you want the length of runs to all be of a fixed length, just leave this
blank.

The run may also stop because the go commands use the [[stop]] command, in the
same way that [[stop]] can be used to stop a forever button. The [[stop]]
command may be used directly in the go commands, or in a procedure called
directly by the go commands. (The intent is that the same `go` procedure should
work both in a button and in a BehaviorSpace experiment.) Note that the step in
which [[stop]] is used is considered to have been aborted, so no results will be
recorded for that step. Therefore, the stopping test should be at the beginning
of the go commands or procedure, not at the end.

**Post run commands:** These are any extra commands that you want run when
each run ends. Usually this is left blank, but you might use it to call the
[[export-world|export-cmds]] command or record the results of
the run in some other way.

##### Post experiment commands
These are any commands that you want to run at
the end of the experiment, after all runs have completed.

**Time limit:** This lets you set a fixed maximum length for each run. If you
don't want to set any maximum, but want the length of the runs to be controlled
by the stop condition instead, enter 0.

**Note on pre and post experiment commands:** These commands execute outside of
the actual runs, so they cannot affect the global variables or agents in the
model (use the Setup commands and Post run commands for that). If you use
primitives like file-open or the CSV extension in the pre or post experiment
commands, their internal state will not carry over into the runs and errors will
likely occur if used there.

### Importing and exporting
*(Since 6.4)*

Although experiments are tied to a model and are usually saved along with a
model, they can also be imported and exported individually to xml files. This
allows you to easily transfer experiments between models, and also prepares
experiments to be run headlessly. After an experiment is exported to an xml file,
it can be edited by hand or by another script, not just within NetLogo.

The **Import** button allows you to import experiments from an xml file. The
selected files may contain any number of experiments, but any experiments that
are formatted incorrectly will not be loaded. If you load an experiment that has
the same name as an existing experiment, the name of the loaded experiment will
be slightly altered to ensure that experiment names remain unique.

The **Export** button allows you to export experiments to an xml file. Any number
of experiments may be selected for export at once, but they will all be combined
into a single output file.

### Special primitives for BehaviorSpace experiments

Currently there are only two, [[behaviorspace-run-number]] and
[[behaviorspace-experiment-name]]. The run number reported by the former
primitive matches the run number used in the results files generated by
BehaviorSpace. The experiment name reported by the latter matches the name with
which the experiment was set up.

### Running an experiment

When you're done setting up your experiment, press the "OK" button, followed by
the "Run" button. A dialog titled "Run Options" will appear.

#### Run options: formats

The "Run Options" dialog lets you choose to create data output files in two primary formats, **Table
output** and **Spreadsheet output**. If one or both of these formats is selected, you can
also select the supplementary **Lists output** and **Statistics output**. Each file path can be entered in its
corresponding text box, or using the **Browse...* button to select a file path using the system
file dialog. If you don't wish to use a particular format, you can clear the file text or click
the **Disable** button and it'll be cleared for you.
The frequency of data collection is determined by the settings of the
**Run metrics every step** and **Run metrics when** options. For **Table output** and
**Spreadsheet output** formats, the initial state of the system is recorded, after the **setup**
commands run but before the **go** commands run for the first time.

After selecting your output formats, BehaviorSpace will prompt you for the name
of a file to save the results to. The default name ends in ".csv". You can
change it to any name you want, but don't leave off the ".csv" part; that
indicates the file is a Comma Separated Values (CSV) file. This is a plain-text
data format that is readable by any text editor as well as by most popular
spreadsheet and database programs.

All four output formats will include a header section that has rows for 1) the NetLogo app
version used, 2) the name of the NetLogo model file used, 3) the name of the BehaviorSpace
experiment used, 4) the date and time at the start, and 5) the dimensions of the world used at
the start.

#### Table output
This format lists each measurement step from each run in its own row, with each
metric in a separate column.  The measurement rows will appear in the order they happen in real
time.  With the **parallel runs** option the measurements may appear in a mixed order as
multiple runs can happen simultaneously.  To help identify which run a row belongs to, there is
a column titled `[run number]` along with a column titled `[step]` that indicates the measurement
number for that run.  Each row also includes the values used for the variables during initial
setup of the run; these values are the same for each of that run's measurement rows.  **Table
output** data is written to the file as each run completes.

The **Table output** format is good to use when you want to further process the data using another
tool, such as importing into a database, a statistics package, or a spreadsheet application for
analysis.

In the **Table output** sample image below, the header section is in red, the run number and step
columns are in blue, the initial values of the variables for the run are in green, and the
measurement metric data is in purple.

![[bs-table.png]]

#### Spreadsheet output
This format lists the step numbers as well as each metric for each run in a
separate column, with each row corresponding to a measurement step that applies to all runs. If one
run finishes before another due to a **stop condition**, then its step numbers after that
point will be blank. At the top of the file there is a `[run number]` row that will have the run
number repeated for each metric at the top of the file.  After that are rows for the initial values
given to each variable for the run.  The spreadsheet output also calculates the min, mean, max, and
final values for the step numbers as well as each metric and lists those after the initial values
before the individual run measurements. Then it lists the actual number of steps a run went through
in a `[total steps]` row.

The **Spreadsheet output** data makes it easier to quickly compare runs against each other, as they
will be aligned vertically when imported into a spreadsheet application.  It can also make
generating comparative graphs of results with initial variable changes across runs easy for the
same reason.

It is important to note that **Spreadsheet output** data is not written to the results file until
the experiment finishes. Since the data is stored in memory until the experiment is done, very
large experiments could run out of memory.  You should disable **Spreadsheet output** unless you
really want it.  Also, if anything interrupts the experiment no spreadsheet results will be written.
Possible sources of interruptions would be runtime errors in the model, running out of memory,
system crashes, or power outages.  For long experiments you may want to also enable **Table output**
format as a precaution so that if something happens and you get no **Spreadsheet output** you'll
at least get partial data output.

In the **Spreadsheet output** sample image below, the header section is in red, the run number row
is in blue, the initial values of the variables for the run are in green, the extra calculated
metrics are in orange, and the measurement metric data is in purple.

![[bs-spreadsheet.png]]

#### Statistics output
*(Since 6.4)*

You can create a file with the mean and standard deviation of each numeric
metric by enabling the **Statistics output**. Metrics are the reporters specified
in the "Measure runs using these reporters as metrics:" box. You must also use the
**Table output** and/or the **Spreadsheet output** because one of them will used
to calculate the mean and standard deviation of each numeric
metric across repetitions for each step. These calculations are done at the end of
the experiment. The statistics are then saved in the specified file.
It is important to note that metrics that produce non-numeric values such as
strings are not included in the statistics.
If the metrics produce lists, the statistics are calculated across elements with
the same index for each list.
Statistics are not calculated for metrics that produce lists that contain non-numeric elements. Also, the type of
the measurement must remain constant. For example, statistics are not calculated if a metric
produces measurements that can be both lists and numbers. Furthermore, the standard deviation may be "N/A",
which means that there were two or fewer collected measurements for that step and parameter combination,
producing a result that is not well-defined. The experiment must use at least 3 repetitions
to produce standard deviation values.

In the **Statistics output** sample image below (creating using the "Red Queen"
library model), the header section is in red, the parameter
combinations are in green, the steps are in blue, and the statistics are in purple.
Starting with column F, the statistics are the mean of "count frogs",  the
standard deviation of "count frogs", followed by the same statistics for
"count snakes", average-poison, and average-resistance. Column E shows the step,
and columns A-D show the parameter combination that was used. The statistics
are calculated across all the repetitions.

![[bs-stats.png]]

#### Lists output
*(Since 6.4)*

This format is a supplement to the other two primary formats, as opposed to a complete data
collection format. If you have any reporters that return a list, you can use the **Lists output**
format to get properly formatted output for those reporters. Data is produced for all
list reporters in the "metrics" box. In both **Spreadsheet output** and
**Table output** formats, lists returned by reporters will be condensed into a single cell, rather
than their elements being spread out with one value per cell. If you need the list values in
individual cells, select the **List output** format in addition to one or both of the other formats.

Note that the **Lists output** format, like the **Spreadsheet output** format, will not contain any
data until the experiment is complete. Also note that the **Lists output** must be used in tandem
with another format, it cannot be used on its own.

In the **Lists output** sample image below, the header section is in red, the reporter name is in
orange, the run number and step columns are in blue, the initial values of the variables for the run
are in green, and the expanded list data is in purple. The list data starts in
row 7, with the headers (the index into the list, starting from 0) starting in
column E.

![[bs-lists.png]]

#### Output File Changes
*(Since 6.4)*

- Output files have version numbers.
- Spreadsheet output always includes step information.
- Spreadsheet output column header `[initial & final values]` was changed to the more accurate `[final value]`.
- [**Statistics output**](#statistics-output) was added.
- [**Lists output**](#lists-output) was added.

#### Run options: update plots and monitors

The "Run Options" dialog lets you choose whether to update plots and monitors or not.
Performance is better when the box is unchecked.
Note that *(Since 6.4)* if you begin the experiment with the box unchecked, you will
not be able to toggle between enabling and disabling the update plots checkbox in the
"Running Experiments" dialog. This gives you an even greater performance improvement
than was obtained before NetLogo 6.4, when such toggling was possible.
Check the box if you you need to export plot data using primitives such as [[export-interface|export-cmds]],
[[export-plot|export-cmds]], [[export-all-plots|export-cmds]], and [[export-world|export-cmds]].

#### Run options: parallel runs

The "Run Options" dialog also lets you select whether you want multiple model runs to happen in parallel, and if so, how
many are allowed to be simultaneously active. The default and recommended maximum number of parallel runs are shown
below the text box *(Since 6.4)*. Your choice of number of parallel runs
is remembered from experiment to experiment *(Since 6.4)*. Because each additional run
increases memory usage we recommend starting with the default number of runs, and then
trying more parallel runs if you want. The recommended maximum number of parallel runs is just an estimate, and
some users have found that performance is significantly decreased when using the maximum.

There are a few cautions associated with parallel runs.

First, if multiple runs are active, only one of them will be in the "foreground" and cause the view and plots to update.
The other runs will happen invisibly in the background.

Second, invisible background runs can't use primitives that only work in the GUI. For example, a background run can't
make a movie.

Third, since parallel runs progress independently of each other, table format output may contain interleaved,
out-of-order results. When you analyze your table data, you may wish to sort it by run number first. (Spreadsheet format
output is not affected by this issue, since it is not written until the experiment completes or is aborted.)

Fourth, using all available processor cores may make your computer slow to use for other tasks while the experiment is
running or slow to complete runs as contention will build for memory between the runs themselves. If your
model uses a large amount of memory, you may find that reducing the number of runs will enable the runs to
complete in less time overall since work will be done by the system keeping the memory for each run available. A good
rule of thumb might be to start with the default value shown in the "Run Options", and bump
up or down from there to see where your "sweet spot" is for least time to complete all runs.

Fifth, doing runs in parallel will multiply the experiment's memory requirements accordingly. You may need to increase
NetLogo's memory ceiling (see [this FAQ
entry](faq.html#how-big-can-my-model-be-how-many-turtles-patches-procedures-buttons-and-so-on-can-my-model-contain)).
By default NetLogo will not exceed 50% of your system's memory.

Sixth, each parallel run will get its own world for the model to run in.  This world is *not* cleared automatically by
BehaviorSpace if a parallel run gets re-used for another repetition, which happens quite frequently.  This means, for
example, if you do `ask patches [ set pcolor red ]` in one run and do not use `clear-all` or `clear-patches` in the
setup commands of the next run, then the patches will all still be red.  In general using `clear-all` before each run
would be a best practice, but there are times when you might not want to, such as loading data from a file that doesn't
change run-to-run.  Just be careful with whatever data is not cleared out.

Seventh, there is a very, very small chance that at startup multiple parallel runs could wind up with the same random
number generator state if they startup at the exact same moment in time.  This means the runs would produce identical
output for all random operations and likely the same results.  This would have a chance to happen when running on very
fast processors and with lots of parallel runs at once.  If you need to make sure this doesn't impact your results, you
can add `random-seed new-seed` to your setup commands to re-generate a new unique random seed for each run.  In fact,
storing the `new-seed` as a global variable so you can output it with the rest of your results would let you re-run a
run later on by manually using that value to set the `random-seed`.

#### Observing runs

After you complete the "Run Options" dialog, another dialog will appear, titled
"Running Experiment". In this dialog, you'll see a progress report of how many
runs have been completed so far and how much time has passed. If you entered any
reporters for measuring the runs, and if you left the "Run metrics every step"
box checked, then you'll see a plot of how they vary over the course of each run.

You can also watch the runs in the main NetLogo window. (If the "Running
Experiment" dialog is in the way, just move it to a different place on the
screen.) If you don't need to see the plots update, then use the checkboxes in
the "Running Experiment" dialog to turn the updating off. This will make the
 experiment go faster. However, if you already disabled updating plots and monitors
  in the "Run Options" dialog, this checkbox will be disabled *(Since 6.4)*.

If you want to stop your experiment before it's finished, you have two options.
To stop the experiment after the current runs have completed and save your progress
for later, press the "Pause" button *(Since 6.4)*. To stop the experiment immediately without
waiting for the current runs to complete, press the "Abort" button. Any output
generated so far will still be saved, but pressing "Abort" can lead to fragmented
data, so aborted experiments cannot be resumed.

When all the runs have finished, the experiment is complete. Spreadsheet, Lists and Stats
 output are created at this point.

#### Paused experiments
*(Since 6.4)*

Paused experiments will appear in the BehaviorSpace window marked with "In Progress".
To resume an experiment where you paused it, select it and press the "Run" button.
To reset a paused experiment to its initial state, select it and press the "Abort"
button.

If you are using Spreadsheet output a file containing the data up until the experiment is
 paused will be written. This data will be used as part of the creation of a complete
 Spreadsheet file. Note that if your experiment is writing to its own external file you
  may need to make some changes in order for pausing to work correctly. For example you
  should use `file-flush` or `file-close` at the end of each run to ensure all the data
   is written to the file, and should do `file-open` before doing any writing during a
   run. When opening a file in writing mode, all new data will be appended to the end
    of the original file, which is probably the behavior you want.

Note that moving or deleting output files before resuming a paused experiment will
cause an error. Outputting new experiment data to a file associated with an existing
paused experiment may also ause an error when that experiment is resumed.



## Advanced Usage

### Running from the command line

It is possible to run BehaviorSpace experiments "headless", that is, from the
command line, without any graphical user interface (GUI). This is useful for
automating runs on a single machine or a cluster of machines.

No Java programming is required. Experiment setups can be created in the GUI and
then run later from the command line, or, if you prefer, you can create or edit
experiment setups directly using XML.

#### How to use it

Run NetLogo using the `NetLogo_Console` app with the `--headless` command line argument.
This is found in the root directory of your NetLogo installation. The
`NetLogo_Console` script supports the following arguments:

- `--headless`: Enable headless mode to run a BehaviorSpace experiment (required, will
open the graphical interface otherwise).
- `--model <path>`: pathname of model to open
(required)
- `--setup-file <path>`: read experiment setups from this file instead of the
  model file
- `--experiment <name>`: name of experiment to run
- `--table <path>`: pathname to send table output to (or `-` for standard
  output)
- `--spreadsheet <path>`: pathname to send table output to (or `-` for standard
  output)
- `--lists <path>`: pathname to send lists output to (or - for standard output),
  cannot be used without `--table` or `--spreadsheet`
- --stats <path>: pathname to send statistics output to (or - for standard output)
 cannot be used without `--table` or `--spreadsheet`
- `--threads <number>`: use this many threads to do model runs in parallel, or 1
  to disable parallel runs. defaults to `floor(0.75 * <number of processors>)`.
- `--update-plots`: enable plot updates. Include this if you want to export plot data,
  or exclude it for better performance.
- `--min-pxcor <number>`: override world size setting in model file
- `--max-pxcor <number>`: override world size setting in model file
- `--min-pycor <number>`: override world size setting in model file
- `--max-pycor <number>`: override world size setting in model file

`--model` is required. If you don't specify `--experiment`, you must specify
`--setup-file`. By default no results are generated, so you'll usually want to
specify either `--table` or `--spreadsheet`, or both. If you specify any of the
world dimensions, you must specify all four.

Note that prior to NetLogo 6.3.0 the directions were to use `netlogo-headless.sh`
(or `netlogo-headless.bat` on Windows) along with a separate installation of Java of the
system to run BehaviorSpace experiments.  The `netlogo-headless.sh` script is still
included with NetLogo and can still be used as before, which might be preferrable in
server environments where the installed Java version is strictly controlled.  But the
recommended method for on a personal computer is to use the `NetLogo_Console
--headless` app.  Because `NetLogo_Console` uses the Java that comes bundled with NetLogo it
requires no extra software installation or configuration.

#### Examples

It is easiest if you create your experiment setup ahead of time in the GUI, so
it is saved as part of the model. To run an experiment setup saved in a model,
here is an example command line, run from the NetLogo 7.0.0-beta2 installation
folder so the paths to the `NetLogo_Console` app and `Wolf Sheep Simple 5.nlogo`
model are correct.

The below commands should work as-is in a terminal on macOS and Linux.  On Windows in the
Command Prompt you can use `^` instead of `\` to break the command across multiple lines,
or just put the command on a single line.

```sh
./NetLogo_Console --headless \
  --model "models/IABM Textbook/chapter 4/Wolf Sheep Simple 5.nlogo" \
  --experiment "Wolf Sheep Simple model analysis" \
  --table -
```

After the named experiment has run, the results are sent to standard output in
table format, as CSV. `-` is how you specify standard output instead of output
to a file.

When running NetLogo headless, it forces the system property `java.awt.headless`
to be true. This tells Java to run in headless mode, allowing NetLogo to run on
machines when a graphical display is not available.

The required `--model` argument is used to specify the model file you want to
open.

The `--experiment` argument is used to specify the name of the experiment you
want to run. (At the time you create an experiment setup in the GUI, you assign
it a name.)

Here's another example that shows some additional, optional arguments:

```sh
./NetLogo_Console --headless \
  --model "models/IABM Textbook/chapter 4/Wolf Sheep Simple 5.nlogo" \
  --experiment "Wolf Sheep Simple model analysis" \
  --max-pxcor 5 \
  --min-pxcor -5 \
  --max-pycor 5 \
  --min-pycor -5
```

Note the use of the optional `--max-pxcor`, `--max-pycor`, etc. arguments to
specify a different world size than that saved in the model. (It's also possible
for the experiment setup to specify values for the world dimensions; if they are
specified by the experiment setup, then there is no need to specify them on the
command line.)

Since neither `--table` nor `--spreadsheet` is specified, no results will be
generated. This is useful if the experiment setup generates all the output you
need by some other means, such as exporting world files or writing to a text
file.

Yet another example:

```sh
./NetLogo_Console --headless \
  --model "models/IABM Textbook/chapter 4/Wolf Sheep Simple 5.nlogo" \
  --experiment "Wolf Sheep Simple model analysis" \
  --table wsp5-table-output.csv \
  --spreadsheet wsp5-spreadsheet-output.csv \
  --lists wsp5-lists-output.csv \
  --stats wsp5-stats-output.csv
```

The optional `--table <filename>` argument specifies that output should be
generated in a table format and written to the given file as CSV data. If `-` is
specified as the filename, than the output is sent to the standard system output
stream. Table data is written as it is generated, with each complete run.

The optional `--spreadsheet <filename>` argument specifies that spreadsheet
output should be generated and written to the given file as CSV data. If `-` is
specified as the filename, than the output is sent to the standard system output
stream. Spreadsheet data is not written out until all runs in the experiment are
finished.

The optional `--lists <filename>` argument specifies that lists
output should be generated and written to the given file as CSV data. If `-` is
specified as the filename, than the output is sent to the standard system output
stream. Lists data is not written out until all runs in the experiment are
finished.

The optional `--stats <filename>` argument specifies that stats
output should be generated and written to the given file as CSV data. If `-` is
specified as the filename, than the output is sent to the standard system output
stream. Stats data is not written out until all runs in the experiment are
finished.

Note that it is legal to specify both `--table` and `--spreadsheet`, and if you
do, both kinds of output file will be generated. If you use `--lists` or `--stats`
 at least one of the `--table` or `--spreadsheet`  options must be used.

Here is an example that shows how to run an experiment setup which is
stored in a separate XML file, instead of in the model file (see below for more
information on the XML file format).  This assumes you've created a
`my-wsp-setups.xml` file with a `My WSP Exploration" experiment and placed it
in your home directory. The most straight-forward way to create a setup file
is to create an experiment using BehaviorSpace in the NetLogo GUI and use the
 **Export ** option.

```sh
./NetLogo_Console --headless \
  --model "models/IABM Textbook/chapter 4/Wolf Sheep Simple 5.nlogo" \
  --setup-file ~/my-wsp-setups.xml \
  --experiment "My WSP Exploration"
```

If the XML file contains more than one experiment setup, it is necessary to use
the `--experiment` argument to specify the name of the setup to use.

In order to run a NetLogo 3D experiment, run headless with the `--3D` argument,
for example:

```sh
./NetLogo_Console --headless \
  --3D \
  --model "models/3D/Sample Models/GasLab/GasLab Free Gas 3D.nlogo3d" \
  --experiment "100 runs" \
  --table -
```

Note that you should supply a 3D model and there are also 3D arguments
`--max-pzcor <number>` and `--min-pzcor <number>`.

The next section has information on how to create standalone experiment setup
files using XML.

### Setting up experiments in XML

We don't yet have detailed documentation on authoring experiment setups in XML,
but if you already have some familiarity with XML, then the following pointers
may be enough to get you started.

The structure of BehaviorSpace experiment setups in XML is determined by a
Document Type Definition (DTD) file. The DTD is stored in NetLogo.jar, as
`system/behaviorspace.dtd`. (JAR files are also zip files, so you can extract
the DTD from the JAR using Java's "jar" utility or with any program that
understands zip format.)

The easiest way to learn what setups look like in XML, though, is to author a
few of them in BehaviorSpace's GUI, save the model, export them *(Since 6.4)* and then examine the
resulting .xml file(s) in a text editor. The experiment setups can also be found
 towards the end of the .nlogo file, in a section that begins and ends with a
`experiments` tag. Example:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE experiments SYSTEM "behaviorspace.dtd">
<experiments>
  <experiment name="My WSP Exploration" repetitions="5" runMetricsEveryStep="false">
    <setup>setup</setup>
    <go>go</go>
    <timeLimit steps="2000"/>
    <metric>count wolves</metric>
    <metric>count sheep</metric>
    <metric>sum [grass-amount] of patches</metric>
    <enumeratedValueSet variable="energy-gain-from-grass">
      <value value="2"/>
    </enumeratedValueSet>
    <steppedValueSet variable="number-of-wolves" first="5" step="1" last="15"/>
    <enumeratedValueSet variable="movement-cost">
      <value value="0.5"/>
    </enumeratedValueSet>
    <enumeratedValueSet variable="energy-gain-from-sheep">
      <value value="5"/>
    </enumeratedValueSet>
    <enumeratedValueSet variable="number-of-sheep">
      <value value="500"/>
    </enumeratedValueSet>
    <enumeratedValueSet variable="grass-regrowth-rate">
      <value value="0.3"/>
    </enumeratedValueSet>
  </experiment>
</experiments>
```

In this example, only one experiment setup is given, but you can put as many as
you want between the beginning and ending `experiments` tags.

Between looking at the DTD, and looking at examples you create in the GUI, it
will hopefully be apparent how to use the tags to specify different kind of
experiments. The DTD specifies which tags are required and which are optional,
which may be repeated and which may not, and so forth.

If you want to create a setup file for NetLogo 6.3.0 and earlier versions for
which **Export** is not available you need to know that in a model file the XML for
 experiment setups does not begin with any XML headers, because the not whole file
 is XML, only part of it.
Therefore if you manually create a separate file for experiment setups, the
extension on the file should be .xml not .nlogo, and you'll need to begin the
file with proper XML headers, as follows:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE experiments SYSTEM "behaviorspace.dtd">
```

The second line must be included exactly as shown. In the first line, you may
specify a different encoding than `UTF-8`, such as `ISO-8859-1`.

### Adjusting JVM Parameters

Opening the NetLogo Headless launcher script will show the options used to
launch java when running NetLogo Headless. You can adjust various JVM parameters
in this script. You may also pass in Java properties starting with `-D` to the
launcher.

NetLogo allocates a maximum of half your total system memory for running your model as it is needed.  If you want to set
a maximum amount of memory for BehaviorSpace to use you can use [the `-Xmx` setting to specify a particular heap
size](faq.html#how-big-can-my-model-be-how-many-turtles-patches-procedures-buttons-and-so-on-can-my-model-contain).

Note the use of `-Dfile.encoding=UTF-8`. This forces all file I/O to use UTF-8
encoding. Doing so ensures that NetLogo can load all models consistently, and
that file-* primitives work consistently on all platforms, including models
containing Unicode characters.

### Controlling API

If BehaviorSpace is not sufficient for your needs, a possible alternative is to
use our Controlling API, which lets you write Java code that controls NetLogo.
The API lets you run BehaviorSpace experiments from Java code, or, you can write
custom code that controls NetLogo more directly to do BehaviorSpace-like things.
See the [Controlling](controlling.html) section of the User Manual for further
details on both possibilities.

</main>