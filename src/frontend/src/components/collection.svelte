<script lang="ts">
    import { images } from 'lib/images';
  
  </script>
  
  <style>
    .image-collection {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
      justify-content: center;
      margin: 0 auto;
      max-width: 1400px
    }
    .image-collection img {
    max-width: 400px;
    max-height: 400px;
    border-radius: 10px;
    object-fit: cover;
    transition: transform 0.3s ease; /* Add transition for smooth scaling */
  }
  .image-collection a:hover img {
    transform: scale(1.4);
  }
  @media (max-width: 600px) {

    .image-collection a:hover img {
    transform: scale(1);
  }

  }
  </style>
  
  <div class="image-collection">
    {#each images as {src, url}}
    <a href={url} target="_blank">
      <img src={src} alt="" />
    </a>
    {/each}
  </div>
  