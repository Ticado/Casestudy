<template>
  <v-app>
    <v-main>
      <v-container>
        <Title>Overzicht van je rewards</Title>
        Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
        eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
        voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
        clita kasd gubergren, no sea takimata sanctus.

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
                <div>
                  <Badge />
                </div>
                <Badge />
                <Badge />
              </v-card-text>
            </FeaturedCard>
          </v-col>

          <v-col :cols="12" md="auto grow">
            <v-card> Behaalde badges </v-card>

            <v-row>
              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div align="center">
                      <v-img
                        max-height="77"
                        max-width="285"
                        src="PNG/BG-badge-grey.png"
                      ></v-img>
                    </div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_locked.png"
                      ></v-img>
                    </div>
                  </FeaturedCardTop>
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
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_bronze.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text align="center">
                    Tekst
                    <div>blablablabla</div>
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_silver.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
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
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_gold.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text align="center">
                    Tekst
                    <div>blablablabla</div>
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_platinum.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text align="center">
                    Tekst
                    <div>blablablabla</div>
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_blue_werkvormen-afmaken.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
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
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_red_bekijken-opleiding.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text align="center">
                    Tekst
                    <div>blablablabla</div>
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_green_eerste-keer-inloggen.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text align="center">
                    Tekst
                    <div>blablablabla</div>
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_pink_opleid.budget-inzetten.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
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
                  <FeaturedCardTop>
                    <div></div>
                    <div align="center">
                      <v-img
                        max-height="100"
                        max-width="90"
                        src="PNG/Badge_purple_themas-afmaken.png"
                      ></v-img>
                    </div>
                    <FeaturedCardStat></FeaturedCardStat>
                  </FeaturedCardTop>
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
