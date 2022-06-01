<template>
  <v-app>
    <v-main>
      <v-container>
        <Title>Overzicht van je rewards</Title>
        Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
        eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
        voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
        clita kasd gubergren, no sea takimata sanctus.

        <v-container class="container--cards">
          <v-row>
            <v-col :sm="12" style="max-width: 285px">
              <FeaturedCard>
                <FeaturedCardTop>
                  <div>Persoonlijke punten</div>
                  <FeaturedCardStat>32</FeaturedCardStat>
                  <div align="center" md="auto grow">
                    <v-img
                      max-height="60"
                      max-width="60"
                      src="PNG/Coin.png"
                    ></v-img>
                  </div>
                </FeaturedCardTop>
                <v-card-text align="center"> Behaalde punten </v-card-text>
                <v-card-text>
                  <Badge />
                  <v-divider></v-divider>
                  <Badge />
                  <v-divider></v-divider>
                  <Badge />
                  <v-divider></v-divider>
                </v-card-text>
              </FeaturedCard>
            </v-col>

            <v-col :cols="12" md="auto grow">
              <v-card> Behaalde badges </v-card>

              <v-row>
                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="locked">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="locked">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar></ProgressBar>
                    <v-card-text align="center"> 2/5 </v-card-text>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="bronze">
                      <div></div>
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="bronze">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="silver">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="silver">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>
              </v-row>

              <v-row>
                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="gold">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="gold">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="plat">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="plat">
                      <div class="BadgeImages__img "></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="blue">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="bblue">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>
              </v-row>

              <v-row>
                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="red">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="bred">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="green">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="bgreen">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="pink">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="bpink">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>
              </v-row>

              <v-row>
                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="purple">
                      <div class="FeaturedCardTop__img"></div>
                      
                      
                    </FeaturedCardTop>
                    <BadgeImages class="bpurple">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                </v-col>

                <v-col> </v-col>

                <v-col> </v-col>
              </v-row>
            </v-col>
          </v-row>
        </v-container>
      </v-container>
    </v-main>
  </v-app>
</template>
<script>
export default {
  randomColor() {
    let colors = ["Red", "purple", "Green", "blue", "yellow", "orange"];
    return colors[Math.floor(math.random() * colors.length)];
  },
};
</script>
<style>
.container--cards {
  max-width: 30px 345px 00px 345px;
}
</style>
