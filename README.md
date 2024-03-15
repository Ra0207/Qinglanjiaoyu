# Qinglanjiaoyu
青蓝教育

@import url(fontawesome-all.min.css);
@import url("https://fonts.googleapis.com/css?family=Raleway:200,700|Source+Sans+Pro:300,600,300italic,600italic");

/*
	Solid State by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
*/

html, body, div, span, applet, object,
iframe, h1, h2, h3, h4, h5, h6, p, blockquote,
pre, a, abbr, acronym, address, big, cite,
code, del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var, b,
u, i, center, dl, dt, dd, ol, ul, li, fieldset,
form, label, legend, table, caption, tbody,
tfoot, thead, tr, th, td, article, aside,
canvas, details, embed, figure, figcaption,
footer, header, hgroup, menu, nav, output, ruby,
section, summary, time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;}

article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;}

body {
	line-height: 1;
}

ol, ul {
	list-style: none;
}

blockquote, q {
	quotes: none;
}

	blockquote:before, blockquote:after, q:before, q:after {
		content: '';
		content: none;
	}

table {
	border-collapse: collapse;
	border-spacing: 0;
}

body {
	-webkit-text-size-adjust: none;
}

mark {
	background-color: transparent;
	color: inherit;
}

input::-moz-focus-inner {
	border: 0;
	padding: 0;
}

input, select, textarea {
	-moz-appearance: none;
	-webkit-appearance: none;
	-ms-appearance: none;
	appearance: none;
}

/* Basic */

	@-ms-viewport {
		width: device-width;
	}

	body {
		-ms-overflow-style: scrollbar;
	}

	@media screen and (max-width: 480px) {

		html, body {
			min-width: 320px;
		}

	}

	html {
		box-sizing: border-box;
	}

	*, *:before, *:after {
		box-sizing: inherit;
	}

	body {
		background-color:#265DC7;
;
		background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
		background-size: auto,
 cover;
		background-attachment: fixed,
 fixed;
		background-position: center,
 center;
	}

		body.is-preload *, body.is-preload *:before, body.is-preload *:after {
			-moz-animation: none !important;
			-webkit-animation: none !important;
			-ms-animation: none !important;
			animation: none !important;
			-moz-transition: none !important;
			-webkit-transition: none !important;
			-ms-transition: none !important;
			transition: none !important;
		}

/* Type */

	body, input, select, textarea {
		color: #FFFFFF;
		font-family: "Source Sans Pro", Helvetica, sans-serif;
		font-size: 16.5pt;
		font-weight: 300;
		line-height: 1.65;
	}

		@media screen and (max-width: 1680px) {

			body, input, select, textarea {
				font-size: 13pt;
			}

		}

		@media screen and (max-width: 1280px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 980px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 736px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 480px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

	a {
		-moz-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		-webkit-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		-ms-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		border-bottom: dotted 1px rgba(255, 255, 255, 0.35);
		color: #ffffff;
		text-decoration: none;
	}

		a:hover {
			border-bottom-color: transparent;
			color: #ffffff !important;
		}

		a.special:not(.button) {
			text-decoration: none;
			border-bottom: 0;
			display: block;
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 0.8em;
			font-weight: 700;
			letter-spacing: 0.1em;
			margin: 0 0 2em 0;
			text-transform: uppercase;
		}

			a.special:not(.button):before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				display: inline-block;
				font-style: normal;
				font-variant: normal;
				text-rendering: auto;
				line-height: 1;
				text-transform: none !important;
				font-family: 'Font Awesome 5 Free';
				font-weight: 900;
			}

			a.special:not(.button):before {
				-moz-transition: background-color 0.2s ease-in-out;
				-webkit-transition: background-color 0.2s ease-in-out;
				-ms-transition: background-color 0.2s ease-in-out;
				transition: background-color 0.2s ease-in-out;
				border-radius: 100%;
				border: solid 2px rgba(255, 255, 255, 0.125);
				content: '\f105';
				display: inline-block;
				font-size: 1.25em;
				height: 2em;
				line-height: 1.75em;
				margin-right: 0.85em;
				text-align: center;
				text-indent: 0.15em;
				vertical-align: middle;
				width: 2em;
			}

			a.special:not(.button):hover:before {
				background-color: rgba(255, 255, 255, 0.025);
			}

			a.special:not(.button):active:before {
				background-color: rgba(255, 255, 255, 0.075);
			}

	strong, b {
		color: #ffffff;
		font-weight: 600;
	}

	em, i {
		font-style: italic;
	}

	p {
		margin: 0 0 2em 0;
	}

	h1, h2, h3, h4, h5, h6 {
		color: #ffe4b4;
		font-family: Raleway, Helvetica, sans-serif;
		font-weight: 700;
		letter-spacing: 0.1em;
		margin: 0 0 1em 0;
		text-transform: uppercase;
	}

		h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
			color: inherit;
			text-decoration: none;
			border-bottom: 0;
		}

		h1 span, h2 span, h3 span, h4 span, h5 span, h6 span {
			font-weight: 200;
		}

		h1.major, h2.major, h3.major, h4.major, h5.major, h6.major {
			padding-bottom: 1em;
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
		}

	h2 {
		font-size: 1.2em;
	}

	h3 {
		font-size: 0.9em;
	}

	h4 {
		font-size: 0.7em;
	}

	h5 {
		font-size: 0.7em;
	}

	h6 {
		font-size: 0.7em;
	}

	@media screen and (max-width: 736px) {

		h2 {
			font-size: 1em;
		}

		h3 {
			font-size: 0.8em;
		}

	}

	sub {
		font-size: 0.8em;
		position: relative;
		top: 0.5em;
	}

	sup {
		font-size: 0.8em;
		position: relative;
		top: -0.5em;
	}

	blockquote {
		border-left: solid 4px rgba(255, 255, 255, 0.125);
		font-style: italic;
		margin: 0 0 2em 0;
		padding: 0.5em 0 0.5em 2em;
	}

	code {
		background: rgba(255, 255, 255, 0.025);
		border-radius: 5px;
		border: solid 2px rgba(255, 255, 255, 0.125);
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0.25em;
		padding: 0.25em 0.65em;
	}

	pre {
		-webkit-overflow-scrolling: touch;
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0 2em 0;
	}

		pre code {
			display: block;
			line-height: 1.75em;
			padding: 1em 1.5em;
			overflow-x: auto;
		}

	hr {
		border: 0;
		border-bottom: solid 2px rgba(255, 255, 255, 0.125);
		margin: 2.5em 0;
	}

		hr.major {
			margin: 4em 0;
		}

	.align-left {
		text-align: left;
	}

	.align-center {
		text-align: center;
	}

	.align-right {
		text-align: right;
	}

