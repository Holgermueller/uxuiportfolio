<template>
  <div id="Jobz">
    <nuxt-link to="/Portfolio">
      <v-chip outlined>
        <v-icon left>mdi-arrow-left</v-icon>
        Back
      </v-chip>
    </nuxt-link>

    <h1 class="app-name display-4">Jobz</h1>
    <h2 class="display-2">Helping first-generation immigrants get hired.</h2>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          First-generation immigrants face many struggles when trying to find
          work, including but not limited to language barriers and unfamiliarity
          with their surroundings.
        </p>
        <p class="headline">
          Solution: Design an app that helps alleviate some of these struggles.
        </p>
      </section>
    </div>

    <v-img src="./jobsdeskhome.png"></v-img>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          I used various articles to gather information on the difficulties
          first-generation immigrants face while job hunting. I designed my
          solutions around the ones that could be most-easily solved with a
          mobile app and website.
        </p>
      </section>
    </div>

    <v-img height="1224" width="1632" src="./jobsideation.png"></v-img>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          After some quick sketching, I decided the problems most easily
          addressed by an app are accessibility to resources and resume
          templating.
        </p>
      </section>
    </div>

    <v-container class="mx-auto my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info mx-auto">
            <p>
              Initial designs for the Jobz mobile app focused on quick resume
              templateing for job seekers on the go.
            </p>
            <br />
            <p>
              Users, after setting up an initial resume, would be able to
              include features they deem necessary to applying to a given job,
              allowing them to easily tailor their resumes to specific job
              listings.
            </p>
          </div>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            src="./jobslofires.png"
            height="609px"
            width="312px"
            class="mx-auto"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="flow-display">
      <v-img
        class="align-end text-center"
        src="./jobslofiflow.png"
        height="300px"
      >
        <p>
          I created a lo-fi prototype to see how if the user flow was intuitive
          enough.
        </p></v-img
      >
      <p class="title adobexd-link">
        You can see the Lo-Fi prototype
        <a
          href="https://xd.adobe.com/view/e6e29c80-a3f0-47b0-9fbe-e3367e43c572-b3b1/"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline text-center">
          A remote usability study of five people uncovered three findings:
        </p>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">1</p>
              <p class="headline text-center">Better resources</p>
              <p class="problem">
                Users don’t just want contact info. To really help them,
                integrate a map or open to Google maps by clicking on the
                address.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">2</p>
              <p class="headline text-center">Ratings</p>
              <p class="problem">
                Users want to know more about a potential employer without
                having to comb the Internet.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">3</p>
              <p class="headline text-center">Continuity</p>
              <p class="problem">
                Users at least wanted the option of beginning work on one
                platform and continuing on another.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <v-container class="mx-auto my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info mx-auto">
            <p>
              Based on the insights from the usability studies, I improved my
              designs to better suit users’ needs, like the inclusion of data
              about potential employers.
            </p>
          </div>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            src="./jobsappprofile.png"
            height="425"
            width="196"
            class="mx-auto"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container class="mx-auto my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            src="./jobssavejob.png"
            height="425"
            width="196"
            class="mx-auto"
          ></v-img>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info mx-auto">
            <p>
              Additional improvements included giving users the option of saving
              job listings until they could get to them later.
            </p>
          </div>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="flow-display">
      <v-img class="align-end text-center" src="./jobsappflow.png">
        <p class="pt-8">
          The hi-fi prototype follows pretty much the same user flow as the
          lo-fi prototype, albeit with a few more features thrown in.
        </p></v-img
      >
      <p class="title adobexd-link">
        Check out the Hi-Fi prototype
        <a
          href="https://xd.adobe.com/view/2fd5fef6-7e13-4db5-90d1-77b27a8abe7a-7a86/"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline text-center">Accessability Considerations:</p>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">1</p>
              <p class="problem">
                Integrated microphone for users who only have the use of one
                hand for whatever reason.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">2</p>
              <p class="problem">
                Colors were checked against WCAG guidelines to ensure color
                contrasts would not exclude anyone.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">3</p>
              <p class="problem">
                Upon creating a profile, users will be able to choose the
                language in which the app will be.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <p class="headline text-center">Responsive Design</p>

    <p class="headline">
      The app designs finished, I moved on to the responsive web designs. For
      the desktop version, I focused more on features better suited to tasks
      done at a keyboard.
    </p>

    <v-img src="./jobsmobileideation.png"></v-img>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          The designs for screen size variation included mobile, tablet, and
          desktop. I optimized the designs to fit specific user needs of each
          device and screen size.
        </p>
      </section>
    </div>

    <v-container class="mx-auto my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <p class="headline text-center">Mobile</p>
          <v-img
            class="mx-auto"
            width="97"
            height="301"
            src="./responsivemobilehome.png"
          ></v-img>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <p class="headline text-center">Tablet</p>
          <v-img
            class="mx-auto"
            width="191"
            height="361"
            src="./tablethome.png"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <p class="headline text-center">Desktop</p>
    <v-img
      class="mx-auto"
      width="635"
      height="420"
      src="./jobsdeskhome.png"
    ></v-img>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline text-center">Takeaways:</p>
        <v-container class="mx-auto my-4" fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg6 xl6>
              <p class="headline text-center">Impact:</p>
              <p>
                Users found the inclusion of things like maps and
                potential-employer ratings from other sites made the Jobz app
                more user friendly, as they did not have to go to another site
                to get this information.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg6 xl6>
              <p class="headline text-center">What I Learned:</p>
              <p>
                Even though a lot of the problems first-generation immigrants
                face cannot be solved with an app, the few problems it does
                solve makes things that much more equitable for them.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <v-img class="mx-auto" src="./jobzsubmitted.png"></v-img>

    <v-btn class="my-16 mx-auto" @click="backToTop" text>
      <v-icon left>mdi-arrow-up</v-icon> Back to top</v-btn
    >
  </div>
</template>

<script>
export default {
  name: 'JobzPage',

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
  background-color: rgba(0, 120, 20, 0.5);
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
.illustration-info {
  margin: auto;
  width: 85%;
  padding: 2%;
  position: relative;
  top: 50%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
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
