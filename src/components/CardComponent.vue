<script>
</script>

<template>
    {{  }}
  <q-card bordered class="q-ma-md" flat>
    <q-card-section class="text-center text-h5" style="background-color: rgb(200, 190, 156)">
      {{  }}
    </q-card-section>
    <q-card-section class="text-h7" style="background-color: rgb(255, 228, 196)">
      <ul>
        <li>
          <span>Szin: </span><b>{{  }}</b>
        </li>
        <li>
          <span>Évjárat: </span><b>{{  }}</b>
        </li>
        <li>
          <span>Hengerűrtartalom: </span><b>{{  }} cm<sup>2</sup></b>
        </li>
        <li>
          <span>Hirdetés dátuma: </span><b>{{  }}</b>
        </li>
      </ul>
    </q-card-section>
    <!-- <q-card-section class="" style="background-color: rgb(200, 190, 156)">
      <div class="text-h7 text-justify">{{ toggled ? displayText : slicedText }}</div>
      <hr />
      <q-toggle
        v-model="toggled"
        color="dark-blue"
        :disable="displayText.length <= 100"
        label="Teljes hirdetés"
        @update:model-value="handleToggle"
      />
    </q-card-section>
    <q-card-section v-if="kepek.length == 1" style="background-color: rgb(255, 228, 196)">
      <div class="q-img q-img--menu" role="img" style="max-height: 200px">
        <div style="padding-bottom: 75%"></div>
        <div class="q-img__container absolute-full">
          <img
            aria-hidden="true"
            class="q-img__image q-img__image--with-transition q-img__image--loaded"
            draggable="false"
            fetchpriotity="auto"
            loading="lazy"
            :src="kepek[0]"
            style="object-fit: scale-down; object-position: 50% 50%"
          />
        </div>
      </div>
    </q-card-section>
    <q-card-section v-if="kepek.length != 1" style="background-color: rgb(255, 228, 196)">
      <q-carousel v-model="slide" style="height: 200px" thumbnails>
        <q-carousel-slide v-for="(item, idx) in kepek" :key="idx" :img-src="kepek[idx]" :name="idx + 1" />
      </q-carousel>
    </q-card-section>

    <q-card-section style="background-color: rgb(200, 190, 156)">
      <div v-for="(item, id) in kepek" :key="id" class="text-h7 text-justify">{{ slide - 1 }} - {{ item }}</div>
    </q-card-section>
    <q-card-actions class="justify-center" style="background-color: rgb(255, 228, 196)">
      <q-btn
        class="bg-green-3"
        label="Hirdetés szerkesztése"
        no-caps
        type="button"
        @click="$emit('editDialog')"
      ></q-btn>
    </q-card-actions> -->
  </q-card>
</template>
<style lang="sass" scoped></style>