/* Row */

	.row {
		display: flex;
		flex-wrap: wrap;
		box-sizing: border-box;
		align-items: stretch;
	}

		.row > * {
			box-sizing: border-box;
		}

		.row.gtr-uniform > * > :last-child {
			margin-bottom: 0;
		}

		.row.aln-left {
			justify-content: flex-start;
		}

		.row.aln-center {
			justify-content: center;
		}

		.row.aln-right {
			justify-content: flex-end;
		}

		.row.aln-top {
			align-items: flex-start;
		}

		.row.aln-middle {
			align-items: center;
		}

		.row.aln-bottom {
			align-items: flex-end;
		}

		.row > .imp {
			order: -1;
		}

		.row > .col-1 {
			width: 8.33333%;
		}

		.row > .off-1 {
			margin-left: 8.33333%;
		}

		.row > .col-2 {
			width: 16.66667%;
		}

		.row > .off-2 {
			margin-left: 16.66667%;
		}

		.row > .col-3 {
			width: 25%;
		}

		.row > .off-3 {
			margin-left: 25%;
		}

		.row > .col-4 {
			width: 33.33333%;
		}

		.row > .off-4 {
			margin-left: 33.33333%;
		}

		.row > .col-5 {
			width: 41.66667%;
		}

		.row > .off-5 {
			margin-left: 41.66667%;
		}

		.row > .col-6 {
			width: 50%;
		}

		.row > .off-6 {
			margin-left: 50%;
		}

		.row > .col-7 {
			width: 58.33333%;
		}

		.row > .off-7 {
			margin-left: 58.33333%;
		}

		.row > .col-8 {
			width: 66.66667%;
		}

		.row > .off-8 {
			margin-left: 66.66667%;
		}

		.row > .col-9 {
			width: 75%;
		}

		.row > .off-9 {
			margin-left: 75%;
		}

		.row > .col-10 {
			width: 83.33333%;
		}

		.row > .off-10 {
			margin-left: 83.33333%;
		}

		.row > .col-11 {
			width: 91.66667%;
		}

		.row > .off-11 {
			margin-left: 91.66667%;
		}

		.row > .col-12 {
			width: 100%;
		}

		.row > .off-12 {
			margin-left: 100%;
		}

		.row.gtr-0 {
			margin-top: 0;
			margin-left: 0em;
		}

			.row.gtr-0 > * {
				padding: 0 0 0 0em;
			}

			.row.gtr-0.gtr-uniform {
				margin-top: 0em;
			}

				.row.gtr-0.gtr-uniform > * {
					padding-top: 0em;
				}

		.row.gtr-25 {
			margin-top: 0;
			margin-left: -0.4375em;
		}

			.row.gtr-25 > * {
				padding: 0 0 0 0.4375em;
			}

			.row.gtr-25.gtr-uniform {
				margin-top: -0.4375em;
			}

				.row.gtr-25.gtr-uniform > * {
					padding-top: 0.4375em;
				}

		.row.gtr-50 {
			margin-top: 0;
			margin-left: -0.875em;
		}

			.row.gtr-50 > * {
				padding: 0 0 0 0.875em;
			}

			.row.gtr-50.gtr-uniform {
				margin-top: -0.875em;
			}

				.row.gtr-50.gtr-uniform > * {
					padding-top: 0.875em;
				}

		.row {
			margin-top: 0;
			margin-left: -1.75em;
		}

			.row > * {
				padding: 0 0 0 1.75em;
			}

			.row.gtr-uniform {
				margin-top: -1.75em;
			}

				.row.gtr-uniform > * {
					padding-top: 1.75em;
				}

		.row.gtr-150 {
			margin-top: 0;
			margin-left: -2.625em;
		}

			.row.gtr-150 > * {
				padding: 0 0 0 2.625em;
			}

			.row.gtr-150.gtr-uniform {
				margin-top: -2.625em;
			}

				.row.gtr-150.gtr-uniform > * {
					padding-top: 2.625em;
				}

		.row.gtr-200 {
			margin-top: 0;
			margin-left: -3.5em;
		}

			.row.gtr-200 > * {
				padding: 0 0 0 3.5em;
			}

			.row.gtr-200.gtr-uniform {
				margin-top: -3.5em;
			}

				.row.gtr-200.gtr-uniform > * {
					padding-top: 3.5em;
				}

		@media screen and (max-width: 1680px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xlarge {
					order: -1;
				}

				.row > .col-1-xlarge {
					width: 8.33333%;
				}

				.row > .off-1-xlarge {
					margin-left: 8.33333%;
				}

				.row > .col-2-xlarge {
					width: 16.66667%;
				}

				.row > .off-2-xlarge {
					margin-left: 16.66667%;
				}

				.row > .col-3-xlarge {
					width: 25%;
				}

				.row > .off-3-xlarge {
					margin-left: 25%;
				}

				.row > .col-4-xlarge {
					width: 33.33333%;
				}

				.row > .off-4-xlarge {
					margin-left: 33.33333%;
				}

				.row > .col-5-xlarge {
					width: 41.66667%;
				}

				.row > .off-5-xlarge {
					margin-left: 41.66667%;
				}

				.row > .col-6-xlarge {
					width: 50%;
				}

				.row > .off-6-xlarge {
					margin-left: 50%;
				}

				.row > .col-7-xlarge {
					width: 58.33333%;
				}

				.row > .off-7-xlarge {
					margin-left: 58.33333%;
				}

				.row > .col-8-xlarge {
					width: 66.66667%;
				}

				.row > .off-8-xlarge {
					margin-left: 66.66667%;
				}

				.row > .col-9-xlarge {
					width: 75%;
				}

				.row > .off-9-xlarge {
					margin-left: 75%;
				}

				.row > .col-10-xlarge {
					width: 83.33333%;
				}

				.row > .off-10-xlarge {
					margin-left: 83.33333%;
				}

				.row > .col-11-xlarge {
					width: 91.66667%;
				}

				.row > .off-11-xlarge {
					margin-left: 91.66667%;
				}

				.row > .col-12-xlarge {
					width: 100%;
				}

				.row > .off-12-xlarge {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.4375em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.4375em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.4375em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.4375em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.875em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.875em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.875em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.875em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.75em;
				}

					.row > * {
						padding: 0 0 0 1.75em;
					}

					.row.gtr-uniform {
						margin-top: -1.75em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.75em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -2.625em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 2.625em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -2.625em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 2.625em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -3.5em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 3.5em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -3.5em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 3.5em;
						}

		}

		@media screen and (max-width: 1280px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-large {
					order: -1;
				}

				.row > .col-1-large {
					width: 8.33333%;
				}

				.row > .off-1-large {
					margin-left: 8.33333%;
				}

				.row > .col-2-large {
					width: 16.66667%;
				}

				.row > .off-2-large {
					margin-left: 16.66667%;
				}

				.row > .col-3-large {
					width: 25%;
				}

				.row > .off-3-large {
					margin-left: 25%;
				}

				.row > .col-4-large {
					width: 33.33333%;
				}

				.row > .off-4-large {
					margin-left: 33.33333%;
				}

				.row > .col-5-large {
					width: 41.66667%;
				}

				.row > .off-5-large {
					margin-left: 41.66667%;
				}

				.row > .col-6-large {
					width: 50%;
				}

				.row > .off-6-large {
					margin-left: 50%;
				}

				.row > .col-7-large {
					width: 58.33333%;
				}

				.row > .off-7-large {
					margin-left: 58.33333%;
				}

				.row > .col-8-large {
					width: 66.66667%;
				}

				.row > .off-8-large {
					margin-left: 66.66667%;
				}

				.row > .col-9-large {
					width: 75%;
				}

				.row > .off-9-large {
					margin-left: 75%;
				}

				.row > .col-10-large {
					width: 83.33333%;
				}

				.row > .off-10-large {
					margin-left: 83.33333%;
				}

				.row > .col-11-large {
					width: 91.66667%;
				}

				.row > .off-11-large {
					margin-left: 91.66667%;
				}

				.row > .col-12-large {
					width: 100%;
				}

				.row > .off-12-large {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.4375em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.4375em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.4375em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.4375em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.875em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.875em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.875em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.875em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.75em;
				}

					.row > * {
						padding: 0 0 0 1.75em;
					}

					.row.gtr-uniform {
						margin-top: -1.75em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.75em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -2.625em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 2.625em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -2.625em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 2.625em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -3.5em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 3.5em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -3.5em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 3.5em;
						}

		}

		@media screen and (max-width: 980px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-medium {
					order: -1;
				}

				.row > .col-1-medium {
					width: 8.33333%;
				}

				.row > .off-1-medium {
					margin-left: 8.33333%;
				}

				.row > .col-2-medium {
					width: 16.66667%;
				}

				.row > .off-2-medium {
					margin-left: 16.66667%;
				}

				.row > .col-3-medium {
					width: 25%;
				}

				.row > .off-3-medium {
					margin-left: 25%;
				}

				.row > .col-4-medium {
					width: 33.33333%;
				}

				.row > .off-4-medium {
					margin-left: 33.33333%;
				}

				.row > .col-5-medium {
					width: 41.66667%;
				}

				.row > .off-5-medium {
					margin-left: 41.66667%;
				}

				.row > .col-6-medium {
					width: 50%;
				}

				.row > .off-6-medium {
					margin-left: 50%;
				}

				.row > .col-7-medium {
					width: 58.33333%;
				}

				.row > .off-7-medium {
					margin-left: 58.33333%;
				}

				.row > .col-8-medium {
					width: 66.66667%;
				}

				.row > .off-8-medium {
					margin-left: 66.66667%;
				}

				.row > .col-9-medium {
					width: 75%;
				}

				.row > .off-9-medium {
					margin-left: 75%;
				}

				.row > .col-10-medium {
					width: 83.33333%;
				}

				.row > .off-10-medium {
					margin-left: 83.33333%;
				}

				.row > .col-11-medium {
					width: 91.66667%;
				}

				.row > .off-11-medium {
					margin-left: 91.66667%;
				}

				.row > .col-12-medium {
					width: 100%;
				}

				.row > .off-12-medium {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.4375em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.4375em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.4375em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.4375em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.875em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.875em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.875em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.875em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.75em;
				}

					.row > * {
						padding: 0 0 0 1.75em;
					}

					.row.gtr-uniform {
						margin-top: -1.75em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.75em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -2.625em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 2.625em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -2.625em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 2.625em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -3.5em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 3.5em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -3.5em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 3.5em;
						}

		}

		@media screen and (max-width: 736px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-small {
					order: -1;
				}

				.row > .col-1-small {
					width: 8.33333%;
				}

				.row > .off-1-small {
					margin-left: 8.33333%;
				}

				.row > .col-2-small {
					width: 16.66667%;
				}

				.row > .off-2-small {
					margin-left: 16.66667%;
				}

				.row > .col-3-small {
					width: 25%;
				}

				.row > .off-3-small {
					margin-left: 25%;
				}

				.row > .col-4-small {
					width: 33.33333%;
				}

				.row > .off-4-small {
					margin-left: 33.33333%;
				}

				.row > .col-5-small {
					width: 41.66667%;
				}

				.row > .off-5-small {
					margin-left: 41.66667%;
				}

				.row > .col-6-small {
					width: 50%;
				}

				.row > .off-6-small {
					margin-left: 50%;
				}

				.row > .col-7-small {
					width: 58.33333%;
				}

				.row > .off-7-small {
					margin-left: 58.33333%;
				}

				.row > .col-8-small {
					width: 66.66667%;
				}

				.row > .off-8-small {
					margin-left: 66.66667%;
				}

				.row > .col-9-small {
					width: 75%;
				}

				.row > .off-9-small {
					margin-left: 75%;
				}

				.row > .col-10-small {
					width: 83.33333%;
				}

				.row > .off-10-small {
					margin-left: 83.33333%;
				}

				.row > .col-11-small {
					width: 91.66667%;
				}

				.row > .off-11-small {
					margin-left: 91.66667%;
				}

				.row > .col-12-small {
					width: 100%;
				}

				.row > .off-12-small {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.3125em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.3125em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.3125em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.3125em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.625em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.625em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.625em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.625em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.25em;
				}

					.row > * {
						padding: 0 0 0 1.25em;
					}

					.row.gtr-uniform {
						margin-top: -1.25em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.25em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -1.875em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 1.875em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -1.875em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 1.875em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -2.5em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 2.5em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -2.5em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 2.5em;
						}

		}

		@media screen and (max-width: 480px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xsmall {
					order: -1;
				}

				.row > .col-1-xsmall {
					width: 8.33333%;
				}

				.row > .off-1-xsmall {
					margin-left: 8.33333%;
				}

				.row > .col-2-xsmall {
					width: 16.66667%;
				}

				.row > .off-2-xsmall {
					margin-left: 16.66667%;
				}

				.row > .col-3-xsmall {
					width: 25%;
				}

				.row > .off-3-xsmall {
					margin-left: 25%;
				}

				.row > .col-4-xsmall {
					width: 33.33333%;
				}

				.row > .off-4-xsmall {
					margin-left: 33.33333%;
				}

				.row > .col-5-xsmall {
					width: 41.66667%;
				}

				.row > .off-5-xsmall {
					margin-left: 41.66667%;
				}

				.row > .col-6-xsmall {
					width: 50%;
				}

				.row > .off-6-xsmall {
					margin-left: 50%;
				}

				.row > .col-7-xsmall {
					width: 58.33333%;
				}

				.row > .off-7-xsmall {
					margin-left: 58.33333%;
				}

				.row > .col-8-xsmall {
					width: 66.66667%;
				}

				.row > .off-8-xsmall {
					margin-left: 66.66667%;
				}

				.row > .col-9-xsmall {
					width: 75%;
				}

				.row > .off-9-xsmall {
					margin-left: 75%;
				}

				.row > .col-10-xsmall {
					width: 83.33333%;
				}

				.row > .off-10-xsmall {
					margin-left: 83.33333%;
				}

				.row > .col-11-xsmall {
					width: 91.66667%;
				}

				.row > .off-11-xsmall {
					margin-left: 91.66667%;
				}

				.row > .col-12-xsmall {
					width: 100%;
				}

				.row > .off-12-xsmall {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.3125em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.3125em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.3125em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.3125em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.625em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.625em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.625em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.625em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.25em;
				}

					.row > * {
						padding: 0 0 0 1.25em;
					}

					.row.gtr-uniform {
						margin-top: -1.25em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.25em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -1.875em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 1.875em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -1.875em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 1.875em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -2.5em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 2.5em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -2.5em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 2.5em;
						}

		}

		@media screen and (max-width: 360px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xxsmall {
					order: -1;
				}

				.row > .col-1-xxsmall {
					width: 8.33333%;
				}

				.row > .off-1-xxsmall {
					margin-left: 8.33333%;
				}

				.row > .col-2-xxsmall {
					width: 16.66667%;
				}

				.row > .off-2-xxsmall {
					margin-left: 16.66667%;
				}

				.row > .col-3-xxsmall {
					width: 25%;
				}

				.row > .off-3-xxsmall {
					margin-left: 25%;
				}

				.row > .col-4-xxsmall {
					width: 33.33333%;
				}

				.row > .off-4-xxsmall {
					margin-left: 33.33333%;
				}

				.row > .col-5-xxsmall {
					width: 41.66667%;
				}

				.row > .off-5-xxsmall {
					margin-left: 41.66667%;
				}

				.row > .col-6-xxsmall {
					width: 50%;
				}

				.row > .off-6-xxsmall {
					margin-left: 50%;
				}

				.row > .col-7-xxsmall {
					width: 58.33333%;
				}

				.row > .off-7-xxsmall {
					margin-left: 58.33333%;
				}

				.row > .col-8-xxsmall {
					width: 66.66667%;
				}

				.row > .off-8-xxsmall {
					margin-left: 66.66667%;
				}

				.row > .col-9-xxsmall {
					width: 75%;
				}

				.row > .off-9-xxsmall {
					margin-left: 75%;
				}

				.row > .col-10-xxsmall {
					width: 83.33333%;
				}

				.row > .off-10-xxsmall {
					margin-left: 83.33333%;
				}

				.row > .col-11-xxsmall {
					width: 91.66667%;
				}

				.row > .off-11-xxsmall {
					margin-left: 91.66667%;
				}

				.row > .col-12-xxsmall {
					width: 100%;
				}

				.row > .off-12-xxsmall {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.3125em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.3125em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.3125em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.3125em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.625em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.625em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.625em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.625em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.25em;
				}

					.row > * {
						padding: 0 0 0 1.25em;
					}

					.row.gtr-uniform {
						margin-top: -1.25em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.25em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -1.875em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 1.875em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -1.875em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 1.875em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -2.5em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 2.5em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -2.5em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 2.5em;
						}

		}

