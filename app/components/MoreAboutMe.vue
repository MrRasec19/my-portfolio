<template>
  <div class="grid grid-cols-1 gap-12 lg:gap-16 items-start lg:px-12">
    <div class="flex md:flex-row flex-col w-full justify-around">
      <div class="w-full text-md md:text-xl text-left md:pr-5 md:mt-0 mb-5">
        If you find me outside of the code, chances are I'm glued to a screen or
        sitting in a stadium. I'm a self-proclaimed sports fanatic, and my heart
        unequivocally belongs to Baseball. Baseball isn't just a hobby; it’s a
        tradition that has been with me since I was a kid (I used to play!).
        Today, I enjoy the thrill from the stands or my couch, closely following
        my favorite teams in both the Major Leagues (MLB) and the Mexican
        Pacific League (LMP). But the full experience happens at home. If you're
        ever in Hermosillo, Sonora (my hometown), you'll almost certainly find
        me at the ballpark—not just for the game, but for the electrifying
        atmosphere, the taste of local food, and the sheer joy of sharing those
        epic moments with family and friends. To me, it’s the perfect pitch of
        social life: great company, the sound of strikeouts, and a cold beer.
      </div>
      <div class="flex justify-center lg:justify-start">
        <NuxtImg
          src="/imgs/me-at-baseball.webp"
          alt="Rasec Camacho"
          width="500"
          height="500"
          loading="lazy"
          class="rounded-sm object-cover aspect-square"
        />
      </div>
    </div>
    <div class="flex md:flex-row flex-col w-full justify-around">
      <div class="flex justify-center lg:justify-start">
        <video
          class="rounded-sm object-cover w-full aspect-square"
          loading="lazy"
          src="/videos/me-hitting.webm"
          autoplay
          loop
          muted
          playsinline
        ></video>
      </div>
      <div class="text-left text-md md:text-xl md:pl-5 w-full md:mt-0 mt-5">
        When it’s time to disconnect and recharge, I head straight for the
        diamond. My favorite escape is Slow Pitch; it’s not the highly
        competitive hardball you see in the major leagues, but a variation of
        softball that prioritizes fun, camaraderie, and a slower pace. I’ve been
        playing for a little over a year on various teams, and what truly
        captivates me is the atmosphere. It’s a purely recreational space, the
        perfect reason to step away from the monitor and enjoy the outdoors.
        It’s the sheer joy of laughing with friends and family on the field,
        getting some exercise without the pressure of high-stakes competition,
        and feeling the satisfaction of a solid hit after a long week of work.
        It’s a simple passion that allows me to be part of a team outside the
        office. If you're looking for a way to share a great time and burn off
        some energy while trying to catch a fly ball, slow pitch is definitely
        the way to go.
      </div>
    </div>
  </div>
</template>

<style scoped>
.object-img {
  object-position: 0px 200px;
}
</style>
