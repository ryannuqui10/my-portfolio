<svelte:head>
	<title>Contact Ryan!</title>
</svelte:head>

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