/* Section/Article */

	section.special, article.special {
		text-align: center;
	}

/* Form */

	form {
		margin: 0 0 2em 0;
	}

		form > :last-child {
			margin-bottom: 0;
		}

		form > .fields {
			display: -moz-flex;
			display: -webkit-flex;
			display: -ms-flex;
			display: flex;
			-moz-flex-wrap: wrap;
			-webkit-flex-wrap: wrap;
			-ms-flex-wrap: wrap;
			flex-wrap: wrap;
			width: calc(100% + 3em);
			margin: -1.5em 0 2em -1.5em;
		}

			form > .fields > .field {
				-moz-flex-grow: 0;
				-webkit-flex-grow: 0;
				-ms-flex-grow: 0;
				flex-grow: 0;
				-moz-flex-shrink: 0;
				-webkit-flex-shrink: 0;
				-ms-flex-shrink: 0;
				flex-shrink: 0;
				padding: 1.5em 0 0 1.5em;
				width: calc(100% - 1.5em);
			}

				form > .fields > .field.half {
					width: calc(50% - 0.75em);
				}

				form > .fields > .field.third {
					width: calc(100%/3 - 0.5em);
				}

				form > .fields > .field.quarter {
					width: calc(25% - 0.375em);
				}

		@media screen and (max-width: 480px) {

			form > .fields {
				width: calc(100% + 3em);
				margin: -1.5em 0 2em -1.5em;
			}

				form > .fields > .field {
					padding: 1.5em 0 0 1.5em;
					width: calc(100% - 1.5em);
				}

					form > .fields > .field.half {
						width: calc(100% - 1.5em);
					}

					form > .fields > .field.third {
						width: calc(100% - 1.5em);
					}

					form > .fields > .field.quarter {
						width: calc(100% - 1.5em);
					}

		}

	label {
		color: #ffffff;
		display: block;
		font-family: Raleway, Helvetica, sans-serif;
		font-size: 0.8em;
		font-weight: 700;
		letter-spacing: 0.1em;
		margin: 0 0 0.7em 0;
		text-transform: uppercase;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	select,
	textarea {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		background: rgba(255, 255, 255, 0.025);
		border-radius: 5px;
		border: none;
		border: solid 2px rgba(255, 255, 255, 0.125);
		color: inherit;
		display: block;
		outline: 0;
		padding: 0 1em;
		text-decoration: none;
		width: 100%;
	}

		input[type="text"]:invalid,
		input[type="password"]:invalid,
		input[type="email"]:invalid,
		input[type="tel"]:invalid,
		select:invalid,
		textarea:invalid {
			box-shadow: none;
		}

		input[type="text"]:focus,
		input[type="password"]:focus,
		input[type="email"]:focus,
		input[type="tel"]:focus,
		select:focus,
		textarea:focus {
			border-color: #5b6ba6;
		}

	select {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='40' height='40' preserveAspectRatio='none' viewBox='0 0 40 40'%3E%3Cpath d='M9.4,12.3l10.4,10.4l10.4-10.4c0.2-0.2,0.5-0.4,0.9-0.4c0.3,0,0.6,0.1,0.9,0.4l3.3,3.3c0.2,0.2,0.4,0.5,0.4,0.9 c0,0.4-0.1,0.6-0.4,0.9L20.7,31.9c-0.2,0.2-0.5,0.4-0.9,0.4c-0.3,0-0.6-0.1-0.9-0.4L4.3,17.3c-0.2-0.2-0.4-0.5-0.4-0.9 c0-0.4,0.1-0.6,0.4-0.9l3.3-3.3c0.2-0.2,0.5-0.4,0.9-0.4S9.1,12.1,9.4,12.3z' fill='rgba(255, 255, 255, 0.125)' /%3E%3C/svg%3E");
		background-size: 1.25rem;
		background-repeat: no-repeat;
		background-position: calc(100% - 1rem) center;
		height: 2.75em;
		padding-right: 2.75em;
		text-overflow: ellipsis;
	}

		select option {
			color: #ffffff;
			background: #2e3141;
		}

		select:focus::-ms-value {
			background-color: transparent;
		}

		select::-ms-expand {
			display: none;
		}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	select {
		height: 2.75em;
	}

	textarea {
		padding: 0.75em 1em;
	}

	input[type="checkbox"],
	input[type="radio"] {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		display: block;
		float: left;
		margin-right: -2em;
		opacity: 0;
		width: 1em;
		z-index: -1;
	}

		input[type="checkbox"] + label,
		input[type="radio"] + label {
			text-decoration: none;
			color: #ffffff;
			cursor: pointer;
			display: inline-block;
			font-size: 1em;
			font-family: "Source Sans Pro", Helvetica, sans-serif;
			text-transform: none;
			letter-spacing: 0;
			font-weight: 300;
			padding-left: 2.4em;
			padding-right: 0.75em;
			position: relative;
		}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				display: inline-block;
				font-style: normal;
				font-variant: normal;
				text-rendering: auto;
				line-height: 1;
				text-transform: none !important;
				font-family: 'Font Awesome 5 Free';
				font-weight: 900;
			}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				background: rgba(255, 255, 255, 0.025);
				border-radius: 5px;
				border: solid 2px rgba(255, 255, 255, 0.125);
				content: '';
				display: inline-block;
				font-size: 0.8em;
				height: 2.0625em;
				left: 0;
				line-height: 2.0625em;
				position: absolute;
				text-align: center;
				top: 0;
				width: 2.0625em;
			}

		input[type="checkbox"]:checked + label:before,
		input[type="radio"]:checked + label:before {
			background: #ffffff;
			border-color: #ffffff;
			content: '\f00c';
			color: #2e3141;
		}

		input[type="checkbox"]:focus + label:before,
		input[type="radio"]:focus + label:before {
			border-color: #4c5c96;
		}

	input[type="checkbox"] + label:before {
		border-radius: 5px;
	}

	input[type="radio"] + label:before {
		border-radius: 100%;
	}

	::-webkit-input-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	:-moz-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	::-moz-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	:-ms-input-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

