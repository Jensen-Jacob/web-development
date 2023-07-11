First of all, congratulations on completing the HTML section and making your way here.

So first of all, every web developer should know the difference between inline css, internal css and external css.

Let's start with Inline CSS.

So inline css refers to the css styling that is directly added into an html tag using the "style" attribute.

Here's an example:

<p style="color: green; font-size: 40px;">Hello World!</p>

<h1>lorem</h1>

Here the styling is added directly into the paragraph tag.

It is important to note that this method (inline css) only affects the particular html tag that it is applied to, i.e. in this case, the styling will only affect the <p> tag and not the <h1>.

Now lets move on to Internal CSS.

Internal CSS is applied by creating a new element in the "head" tag and the styling specified within the same affects the entire page.

Here's an example:

<html>
<head>
<title>Internal CSS</title>
<style>
    h1{
        color: green;
    }

    .blue {
        color: blue;
    }

    #green{
        color: green;
    }
</style>
</head>
<body>
    <h1>Hello</h1>
    <h1 class="blue">World</h1>
    <h1 id="green">!</h1>
</body>
</html>

In the above example, inline css is used to apply styles to the entire page. Here, all the h1s in general will be colored green, all elements with the class "blue" will be colored blue and all elements with the id "green" will be colored green.

It is important to note that internal css will only affect the page that it is written in and nothing else.

Last but not least, we have External CSS.

External CSS is similar to Internal CSS except for the fact that External CSS is written in a separate .css file and is referenced using the link tag in the head element of the respective html page.

The benefit of having External CSS is that the same CSS file can be used by multiple web pages as long as it is linked to them.

The syntax for linking external css is as follows: 
<link rel="stylesheet" href="mystyle.css">

If you have any more doubts about this topic, feel free to google them.

Best of luck on your coding journey!