# gallery.html
my history
<section id="photo-albums">
  <style>
#photo-albums {
  margin: 2rem 0;
}

#photo-albums h2,
#photo-albums h3 {
  font-family: sans-serif;
}

.album-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.album-grid figure {
  width: 180px;
  margin: 0;
}

.album-grid img {
  width: 100%;
  height: auto;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.2);
}
.album-grid figcaption {
  font-size: 0.85rem;
  text-align: center;
  margin-top: 0.25rem;
}
</style>
  <h2>Photo Albums</h2>
<style>
  /* Section styling */
#gallery {
  padding: 2rem 1rem;
  max-width: 1100px;
  margin: 0 auto;
}

#gallery h2 {
  font-family: sans-serif;
  margin-bottom: 1rem;
  text-align: center;
}

/* Responsive grid */
.gallery-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

/* Each item */
.gallery-item {
  flex: 1 1 calc(25% - 1rem); /* 4 columns on large screens */
  max-width: calc(25% - 1rem);
  box-sizing: border-box;
}

.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 4px;
  object-fit: cover;
  box-shadow: 0 2px 4px rgba(0,0,0,0.15);
}

.gallery-item figcaption {
  font-size: 0.85rem;
  text-align: center;
  margin-top: 0.25rem;
}

/* Medium screens: 2 columns */
@media screen and (max-width: 800px) {
  .gallery-item {
    flex: 1 1 calc(50% - 1rem);
    max-width: calc(50% - 1rem);
  }
}

/* Small screens: 1 column */
@media screen and (max-width: 500px) {
  .gallery-item {
    flex: 1 1 100%;
    max-width: 100%;
  }
}

</style>

  <!-- Album 1 -->
  <h3>Research Visits</h3>
  <div class="album-grid">
    <figure>
      <img src="assets/images/albums/research/paris_2022.jpg" alt="Paris conference 2022">
      <figcaption>Paris, 2022 – Conference on Physics</figcaption>
    </figure>
    <figure>
      <img src="assets/images/albums/research/prague_2019.jpg" alt="Prague Terahertz meeting">
      <figcaption>Prague, 2019 – Terahertz Meeting</figcaption>
    </figure>
    <!-- Add more <figure> blocks as needed -->
  </div>

  <!-- Album 2 -->
  <h3>Family & Personal</h3>
  <div class="album-grid">
    <figure>
      <img src="assets/images/albums/family/family1.jpg" alt="Family photo">
      <figcaption>Family</figcaption>
    </figure>
    <!-- More photos -->
  </div>
</section>

<section id="gallery">
  <h2>Photo Gallery</h2>

  <div class="gallery-grid">
    <figure class="gallery-item">
      <img src="assets/images/gallery/photo1.jpg" alt="Description 1">
      <figcaption>Paris, 2022 – Conference</figcaption>
    </figure>

    <figure class="gallery-item">
      <img src="assets/images/gallery/photo2.jpg" alt="Description 2">
      <figcaption>Prague, 2019 – Terahertz Meeting</figcaption>
    </figure>

    <figure class="gallery-item">
      <img src="assets/images/gallery/photo3.jpg" alt="Description 3">
      <figcaption>Meghalaya – Field Visit</figcaption>
    </figure>

    <!-- Add more <figure> blocks as needed -->
  </div>
</section>