/* Box */

	.box {
		border-radius: 5px;
		border: solid 2px rgba(255, 255, 255, 0.125);
		margin-bottom: 2em;
		padding: 1.5em;
	}

		.box > :last-child,
		.box > :last-child > :last-child,
		.box > :last-child > :last-child > :last-child {
			margin-bottom: 0;
		}

		.box.alt {
			border: 0;
			border-radius: 0;
			padding: 0;
		}

/* Icon */

	.icon {
		text-decoration: none;
		border-bottom: none;
		position: relative;
	}

		.icon:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			display: inline-block;
			font-style: normal;
			font-variant: normal;
			text-rendering: auto;
			line-height: 1;
			text-transform: none !important;
			font-family: 'Font Awesome 5 Free';
			font-weight: 400;
		}

		.icon > .label {
			display: none;
		}

		.icon:before {
			line-height: inherit;
		}

		.icon.solid:before {
			font-weight: 900;
		}

		.icon.brands:before {
			font-family: 'Font Awesome 5 Brands';
		}

/* Image */

	.image {
		border-radius: 5px;
		border: 0;
		display: inline-block;
		position: relative;
	}

		.image img {
			border-radius: 5px;
			display: block;
		}

		.image.left, .image.right {
			max-width: 40%;
		}

			.image.left img, .image.right img {
				width: 100%;
			}

		.image.left {
			float: left;
			padding: 0 1.5em 1em 0;
			top: 0.25em;
		}

		.image.right {
			float: right;
			padding: 0 0 1em 1.5em;
			top: 0.25em;
		}

		.image.fit {
			display: block;
			margin: 0 0 2em 0;
			width: 100%;
		}

			.image.fit img {
				width: 100%;
			}

		.image.main {
			display: block;
			margin: 0 0 3em 0;
			width: 100%;
		}

			.image.main img {
				width: 100%;
			}

/* List */

	ol {
		list-style: decimal;
		margin: 0 0 2em 0;
		padding-left: 1.25em;
	}

		ol li {
			padding-left: 0.25em;
		}

	ul {
		list-style: disc;
		margin: 0 0 2em 0;
		padding-left: 1em;
	}

		ul li {
			padding-left: 0.5em;
		}

		ul.alt {
			list-style: none;
			padding-left: 0;
		}

			ul.alt li {
				border-top: solid 1px rgba(255, 255, 255, 0.125);
				padding: 0.5em 0;
			}

				ul.alt li:first-child {
					border-top: 0;
					padding-top: 0;
				}

	dl {
		margin: 0 0 2em 0;
	}

		dl dt {
			display: block;
			font-weight: 600;
			margin: 0 0 1em 0;
		}

		dl dd {
			margin-left: 2em;
		}

/* Actions */

	ul.actions {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		cursor: default;
		list-style: none;
		margin-left: -1em;
		padding-left: 0;
	}

		ul.actions li {
			padding: 0 0 0 1em;
			vertical-align: middle;
		}

		ul.actions.special {
			-moz-justify-content: center;
			-webkit-justify-content: center;
			-ms-justify-content: center;
			justify-content: center;
			width: 100%;
			margin-left: 0;
		}

			ul.actions.special li:first-child {
				padding-left: 0;
			}

		ul.actions.stacked {
			-moz-flex-direction: column;
			-webkit-flex-direction: column;
			-ms-flex-direction: column;
			flex-direction: column;
			margin-left: 0;
		}

			ul.actions.stacked li {
				padding: 1.3em 0 0 0;
			}

				ul.actions.stacked li:first-child {
					padding-top: 0;
				}

		ul.actions.fit {
			width: calc(100% + 1em);
		}

			ul.actions.fit li {
				-moz-flex-grow: 1;
				-webkit-flex-grow: 1;
				-ms-flex-grow: 1;
				flex-grow: 1;
				-moz-flex-shrink: 1;
				-webkit-flex-shrink: 1;
				-ms-flex-shrink: 1;
				flex-shrink: 1;
				width: 100%;
			}

				ul.actions.fit li > * {
					width: 100%;
				}

			ul.actions.fit.stacked {
				width: 100%;
			}

		@media screen and (max-width: 480px) {

			ul.actions:not(.fixed) {
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				margin-left: 0;
				width: 100% !important;
			}

				ul.actions:not(.fixed) li {
					-moz-flex-grow: 1;
					-webkit-flex-grow: 1;
					-ms-flex-grow: 1;
					flex-grow: 1;
					-moz-flex-shrink: 1;
					-webkit-flex-shrink: 1;
					-ms-flex-shrink: 1;
					flex-shrink: 1;
					padding: 1em 0 0 0;
					text-align: center;
					width: 100%;
				}

					ul.actions:not(.fixed) li > * {
						width: 100%;
					}

					ul.actions:not(.fixed) li:first-child {
						padding-top: 0;
					}

					ul.actions:not(.fixed) li input[type="submit"],
					ul.actions:not(.fixed) li input[type="reset"],
					ul.actions:not(.fixed) li input[type="button"],
					ul.actions:not(.fixed) li button,
					ul.actions:not(.fixed) li .button {
						width: 100%;
					}

						ul.actions:not(.fixed) li input[type="submit"].icon:before,
						ul.actions:not(.fixed) li input[type="reset"].icon:before,
						ul.actions:not(.fixed) li input[type="button"].icon:before,
						ul.actions:not(.fixed) li button.icon:before,
						ul.actions:not(.fixed) li .button.icon:before {
							margin-left: -0.5rem;
						}

		}

