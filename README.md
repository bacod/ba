<html>
<head>
  <title>Your Website Title</title>
    <!-- You can use open graph tags to customize link previews.
    Learn more: https://developers.facebook.com/docs/sharing/webmasters -->
  <meta property="og:url"           content="https://www.codee.com.ba/your-page.html" />
  <meta property="og:type"          content="website" />ba
  <meta property="og:title"         content="Your Website Title" />ba
  <meta property="og:description"   content="Your description" />ba
  <meta property="og:image"         content="https://www.codee.com.ba/path/image.jpg" />
</head>
<body>

  <!-- Load Facebook SDK for JavaScript -->
  <div id="fb-root"></div>
  <script>(function(d, s, id) {
    var js, fjs = d.getElementsByTagName(s)[0];
    if (d.getElementById(id)) return;
    js = d.createElement(s); js.id = id;
    js.src = "https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v3.0";
    fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'facebook-jssdk'));</script>

  <!-- Your like button code -->
  <div class="fb-like" 
    data-href="https://www.codee.com.ba/your-page.html" 
    data-layout="standard" 
    data-action="like" 
    data-show-faces="true">
  </div>

</body>
</html>ba
