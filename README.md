# Basic Parallax Effect

This is some simple example how we can use pallax.

If you wish to have the same image on all of your parallax effect pages, you just need to make few changes in css. 
On the first line in our stylesheet or css after parallax you do it like this:

.parallax, parallax2, parallax3 {
	height: 500px;
	background: url('image') repeat fixed 100%;
}

And on this way you will have the same image on all of your parallax effects.
You can also add position of picture, background-position: center bottom left right or on the same line on 
background: url('image') center repeact fixed 100%;
