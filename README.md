<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Image Gallery</title>
  <style>
   body{
    background-color: beige;
   }
    h2{
        color:dimgray;
        text-align: left;
    }
    .gallery {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }

    .thumbnail {
      width: 100px;
      cursor: pointer;
      transition: transform 0.2s;
    }

    .thumbnail:hover {
      transform: scale(1.1);
    }

    .lightbox {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100vw; height: 100vh;
      background: rgba(0, 0, 0, 0.8);
      justify-content: center;
      align-items: center;
    }

    .lightbox img {
      max-width: 90%;
      max-height: 90%;
    }

    .lightbox:target {
      display: flex;
    }
  </style>
</head>
<body>


<h2><B>Image Gallery of Scenery</B></h2>
<h4>click to zoom:</h4>

<div class="gallery">
  <a href="#img1"><img src="https://media.istockphoto.com/id/1381637603/photo/mountain-landscape.jpg?s=612x612&w=0&k=20&c=w64j3fW8C96CfYo3kbi386rs_sHH_6BGe8lAAAFS-y4=" class="thumbnail"></a>
  <a href="#img2"><img src="https://www.shutterstock.com/image-photo/banff-national-park-lake-minnewanka-600nw-2527379207.jpg" class="thumbnail"></a>
  <a href="#img3"><img src="https://img.freepik.com/free-photo/fuji-mountain-kawaguchiko-lake-sunset-autumn-seasons-fuji-mountain-yamanachi-japan_335224-1.jpg" class="thumbnail"></a>
  <a href="#img4"><img src="https://t4.ftcdn.net/jpg/06/18/89/01/360_F_618890114_KvUt2AtvgDCccwgAkwV4ntGtp6Qe7tYz.jpg"class="thumbnail"></a>
  <a href="#img5"><img src="https://static.vecteezy.com/system/resources/thumbnails/055/419/300/small/mountains-and-trees-are-reflected-in-a-lake-free-photo.jpg"class="thumbnail"></a>
  <a href="#img6"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRkIUKAUiSw6IVfk-viBGoeY625cEOBV1KGp6shkKcjPW7RHw-XQty0HazGxfk2EX8COL4&usqp=CAU"class="thumbnail"></a>
</div>

<div id="img1" class="lightbox">
  <a href="#"><img src="https://media.istockphoto.com/id/1381637603/photo/mountain-landscape.jpg?s=612x612&w=0&k=20&c=w64j3fW8C96CfYo3kbi386rs_sHH_6BGe8lAAAFS-y4="></a>
</div>
<div id="img2" class="lightbox">
  <a href="#"><img src="https://www.shutterstock.com/image-photo/banff-national-park-lake-minnewanka-600nw-2527379207.jpg"></a>
</div>
<div id="img3" class="lightbox">
  <a href="#"><img src="https://img.freepik.com/free-photo/fuji-mountain-kawaguchiko-lake-sunset-autumn-seasons-fuji-mountain-yamanachi-japan_335224-1.jpg"></a>
</div>
<div id="img4" class="lightbox">
  <a href="#"><img src="https://t4.ftcdn.net/jpg/06/18/89/01/360_F_618890114_KvUt2AtvgDCccwgAkwV4ntGtp6Qe7tYz.jpg"></a>
</div>
<div id="img5" class="lightbox">
  <a href="#"><img src="https://static.vecteezy.com/system/resources/thumbnails/055/419/300/small/mountains-and-trees-are-reflected-in-a-lake-free-photo.jpg"></a>
</div>
<div id="img6" class="lightbox">
  <a href="#"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRkIUKAUiSw6IVfk-viBGoeY625cEOBV1KGp6shkKcjPW7RHw-XQty0HazGxfk2EX8COL4&usqp=CAU"></a>
</div>

</body>
</html>

