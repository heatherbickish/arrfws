<script setup>


</script>

<template>
  <!-- SECTION Hero img -->
  <section class="container-fluid puppy-bg">
    <div class="row mt-4 justify-content-between">
      <div class="col-md-5">
        <div>
          <img src="/public/img/puppy.png" alt="" class="puppy-img">
        </div>
      </div>
      <div class="col-md-5 text-light">
        <div class="mt-5">
          <h5>OUR PURPOSE:</h5>
          <h1 class="mt-5">
            The Animal Adoption <br> and Rescue Foundation <br> (AARF) exists to <br> improve the lives of <br>cats and
            dogs while <br> strengthening the <br> human-animal bond.
          </h1>
          <div class="mt-5">
            <button class="btn bg-light rounded-pill px-4 py-3 fw-bold orangecicle">LEARN MORE</button>
          </div>
        </div>
      </div>
    </div>
  </section>
  e
  <!-- SECTION  Get Involved -->
  <section class="container-fluid">
    <div class="row mt-5 justify-content-center align-items-center">
      <div class="col-md-3">
        <div class="mt-5">
          <h1>Get Involved</h1>
        </div>
      </div>
      <div class="col-md-6">
        <div class="mt-5">
          <p class="involved-p fs-5">There are many ways you can make an impact. Adopt, Foster, Volunteer, or Donate.
            See
            what is right for
            you.
            We appreciate your interest.</p>
        </div>
      </div>
    </div>

    <!-- SECTION Get Involved pics and text -->
    <div class="row justify-content-center gap-2 mt-5">
      <div class="col-md-3">
        <div class="mt-5">
          <img
            src="https://images.unsplash.com/photo-1522276498395-f4f68f7f8454?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="" class="involved-img">
        </div>
        <div class="mt-5">
          <h5 class="orange">ADOPT</h5>
        </div>
        <div class="mt-4">
          <em>
            <p class="img-p">Looking for a new furry family member? Thank you for thinking about adopting from a
              rescue
              organization.
              Each adoption saves two lives: the one you adopt and the space you've opened up for another animal to be
              helped. You will be your new pet's hero!
            </p>
          </em>
        </div>
        <div class="text-center mt-4">
          <button class="btn rounded-pill bg-orange text-light py-2 px-3">LEARN MORE ABOUT ADOPTING</button>
        </div>
      </div>
      <div class="col-md-3">
        <div class="mt-5">
          <img
            src="https://images.unsplash.com/photo-1612957775937-8157953886f5?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="" class="involved-img">
        </div>
        <div class="mt-5">
          <h5 class="orange">FOSTER</h5>
        </div>
        <div class="mt-4">
          <em>
            <p class="img-p">Providing a temporary home for a cat or dog is a gift that keeps on giving. Animals that
              are fostered become more adoptable because of all the love, care and attention they are given. This is
              where they learn to trust again. Opening you doors to a homeless pet is rewarding beyond words.
            </p>
          </em>
        </div>
        <div class="text-center mt-4">
          <button class="btn rounded-pill bg-orange text-light py-2 px-3">LEARN MORE ABOUT FOSTERING</button>
        </div>
      </div>
      <div class="col-md-3">
        <div class="mt-5">
          <img
            src="https://images.unsplash.com/photo-1493101561740-e745892775b2?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="" class="involved-img">
        </div>
        <div class="mt-5">
          <h5 class="orange">VOLUNTEER</h5>
        </div>
        <div class="mt-4">
          <em>
            <p class="img-p">AARF volunteers make a <b>BIG DIFFERENCE.</b> They are a remarkable community of
              knowledgable, caring and didicated group who welcome everyone who wants to pitch in. New faces are always
              appreciated. Please check out the many opportunities for you to contribute.
            </p>
          </em>
        </div>
        <div class="text-center mt-4">
          <button class="btn rounded-pill bg-orange text-light py-2 px-3">LEARN MORE ABOUT VOLUNTEERING</button>
        </div>
      </div>
    </div>
  </section>


</template>

<style scoped lang="scss">
.puppy-img {
  height: 40rem;
}

.involved-p {
  line-height: 30px;
}

.img-p {
  line-height: 30px;
}

h1 {
  line-height: 50px;
}

.involved-img {
  height: 16rem;
  width: 100%;
  object-fit: cover;
  object-position: center;
}
</style>
