<template>
  <v-container fluid grid-list-md>


  <v-carousel style="height:350px">
    <v-carousel-item v-for="(item,i) in items" :src="item.src" :key="i"></v-carousel-item>
  </v-carousel>


    <v-layout row wrap>

      <v-flex d-flex xs12 sm6 md4>
        <v-layout row wrap>
          
          <v-flex d-flex>

<!-- 
            <v-card color="purple lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
 -->
           <v-card color="purple lighten-1" class="white--text">
              <v-container fluid grid-list-lg>
                <v-layout row>
                        <v-flex xs5>
                    <v-card-media
                      src="/static/img/3.jpg"
                      height="125px"
                      contain
                    ></v-card-media>
                  </v-flex>
                  <v-flex xs7>
                    <div>
                      <div class="headline">This is the title</div>
                      <div>This is where the content of the post will go and on click of this tile we will get the details of full post. There will be alink for like and share</div>
                    </div>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-card>



          </v-flex>
          
          <v-flex d-flex>
            <v-card color="purple lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>

          <v-flex d-flex>
            <v-card color="purple lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>

          <v-flex d-flex>
            <v-card color="purple lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>

          <v-flex d-flex>
            <v-card color="purple lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>

        </v-layout>
      </v-flex>

      <v-flex d-flex xs12 sm6 md4>
        <v-layout row wrap>



          
          <v-flex d-flex>

          <v-card color="light-blue lighten-1" class="white--text">
              <v-container fluid grid-list-lg>
                <v-layout row>
                        <v-flex xs5>
                    <v-card-media
                      src="/static/img/3.jpg"
                      height="125px"
                      contain
                    ></v-card-media>
                  </v-flex>
                  <v-flex xs7>
                    <div>
                      <div class="headline">This is the title</div>
                      <div>This is where the content of the post will go and on click of this tile we will get the details of full post. There will be alink for like and share</div>
                    </div>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-card>

<!-- 
            <v-card color="light-blue lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
 -->
           </v-flex>
          
         
         <v-flex d-flex>
            <v-card color="light-blue lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>
         
          <v-flex d-flex>
            <v-card color="light-blue lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>
        
          <v-flex d-flex>
            <v-card color="light-blue lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>
        
        <v-flex d-flex>
            <v-card color="light-blue lighten-1" dark>
              <v-card-text
              v-text="lorem.slice(0, 170)">
              </v-card-text>
            </v-card>
          </v-flex>
        


        </v-layout>
      </v-flex>



      <v-flex d-flex xs12 sm6 md4 child-flex>
        <v-card color="indigo" dark>
          <v-card-text
          v-text="lorem.slice(0, 90)">
          </v-card-text>
        </v-card>
      </v-flex>
      
   
    </v-layout>



    <v-layout row wrap>

      <v-flex d-flex xl12 sm6 md8>
        <v-layout row wrap>
          
          <v-flex d-flex>
            <v-card color="teal lighten-1" dark>
              <v-card-text
              v-text="lorem">
              </v-card-text>
            </v-card>
          </v-flex>
          <v-flex d-flex>
            <v-card color="deep-orange lighten-1" dark>
              <v-card-text
              v-text="lorem">
              </v-card-text>
            </v-card>
          </v-flex>

        </v-layout>
      </v-flex>

      <v-flex d-flex xs12 sm6 md4>
        <v-layout row wrap>
          
        <v-flex d-flex>
            <v-card color="gray lighten-1" dark>
              <v-card-text
              v-text="lorem + lorem + lorem ">
              </v-card-text>
            </v-card>
          </v-flex>
        <v-flex d-flex>
            <v-card color="gray lighten-1" dark>
              <v-card-text
              v-text="lorem + lorem + lorem ">
              </v-card-text>
            </v-card>
          </v-flex>


        </v-layout>
      </v-flex>

   
    </v-layout>

  </v-container>
</template> 
<script>
  export default {
    data: () => ({
      lorem: `Lorem ipsum dolor sit amet, mel at clita quando. Te sit oratio vituperatoribus, nam ad ipsum posidonium mediocritatem, explicari dissentiunt cu mea. Repudiare disputationi vim in, mollis iriure nec cu, alienum argumentum ius ad. Pri eu justo aeque torquatos.`,
      items: [
          {
            src: '/static/img/1.jpg'
          },
          {
            src: '/static/img/2.jpg'
          },
          {
            src: '/static/img/3.jpg'
          }
        ]
    })
  }
</script>