/* Icons */

	ul.icons {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.icons li {
			display: inline-block;
			padding: 0 1em 0 0;
		}

			ul.icons li:last-child {
				padding-right: 0;
			}

			ul.icons li .icon:before {
				font-size: 1.25em;
			}

/* Contact */

	ul.contact {
		list-style: none;
		padding: 0;
	}

		ul.contact li {
			text-decoration: none;
			margin: 2.5em 0 0 0;
			padding: 0 0 0 3.25em;
			position: relative;
		}

			ul.contact li:before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				display: inline-block;
				font-style: normal;
				font-variant: normal;
				text-rendering: auto;
				line-height: 1;
				text-transform: none !important;
				font-family: 'Font Awesome 5 Free';
				font-weight: 400;
			}

			ul.contact li:before {
				border-radius: 100%;
				border: solid 2px rgba(255, 255, 255, 0.125);
				display: inline-block;
				font-size: 0.8em;
				height: 2.5em;
				left: 0;
				line-height: 2.35em;
				position: absolute;
				text-align: center;
				top: 0;
				width: 2.5em;
			}

			ul.contact li:first-child {
				margin-top: 0;
			}

		@media screen and (max-width: 736px) {

			ul.contact li {
				margin: 1.5em 0 0 0;
			}

		}

/* Pagination */

	ul.pagination {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.pagination li {
			display: inline-block;
			padding-left: 0;
			vertical-align: middle;
		}

			ul.pagination li > .page {
				-moz-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
				-webkit-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
				-ms-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
				transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
				border-bottom: 0;
				border-radius: 5px;
				display: inline-block;
				height: 1.5em;
				line-height: 1.5em;
				margin: 0 0.125em;
				min-width: 1.5em;
				padding: 0 0.5em;
				text-align: center;
			}

				ul.pagination li > .page:hover {
					background-color: rgba(255, 255, 255, 0.025);
				}

				ul.pagination li > .page.active {
					background-color: #4c5c96;
				}

			ul.pagination li:first-child {
				padding-right: 0.75em;
			}

			ul.pagination li:last-child {
				padding-left: 0.75em;
			}

		@media screen and (max-width: 480px) {

			ul.pagination li:nth-child(n+2):nth-last-child(n+2) {
				display: none;
			}

			ul.pagination li .button {
				width: 100%;
			}

			ul.pagination li:first-child {
				width: calc(50% - 2px);
				text-align: left;
				padding-right: 0.325em;
			}

			ul.pagination li:last-child {
				width: calc(50% - 2px);
				text-align: right;
				padding-left: 0.325em;
			}

		}

/* Table */

	.table-wrapper {
		-webkit-overflow-scrolling: touch;
		overflow-x: auto;
	}

	table {
		margin: 0 0 2em 0;
		width: 100%;
	}

		table tbody tr {
			border: solid 1px rgba(255, 255, 255, 0.125);
			border-left: 0;
			border-right: 0;
		}

			table tbody tr:nth-child(2n + 1) {
				background-color: rgba(255, 255, 255, 0.025);
			}

		table td {
			padding: 0.75em 0.75em;
		}

		table th {
			color: #ffffff;
			font-size: 0.9em;
			font-weight: 600;
			padding: 0 0.75em 0.75em 0.75em;
			text-align: left;
		}

		table thead {
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
		}

		table tfoot {
			border-top: solid 2px rgba(255, 255, 255, 0.125);
		}

		table.alt {
			border-collapse: separate;
		}

			table.alt tbody tr td {
				border: solid 1px rgba(255, 255, 255, 0.125);
				border-left-width: 0;
				border-top-width: 0;
			}

				table.alt tbody tr td:first-child {
					border-left-width: 1px;
				}

			table.alt tbody tr:first-child td {
				border-top-width: 1px;
			}

			table.alt thead {
				border-bottom: 0;
			}

			table.alt tfoot {
				border-top: 0;
			}


/* Button */

	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	.button {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: background-color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out;
		background-color: transparent;
		border-radius: 5px;
		border: 0;
		box-shadow: inset 0 0 0 2px rgba(255, 255, 255, 0.125);
		color: #ffffff !important;
		cursor: pointer;
		display: inline-block;
		font-family: Raleway, Helvetica, sans-serif;
		font-size: 0.8em;
		font-weight: 700;
		height: 3.75em;
		letter-spacing: 0.1em;
		line-height: 3.75em;
		padding: 0 2.25em;
		text-align: center;
		text-decoration: none;
		text-transform: uppercase;
		white-space: nowrap;
	}

		input[type="submit"]:hover,
		input[type="reset"]:hover,
		input[type="button"]:hover,
		button:hover,
		.button:hover {
			background-color: rgba(255, 255, 255, 0.025);
		}

		input[type="submit"]:active,
		input[type="reset"]:active,
		input[type="button"]:active,
		button:active,
		.button:active {
			background-color: rgba(255, 255, 255, 0.075);
		}

		input[type="submit"].icon:before,
		input[type="reset"].icon:before,
		input[type="button"].icon:before,
		button.icon:before,
		.button.icon:before {
			margin-right: 0.5em;
			color: rgba(255, 255, 255, 0.35);
		}

		input[type="submit"].primary,
		input[type="reset"].primary,
		input[type="button"].primary,
		button.primary,
		.button.primary {
			background-color: #4c5c96;
			box-shadow: none;
		}

			input[type="submit"].primary:hover,
			input[type="reset"].primary:hover,
			input[type="button"].primary:hover,
			button.primary:hover,
			.button.primary:hover {
				background-color: #53639e;
			}

			input[type="submit"].primary:active,
			input[type="reset"].primary:active,
			input[type="button"].primary:active,
			button.primary:active,
			.button.primary:active {
				background-color: #45558d;
			}

			input[type="submit"].primary.icon:before,
			input[type="reset"].primary.icon:before,
			input[type="button"].primary.icon:before,
			button.primary.icon:before,
			.button.primary.icon:before {
				color: #7985b0;
			}

		input[type="submit"].fit,
		input[type="reset"].fit,
		input[type="button"].fit,
		button.fit,
		.button.fit {
			width: 100%;
		}

		input[type="submit"].small,
		input[type="reset"].small,
		input[type="button"].small,
		button.small,
		.button.small {
			font-size: 0.6em;
		}

		input[type="submit"].large,
		input[type="reset"].large,
		input[type="button"].large,
		button.large,
		.button.large {
			font-size: 1em;
		}

		input[type="submit"].disabled, input[type="submit"]:disabled,
		input[type="reset"].disabled,
		input[type="reset"]:disabled,
		input[type="button"].disabled,
		input[type="button"]:disabled,
		button.disabled,
		button:disabled,
		.button.disabled,
		.button:disabled {
			opacity: 0.25;
		}

		@media screen and (max-width: 480px) {

			input[type="submit"],
			input[type="reset"],
			input[type="button"],
			button,
			.button {
				padding: 0;
			}

		}

/* Features */

	.features {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		margin: 0 0 2em 0;
	}

		.features article {
			padding: 1.75em 1.75em 0.1em 1.75em ;
			background-color: #353849;
			border-radius: 5px;
			margin: 1.5em 3em 1.5em 0;
			width: calc(50% - 1.5em);
		}

			.features article:nth-child(2n) {
				margin-right: 0;
			}

			.features article .image {
				border-radius: 5px 5px 0 0;
				display: block;
				margin-bottom: 1.75em;
				margin-left: -1.75em;
				margin-top: -1.75em;
				position: relative;
				width: calc(100% + 3.5em);
			}

				.features article .image img {
					border-radius: 5px 5px 0 0;
					width: 100%;
				}

		@media screen and (max-width: 980px) {

			.features article {
				margin: 1em 2em 1em 0;
				width: calc(50% - 1em);
			}

		}

		@media screen and (max-width: 736px) {

			.features article {
				padding: 1.5em 1.5em 0.1em 1.5em ;
				margin: 0.875em 1.75em 0.875em 0;
				width: calc(50% - 0.875em - 1px);
			}

				.features article .image {
					margin-bottom: 1.5em;
					margin-left: -1.5em;
					margin-top: -1.5em;
					width: calc(100% + 3em);
				}

		}

		@media screen and (max-width: 480px) {

			.features {
				display: block;
			}

				.features article {
					width: 100%;
					margin: 0 0 2em 0 !important;
				}

		}

/* Header */

	#header {
		-moz-transition: background-color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out;
		background-color: rgba(53, 56, 73, 0.95);
		height: 3.5em;
		left: 0;
		line-height: 3.5em;
		padding: 0 1.25em;
		position: fixed;
		top: 0;
		width: 100%;
		z-index: 10000;
	}

		#header h1 {
			-moz-transition: opacity 0.2s ease-in-out, visibility 0.2s;
			-webkit-transition: opacity 0.2s ease-in-out, visibility 0.2s;
			-ms-transition: opacity 0.2s ease-in-out, visibility 0.2s;
			transition: opacity 0.2s ease-in-out, visibility 0.2s;
			border-bottom: 0;
			font-size: 0.8em;
			margin-bottom: 0;
			opacity: 1;
			visibility: visible;
		}

			#header h1 a {
				border: 0;
			}

		#header nav {
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 0.8em;
			font-weight: 700;
			height: 3em;
			letter-spacing: 0.1em;
			line-height: 3em;
			position: absolute;
			right: 0.7em;
			text-transform: uppercase;
			top: 0.7em;
		}

			#header nav a {
				border: 0;
				display: inline-block;
				padding: 0 1em;
			}

				#header nav a:before {
					float: right;
					margin-left: 0.75em;
				}

				#header nav a[href="#menu"] {
					text-decoration: none;
					-moz-transition: background-color 0.2s ease-in-out;
					-webkit-transition: background-color 0.2s ease-in-out;
					-ms-transition: background-color 0.2s ease-in-out;
					transition: background-color 0.2s ease-in-out;
					border-radius: 5px;
					box-shadow: inset 0 0 0 2px rgba(255, 255, 255, 0.125);
					padding: 0 1.35em;
				}

					#header nav a[href="#menu"]:before {
						-moz-osx-font-smoothing: grayscale;
						-webkit-font-smoothing: antialiased;
						display: inline-block;
						font-style: normal;
						font-variant: normal;
						text-rendering: auto;
						line-height: 1;
						text-transform: none !important;
						font-family: 'Font Awesome 5 Free';
						font-weight: 900;
					}

					#header nav a[href="#menu"]:before {
						content: '\f0c9';
						line-height: inherit;
					}

					#header nav a[href="#menu"]:hover {
						background-color: rgba(255, 255, 255, 0.025);
					}

					#header nav a[href="#menu"]:active {
						background-color: rgba(255, 255, 255, 0.075);
					}

		#header.alt {
			background-color: transparent;
		}

			#header.alt h1 {
				opacity: 0;
				visibility: hidden;
			}

		@media screen and (max-width: 736px) {

			#header {
				height: 2.75em;
				line-height: 2.75em;
			}

				#header nav {
					top: 0;
					right: 0;
					height: inherit;
					line-height: inherit;
				}

					#header nav a {
						height: inherit;
						line-height: inherit;
					}

						#header nav a[href="#menu"] {
							box-shadow: none;
							padding: 0 1em;
							border-radius: 0;
						}

							#header nav a[href="#menu"]:hover, #header nav a[href="#menu"]:active {
								background-color: inherit;
							}

		}

		@media screen and (max-width: 480px) {

			#header nav a[href="#menu"] {
				width: 4em;
				white-space: nowrap;
				text-indent: 4em;
				position: relative;
			}

				#header nav a[href="#menu"]:before {
					width: inherit;
					position: absolute;
					top: 0;
					left: 0;
					text-indent: 0;
					text-align: right;
					margin-left: 0;
					padding-right: 1.25em;
				}

		}

