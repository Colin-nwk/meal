<template>
  <v-container grid-list-lg>
    <v-layout row>
      <v-flex xs12 class="text-xs-center display-1 font-weight-black my-5">Available Meal Plans</v-flex>
    </v-layout>
    <v-layout row wrap>
      <v-flex xs12 md4>
        <v-card>
          <v-img src hight="500px">
            <v-container fill-height fluid>
              <v-layout fill-height>
                <v-flex xs12 align-end flexbox>
                  <span class="headline white--text">KETO</span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-img>
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-0">Keto</h3>
              <div>Mollitia sapiente perspiciatis labore odio eaque unde fugiat eos voluptates, dicta,</div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <v-img src hight="500px">
            <v-container fill-height fluid>
              <v-layout fill-height>
                <v-flex xs12 align-end flexbox>
                  <span class="headline white--text">PALEO</span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-img>
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-0">Paleo</h3>
              <div>Lorem, ipsum dolor sit amet consectetur adipisicing elit.dipisicing elitdipisicing elit</div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <v-img src hight="500px">
            <v-container fill-height fluid>
              <v-layout fill-height>
                <v-flex xs12 align-end flexbox>
                  <span class="headline white--text">VEGAN</span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-img>
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-0">Vegan</h3>
              <div>atque, id eveniet temporibus consequuntur nihil! Quia eveniet laborum deleniti dolorem!</div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "HomePlans"
};
</script>
