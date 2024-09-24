<template>
  <div>
    <div id="aboutMe">
      <div class="container-fluid p-5">
        <div class="d-flex justify-content-center">
          <div class="about-text mt-2 text-center">
            <h1 class="pb-3 fw-bold fs-3 text-uppercase my-3 border-bottom">
              About me
            </h1>
            <p class="fs-5">
              "With a passion for web development, eager to dive into both
              frontend and backend technologies. With a foundational knowledge
              of Angular and Laravel, I enjoy and a keen to learn more and
              enhance my skills in creating dynamic, user-friendly web
              applications. My approach emphasizes clean code, seamless user
              experiences, and a commitment to continual learning. I am excited
              to explore new technologies and methodologies, whether working
              independently or collaborating with a team. My goal is to deliver
              innovative and high-quality solutions that meet and exceed client
              expectations."
            </p>
            <button class="btn btn-outline-primary mt-3 mainBtn">
              <nuxt-link
                class="icon-link icon-link-hover text-decoration-none fw-bold font-monospace"
                style="
                  --bs-icon-link-transform: translate3d(0, -0.125rem, 0);
                  --bs-link-hover-color-rgb: 255, 255, 255;
                "
                to="https://drive.google.com/file/d/1ROsU18kH75BjypHlEZfbppAMTkemDD2_/view?usp=sharing"
                target="_blank"
              >
                <i
                  class="fa-solid fa-file-export me-2 bi"
                  aria-hidden="true"
                ></i>
                View Resume</nuxt-link
              >
            </button>
            <button class="btn btn-outline-primary mt-3 mainBtn ms-3">
              <nuxt-link
                class="icon-link icon-link-hover text-decoration-none fw-bold font-monospace"
                style="
                  --bs-icon-link-transform: translate3d(0, -0.125rem, 0);
                  --bs-link-hover-color-rgb: 255, 255, 255;
                "
                to="https://github.com/JBHtzy"
                target="_blank"
              >
                <i class="fa-brands fa-github me-2 bi" aria-hidden="true"></i>
                GitHub</nuxt-link
              >
            </button>
          </div>
        </div>
      </div>
    </div>

    <!-- Images-skills -->
    <div class="container mb-5" id="techSkills">
      <div class="row row-cols-2 row-cols-lg-5 g-2 g-lg-3 py-3 mt-2">
        <div class="col-3">
          <img
            src="https://www.kindpng.com/picc/b/23-237385_transparent-jquery-logo-png-html-css-logo-png.png"
            width="150"
            alt="HTML, CSS, JS"
          />
        </div>
        <div class="col">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/2560px-PHP-logo.svg.png"
            width="150"
            alt="PHP"
          />
        </div>
        <div class="col">
          <img
            src="https://upload.wikimedia.org/wikipedia/labs/8/8e/Mysql_logo.png"
            width="150"
            alt="MYSQL"
          />
        </div>
        <div class="col">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Logo_jQuery.svg/1280px-Logo_jQuery.svg.png"
            width="150"
            alt="jQuery"
          />
        </div>
        <div class="col">
          <img
            src="~/assets/imgs/angular-logo-1.png"
            width="150"
            alt="Angular"
          />
        </div>
        <div class="col">
          <img src="~/assets/imgs/laravel.png" width="150" alt="Laravel" />
        </div>
        <div class="col">
          <img
            src="~/assets/imgs/Figma-Logo-PNG-HD-Image.png"
            width="150"
            alt="Figma"
          />
        </div>
        <div class="col">
          <img
            src="~/assets/imgs/git-github.png"
            width="150"
            alt="Git, GitHub"
          />
        </div>
        <div class="col">
          <img
            src="https://logovectorseek.com/wp-content/uploads/2019/10/bootstrap-logo-vector.png"
            width="150"
            alt="Bootstrap"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>
