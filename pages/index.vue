<template>
<div>
    <v-sheet
    class="mx-auto mb-2"
  >
    <v-slide-group
      show-arrows
    >
      <v-slide-item
        v-for="n in 25"
        :key="n"
        v-slot="{ active, toggle }"
        class="mt-"
      >
        <v-btn
          class="mx-2"
          :input-value="active"
          active-class="grey white--text"
          depressed
          rounded
          @click="toggle"
        >
          {{ keywords[n] }}
        </v-btn>
      </v-slide-item>
    </v-slide-group>
  </v-sheet>
   <!-- <v-card
      class="d-flex flex-row mb-5"
      :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'"
      flat
      tile
    > -->



    <v-row no-gutters>
      <v-card
        v-for="n in 5"
        :key="n"
        class="pl-11 mx-5 my-2"
      >
      <v-responsive
          v-if="n === 2"
          :key="`width-${n}`"
          width="100%" 
        ></v-responsive>
    <v-img class="py-2"
      src="https://www.desicomments.com/wallpapers/wp-content/uploads/2015/07/Call-Of-Duty-Black-Ops-3-Gameplay-600x326.jpg"
      height="170px"
      width="170px"
    ></v-img>

    <v-card-title class="py-4">
      BLURR BURR
    </v-card-title>

    <v-card-subtitle class="pa-0">
      Ryan Kaabel <v-icon>mdi-check-decagram</v-icon>
    </v-card-subtitle>

    <v-card-subtitle class="pa-0">
      1,000 views 30 minutes ago
    </v-card-subtitle>
    </v-card>
    </v-row>





    <v-row no-gutters>
      <v-card
        v-for="n in 5"
        :key="n"
        class="pl-11 mx-5 my-2"
      >
      <v-responsive
          v-if="n === 2"
          :key="`width-${n}`"
          width="100%" 
        ></v-responsive>
    <v-img class="py-2"
      src="https://www.desicomments.com/wallpapers/wp-content/uploads/2015/07/Call-Of-Duty-Black-Ops-3-Gameplay-600x326.jpg"
      height="170px"
      width="170px"
    ></v-img>

    <v-card-title class="py-4">
      BLURR BURR
    </v-card-title>

    <v-card-subtitle class="pa-0">
      Ryan Kaabel <v-icon>mdi-check-decagram</v-icon>
    </v-card-subtitle>

    <v-card-subtitle class="pa-0">
      1,000 views 30 minutes ago
    </v-card-subtitle>
    </v-card>
    </v-row>






    <v-row no-gutters>
      <v-card
        v-for="n in 5"
        :key="n"
        class="pl-11 mx-5 my-2"
      >
      <v-responsive
          v-if="n === 2"
          :key="`width-${n}`"
          width="100%" 
        ></v-responsive>
    <v-img class="py-2"
      src="https://www.desicomments.com/wallpapers/wp-content/uploads/2015/07/Call-Of-Duty-Black-Ops-3-Gameplay-600x326.jpg"
      height="170px"
      width="170px"
    ></v-img>

    <v-card-title class="py-4">
      BLURR BURR
    </v-card-title>

    <v-card-subtitle class="pa-0">
      Ryan Kaabel <v-icon>mdi-check-decagram</v-icon>
    </v-card-subtitle>

    <v-card-subtitle class="pa-0">
      1,000 views 30 minutes ago
    </v-card-subtitle>
    </v-card>
    </v-row>




      <!-- <v-img class="pt-8 py-n1 px-5"
  lazy-src="https://tse3.mm.bing.net/th?id=OIP.oa12mFVrOPHB44YpM51Q4gHaEo&pid=Api&P=0&w=290&h=181"
  max-height="250"
  max-width="249"
  src="https://tse3.mm.bing.net/th?id=OIP.oa12mFVrOPHB44YpM51Q4gHaEo&pid=Api&P=0&w=290&h=181"
></v-img>

<v-sheet class="ms-2 py-1">
      {{ videoTitles[n] }}
      <v-icon
      class="ml-n2">mdi-dots-vertical</v-icon>
      </v-sheet>

<v-img class="pt-8"
  lazy-src="https://wallpapercave.com/uwp/uwp1786365.jpeg"
  max-height="250"
  max-width="249"
  src="https://wallpapercave.com/uwp/uwp1789358.jpeg"
></v-img>

<v-sheet class="ms-2 py-1 font-weight-bold text-subtitle-1">
      {{ videoTitles1[n] }}
      <v-icon
      class="ml-n2 ">mdi-dots-vertical</v-icon>
      <p class="font-weight-light text-subtitle-2">Manny Khoshbin <v-icon>mdi-check-decagram</v-icon></p> 
      <div class="font-weight-thin text-subtitle-2 pt-n5">1234 views 3 weeks ago</div>
      </v-sheet>

<v-img class="pt-8"
  lazy-src="https://wallpapercave.com/uwp/uwp1789358.jpeg"
  max-height="250"
  max-width="249"
  src="https://wallpapercave.com/uwp/uwp1789358.jpeg"
></v-img>

      <v-sheet class="ms-2 py-1">
      {{ videoTitles2[n] }}
      
      
      
      <v-icon
      class="ml-n2">mdi-dots-vertical</v-icon>
      </v-sheet>
      </v-card> -->
      





</div>
</template>
<script>

export default {
  data: () => ({
    keywords: ['Music', 'Mixes', 'COVID', 'Programming', 'League of Legends', 'Cryptocurrency', 'Rap', 'Vue', 'Sander stimmer', 'Tesla', 'Trailers', 'Tools', 'Experiments', 'Outer space', 'Snow'],
    videoTitles: ['','How nft Broke The Internet','Incredible Unknown Facts','8 Little-Known Facts About nft','The nft Guide For Everyone','The Untold Story of nft','What is nft All About?', 'Shining a Light on nft'],
    videoTitles1: ['','My Thoughts on nft','Nft For Beginners','Mastering nft','Mastering nft','Best & Worst nft Trends','A Chat About lol', 'Is lol Dead?'],
    videoTitles2: ['','Travis Scott - 2 MINUTES LATE','Travis Scott - ESCAPE PLAN','Travis Scott - MAFIA','Travis Scott - Blue Chips','Travis Scott - Pull Up','Travis Scott - Astroworld', 'Travis Scott - SICKO MODE'],
  }),
}
</script>

