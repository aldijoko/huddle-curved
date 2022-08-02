<script>
</script>

<header>
	<nav class="navbar">
		<div class="icon">
			<img src="images/logo.svg" alt="" />
		</div>
		<div class="btnHeader">
			<button>Try It Free</button>
		</div>
	</nav>
</header>

<section class="topContainer">
	<h1 class="topHeader">Build The Community Your Fans Will Love</h1>
	<p class="topTxt">
		Huddle re-imagines the way we build communities. You have a voice, but so does your audience.
		Create connections with your users as you engage in genuine discussion.
	</p>
	<button class="btnGet">Get Started For Free</button>
	<div class="topImg">
		<img src="images/screen-mockups.svg" alt="" />
	</div>
	<div class="topContent">
		<div class="community">
			<img class="comIcon" src="images/icon-communities.svg" alt="" />
			<h1 class="comHeader">1.4k+</h1>
			<p class="comSubs">Communities Formed</p>
		</div>
		<div class="message">
			<img class="mesIcon" src="images/icon-messages.svg" alt="" />
			<h1 class="comHeader">2.7m+</h1>
			<p class="comSubs">Messages Sent</p>
		</div>
	</div>
	<div class="topBg">
		<img class="bg-top1" src="images/bg-section-top-desktop-1.svg" alt="" />
		<!-- <img class="bg-top2" src="images/bg-section-top-desktop-2.svg" alt=""> -->
	</div>
</section>

<section class="oneContainer">
	<div class="oneContent">
		<div class="oneLeft">
			<h1 class="leftHeader">Grow Together</h1>
			<p class="leftSubtitle">
				Generate meaningful discussions with your audience and build a strong, loyal community.
				Think of the insighful conversations you miss out on with a feedback form.
			</p>
		</div>
		<div class="oneRight">
			<img class="imgOne" src="images/illustration-grow-together.svg" alt="" />
		</div>
	</div>
</section>

<section class="twoContainer">
	<div class="twoImgBg">
		<img src="images/bg-section-bottom-desktop-1.svg" alt="" />
	</div>
	<div class="twoContent">
		<div class="oneRight">
			<img class="imgOne" src="images/illustration-flowing-conversation.svg" alt="" />
		</div>
		<div class="oneLeft">
			<h1 class="leftHeader">Flowing Conversations</h1>
			<p class="leftSubtitle">
				You wouldn't paginate a conversation in a real life. so why do it online? Our threads have
				just-in-time loading for a more natural flow.
			</p>
		</div>
	</div>
	<div class="topBg">
		<img class="bg-top1" src="images/bg-section-top-desktop-2.svg" alt="" />
	</div>
</section>

<section class="threeContainer">
	<div class="threeContent">
		<div class="oneLeft">
			<h1 class="leftHeader">Your Users</h1>
			<p class="leftSubtitle">
				It takes no time at all to integrate Huddle with your app's authentication solution. This
				means, once signed in to your app, your users can start chatting immediately.
			</p>
		</div>
		<div class="oneRight">
			<img class="imgOne" src="images/illustration-your-users.svg" alt="" />
		</div>
	</div>
</section>

<section class="fourContainer">
	<div class="twoImgBg">
		<img src="images/bg-section-bottom-desktop-2.svg" alt="" />
	</div>
	<div class="fourContent">
		<h1 class="fourHeader">Ready To Build Your Community?</h1>
		<button class="btnGet">Get Started For Free</button>
	</div>
	<div class="topBg">
		<img class="bg-top1" src="images/bg-footer-top-desktop.svg" alt="" />
	</div>
</section>

<footer>
	<div class="footerContainer">
		<div class="footerContent">
			<div class="footerLeft">
				<img src="images/footer-logo.svg" alt="" />
				<p class="txtAddress">
					Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla quam, hendrerit
					lacinia vestibulum a, ultrices quis sem.
				</p>
				<div class="footerContact">
					<img class="footerIcon" src="images/icon-phone.svg" alt="" />
					<p class="footerTxt">+1-543-123-4567</p>
				</div>
				<div class="footerContact">
					<img class="emailIcon" src="images/icon-email.svg" alt="" />
					<p class="footerTxt">example@huddle.com</p>
				</div>
			</div>
			<div class="footerRight">
				<h1 class="newsHeader">newsletter</h1>
				<p class="newsText">
					To recieve tips on how to grow your community, sign up to our weekly newsletter. We’ll
					never send you spam or pass on your email address
				</p>
				<div class="btnSubs">
					<input class="inputSubs" placeholder="example.com" type="text" />
					<button class="btnSub">Subscribe</button>
				</div>
			</div>
		</div>
		<div class="footerSosmed">
			<i class="socials fab fa-facebook-square fa-2xl" />
			<i class="socials fab fa-instagram fa-2xl" />
			<i class="socials fab fa-twitter-square fa-2xl" />
		</div>
	</div>