/* Menu */

	#page-wrapper {
		-moz-transition: -moz-filter 0.25s ease;
		-webkit-transition: -webkit-filter 0.25s ease;
		-ms-transition: -ms-filter 0.25s ease;
		transition: filter 0.25s ease;
	}

	#menu {
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		pointer-events: none;
		-moz-transition: opacity 0.35s ease, visibility 0.35s;
		-webkit-transition: opacity 0.35s ease, visibility 0.35s;
		-ms-transition: opacity 0.35s ease, visibility 0.35s;
		transition: opacity 0.35s ease, visibility 0.35s;
		-moz-user-select: none;
		-webkit-user-select: none;
		-ms-user-select: none;
		user-select: none;
		-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
		background: rgba(46, 49, 65, 0.8);
		cursor: default;
		height: 100%;
		left: 0;
		opacity: 0;
		position: fixed;
		text-align: center;
		top: 0;
		visibility: hidden;
		width: 100%;
	}

		#menu .inner {
			padding: 2.5em 1.5em 0.5em 1.5em ;
			-moz-transform: translateY(0.5em);
			-webkit-transform: translateY(0.5em);
			-ms-transform: translateY(0.5em);
			transform: translateY(0.5em);
			-moz-transition: opacity 0.35s ease, -moz-transform 0.35s ease;
			-webkit-transition: opacity 0.35s ease, -webkit-transform 0.35s ease;
			-ms-transition: opacity 0.35s ease, -ms-transform 0.35s ease;
			transition: opacity 0.35s ease, transform 0.35s ease;
			-webkit-overflow-scrolling: touch;
			background: #4c5c96;
			border-radius: 5px;
			display: block;
			max-width: 100%;
			opacity: 0;
			position: relative;
			width: 18em;
		}

		#menu h2 {
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
			padding-bottom: 1em;
		}

		#menu .close {
			background-image: url("images/close.svg");
			background-position: 75% 25%;
			background-repeat: no-repeat;
			background-size: 2em 2em;
			border: 0;
			content: '';
			display: block;
			height: 4em;
			overflow: hidden;
			position: absolute;
			right: 0;
			text-align: center;
			text-indent: 4em;
			top: 0;
			width: 4em;
		}

		#menu .links {
			list-style: none;
			margin-bottom: 1.5em;
			padding: 0;
		}

			#menu .links li {
				padding: 0;
			}

				#menu .links li a {
					border-radius: 5px;
					border: 0;
					display: block;
					font-family: Raleway, Helvetica, sans-serif;
					font-size: 0.8em;
					font-weight: 200;
					letter-spacing: 0.1em;
					line-height: 1.85em;
					padding: 0.75em 0;
					text-transform: uppercase;
				}

					#menu .links li a:hover {
						background: #45558d;
					}

		@media screen and (max-width: 736px) {

			#menu .inner {
				max-height: 100%;
				overflow-y: auto;
				overflow-x: hidden;
			}

				#menu .inner .close {
					background-size: 1.5em 1.5em;
				}

		}

	body.is-menu-visible #page-wrapper {
		-moz-filter: blur(1.5px);
		-webkit-filter: blur(1.5px);
		-ms-filter: blur(1.5px);
		filter: blur(1.5px);
	}

	body.is-menu-visible #menu {
		pointer-events: auto;
		opacity: 1;
		visibility: visible;
	}

		body.is-menu-visible #menu .inner {
			-moz-transform: translateY(0);
			-webkit-transform: translateY(0);
			-ms-transform: translateY(0);
			transform: translateY(0);
			opacity: 1;
		}

