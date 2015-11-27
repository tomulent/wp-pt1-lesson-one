HTML and the World Wide Web
===
What if I told you, the Web (what you may call the internet) is just a bunch of text files? It’s a gross oversimplification, but it’s pretty true. I’ll prove it to you.

First we need to understand what HTML is. As I mentioned earlier, HTML is an abbreviation for Hyper Text Markup Language. It is essentially a way to “mark up” text to give it meaning that a web browser can understand. I will mention this here and multiple times throughout the next few lessons: HTML describes the structure of our content for our web page. Think “HTML = structure/content”. The browser interprets our HTML and lays out (or displays) the structure and content that we coded. HTML does not deal with HOW it is displayed in the browser (we will visit this concept later and in future lessons).

HTML consists of “tags” which are single words called “elements” enclosed by “`< >`”. There are two types: “opening” (like `<h1>`) and “closing” (like `</h1>`). These tell the browser that everything in between the opening and closing tags have a special meaning. For instance, the tag `<h1>` means heading one. So when the browser sees

```html
<h1>This is a Heading</h1>
```

It knows that everything between `<h1>` and `</h1>` is heading one text. Likewise, the browser knows everything in between the <p> and </p> tags is a paragraph. Enough talk, let’s jump in!

Open up your text editor and type the following html exactly as shown below. You will have to type it yourself, do not copy and paste. This lesson and its code was written in a word processor and if you simply copy and paste it, it will not format properly in a text editor.


```html
<!DOCTYPE html>
<html>

  <head>
    <title>This is the Title</title>
  </head>
  
  <body>
    <h1>Hello World!</h1>
    <p>This is a paragraph</p>
  </body>
  
</html>
```
Now save it with the title “index.html” and then open it (in the picture, I have mine saved differently, but ignore that). To open this html file, either double click the file or right-click, choose “Open With” and pick either Firefox or Google Chrome. Notice that this file opens up in your browser. The file extension .html tells your computer that this is a file for the browser to read. The browser opens it, sees that it begins with <!DOCTYPE html> and an <html> tag, knows that it’s reading a HTML document which contains Hyper Text Markup Language, and everything in between the <html> tags should be treated as such.

Congrats! You have just coded your (almost complete) first web page. This may be overwhelming, but do not fear! I will step you through this line-by-line, so you can understand everything you just wrote. Let’s dive in!

## Revelation Time

So what have we created here? You made a file containing a bunch of text that you “marked up” using HTML tags that your browser opened and interpreted to display what you wanted. Guess what? At its most basic, that is what the web is made of. When you type “google.com” into your browser’s address bar, a request is sent to a specially formatted computer called a “server” that locates a file called “google.html” then sends it to your browser which reads the code and displays it in a way that looks good. Of course there is a lot more going on but in essence the web is a collection of text files sitting in a computer somewhere.

