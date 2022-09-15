<template>
  <div id="HepcatsCaseStudy">
    <nuxt-link to="/Portfolio">
      <v-chip outlined>
        <v-icon left>mdi-arrow-left</v-icon>
        Back
      </v-chip>
    </nuxt-link>
    <h1 class="app-name display-4">HepCatz</h1>
    <h2 class="display-2">Where the cool kids get their clothes</h2>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          HepCatz in a mobile-responsive, online marketplace that allows
          musicians to sell their merch to fans in a more-accessible manner.
        </p>
      </section>
    </div>

    <v-container fluid class="my-8">
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg4 xl4>
          <v-img
            class="full my-8 mx-auto"
            height="609px"
            width="312px"
            src="./apparelhepcats.png"
          ></v-img>
        </v-flex>
        <v-flex xs12 sm12 md6 lg8 xl8>
          <v-img
            class="full my-8 mx-auto"
            height="610px"
            width="860px"
            src="./desktophomehepcats.png"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          It can be difficult to find official merchandise directly from the
          musicians you love, especially with so much bootleg merchandise out
          there.
        </p>
        <p class="headline">
          HepCatz allows fans to get their gear directly from the musicians they
          love.
        </p>
      </section>
    </div>

    <div class="illus-notes">
      <p class="title text-center py-8 my-8">
        While moving through design phases, I put user feedback front and center
        in my design ideas.
      </p>
    </div>

    <v-img src="./hepcatsfilter.png"></v-img>

    <div class="illus-notes">
      <p class="title text-center py-8 my-8">
        A filter will be positioned front and center. This will give users more
        precise search results.
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <h3 class="headline text-center py-4">User painpoints:</h3>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg6 xl6>
              <p class="headline text-center">Item search</p>
              <p class="problem">
                Most online marketplaces have poor search capabilities that
                don’t allow users to filter items well.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg6 xl6>
              <p class="headline text-center">Merch Authenticity</p>
              <p class="problem">
                There are many sites that offer what appears to be official
                merchandise, but is in fact counterfeit/bootleg merch.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <div class="flow-display">
      <v-img class="align-end text-center" src="./hepcatstruelofi.png">
        <p class="pt-8">
          The user flow centers on ease of finding the item you want and buying
          is as quick as possible.
        </p>
      </v-img>
      <p class="title adobexd-link">
        Check out the lo-fi prototype
        <a
          href="https://xd.adobe.com/view/f804a300-3e50-44d1-beb0-0f4086cfd888-ad57/"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <h3 class="headline text-center py-4">
          A couple rounds of usability studies unearthed a few things to take
          into consideration:
        </h3>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">1</p>
              <p class="problem">
                Users want clearer indication when something has been added to
                their cart.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">2</p>
              <p class="problem">
                Users want a way to resume shopping without using the back
                button on their browser.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">3</p>
              <p class="problem">
                Customers like to get more info about a product, besides the
                name.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <div class="illus-notes">
      <p class="title text-center pt-8 my-8">
        The back button above the item tells users their info won't be lost if
        they go back a screen.
      </p>
      <p class="title text-center pb-8 my-8">
        Clear indications they’ve added items to their carts allows users to
        shop with ease.
      </p>
    </div>

    <v-container fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            class="mx-auto"
            src="./hepcatscart.png"
            height="670"
            width="386"
          ></v-img>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            class="mx-auto"
            src="./hepcatsincart.png"
            height="670"
            width="386"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="illus-notes">
      <p class="title text-center py-8 my-8">
        Descriptions and alternate views of the items allow users to make
        informed purchases.
      </p>
    </div>

    <div class="flow-display">
      <v-img class="align-end text-center" src="./hepcatshififlow.png">
        <p class="pt-8">
          The hi-fi prototype demonstrates a clear user flow and a minimalist
          design the won’t distract the user from their shopping
        </p></v-img
      >
      <p class="title adobexd-link">
        Check out the Hi-Fi prototype
        <a
          href="https://xd.adobe.com/view/94ede236-b619-4328-9079-af82edad2e5b-c1be/"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <v-btn class="my-16 mx-auto" @click="backToTop" text>
      <v-icon left>mdi-arrow-up</v-icon> Back to top</v-btn
    >
  </div>
</template>

<script>
export default {
  name: 'HepcatsPage',

  methods: {
    backToTop() {
      window.scrollTo(0, 0)
    },
  },
}
</script>

<style scoped>
a {
  text-decoration: none;
}
h1,
h2 {
  text-align: center;
  margin: 4% auto;
}
.section-background {
  background-color: rgba(71, 58, 212, 0.5);
  border-radius: 5px;
}
.case-study-info {
  width: 85%;
  margin: 8% auto;
  padding: 8%;
}
.problem {
  width: 90%;
  margin: auto;
}
.illus-notes {
  background-color: rgba(71, 58, 212, 0.3);
  border-radius: 5px;
}
.flow-display {
  margin: 8% 0;
}
.adobexd-link {
  text-align: center;
}
.v-btn {
  display: block;
}
</style>