/* Banner */

	#banner {
		padding: 10em 0 4.75em 0 ;
	}

		#banner .inner {
			margin: 0 auto;
			width: 55em;
		}

		#banner .logo {
			-moz-transition: opacity 2s ease, -moz-transform 1s ease;
			-webkit-transition: opacity 2s ease, -webkit-transform 1s ease;
			-ms-transition: opacity 2s ease, -ms-transform 1s ease;
			transition: opacity 2s ease, transform 1s ease;
			-moz-transform: translateY(0);
			-webkit-transform: translateY(0);
			-ms-transform: translateY(0);
			transform: translateY(0);
			opacity: 1;
			margin: 0 0 1.3em 0;
		}

			#banner .logo .icon {
				border-radius: 100%;
				border: solid 2px rgba(255, 255, 255, 0.125);
				cursor: default;
				display: inline-block;
				font-size: 2em;
				height: 2.25em;
				line-height: 2.25em;
				text-align: center;
				width: 2.25em;
			}

		#banner h2 {
			-moz-transition: opacity 0.5s ease, -moz-transform 0.5s ease, -moz-filter 0.25s ease;
			-webkit-transition: opacity 0.5s ease, -webkit-transform 0.5s ease, -webkit-filter 0.25s ease;
			-ms-transition: opacity 0.5s ease, -ms-transform 0.5s ease, -ms-filter 0.25s ease;
			transition: opacity 0.5s ease, transform 0.5s ease, filter 0.25s ease;
			-moz-transform: translateX(0);
			-webkit-transform: translateX(0);
			-ms-transform: translateX(0);
			transform: translateX(0);
			-moz-transition-delay: 0.65s;
			-webkit-transition-delay: 0.65s;
			-ms-transition-delay: 0.65s;
			transition-delay: 0.65s;
			-moz-filter: blur(0);
			-webkit-filter: blur(0);
			-ms-filter: blur(0);
			filter: blur(0);
			opacity: 1;
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
			font-size: 2.25em;
			margin-bottom: 0.8em;
			padding-bottom: 0.4em;
		}

		#banner p {
			-moz-transition: opacity 0.5s ease, -moz-transform 0.5s ease, -moz-filter 0.25s ease;
			-webkit-transition: opacity 0.5s ease, -webkit-transform 0.5s ease, -webkit-filter 0.25s ease;
			-ms-transition: opacity 0.5s ease, -ms-transform 0.5s ease, -ms-filter 0.25s ease;
			transition: opacity 0.5s ease, transform 0.5s ease, filter 0.25s ease;
			-moz-transform: translateX(0);
			-webkit-transform: translateX(0);
			-ms-transform: translateX(0);
			transform: translateX(0);
			-moz-transition-delay: 0.8s;
			-webkit-transition-delay: 0.8s;
			-ms-transition-delay: 0.8s;
			transition-delay: 0.8s;
			-moz-filter: blur(0);
			-webkit-filter: blur(0);
			-ms-filter: blur(0);
			filter: blur(0);
			opacity: 1;
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 1em;
			font-weight: 200;
			letter-spacing: 0.1em;
			line-height: 2;
			text-transform: uppercase;
		}

		@media screen and (max-width: 1280px) {

			#banner {
				padding: 7em 0 8.25em 0 ;
				background-color: #2e3141;
				background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
				background-size: auto,
 cover;
				background-position: center,
 center;
				margin-bottom: -6.5em;
			}

		}

		@media screen and (max-width: 980px) {

			#banner {
				padding: 12em 3em 12.375em 3em ;
				margin-bottom: -4.75em;
			}

				#banner .inner {
					width: 100%;
				}

		}

		@media screen and (max-width: 736px) {

			#banner {
				padding: 5em 2em 4.25em 2em ;
				margin-bottom: -2.5em;
			}

				#banner .logo {
					margin: 0 0 1em 0;
				}

					#banner .logo .icon {
						font-size: 1.5em;
					}

				#banner h2 {
					font-size: 1.5em;
				}

				#banner p {
					font-size: 0.8em;
				}

		}

		body.is-preload #banner .logo {
			-moz-transform: translateY(0.5em);
			-webkit-transform: translateY(0.5em);
			-ms-transform: translateY(0.5em);
			transform: translateY(0.5em);
			opacity: 0;
		}

		body.is-preload #banner h2 {
			opacity: 0;
			-moz-transform: translateX(0.25em);
			-webkit-transform: translateX(0.25em);
			-ms-transform: translateX(0.25em);
			transform: translateX(0.25em);
			-moz-filter: blur(2px);
			-webkit-filter: blur(2px);
			-ms-filter: blur(2px);
			filter: blur(2px);
		}

		body.is-preload #banner p {
			opacity: 0;
			-moz-transform: translateX(0.5em);
			-webkit-transform: translateX(0.5em);
			-ms-transform: translateX(0.5em);
			transform: translateX(0.5em);
			-moz-filter: blur(2px);
			-webkit-filter: blur(2px);
			-ms-filter: blur(2px);
			filter: blur(2px);
		}

