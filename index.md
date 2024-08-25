<!DOCTYPE html>
<html>
<head>
  <title>Image Gallery</title>
  <style>
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .gallery-item   
 {
      width: 32%;
      margin-bottom: 20px;
    }

    .gallery-item img {
      width: 100%;
      height: auto;
      border: 1px solid #ccc;
      cursor: pointer;
      transition: transform 0.3s ease;
    }

    .gallery-item img:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body>
  <div class="gallery">
    <div class="gallery-item">
      <img src="https://i.imgur.com/aclLmH6.jpeg" alt="Image 1">
    </div>
    <div class="gallery-item">
      <img src="https://i.imgur.com/aclLmH6.jpeg" alt="Image 2">
    </div>
    <div class="gallery-item">
      <img src="https://i.imgur.com/aclLmH6.jpeg" alt="Image 3">
    </div>
  </div>
</body>
</html>
