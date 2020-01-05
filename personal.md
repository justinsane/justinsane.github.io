---
layout: page
title: Personal
subtitle: A bit on my interests and hobbies
---

## Here's some of my interests:
- reading
- technology
- cars
- food
- endurance sports
- traveling


<div id="my-carousel" class="carousel slide" data-ride="carousel">
  <!-- Indicators: the little circles at the bottom of the slides that show which number image you're on -->
<!-- Make sure you have the same number of indicators as "Items divs below" -->
  <ol class="carousel-indicators">
    <li data-target="#my-carousel" data-slide-to="0" class="active"></li>
    <li data-target="#my-carousel" data-slide-to="1"></li>
    <li data-target="#my-carousel" data-slide-to="2"></li>
  </ol>

  <!-- Wrapper for slides -->
  <div class="carousel-inner" role="listbox">

    <div class="item active">
			<!-- Images: edit the value of src="..." with a url of your own picture, or a relative path to the img in in the images folder. -->
			<!-- Absolute pa†h: https://some-image-path.com -->
			<!-- relative path: {{ 'img/name-of-the-img-in-this-folder.jpg' | relative_url }} -->

      <img src="{{ 'img/404-southpark.jpg' | relative_url }}" />
			<!-- Captions: put html between the open/close tag of carousel-caption to add a caption -->
      <div class="carousel-caption">
				<p>A slide</p>
      </div>

    </div>

    <div class="item">
			<!-- Images: edit the value of src="..." with a url of your own picture -->
      <img src="https://picsum.photos/id/100/750/417" />
			<!-- Captions: put html between the open/close tag of carousel-caption to add a caption -->
			<div class="carousel-caption">
				<p>And another.</p>
      </div>
		</div>
		
		<div class="item">
			<!-- Images: edit the value of src="..." with a url of your own picture -->
      <img src="https://picsum.photos/id/1020/750/417" />
			<!-- Captions: put html between the open/close tag of carousel-caption to add a caption -->
			<div class="carousel-caption">
				<p>Last one.</p>
      </div>
    </div>
  </div>

  <!-- Controls: These are the left/right arrows to control slides, don't touch these -->
  <a class="left carousel-control" href="#my-carousel" role="button" data-slide="prev">
		<!-- you could customize the arrow icons with one of these if you wanted. https://getbootstrap.com/docs/3.3/components/#glyphicons-how-to-use -->
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#my-carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>