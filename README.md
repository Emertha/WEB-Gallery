# WEB-Gallery
* {

 box-sizing: border-box;

}

body {

font-family: 'Amatic SC', cursive;
margin: 0;
padding: 0;

}
.container {

 max-width: 1000px;

 margin: 0 auto;

}
header {

 width: 100%;

 height: 60px;

 background-color: #006633;
}
.logo {

 float: left;
margin-top: 5px;

}

.menu {

 float: right;


}

.clear {

 clear: both;

}
ul {

 list-style-type: none;

 padding: 0;

 margin: 0;

}

ul li {

 display: inline-block;

}

ul li a {

 text-decoration: none;

 color: #FFFFFF;

 text-transform: uppercase;

 font-size: 18px;

 text-align: center;

 display: inline-block;

 line-height: 60px;

 padding: 0 10px;

}

ul li a:hover {

 background-color: #919db7;

 color: #FFFFFF;

}
.jumbotron {

 width: 100%;

 height: 100vh;

 background-image: url(https://images.unsplash.com/photo-1478033394151-c931d5a4bdd6?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=17d2798bb3e28902f41b86c4dc1892ad&auto=format&fit=crop&w=668&q=80);

 background-size: cover;

 background-position: center;

 overflow: hidden;

 text-align: center;

}
.jumbotron-welcome {

 margin: 20vh auto;

 background: rgba(255, 255, 255, 0.5);
max-width: 800px;

}

.jumbotron-main {

 font-size: 55px;

 color: #5b627e;

 margin: 0;

 line-height: 20vh;

}

.jumbotron-text {

 font-size: 40px;

 color: #191E2A;

 padding: 20px;

 margin: 0;

}

.jumbotron-button {

 font-size: 20px;

 background-color: #5b627e;

 color: #FFFFFF;

 text-align: center;

 border: none;

 padding: 10px 25px;

 margin: 10px auto;

 cursor: pointer;

}

.jumbotron-button:hover {

 opacity: 0.6;

 background-color: #FFFFFF;

 color: #5b627e;

}
.gallery {

 text-align: center;
 margin: 0 auto;
background: linear-gradient(to bottom, #627d4d 24%,#1f3b08 71%);
 padding: 5px;
 padding-bottom: 50px;
 box-shadow: 0 1px 2px rgba(0,0,0,.3);

}

.gallery-text {

 color: #5b627e;

 padding: 50px;

 margin: 0;

 font-size: 40px;

}

.gallery-pics img {

 object-fit: cover;
position: relative;
  
  padding: 5px;
 float: left;

 width: 25%;
 max-height: 150px;

 }

.gallery-pics img:hover {
z-index: 1;
 
  transform: scale(2.0,2.0);
  transition: .3s transform;
 cursor: pointer;

}

footer {

 background-color: #142804;

 text-align: center;

}

footer p {

 margin: 0;

 padding: 20px

}
