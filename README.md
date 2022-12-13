# gTong0723.github.io
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>制裁小灰灰俱乐部</title>
<!--[if lte IE 8]>
<script>
  document.createElement("nav");
  document.createElement("header");
  document.createElement("footer");
  document.createElement("section");
  document.createElement("aside");
  document.createElement("article");
</script>
<![endif]-->
<link rel="stylesheet" href="style.css">
</head>
<body>
<header id="page_header">
  <nav>
        <ul>
            <li><a href="#">最新文档</a></li>
            <li><a href="#">精选文档</a></li>
            <li><a href="#">技术支持</a></li>
            <li><a href="#">联系我们</a></li>
        </ul>
    </nav>
</header>
<section id="posts">
    <article class="post">
        <header>
            <h2>小灰灰的一生与开发</h2>
            <p>gTong发布于
                <time datetime="2015-10-01T14:39">October 1st, 2015 at 2:39PM</time>
            </p>
        </header>
        <aside>
            <p> &ldquo;本博客文章如无特别注明，均为原创，欢迎转载、传阅，共同交流~&rdquo; </p>
        </aside>
        <p>在移动设备上进行网页的重构或开发，首先得搞明白的就是移动设备上的viewport了，只有明白了viewport的概念以及弄清楚了跟viewport有关的meta标签的使用，才能更好地让我们的网页适配或响应各种不同分辨率的移动设备。</p>
        <p>通俗的讲，移动设备上的viewport就是设备的屏幕上能用来显示我们的网页的那一块区域，在具体一点，就是浏览器上(也可能是一个app中的webview)用来显示网页的那部分区域，但viewport又不局限于浏览器可视区域的大小，它可能比浏览器的可视区域要大，也可能比浏览器的可视区域要小。在默认情况下，一般来讲，移动设备上的viewport都是要大于浏览器可视区域的，这是因为考虑到移动设备的分辨率相对于桌面电脑来说都比较小，所以为了能在移动设备上正常显示那些传统的为桌面浏览器设计的网站，移动设备上的浏览器都会把自己默认的viewport设为980px或1024px（也可能是其它值，这个是由设备自己决定的），但带来的后果就是浏览器会出现横向滚动条，因为浏览器可视区域的宽度是比这个默认的viewport的宽度要小的。下图列出了一些设备上浏览器的默认viewport的宽度。</p>
        <footer>
            <p><a href="comments"><i>14 评论</i></a> ...</p>
        </footer>
    </article>
</section>
<section id="sidebar">
