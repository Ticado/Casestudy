<script>
export default {
  data: (vm) => ({
    items: [],
  }),
  async created() {
    this.items = await fetch(`http://localhost:5002/posts`).then((e) =>
      e.json()
    );
  },
};
</script>




<template>
  <v-app style="background: #f4f7f6 0% 0% no-repeat">
    <v-main>
      <v-container>
        <Title class="pb-3">Overzicht van je rewards</Title>
        <p class="pb-4">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus.
        </p>

        <v-container class="container--cards">
          <v-row>
            <v-col :sm="12" :md="3" style="max-width: 285px">
              <LeftCard>
                <LeftCardTop>
                  <div>Persoonlijke punten</div>
                  <FeaturedCardStat class="pb-4">32</FeaturedCardStat>
                </LeftCardTop>
                <LeftCardBadge class="Coin">
                  <div class="LeftCardBadge__img"></div>
                </LeftCardBadge>
                <v-card-text align="center" style="font-weight: bold">
                  BEHAALDE PUNTEN
                  <VanTot>
                    <v-row>
                      <v-col>
                        Van <br />
                        2020
                      </v-col>
                      <VanTotBorder> </VanTotBorder>
                      <v-col>
                        Tot <br />
                        ...
                      </v-col>
                    </v-row>
                  </VanTot>
                </v-card-text>

                <v-card-text>
                  <Badge></Badge>
                  <v-divider style="border-color: #6DC8BF " class="pb-2"></v-divider>
                  <Badge />
                  <v-divider style="border-color: #6DC8BF " class="pb-2"></v-divider>
                  <Badge />
                  <v-divider style="border-color: #6DC8BF " class="pb-2"></v-divider>
                </v-card-text>
              </LeftCard>
            </v-col>

            <v-col :cols="9" :md="9"  margin>
              <h1 style="color: #00504a">Behaalde badges</h1>
              <p class="pb-10">
                Allemaal tekst die ik niet ga schrijven lol haha xd
              </p>
              <v-row>
                <v-col cols="4"  v-for="(item, index) in items" :key="index">
                  <FeaturedCard>
                    <FeaturedCardTop :class="item.backgroundTop">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages :class="item.badge">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar></ProgressBar>
                    <v-card-text align="center">
                     <div style="font-weight: bold"> {{item.title}} </div>
                    <div>Je hebt {{item.progress}} van de 5 {{item.title}} afgerond. Rond er 5 af en verdien de {{item.badge}} badge!</div>
                    </v-card-text>
                  </FeaturedCard>
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
                </v-col>

              </v-row>
              <v-col :cols="12" md="auto grow" margin>
                <h1 style="color: #00504a">Nog te behalen badges</h1>
                <p class="pb-10">
                  Allemaal tekst die ik niet ga schrijven lol haha xd
                </p>
                <v-row>
                  <v-col>
                    <FeaturedCard>
                      <FeaturedCardTop class="locked">
                        <div class="FeaturedCardTop__img"></div>
                      </FeaturedCardTop>
                      <BadgeImages class="locked">
                        <div class="BadgeImages__img"></div>
                      </BadgeImages>
                      <ProgressBarLocked></ProgressBarLocked>
                      <v-card-text align="center">
                        <div style="font-weight: bold"></div>
                        <div>blablablabla</div>
                      </v-card-text>
                    </FeaturedCard>
                  </v-col>

                  <v-col>
                    <FeaturedCard>
                      <FeaturedCardTop class="locked">
                        <div></div>
                        <div class="FeaturedCardTop__img"></div>
                      </FeaturedCardTop>
                      <BadgeImages class="locked">
                        <div class="BadgeImages__img"></div>
                      </BadgeImages>
                      <ProgressBarLocked></ProgressBarLocked>
                      <v-card-text align="center">
                        <div style="font-weight: bold"></div>
                        <div>blablablabla</div>
                      </v-card-text>
                    </FeaturedCard>
                  </v-col>

                  <v-col>
                    <FeaturedCard>
                      <FeaturedCardTop class="locked">
                        <div class="FeaturedCardTop__img"></div>
                      </FeaturedCardTop>
                      <BadgeImages class="locked">
                        <div class="BadgeImages__img"></div>
                      </BadgeImages>
                      <ProgressBarLocked></ProgressBarLocked>
                      <v-card-text align="center">
                        <div style="font-weight: bold"></div>
                        <div>blablablabla</div>
                      </v-card-text>
                    </FeaturedCard>
                  </v-col>
                </v-row>
              </v-col>
            </v-col>
          </v-row>
        </v-container>
      </v-container>
      <BackgroundShapeBottom class="BottomShape--left"> </BackgroundShapeBottom>
      <BackgroundShapeBottom class="BottomShape--right"> </BackgroundShapeBottom>
    </v-main>
  </v-app>
</template>

<style>
.container--cards {
  max-width: 30px 345px 00px 345px;
}
</style>
