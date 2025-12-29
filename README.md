# gallery.html
my history
<section id="photo-albums">
  <h2>Photo Albums</h2>

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
