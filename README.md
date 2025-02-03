HTML File:
		HTML is the standard markup language for Web pages. With HTML we can create our own Website. Basically its creat web page structure. it is a consists of a series of elements.
A header:
		HTML headings are defined with the <h1> to <h6> tags. <h1> defines the most important heading. 
		<!--A header-->
    <h1>Simple Webpage Design</h1>
(css)
/*A header*/
h1{
    text-align: center;
    font-size: 45px;
    background-color: rgb(110, 110, 110);
    font-family: 'Courier New', Courier, monospace;
    height: 100px;
    padding: 0;
    width: 100%;
    margin: 0;
    padding-top: 25px;
}
A main(content section with text and images):
		Here we use div tag, img tag, id using as a bookmark, form tag etc. 
		    1. The <div> element is by default a block element, meaning that it takes all 		available width, and comes with line breaks before and after.
		  2. The HTML id attribute is used to specify a unique id for an HTML element.              The value of the id attribute must be unique within the HTML document.HTML bookmarks are used to allow readers to jump to specific parts of a webpage. Bookmarks can be useful if our page is very long. To use a bookmark,  must first create it, and then add a link to it. Then, when the link is clicked, the page will scroll to the location with the bookmark.
		  3. An HTML form is used to collect user input. The user input is most often sent to a server for processing.The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc. 
		4.Images can improve the design and the appearance of a web page. Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.
<!--A main-->
        <div class="main">
        <div id="home">
            <h3><u><b>Simple Webpage Design</b></u></h3>
            <p>Make your business shine online with a custom simple website designed just for you by a professional designer. Need ideas? We’ve collected some amazing examples of simple websites from our global community of designers. Get inspired and start planning the perfect simple web design today.</p>
        </div>
        <div id="blog">
            <h3><b>BLOG</b></h3>
            <ol>
                <li><u><a href="#Front-end languages">Front-end languages</a></u><p>Html, The stander markup language for creating web pages is essentia;ll for front end development because it gives developers a way to define the content and structure of a website or application. HTML tags define heading paragraphs ,list, links,image, and other elements that makeup a web page. Despite the many advamcements in web technologies. HTML remains a cornerstone of the web development industry. while newer technologies have emerged to enhance web development capabilities, HTML remains the foundation upon which they aer built. </p></li>
                <li><u><a href="#Cascading Style Sheets(CSS)">Cascading Style Sheets(CSS)</a></u><p>CSS is a stylesheet language used for describing the look and layout of document written in HTML. CSS is used to control the layout, colors,fonts, andd other visual elements of a website or application. It allows developers to separate the content and structure defined in HTML form the visual presentation of the site, making it easier to maintain and update the appearance of a websites. CSS Has become increasingly crucial in front- end developers as the web becomes more visually sophisticated. It is now possible to create complex and highly-stylized web pages and applications, thanks to CSS, ability to control visual elements.</p></li>
                <li><u><a href="#JavaScript">JavaScript</a></u><p>    Javasript is a high-level programming language widley used for front-end development to add interactivity and dynamic behavior to web pages and application making them more engaging and user-friendly.JavaScrift can creat a wide range of effects such as animation, form validation and dynamic updates to a web page without requiring a page refresh JavScrift has become an indispensable tool for front-end developers and its importance is only growing as the web becomes more complex and dynamic with the rise of single-page applications and other modern web development trends, JaveScript has become a must have skill for front-end developers for its versatility ease of use, abd ubiquity.
                </p></li>
        
            </ol>
        </div>
        <div id="about">
            <h2 style="text-align: center; background-color: rgb(3, 49, 49); color: wheat;" id="Front-end languages" style="text-align: center; background-color: rgb(3, 49, 49); color: wheat;">Front-end languages</h2>
        <img height="450" width="450" src="html-css-java.jpg" alt="">
        <img height="450" width="450" src="html-css-java1.avif" alt="">
        <img height="450" width="450" src="html.png" alt="">
        <img height="450" width="450" src="java.avif" alt="">
        <h2 style="text-align: center; background-color: rgb(3, 49, 49); color: wheat;" id="Cascading Style Sheets(CSS)">Cascading Style Sheets(CSS)</h2>
        <img height="450" width="450" src="css.png" alt="">
        <img height="450" width="450" src="css.png" alt="">
        <img height="450" width="450" src="css.png" alt="">
        <img height="450" width="450" src="css.png" alt="">
        <h2 style="text-align: center; background-color: rgb(3, 49, 49); color: wheat;" id="JavaScript">JavaScript</h2>
        <img height="450" width="450" src="java1.png" alt="">
        <img height="450" width="450" src="java1.png" alt="">
        <img height="450" width="450" src="java1.png" alt="">
        <img height="450" width="450" src="java1.png" alt="">
    </div >
    <div id="contact">
        <form action="#">
            <legend>
            <label for="name">First Name: <input type="text" name="name" placeholder="Enter your Name"></label>
            <br><br><label for="lname">last Name:
                <input type="text" placeholder="Enter your last name" name="lname">
            </label><br><br>
            <label for="date">Date of Birth: <input type="date"></label>
            <br><br><label for="number">contact Number: <input type="text"></label>
            <br><br><label for="email">Email: <input type="email" placeholder="abc@gmail.com"></label>
        </legend>
        </form>
    </div>
    </div>
(css)
/*A main*/
.main{
    margin-left: 8%;
    padding: 1px 10px;
    text-align: justify;
    font-style: italic;
}
.last h2{
    text-align: center;
    font-size: 30px;
}
form{
    text-align: center;
    border: 1px solid black;
    margin: 5px;
    padding: 5px;
    background-color: rgb(177, 113, 236);
}
A sidebar: 

 <!--A sidebar-->
        <ul>
            <li><a href="#home">HOME</a></li>
            <li><a href="#blog">BLOG</a></li>
            <li><a href="#about">ABOUT</a></li>
            <li><a href="#contact">CONTACT</a></li>
        </ul> 
(css)
/*A sidebar*/
 ul{
    position: fixed;
    height: 100%;
    padding: 0;
    margin: 0;
    width: 100px;
    text-decoration: none;
    background-color: rgb(36, 31, 31);
}
ul li {
    list-style-type: none;
    text-align: center;
    border-bottom: 1px solid black;

}
ul li:last-child{
    border-bottom: none;
}
ul li a{
    display: block;
    padding:8px 16px ;
    text-decoration: none;
    color: whitesmoke;
}
li a:hover{
    background-color: rgb(3, 22, 12);
    color: black;
}
li a:active{
    background-color: black;
    color: white;
}
A footer:
 <!--A footer-->
        <footer>
            <div class="last"><h2>THis is footer</h2></div>
            <div class="footering">
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam labore est, reprehenderit placeat voluptate debitis delectus ducimus officiis, odio molestiae aperiam. Suscipit delectus hic corporis eveniet inventore tempore non porro.</p>
        
            </div>
            <div class="icon">
            <i class="fa-brands fa-facebook"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
            </div>
            <div>
                <p>
                copyright@2021 by Taslima Akter Munni </p>
            </div>
            </footer>
(css):
/*a footer*/
footer{
    text-align: center;
    position: absolute;
    background-color: black;
    color: white;
    width: 100%;
    padding: 10px;
    margin: 0;
}
.icon i{
    font-size: 25px;
    padding: 5px;
}
