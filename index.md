---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h2>Neuroalgebra is a portal for brain cell computations with stochasticity and 3D environment.</h2>

  <!-- Container for all three tools with videos -->
  <div class="tools-container">

    <!-- ASTRO -->
    <div class="video-container" onclick="location.href='{% link astro.md %}'">
      <div class="video-text">
        <p><strong><h3>ASTRO</h3></strong> simulates complex realistic astrocytes based on 3D two-photon and EM data</p>
      </div>
      <video loop autoplay muted>
        <source src="assets/Astro.mp4" type="video/mp4">
        Your browser does not support MP4 videos.
      </video>
    </div>

    <!-- BRAINCELL -->
    <div class="video-container" onclick="location.href='{% link braincell.md %}'">
      <div class="video-text">
      <p><strong><h3>BRAINCELL</h3></strong> simulates realistic brain cells with stochastic nano-properties and interactive 3D environment</p>
      </div>
      <br><br>
      <video loop autoplay muted>
        <source src="assets/BrainCellSpine.mp4" type="video/mp4">
        Your browser does not support MP4 videos.
      </video>
    </div>

    <!-- ARACHNE -->
    <div class="video-container" onclick="location.href='{% link arachne.md %}'">
      <div class="video-text">
        <p><strong><h3>ARACHNE</h3></strong> simulates spiking neuronal networks with volume transmission</p>
      </div>
      <br><br>
      <video loop autoplay muted>
        <source src="assets/Arachne.mp4" type="video/mp4">
        Your browser does not support MP4 videos.
      </video>
    </div>
  </div>
