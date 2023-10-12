<script>
import {goto} from '$app/navigation';
import Navbar from '../utils/Navbar.svelte';



</script>

  

<Navbar />
<main>
    <div>
    <section class="relative flex h-[80vh] shrink-0 flex-col items-center justify-center">
        <video class="absolute -z-10 w-full h-full object-cover blur-sm saturated" muted autoplay loop playsinline disablepictureinpicture>
            <source src="/video.mp4" type="video/mp4" />
          </video>
        <h1 class="text-3xl font-bold underline text-white">I Am Yap Heng Jian</h1>

        <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
        <a href="/about">About my site</a>

      </section>

      </div>

    

</main>
