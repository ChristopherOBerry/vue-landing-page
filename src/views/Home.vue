<template>
  <div class="home bg-primary text-white">
    <div class="row my-4">
      <div class="col-12" style="height:10vh;">
        <h1 class="text-center">Christopher O'Berry</h1>
      </div>
      <div class="col-12 my-1" style="height:10vh;">
        <h5 class="text-center">Software Developer and Content Manager</h5>
      </div>
    </div>
    <div class="row bg-info rounded border text-center">
      <div class="row d-flex justify-content-center">
        <div class="col">
          <h1 class="align-self-center my-4">About Me</h1>
          <p class="align-self-center">
            <img
              class="img-fluid"
              src="../assets/codeworks-logo.png"
              alt="codeworks logo"
              style="height:5vh;"
            /> I am currently attending
            <a
              target="_blank"
              href="https://boisecodeworks.com/"
            >Boise CodeWorks</a> for experience and certification on building full-stack web applications. Working with Javascript, HTML, CSS, Bootstrap, Node.js, Vue.js, C#, MySQL, MongoDB, Dapper, Postman, OOP, REST API Design, and Observer Pattern. During my time at CodeWorks, I have worked on several projects, both solo and collaboratively.
          </p>

          <p>In the future, I hope to pursue a career in Web Development specializing in Front-End development.</p>
          <p>
            At present, I am serving the role of Content Manager for
            <a
              target="_blank"
              href="http://www.quietspeculation.com"
            >QuietSpeculation.com</a>, where I utilize WordPress and HTML5 to create and edit content pieces.
          </p>
        </div>
      </div>
    </div>

    <div class="row my-4">
      <div class="col-12 text-center">
        <button
          class="btn btn-info mx-auto border"
          type="button"
          data-toggle="collapse"
          data-target="#collapseExample"
          aria-expanded="false"
          aria-controls="collapseExample"
        >My Tools</button>
      </div>
      <div class="col-12 my-4">
        <skills class="collapse" id="collapseExample"></skills>
      </div>
    </div>
    <div class="row my-4">
      <div class="col-12 text-center">
        <experience id="xp"></experience>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

import Skills from "@/components/Skills";
import Experience from "@/components/Experience";

export default {
  name: "home",
  components: {
    Skills,
    Experience
  }
};
</script>

<style>
</style>

