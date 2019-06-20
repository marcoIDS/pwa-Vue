<template>
  <v-container>
    <v-layout row>
      <v-flex xs12 sm3 pa-2>
        <v-card>
          <v-img
            src="https://www.dondeir.com/wp-content/uploads/2017/03/buffet-de-pizzas-en-cdmx-como-todo-que-puedas-por-149-pesos-3-1024x767.jpg"
            height="200px"
          >
          </v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Pepperoni</div>
              <span class="green--text">$128.99</span>
            </div>
          </v-card-title>

          <v-card-actions>
            <!-- <v-btn flat>Share</v-btn> -->
            <v-btn flat color="purple" :to="{ name: 'order', params: { id: 1 }}">Ordenar</v-btn>
            <!-- <router-link flat color="purple" :to="{ name: 'order', params: { userId: 1 }}">Ordenar</router-link> -->
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 sm3 pa-2>
        <v-card>
          <v-img
            src="https://los40mx00.epimg.net/los40/imagenes/2017/02/24/yaparate/1487951977_108801_1487952114_noticia_normal.jpg"
            height="200px"
          >
          </v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Hawaiana</div>
              <span class="green--text">$129.99</span>
            </div>
          </v-card-title>

          <v-card-actions>
            <!-- <v-btn flat>Share</v-btn> -->
            <v-btn flat color="purple" :to="{ name: 'order', params: { id: 2 }}">Ordenar</v-btn>
            <!-- <router-link flat color="purple" :to="{ name: 'order', params: { userId: 1 }}">Ordenar</router-link> -->
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 sm3 pa-2 >
        <v-card>
          <v-img
            src="https://www.la-mejor-receta.com/imagenes/recetas/pizza52.jpg"
            height="200px"
          >
          </v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Mexicana</div>
              <span class="green--text">$129.99</span>
            </div>
          </v-card-title>

          <v-card-actions>
            <!-- <v-btn flat>Share</v-btn> -->
            <v-btn flat color="purple" :to="{ name: 'order', params: { id: 3 }}">Ordenar</v-btn>
            <!-- <router-link flat color="purple" :to="{ name: 'order', params: { id: 1 }}">Ordenar</router-link> -->
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 sm3 pa-2 >
        <v-card>
          <v-img
            src="https://thermomix-alcala.es/media/Posts/attachments/b967bde382c7fdbb3703f9005ec21720.jpg"
            height="200px"
          >
          </v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Champiñones</div>
              <span class="green--text">$125.99</span>
            </div>
          </v-card-title>

          <v-card-actions>
            <!-- <v-btn flat>Share</v-btn> -->
            <v-btn flat color="purple" :to="{ name: 'order', params: { id: 4 }}">Ordenar</v-btn>
            <!-- <router-link flat color="purple" :to="{ name: 'order', params: { userId: 1 }}">Ordenar</router-link> -->
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 sm3 pa-2 >
        <v-card>
          <v-img
            src="https://d1bi2srgse3uhl.cloudfront.net/uploads/2018/04/image5ad7965c3aa98.jpg"
            height="200px"
          >
          </v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Argentina</div>
              <span class="green--text">$125.99</span>
            </div>
          </v-card-title>

          <v-card-actions>
            <!-- <v-btn flat>Share</v-btn> -->
            <v-btn flat color="purple" :to="{ name: 'order', params: { id: 5 }}">Ordenar</v-btn>
            <!-- <router-link flat color="purple" :to="{ name: 'order', params: { userId: 1 }}">Ordenar</router-link> -->
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>

      <v-flex xs12 sm3 pa-2 >
        <v-card>
          <v-img
            src="https://i.ytimg.com/vi/6jNMinJKE40/maxresdefault.jpg"
            height="200px"
          >
          </v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Vegetariana</div>
              <span class="green--text">$139.99</span>
            </div>
          </v-card-title>

          <v-card-actions>
            <!-- <v-btn flat>Share</v-btn> -->
            <v-btn flat color="purple" :to="{ name: 'order', params: { id: 6 }}">Ordenar</v-btn>
            <!-- <router-link flat color="purple" :to="{ name: 'order', params: { userId: 1 }}">Ordenar</router-link> -->
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>

    </v-layout>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      show:false
    })
  }
</script>

<style>

</style>
