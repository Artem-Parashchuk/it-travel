<script setup>
import FavoritePlaceBtn from './FavoritePlaceBtn.vue'
import DeleteIcon from './DeleteIcon.vue'
import EditIcon from './EditIcon.vue'
</script>

<template>
  <section class="text-grey mb-6 last:mb-0">
    <div class="flex gap-4">
      <img class="w-[76px] h-[76px] shrink-0" src="" alt="" />
      <div>
        <div class="flex justify-between items-center mb-2">
          <h2 class="font-bold text-sm text-[#2c2c2c]">Палац Спорту</h2>
          <div class="flex gap-2">
            <FavoritePlaceBtn><EditIcon /></FavoritePlaceBtn>
            <FavoritePlaceBtn><DeleteIcon /></FavoritePlaceBtn>
          </div>
        </div>
        <p class="text-xs line-clamp-3">
          Київський палац спорту (КПС) - найбільша крита споруда розташована у центральній частині
          міста Київ, біля підніжжя
        </p>
      </div>
    </div>

    <div class="h-[1px] w-full bg-[#ececec] mt-4"></div>
  </section>
</template>
