<template>
  <div id="Resume">
    <main>
      <div class="header">
        <h1 class="name">Holger Mueller</h1>
        <p class="description">UX/UI | Full Stack | Jamstack</p>
        <p class="location">909 Oak St, Batesville, AR 72501</p>
        <div class="email">9jholger@gmail.com</div>
      </div>

      <hr />

      <section class="social-links">
        <a href="https://github.com/Holgermueller" target="_blank" class="link"
          >Github</a
        >
        <a
          href="https://www.linkedin.com/in/holger-mueller-75855114a/"
          target="_blank"
          class="link"
          >LinkedIn</a
        >
        <a
          href="https://stackoverflow.com/users/9111512/holger-mueller?tab=profile"
          target="_blank"
          class="link"
          >Stack Overflow</a
        >
        <a
          href="https://holgermueller.github.io/portfolio/"
          class="link"
          target="_blank"
          >Portfolio</a
        >
        <a href="/WebDevResume.pdf" download="" target="_blank" class="link"
          >Download</a
        >
      </section>

      <hr />

      <section class="skills">
        <h2>Skills</h2>
        <p class="skill">
          Developing Single-Page applications using React and Vuejs.
          Specifically, built a wish-list application that allows users to login
          and keep a list of items they’d wish to buy and prioritized those
          items.
        </p>
        <p class="skill">
          Developing SQL and NoSQL databases such as MongoDB, Firebase and
          MySQL.
        </p>
        <p class="skill">
          Wireframing, mock-uping, and lo-fi and hi-fi prototyping with Figma
          and Adobe XD.
        </p>
      </section>

      <div class="stack">
        <h2>Tech Stack</h2>
        <div class="stack-cards">
          <div class="stack-card">
            <span>Figma, Adobe XD, Pen and Paper</span>
          </div>

          <div class="stack-card"><span>Vue, Vuex, Vuetify, Nuxt</span></div>
          <div class="stack-card">
            <span>React, Gatsby, Redux, Material UI</span>
          </div>
          <div class="stack-card"><span>JS, Node, Express</span></div>
          <div class="stack-card"><span>Firebase, MySQL, MongoDB</span></div>
        </div>
      </div>

      <section class="projects">
        <h2>Personal Projects</h2>

        <a
          href="https://holgermueller.github.io/blog/"
          class="project-link"
          target="_blank"
        >
          <h3 class="project">Blog</h3></a
        >
        <p class="project-description">
          Nuxt JS front-end JAMstacked with markdown files serving as the
          backend (ends?).
        </p>

        <a
          href="https://holgermueller.github.io/qrcoder/"
          class="project-link"
          target="_blank"
        >
          <h3 class="project">QR Coder</h3></a
        >
        <p class="project-description">
          HTML, CSS, Vanilla JS, and the QR Code CDN allow users to generated a
          QR code they can download to print in various sizes, with a little
          Three JS thrown in.
        </p>

        <a
          href="https://trackmyhours-74a8f.web.app/"
          class="project-link"
          target="_blank"
        >
          <h3 class="project">Hours Tracker</h3></a
        >
        <p class="project-description">
          Vue and Cloud Firestore came together to make thi incrementer I used
          totrackhours I needed tomake up at workdue to stor closures.
        </p>

        <a
          href="https://less-wish-list.web.app/"
          class="project-link"
          target="_blank"
        >
          <h3 class="project">Wish List</h3></a
        >
        <p class="project-description">
          Vue front-ended, Cloud Firestore back-ended alternative to a certain
          large company's wishlist feature. Features dynamic coloring determined
          by
        </p>

        <a
          href="https://holgermueller.github.io/weatherapp/"
          class="project-link"
          target="_blank"
        >
          <h3 class="project">Weather App</h3></a
        >
        <p class="project-description">
          Obligatory portfolio project pulls and displays data from the
          OpenWeather API, along with a dynamic background image determined by
          current weather conditions.
        </p>
      </section>

      <section class="work">
        <h2>Profesional Work Experience</h2>
        <h3 class="job">
          Web Development Tutor, Wyzant and Varsity Tutors, Remote
        </h3>
        <strong class="job-date"> April 2023 - Current </strong>

        <ul class="responsibilities">
          <li>Tutoring students on HTML, CSS, and JavaScript fundamentals</li>
          <li>Review process for pushing code to Github</li>
        </ul>

        <h3 class="job">
          Floor/Inventory Lead/Manager, Magers &amp; Quinn Booksellers,
          Minneapolis, MN
        </h3>
        <strong class="job-date">Aug. 2019 - June 2022</strong>
        <ul class="responsibilities">
          <li>
            Collaborate with warehouse management to maximize inventory flow
          </li>
          <li>Prioritize multiple tasks for execution by floor staff</li>
          <li>
            Communicate with floor staff to devise the best plans to meet
            deliverables
          </li>
          <li>Assist in training of new team members</li>
          <li>
            Consult with floor management to formalize inventory SOP documents
          </li>
        </ul>
        <h3 class="job">
          Bookseller, Magers &amp; Quinn Booksellers, Minneapolis, MN
        </h3>
        <strong class="job-date">Sept. 2015 - Aug. 2019</strong>
        <ul class="responsibilities">
          <li>Authorized to buy used books after one year</li>
          <li>Authorized to price used paperbacks after two years</li>
          <li>Receive inventory into the database/POS system</li>
          <li>Assist in fulfillment of online orders</li>
          <li>Keep store organized and presentable</li>
          <li>Assist in training of floor staff</li>
        </ul>

        <h3 class="job">
          Adjunct Professor of English SUNY Orange, Middletown, NY
        </h3>
        <strong class="job-date">Jan. 2013 - Aug. 2015</strong>
        <ul class="responsibilities">
          <li>
            Composed writing assignments and exercises on various topics to
            maximize student engagement with course materials
          </li>
          <li>
            Communicated complex, abstract concepts and technical terms to
            multiple students in clear, understandable terms
          </li>
          <li>Proofread student papers to point out areas for improvement</li>
          <li>
            Met with students individually to plan best approaches for improving
            writing skills
          </li>
        </ul>

        <h3 class="job">
          Faculty Writing Consultant SUNY Orange, Middletown, NY
        </h3>
        <strong class="job-date">Jan. 2013 - Aug. 2015</strong>
        <ul class="responsibilities">
          <li>
            Communicated directly with students to assess their skills and
            develop solutions to meet their needs
          </li>
          <li>
            Communicated complex, abstract concepts and technical terms to
            students in clear, understandable terms
          </li>
          <li>
            Composed writing exercises to improve students’ writing skills
          </li>
          <li>
            Worked with multiple students based on individual progress and need
          </li>
          <li>
            Proofread student papers to point out areas for student improvement
          </li>
        </ul>

        <h3 class="job">Writing Consultant, SUNY Orange, Middletown, NY</h3>
        <strong class="job-date">Mar. 2009 - Aug. 2015</strong>
        <ul class="responsibilities">
          <li>
            Communicated directly with students to assess their skills and
            develop solutions to meet their needs
          </li>
          <li>
            Communicated complex, abstract concepts and technical terms to
            students in clear, understandable terms
          </li>
          <li>Composed writing exercises to improve students’ skills</li>
          <li>
            Worked with multiple students based on individual progress and need
          </li>
          <li>Proofread student papers to point out areas for improvement</li>
        </ul>
      </section>

      <section class="education">
        <h2>Education</h2>
        <h3 class="school">Google IT Support Specialization Certificate</h3>
        <p class="further-description">Professional Certificate</p>
        <h3 class="school">Google UX Design</h3>
        <p class="further-description">Professional Certificate</p>
        <h3 class="school">Free Code Camp</h3>
        <p class="further-description">
          Javascript Algorithms and Data Structures Certificate
        </p>
        <h3 class="school">Wes Bos</h3>
        <p class="further-description">JS30</p>
        <h3 class="school">University of Minnesota</h3>
        <p class="further-description">
          Full Stack Web Development Certificate
        </p>

        <h3 class="school">SUNY New Paltz</h3>
        <p class="further-description">
          Master of Arts English Literature, Bachelor of Arts Creative Writing
        </p>
      </section>
    </main>
  </div>