/* Wrapper */

	#wrapper > header {
		padding: 11em 0 2.25em 0 ;
	}

		#wrapper > header .inner {
			margin: 0 auto;
			width: 55em;
		}

		#wrapper > header h2 {
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
			font-size: 2em;
			margin-bottom: 0.8em;
			padding-bottom: 0.4em;
		}

		#wrapper > header p {
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 1em;
			font-weight: 200;
			letter-spacing: 0.1em;
			line-height: 2;
			text-transform: uppercase;
		}

	@media screen and (max-width: 1280px) {

		#wrapper > header {
			padding: 9em 0 6.25em 0 ;
			background-color: #2e3141;
			background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
			background-size: auto,
 cover;
			background-position: center,
 0% 30%;
			margin-bottom: -6.5em;
		}

	}

	@media screen and (max-width: 980px) {

		#wrapper > header {
			padding: 11em 3em 7.375em 3em ;
			background-size: auto,
 cover;
			background-position: center,
 0% 0%;
			margin-bottom: -4.75em;
		}

			#wrapper > header .inner {
				width: 100%;
			}

	}

	@media screen and (max-width: 736px) {

		#wrapper > header {
			padding: 6.5em 2em 3em 2em ;
			background-size: auto,
 125%;
			margin-bottom: -2.5em;
		}

			#wrapper > header h2 {
				font-size: 1.25em;
			}

			#wrapper > header p {
				font-size: 0.8em;
			}

	}

	.wrapper {
		background-color: #2e3141;
		margin: 6.5em 0;
		position: relative;
	}

		.wrapper:before, .wrapper:after {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%232e3141%3B' /%3E%3C/svg%3E");
		}

		.wrapper:before {
			box-shadow: inset 0 -1px 0 0 #2e3141, 0 1px 0 0 #2e3141;
		}

		.wrapper:after {
			box-shadow: inset 0 -1px 0 0 #2e3141, 0 1px 0 0 #2e3141;
		}

		.wrapper:before, .wrapper:after {
			background-repeat: no-repeat;
			background-size: 100% 100%;
			content: '';
			display: block;
			height: 6.5em;
			position: absolute;
			width: 100%;
		}

		.wrapper:before {
			left: 0;
			top: -6.5em;
		}

		.wrapper:after {
			-moz-transform: scaleY(-1);
			-webkit-transform: scaleY(-1);
			-ms-transform: scaleY(-1);
			transform: scaleY(-1);
			bottom: -6.5em;
			left: 0;
		}

		.wrapper.alt:before {
			-moz-transform: scaleX(-1);
			-webkit-transform: scaleX(-1);
			-ms-transform: scaleX(-1);
			transform: scaleX(-1);
		}

		.wrapper.alt:after {
			-moz-transform: scaleY(-1) scaleX(-1);
			-webkit-transform: scaleY(-1) scaleX(-1);
			-ms-transform: scaleY(-1) scaleX(-1);
			transform: scaleY(-1) scaleX(-1);
		}

		.wrapper .inner {
			padding: 3em 0 1em 0 ;
			margin: 0 auto;
			width: 55em;
		}

		.wrapper.style2 {
			background-color: #353849;
		}

			.wrapper.style2:before, .wrapper.style2:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23353849%3B' /%3E%3C/svg%3E");
			}

			.wrapper.style2:before {
				box-shadow: inset 0 -1px 0 0 #353849, 0 1px 0 0 #353849;
			}

			.wrapper.style2:after {
				box-shadow: inset 0 -1px 0 0 #353849, 0 1px 0 0 #353849;
			}

		.wrapper.style3 {
			background-color: #3d4051;
		}

			.wrapper.style3:before, .wrapper.style3:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%233d4051%3B' /%3E%3C/svg%3E");
			}

			.wrapper.style3:before {
				box-shadow: inset 0 -1px 0 0 #3d4051, 0 1px 0 0 #3d4051;
			}

			.wrapper.style3:after {
				box-shadow: inset 0 -1px 0 0 #3d4051, 0 1px 0 0 #3d4051;
			}

		.wrapper.style4 {
			background-color: #454858;
		}

			.wrapper.style4:before, .wrapper.style4:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23454858%3B' /%3E%3C/svg%3E");
			}

			.wrapper.style4:before {
				box-shadow: inset 0 -1px 0 0 #454858, 0 1px 0 0 #454858;
			}

			.wrapper.style4:after {
				box-shadow: inset 0 -1px 0 0 #454858, 0 1px 0 0 #454858;
			}

		.wrapper.style5 {
			background-color: #4d5060;
		}

			.wrapper.style5:before, .wrapper.style5:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%234d5060%3B' /%3E%3C/svg%3E");
			}

			.wrapper.style5:before {
				box-shadow: inset 0 -1px 0 0 #4d5060, 0 1px 0 0 #4d5060;
			}

			.wrapper.style5:after {
				box-shadow: inset 0 -1px 0 0 #4d5060, 0 1px 0 0 #4d5060;
			}

		.wrapper.style6 {
			background-color: #555867;
		}

			.wrapper.style6:before, .wrapper.style6:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23555867%3B' /%3E%3C/svg%3E");
			}

			.wrapper.style6:before {
				box-shadow: inset 0 -1px 0 0 #555867, 0 1px 0 0 #555867;
			}

			.wrapper.style6:after {
				box-shadow: inset 0 -1px 0 0 #555867, 0 1px 0 0 #555867;
			}

		.wrapper.spotlight {
			background-color: #4c5c96;
		}

			.wrapper.spotlight:before, .wrapper.spotlight:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%234c5c96%3B' /%3E%3C/svg%3E");
			}

			.wrapper.spotlight:before {
				box-shadow: inset 0 -1px 0 0 #4c5c96, 0 1px 0 0 #4c5c96;
			}

			.wrapper.spotlight:after {
				box-shadow: inset 0 -1px 0 0 #4c5c96, 0 1px 0 0 #4c5c96;
			}

			.wrapper.spotlight .inner {
				display: -moz-flex;
				display: -webkit-flex;
				display: -ms-flex;
				display: flex;
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				-moz-flex-direction: row;
				-webkit-flex-direction: row;
				-ms-flex-direction: row;
				flex-direction: row;
			}

			.wrapper.spotlight .image {
				border-radius: 100%;
				margin: 0 3em 2em 0;
				width: 22em;
				overflow: hidden;
				-ms-flex: 1;
			}

				.wrapper.spotlight .image img {
					border-radius: 100%;
					width: 100%;
				}

			.wrapper.spotlight .content {
				width: 100%;
				-ms-flex: 2;
			}

			.wrapper.spotlight:nth-child(2n - 1) .inner {
				-moz-flex-direction: row-reverse;
				-webkit-flex-direction: row-reverse;
				-ms-flex-direction: row-reverse;
				flex-direction: row-reverse;
				text-align: right;
			}

			.wrapper.spotlight:nth-child(2n - 1) .image {
				margin: 0 0 2em 3em;
			}

			.wrapper.spotlight.style2 {
				background-color: #45558d;
			}

				.wrapper.spotlight.style2:before, .wrapper.spotlight.style2:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%2345558d%3B' /%3E%3C/svg%3E");
				}

				.wrapper.spotlight.style2:before {
					box-shadow: inset 0 -1px 0 0 #45558d, 0 1px 0 0 #45558d;
				}

				.wrapper.spotlight.style2:after {
					box-shadow: inset 0 -1px 0 0 #45558d, 0 1px 0 0 #45558d;
				}

			.wrapper.spotlight.style3 {
				background-color: #3f4e85;
			}

				.wrapper.spotlight.style3:before, .wrapper.spotlight.style3:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%233f4e85%3B' /%3E%3C/svg%3E");
				}

				.wrapper.spotlight.style3:before {
					box-shadow: inset 0 -1px 0 0 #3f4e85, 0 1px 0 0 #3f4e85;
				}

				.wrapper.spotlight.style3:after {
					box-shadow: inset 0 -1px 0 0 #3f4e85, 0 1px 0 0 #3f4e85;
				}

			.wrapper.spotlight.style4 {
				background-color: #39477c;
			}

				.wrapper.spotlight.style4:before, .wrapper.spotlight.style4:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%2339477c%3B' /%3E%3C/svg%3E");
				}

				.wrapper.spotlight.style4:before {
					box-shadow: inset 0 -1px 0 0 #39477c, 0 1px 0 0 #39477c;
				}

				.wrapper.spotlight.style4:after {
					box-shadow: inset 0 -1px 0 0 #39477c, 0 1px 0 0 #39477c;
				}

			.wrapper.spotlight.style5 {
				background-color: #324072;
			}

				.wrapper.spotlight.style5:before, .wrapper.spotlight.style5:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23324072%3B' /%3E%3C/svg%3E");
				}

				.wrapper.spotlight.style5:before {
					box-shadow: inset 0 -1px 0 0 #324072, 0 1px 0 0 #324072;
				}

				.wrapper.spotlight.style5:after {
					box-shadow: inset 0 -1px 0 0 #324072, 0 1px 0 0 #324072;
				}

			.wrapper.spotlight.style6 {
				background-color: #2d3a69;
			}

				.wrapper.spotlight.style6:before, .wrapper.spotlight.style6:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%232d3a69%3B' /%3E%3C/svg%3E");
				}

				.wrapper.spotlight.style6:before {
					box-shadow: inset 0 -1px 0 0 #2d3a69, 0 1px 0 0 #2d3a69;
				}

				.wrapper.spotlight.style6:after {
					box-shadow: inset 0 -1px 0 0 #2d3a69, 0 1px 0 0 #2d3a69;
				}

		@media screen and (max-width: 980px) {

			.wrapper {
				margin: 4.75em 0;
			}

				.wrapper:before, .wrapper:after {
					height: 4.75em;
				}

				.wrapper:before {
					top: -4.75em;
				}

				.wrapper:after {
					bottom: -4.75em;
					left: 0;
				}

				.wrapper .inner {
					padding: 3em 3em 1em 3em ;
					width: 100%;
				}

				.wrapper.spotlight .image {
					margin: 0 2em 2em 0;
					width: 32em;
				}

				.wrapper.spotlight:nth-child(2n - 1) .image {
					margin: 0 0 2em 2em;
				}

		}

		@media screen and (max-width: 736px) {

			.wrapper {
				margin: 2.5em 0;
			}

				.wrapper:before, .wrapper:after {
					height: 2.5em;
				}

				.wrapper:before {
					top: -2.5em;
				}

				.wrapper:after {
					bottom: -2.5em;
					left: 0;
				}

				.wrapper .inner {
					padding: 2em 2em 0.1em 2em ;
				}

				.wrapper.spotlight .inner {
					-moz-align-items: -moz-flex-start;
					-webkit-align-items: -webkit-flex-start;
					-ms-align-items: -ms-flex-start;
					align-items: flex-start;
				}

				.wrapper.spotlight .image {
					width: 19em;
					margin: 0 1.75em 2em 0;
				}

				.wrapper.spotlight:nth-child(2n - 1) .image {
					margin: 0 0 2em 1.75em;
				}

		}

		@media screen and (max-width: 480px) {

			.wrapper.spotlight .inner {
				display: block;
			}

			.wrapper.spotlight .image {
				margin: 0 0 1em 0 !important;
				max-width: 85%;
				width: 12em;
			}

		}

		@media screen and (max-width: 360px) {

			.wrapper .inner {
				padding: 2em 1.5em 0.1em 1.5em ;
			}

		}

/* Footer */

	#footer .inner {
		padding: 5em 0 3em 0 ;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row;
		-webkit-flex-direction: row;
		-ms-flex-direction: row;
		flex-direction: row;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		margin: 0 auto;
		width: 55em;
	}

		#footer .inner > * {
			width: 100%;
		}

		#footer .inner form {
			margin: 0 3em 0 0;
			width: calc(50% - 1.5em);
		}

		#footer .inner .contact {
			width: calc(50% - 1.5em);
		}

		#footer .inner .copyright {
			border-top: solid 2px rgba(255, 255, 255, 0.125);
			list-style: none;
			margin: 4em 0 2em 0;
			padding: 2em 0 0 0;
			width: 100%;
		}

			#footer .inner .copyright li {
				border-left: solid 2px rgba(255, 255, 255, 0.125);
				color: rgba(255, 255, 255, 0.35);
				display: inline-block;
				font-size: 0.9em;
				line-height: 1;
				margin-left: 1em;
				padding: 0;
				padding-left: 1em;
			}

				#footer .inner .copyright li:first-child {
					border-left: 0;
					margin-left: 0;
					padding-left: 0;
				}

				#footer .inner .copyright li a {
					color: inherit;
				}

	@media screen and (max-width: 1280px) {

		#footer {
			background-color: #2e3141;
			background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
			background-size: auto,
 cover;
			background-position: center,
 center;
			margin-top: -6.5em;
			padding-top: 6.5em;
		}

	}

	@media screen and (max-width: 980px) {

		#footer {
			margin-top: -4.75em;
			padding-top: 4.75em;
		}

			#footer .inner {
				padding: 3em 3em 1em 3em ;
				display: block;
				width: 100%;
			}

				#footer .inner form {
					width: 100%;
					margin: 0 0 4em 0;
				}

				#footer .inner .contact {
					width: 100%;
					margin: 0 0 4em 0;
				}

				#footer .inner .copyright {
					margin: 4em 0 2em 0;
				}

	}

	@media screen and (max-width: 736px) {

		#footer {
			margin-top: -2.5em;
			padding-top: 2.5em;
		}

			#footer .inner {
				padding: 2em 2em 0.1em 2em ;
			}

				#footer .inner form {
					margin: 0 0 3em 0;
				}

				#footer .inner .contact {
					margin: 0 0 3em 0;
				}

	}

	@media screen and (max-width: 480px) {

		#footer .inner .copyright li {
			border-left: 0;
			display: block;
			margin: 1em 0 0 0;
			padding-left: 0;
		}

			#footer .inner .copyright li:first-child {
				margin-top: 0;
			}

	}

	@media screen and (max-width: 360px) {

		#footer .inner {
			padding: 2em 1.5em 0.1em 1.5em ;
		}

	}
