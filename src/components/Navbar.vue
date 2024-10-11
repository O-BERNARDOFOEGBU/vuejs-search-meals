<Template>
   <header class="bg-white shadow-md h-16 flex justify-between items-stretch">
      <router-link
        :to="{ name: 'home' }"
        class="inline-flex items-center px-5 h-full"
      >
        Home
      </router-link>
      <div class="flex items-center gap-1">
        <router-link
          :to="{ name: 'byName' }"
          class="inline-flex items-center px-2 h-full transistion-colors hover:bg-purple-100"
        >
          Search Meals
        </router-link>
        <router-link
          :to="{ name: 'byLetter' }"
          class="inline-flex items-center px-2 h-full transistion-colors hover:bg-purple-100"
        >
          Meals By letter
        </router-link>
        <router-link
          :to="{ name: 'byIngredient' }"
          class="inline-flex items-center px-2 h-full transistion-colors hover:bg-purple-100"
        >
          Meals By Ingredients
        </router-link>
      </div>
    </header>
</Template>