</footer>

<style>
	.navbar {
		width: 100%;
		display: flex;
		justify-content: space-between;
		padding: 50px;
	}

	.btnHeader button {
		background-color: white;
		padding: 12px;
		width: 150px;
		border-radius: 20px;
		font-weight: 700;

		border: 1px solid var(--lightPink);
		color: var(--lightPink);
		cursor: pointer;
		transition: all 0.5s ease;
	}

	.btnHeader button:hover {
		border: 1px solid hsl(320, 48%, 86%);
		color: hsl(320, 48%, 86%);
		box-shadow: hsl(321, 93%, 84%) 1.95px 1.95px 2.6px;
	}

	.topContainer {
		text-align: center;
		padding: 200px 0px 0px 0px;
		width: 100%;
	}

	.topHeader {
		font-size: 48px;
	}

	.topTxt {
		padding: 1rem 30rem;
	}

	.btnGet {
		margin-top: 30px;
		width: 300px;
		padding: 18px;
		color: white;
		background-color: var(--pink);
		border: 1px solid var(--pink);
		border-radius: 25px;
		cursor: pointer;
		font-weight: 700;
	}

	.topImg {
		width: 100%;
		margin-top: 100px;
	}

	.topContent {
		width: 100%;
		display: flex;
		padding: 50px 50px 100px;
		justify-content: space-around;
	}

	.comIcon {
		width: 20%;
		display: flex;
	}

	.mesIcon {
		width: 15%;
		display: flex;
	}

	.comHeader {
		font-size: 65px;
	}

	.comSubs {
		color: grey;
		opacity: 0.8;
	}

	.topBg {
		/* background-image: url(images/bg-section-top-desktop-1.svg);
        background-repeat: no-repeat;
        background-size: cover; */
		width: 100%;
		display: flex;
	}

	.bg-top1 {
		width: 100%;
	}

	.oneContainer,
	.threeContainer {
		background-color: var(--paleBlue);
		width: 100%;
	}

	.oneContent {
		padding: 50px;
		display: flex;
	}

	.oneLeft {
		width: 50%;
		padding: 50px;
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.leftHeader {
		font-size: 36px;
		margin-bottom: 10px;
	}

	.leftSubtitle {
		color: var(--Grayish);
		width: 100%;
		padding: 20px 20px 20px 0px;
		letter-spacing: 1px;
		line-height: 1.5rem;
	}

	.oneRight {
		width: 50%;
		padding: 50px;
	}

	.imgOne {
		width: 100%;
	}

	.twoContainer,
	.fourContainer {
		background-color: white;
		width: 100%;
	}

	.twoImgBg {
		width: 100%;
	}

	.twoContent,
	.threeContent {
		padding: 50px;
		display: flex;
	}

	.fourContent {
		padding: 150px 50px;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.fourHeader {
		font-size: 40px;
	}

	footer {
		background-color: var(--darkCyan);
		width: 100%;
	}

	.footerContainer {
		padding: 50px 100px;
		width: 100%;
	}

	.footerContent {
		display: flex;
		width: 100%;
	}

	.footerLeft {
		width: 50%;
		margin-top: 100px;
		color: white;
	}

	.txtAddress {
		margin-top: 20px;
		width: 50%;
		line-height: 1.5rem;
	}

	.footerContact {
		display: flex;
		width: 100%;
		margin-top: 20px;
	}

	.footerIcon {
		width: 15px;
		height: 20px;
	}

	.emailIcon {
		width: 20px;
		height: 20px;
	}

	.footerTxt {
		margin-left: 20px;
	}

	.footerRight {
		width: 50%;
		color: white;
		margin-top: 100px;
	}

	.newsHeader {
		font-size: 30px;
		text-transform: uppercase;
	}

	.newsText {
		width: 55%;
		margin-top: 20px;
		line-height: 1.5rem;
	}

	.btnSubs {
		width: 100%;
		display: flex;
		margin-top: 30px;
		gap: 2rem;
	}

	.inputSubs {
		width: 50%;
		padding: 12px;
		border-radius: 10px;
	}

	.inputSubs:focus {
		outline: none;
		border: 1px solid var(--paleBlue);
	}

	.btnSub {
		background-color: var(--pink);
		color: white;
		font-weight: 700;
		padding: 10px;
		border-radius: 10px;
		width: 25%;
		border: 1px solid var(--pink);
		cursor: pointer;
	}

	.footerSosmed {
		width: 20%;
		display: flex;
		/* justify-content: space-between; */
		color: white;
		margin-top: 5rem;
        /* margin-right: 3rem; */
        cursor: pointer;
	}

    .socials {
        margin-right: 20px;
    }

    .socials:hover {
        color: skyblue;
    }
</style>
