<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>My News Website</title> 
  <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 28px;
        }
        header p {
            margin: 5px 0 0;
            font-size: 16px;
        }
        nav {
            background-color: #444;
            overflow: hidden;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            font-size: 16px;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        h2 {
            margin-bottom: 20px;
            font-size: 24px;
            text-align: center;
        }
        .news-section {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .news-article {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .news-article img {
            width: 100%;
            border-radius: 5px 5px 0 0;
        }
        .news-article h3 {
            font-size: 18px;
            margin: 10px;
        }
        .news-article p {
            font-size: 14px;
            margin: 10px;
            color: #555;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style> 
 </head> 
 <body> <!-- Header --> 
  <header> 
   <h1>My News Website</h1> 
   <p>Your daily source of news</p> 
  </header> <!-- Navigation Bar --> 
  <nav> <a href="#">Home</a> <a href="#">World</a> <a href="#">Technology</a> <a href="#">Sports</a> <a href="#">Contact</a> 
  </nav> <!-- Main Content --> 
  <div class="container"> 
   <h2>Latest News</h2> 
   <div class="news-section"> <!-- News Article 1 --> 
    <div class="news-article"> 
     <img src="https://via.placeholder.com/300x200" alt="News Image"> 
     <h3>News Headline 1</h3> 
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vehicula.</p> 
    </div> <!-- News Article 2 --> 
    <div class="news-article"> 
     <img src="https://via.placeholder.com/300x200" alt="News Image"> 
     <h3>News Headline 2</h3> 
     <p>Suspendisse potenti. Nullam auctor, urna eu finibus vulputate, magna.</p> 
    </div> <!-- News Article 3 --> 
    <div class="news-article"> 
     <img src="https://via.placeholder.com/300x200" alt="News Image"> 
     <h3>News Headline 3</h3> 
     <p>Curabitur vel tincidunt justo. Proin id lectus sed odio auctor posuere.</p> 
    </div> 
   </div> 
  </div> <!-- Footer --> 
  <footer> 
   <p>© 2025 My News Website. All Rights Reserved.</p> 
  </footer> 
 </body>
</html> 
