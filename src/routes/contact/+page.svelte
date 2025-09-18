<svelte:head>
	<title>Contact Ryan!</title>
</svelte:head>

<nav>
    <a href="../"> Home Page </a>
    <a href="../projects"> My Projects </a>
    <a class="current" href="../contact"> Contact Me </a>
    <a href="https://github.com/ryannuqui10" target="_blank"> My Github Profile </a>
</nav>
<h1> Contact Me </h1>
<form action = "mailto:rnuqui@andrew.cmu.edu" method="POST" enctype="text/plain"> 
    <label>
        Email:
        <input name="email" type="email">
    </label>
    <label>
        Subject: 
        <input name="subject">
    </label>
    <label>
        Body: 
        <textarea name="body"> </textarea>
    </label>
    <button> Submit </button>
</form>