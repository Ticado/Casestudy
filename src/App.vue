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
              </FeaturedCardTop>
              <v-card-text>
                Behaalde punten
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
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>
            </v-row>

            <v-row>
              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>
            </v-row>

            <v-row>
              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>

              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
                  </v-card-text>
                </FeaturedCard>
              </v-col>
            </v-row>

            <v-row>
              <v-col>
                <FeaturedCard>
                  <FeaturedCardTop>
                    <div>Persoonlijke punten</div>
                    <FeaturedCardStat>32</FeaturedCardStat>
                  </FeaturedCardTop>
                  <ProgressBar> </ProgressBar>
                  <v-card-text>
                    Behaalde punten
                    <Badge />
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
