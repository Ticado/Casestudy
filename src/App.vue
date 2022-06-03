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
            <v-col :sm="12" style="max-width: 285px">
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

            <v-col :cols="12" md="auto grow" margin>
              <h1 style="color: #00504a">Behaalde badges</h1>
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
                    <ProgressBar></ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
                </v-col>

                <v-col>
                  <FeaturedCard>
                    <FeaturedCardTop class="plat">
                      <div class="FeaturedCardTop__img"></div>
                    </FeaturedCardTop>
                    <BadgeImages class="plat">
                      <div class="BadgeImages__img"></div>
                    </BadgeImages>
                    <ProgressBar> </ProgressBar>
                    <v-card-text align="center">
                      Tekst
                      <div>blablablabla</div>
                    </v-card-text>
                  </FeaturedCard>
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
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
                  <FeaturedCardBottom align="center">
                    <v-card-text> Behaald op ??-??-?? </v-card-text>
                  </FeaturedCardBottom>
                </v-col>

                <v-col> </v-col>

                <v-col> </v-col>
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
                        Tekst
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
                        Tekst
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
                        Tekst
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
<script>


export default 
  {
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
