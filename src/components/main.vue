<template>
  <!-- eslint-disable max-len -->
  <main>
    <section class="section-header relative w-full min-h-screen bg-cover bg-no-repeat bg-center flex flex-col items-center justify-center">
      <img src="../assets/desktop/image-header.jpg" alt="Image Header" class="w-full min-h-screen object-cover">

      <div class="absolute flex flex-col items-center gap-y-24 top-44">
        <h1 class="uppercase font-black text-4xl md:text-5xl text-white text-center">
          We Are Creatives
        </h1>

        <img src="../assets/icon-arrow-down.svg" alt="Icon Arrow Down">
      </div>
    </section>

    <!-- Content -->
    <section class="flex flex-col-reverse md:flex-row text-center md:text-left">
      <div class="w-full min-h-full flex items-center justify-center">
        <div class="flex flex-col justify-between gap-y-8 w-3/5 my-20 md:my-8">
          <h2 class="font-black text-4xl text-gray-700">
            Transform your brand
          </h2>

          <p class="text-gray-400">
            We are a full-service creative agency specializing in helping brands grow fast. Engage your clients through compelling visuals that do most of the marketing for you.
          </p>

          <a href="#" class="egg relative uppercase text-gray-700 w-32 text-center mx-auto md:mx-0">
            Learn more
          </a>
        </div>
      </div>

      <div class="w-full min-h-full">
        <img src="../assets/desktop/image-transform.jpg" alt="An Egg" class="w-full h-full object-cover object-center">
      </div>
    </section>

    <section class="flex flex-col md:flex-row">
      <div class="w-full min-h-full">
        <img src="../assets/desktop/image-stand-out.jpg" alt="A Glass" class="w-full h-full object-cover object-center">
      </div>

      <div class="w-full min-h-full flex items-center justify-center text-center md:text-left">
        <div class="flex flex-col justify-between gap-y-8 w-3/5 my-20 md:my-8">
          <h2 class="font-black text-4xl text-gray-700">
            Stand out to the right audience
          </h2>

          <p class="text-gray-400">
            Using a collaborative formula of designers, researchers, photographers, videographers, and copywriters, we’ll build and extend your brand in digital places.
          </p>

          <a href="#" class="glass relative uppercase text-gray-700 w-32 text-center mx-auto md:mx-0">
            Learn more
          </a>
        </div>
      </div>
    </section>

    <section class="flex flex-col md:flex-row">
      <div class="relative w-full min-h-full -mr-px">
        <img src="../assets/desktop/image-graphic-design.jpg" alt="Cherry" class="w-full h-screen md:h-full object-cover object-center">

        <div class="absolute bottom-12 w-full flex justify-center">
          <div class="w-96 text-center">
            <h3 class="font-black text-2xl text-green-900 mb-6">
              Graphic design
            </h3>

            <p class="text-green-800 opacity-90 w-11/12 mx-auto tracking-tighter">
              Great design makes you memorable. We deliver artwork that underscores your brand message and captures potential clients’ attention.
            </p>
          </div>
        </div>
      </div>

      <div class="relative w-full min-h-full">
        <img src="../assets/desktop/image-photography.jpg" alt="Cherry" class="w-full h-screen md:h-full object-cover object-center">

        <div class="absolute bottom-12 w-full flex justify-center">
          <div class="w-80 text-center">
            <h3 class="font-black text-2xl text-green-900 mb-6">
              Photography
            </h3>

            <p class="text-green-800 opacity-90 mx-auto tracking-tighter">
              Increase your credibility by getting the most stunning, high-quality photos that improve your business image.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="testimonials text-center pt-20 md:pt-28 pb-32 px-4 min-h-screen">
      <h2 class="uppercase font-black text-gray-400 text-lg mb-16">
        Client Testimonials
      </h2>

      <div class="card-list flex flex-col md:flex-row gap-x-8 gap-y-12 justify-center items-center">
        <article class="flex flex-col items-center w-80 gap-y-16">
          <img src="../assets/image-emily.jpg" alt="Emily R." class="rounded-full w-16">

          <p class="text-gray-500">
            We put our trust in Sunnyside and they delivered, making sure our needs were met and deadlines were always hit.
          </p>

          <div>
            <h3 class="font-black">
              Emily R.
            </h3>
            <span class="text-gray-400 font-semibold text-xs">
              Marketing Director
            </span>
          </div>
        </article>

        <article class="flex flex-col items-center w-80 gap-y-16">
          <img src="../assets/image-thomas.jpg" alt="Thomas S." class="rounded-full w-16">

          <p class="text-gray-500">
            Sunnyside’s enthusiasm coupled with their keen interest in our brand’s success made it a satisfying and enjoyable experience.
          </p>

          <div>
            <h3 class="font-black">
              Thomas S.
            </h3>
            <span class="text-gray-400 font-semibold text-xs">
              Chief Operating Officer
            </span>
          </div>
        </article>

        <article class="flex flex-col items-center w-80 gap-y-16">
          <img src="../assets/image-jennie.jpg" alt="Jennie F." class="rounded-full w-16">

          <p class="text-gray-500">
            Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly recommended!
          </p>

          <div>
            <h3 class="font-black">
              Jennie F.
            </h3>
            <span class="text-gray-400 font-semibold text-xs">
              Business Owner
            </span>
          </div>
        </article>
      </div>
    </section>

    <section class="grid grid-cols-2 grid-rows-2 md:grid-cols-4 md:grid-rows-1">
      <img src="../assets/desktop/image-gallery-milkbottles.jpg" alt="Milk Bottles">
      <img src="../assets/desktop/image-gallery-orange.jpg" alt="Orange">
      <img src="../assets/desktop/image-gallery-cone.jpg" alt="Cones">
      <img src="../assets/desktop/image-gallery-sugarcubes.jpg" alt="Sugar Cubes">
    </section>

  </main>
</template>

<script>
export default {

};
</script>

<style scoped lang="scss">

section {
  font-family: 'Fraunces', serif;
  // background-image: url(../assets/desktop/image-header.jpg);

  div {
    h1 {
      letter-spacing: 0.5rem;
    }

    p {
      font-family: 'Barlow', sans-serif;
    }

    a::after {
      content: "";
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 8px;
      opacity: 0.3;
      z-index: -10;
      border-radius: 10px;
      transition: 0.2s;
    }

    a:hover::after {
      opacity: 1;
    }

    a.egg::after {
      background-color: hsl(51, 100%, 49%);
    }

    a.glass::after {
      background-color: hsl(7, 99%, 70%);
    }
  }

  &.testimonials {
    h2 {
      letter-spacing: 5px;
    }

    .card-list {
      article {
        span {
          font-family: 'Barlow', sans-serif;
        }
      }
    }
  }
}

</style>
