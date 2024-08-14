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
      max-width: 1200px
    }
    .image-collection img {
    max-width: 300px;
    max-height: 300px;
    border-radius: 10px;
    object-fit: cover;
    transition: transform 0.3s ease; /* Add transition for smooth scaling */
  }
  .image-collection a:hover img {
    transform: scale(1.1); /* Scale the image to 110% on hover */
  }
  </style>
  
  <div class="image-collection">
    {#each images as {src, url}}
    <a href={url} target="_blank">
      <img src={src} alt="" />
    </a>
    {/each}
  </div>
  