</template>

<style scoped>
#Resume {
  margin: 0;
  font-family: 'Roboto', sans-serif;
  color: #080808;
  line-height: 1.6;
}
main {
  width: 75%;
  margin-top: auto;
  padding-bottom: 5%;
  margin-left: auto;
  margin-right: auto;
}

.header {
  text-align: center;
}

.name {
  font-size: 3rem;
  font-weight: 500;
  color: #085b68;
}
.description,
.location,
.email {
  font-weight: 400;
  font-size: 1rem;
}

hr {
  margin: 2% 0;
}

.social-links {
  display: flex;
  justify-content: space-between;
  column-gap: 0.5rem;
  flex-wrap: wrap;
}

a {
  text-decoration: none;
  font-weight: 400;
  font-size: 1rem;
  color: #085b68;
}

a:hover {
  color: skyblue;
}

h2 {
  font-size: 1.5rem;
  font-weight: 400;
}

h3 {
  font-weight: 300;
  font-size: 1.25rem;
}

.skill {
  margin-left: 2rem;
}
.stack-cards,
.project,
.job,
.job-date,
.school {
  margin-left: 2rem;
}

.responsibilities {
  margin-left: 2rem;
  font-weight: 300;
  font-size: 1rem;
}
.project-description,
.further-description {
  margin-left: 4rem;
}
</style>
