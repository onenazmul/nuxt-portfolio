<template>
  <div class="page-content">
    <div class="common-area services">
      <b-container>
        <b-row>
          <b-col>
            <div class="title-area text-center">
              <p>
                <nuxt-link to="/contact">Get support</nuxt-link> to choose the
                best course for you.
              </p>
              <h2>Top notch courses to achieve <span>online success</span></h2>
            </div>
          </b-col>
        </b-row>
        <b-row>
          <b-col v-for="course in courses" :key="course.id" md="4">
            <div class="single-course-box text-center">
              <b-card
                :title="course.title"
                img-src="https://shikhbeshobai.com/wp-content/uploads/2019/07/php-1200x615.png"
                img-alt="Course"
                img-top
                tag="article"
                style="max-width: 100%;"
                class="mb-2"
              >
                <b-card-text>
                  Totally Project Based Lecture, Power Point Presentation, Video
                  Demo, Practice, Question and Answer session
                </b-card-text>
                <nuxt-link to="/single-course" class="btn btn-info"
                  >Check Details</nuxt-link
                >
              </b-card>
            </div>
          </b-col>
          <b-col md="4">
            <div class="single-course-box text-center">
              <b-card
                title="PHP + Laravel Framework"
                img-src="https://shikhbeshobai.com/wp-content/uploads/2019/07/php-1200x615.png"
                img-alt="Course"
                img-top
                tag="article"
                style="max-width: 100%;"
                class="mb-2"
              >
                <b-card-text>
                  Totally Project Based Lecture, Power Point Presentation, Video
                  Demo, Practice, Question and Answer session
                </b-card-text>
                <nuxt-link to="/single-course" class="btn btn-info"
                  >Check Details</nuxt-link
                >
              </b-card>
            </div>
          </b-col>
          <b-col md="4">
            <div class="single-course-box text-center">
              <b-card
                title="PHP + Laravel Framework"
                img-src="https://shikhbeshobai.com/wp-content/uploads/2019/07/php-1200x615.png"
                img-alt="Course"
                img-top
                tag="article"
                style="max-width: 100%;"
                class="mb-2"
              >
                <b-card-text>
                  Totally Project Based Lecture, Power Point Presentation, Video
                  Demo, Practice, Question and Answer session
                </b-card-text>
                <nuxt-link to="/single-course" class="btn btn-info"
                  >Check Details</nuxt-link
                >
              </b-card>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div class="common-area serv-2">
      <b-container>
        <b-row>
          <b-col md="7">
            <div class="title-area text-left">
              <p>
                <a href="/about">Learn more </a> about Bijoy Techs’s unique
                services.
              </p>
              <h2>
                We listen and work together to create a truly
                <span>unique experience</span>
              </h2>
              <p>
                We design, build and support websites and apps for clients
                worldwide. Create beautiful, eye-catching on-page messages
                without the need for a developer.
              </p>
            </div>
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis
              quas corporis minima ipsum voluptatibus suscipit sequi magnam
              illo! Deleniti labore eaque sunt vero maiores. Voluptates
              reiciendis eaque deserunt maxime necessitatibus aliquid quod sint
              perspiciatis rem ullam, enim at optio sequi illum velit nostrum
              inventore nihil, delectus dicta et fugiat! Impedit sunt
              consequuntur, qui voluptate necessitatibus excepturi iste incidunt
              tenetur fugiat voluptatibus quo aliquid non! Consequuntur quae
              amet animi ut voluptas ducimus dolorem magni quis, nisi
              repellendus voluptatum laudantium reprehenderit provident libero
              sint illum numquam ratione, totam facere, commodi vitae eligendi.
              Officiis sed molestias aliquam natus asperiores repellendus
              temporibus quisquam ipsa. Magni architecto esse tempore tenetur
              corrupti consectetur eaque ullam dolore illo. Harum, porro
              aliquam? Eum quibusdam tempore amet magni? Quam.
            </p>
          </b-col>
          <b-col>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis
              quas corporis minima ipsum voluptatibus suscipit sequi magnam
              illo! Deleniti labore eaque sunt vero maiores. Voluptates
              reiciendis eaque deserunt maxime necessitatibus aliquid quod sint
              perspiciatis rem ullam, enim at optio sequi illum velit nostrum
              inventore nihil, delectus dicta et fugiat! Impedit sunt
              consequuntur, qui voluptate necessitatibus excepturi iste incidunt
              tenetur fugiat voluptatibus quo aliquid non! Consequuntur quae
              amet animi ut voluptas ducimus dolorem magni quis, nisi
              repellendus voluptatum laudantium reprehenderit provident libero
              sint illum numquam ratione, totam facere, commodi vitae eligendi.
              Officiis sed molestias aliquam natus asperiores repellendus
              temporibus quisquam ipsa. Magni architecto esse tempore tenetur
              corrupti consectetur eaque ullam dolore illo. Harum, porro
              aliquam? Eum quibusdam tempore amet magni? Quam.
            </p>
          </b-col>
          <b-col>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis
              quas corporis minima ipsum voluptatibus suscipit sequi magnam
              illo! Deleniti labore eaque sunt vero maiores. Voluptates
              reiciendis eaque deserunt maxime necessitatibus aliquid quod sint
              perspiciatis rem ullam, enim at optio sequi illum velit nostrum
              inventore nihil, delectus dicta et fugiat! Impedit sunt
              consequuntur, qui voluptate necessitatibus excepturi iste incidunt
              tenetur fugiat voluptatibus quo aliquid non! Consequuntur quae
              amet animi ut voluptas ducimus dolorem magni quis, nisi
              repellendus voluptatum laudantium reprehenderit provident libero
              sint illum numquam ratione, totam facere, commodi vitae eligendi.
              Officiis sed molestias aliquam natus asperiores repellendus
              temporibus quisquam ipsa. Magni architecto esse tempore tenetur
              corrupti consectetur eaque ullam dolore illo. Harum, porro
              aliquam? Eum quibusdam tempore amet magni? Quam.
            </p>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
// import Course from '@/components/Course'
export default {
  //   components: { Course },
  data() {
    return {
      courses: [{ title: 'Course one', duration: '6 Months', id: 1 }]
    }
  },
  head() {
    return {
      title: 'Courses'
    }
  }
}
</script>
