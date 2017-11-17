<template>
  <div class="main">
    <div class="cv">
      <div class="header">
        Duck Yeon Kim
        <a href="https://github.com/ceruberu" class="link">
          <img class="github" src="../assets/github.png"/> 
        </a>
      </div>
      <div class="section">
        <div class="sectionHeader">
          About Me
        </div>
        <div class="sectionBody">
          As a developer, I am passionate and self disciplined.
          I fell in love with coding because it gives equal chance to everyone.
          You don't need fancy MBAs or law schools to be the experts.
          All you need is a laptop, wifi, and willingness to keep learning.
          I also enjoy solving problems as they always make me a better developer. 
          I try to catch up with latest technology because I like how the Javascript society is constantly adapting and evolving.
          <br>
          <br>
          As a person, I am friendly and open-minded.
          I'm born in Seoul and grew in Bangkok. 
          I also went to exchange program in Barcelona for half a year.
          I made friends with different backgrounds and minds.
          All my experiences from different places of the world are my greatest strength.
        </div>
      </div>
      <div class="section">
        <div class="sectionHeader">
          Experience
        </div>
        <div class="sectionBody">

        </div>
      </div>
      <div class="section">
        <div class="sectionHeader">
          Tech Stacks
        </div>
        <div class="sectionBody techstacks">
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/react.png"/>
              React
            </div>
            <ul class="techstackBody">
              <li>Able to make SSR / CSR websites</li>
              <li>Fully understood react lifecycle</li>
              <li>Currently studying React Native</li>
            </ul>
          </div>
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/vue.png"/>
              Vue
            </div>
            <ul class="techstackBody">
              <li>This website is made in Vue 2.0</li>
            </ul>
          </div>
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/redux.png"/>
              Redux
            </div>
            <ul class="techstackBody">
              <li>State-management in client side</li>
            </ul>
          </div>
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/graphql.png"/>
              Graphql
            </div>
            <ul class="techstackBody">
              <li>Able to connect front-end with MongoDB</li>
            </ul>
          </div>
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/mongodb.png"/>
              MongoDB
            </div>
            <ul class="techstackBody">
              <li>Use pure MongoDB or with Mongoose</li>
            </ul>
          </div>
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/docker.png"/>
              Docker
            </div>
            <ul class="techstackBody">
              <li>Able to make DevOps system with Docker images</li>
              <li>Experience in Docker Compose and Docker Swarm</li>
            </ul>
          </div>
          <div class="techstack">
            <div class="techstackHeader">
              <img class="techstackLogo" src="../assets/scrapy.png"/>
              Scrapy
            </div>
            <ul class="techstackBody">
              <li>Python-based scrawling framework</li>
              <li>Use ScrapingHub to automate scrawling process with MongoDB</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="section">
        <div class="sectionHeader">
          Education
        </div>
        <div class="sectionBody educations">
          <div class="education">
            <h3>Sillicon Valley Coding - Javscript Programing Bootcamp (2016)</h3>
            <h4>Fullstack Javascript Engineer</h4>
            <h4 style="color:gray">Seoul, Korea</h4>
            <ul>
              <li>Covered everything from Javascript fundamentals (Closure Scope, Inheritance and Instantiation Patterns, etc)<br>
               <li>Front-end frameworks (React.js & Angular.js)</li>
               <li>Server side Javascript (Node, Express)</li>
               <li>Databases (Mongoose, MongoDB, mySQL, etc) </li>
               <li>While using Javascript as a tool, we also managed to cover fundamental Computer Science topics such as Data Structures, Algorithms, and Complexity Analysis.</li>
               <li>A quick summary of the curriculum - Javascript fundamentals, Data Structures, D3, Backbone, Angular, React, Node, and Express.</li>
            </ul>
          </div>
          <div class="education">
            <h3>Chulalongkorn University (2011 - 2017)</h3>
            <h4>Bachelor of Economics - International Program</h4>
            <h4 style="color:gray">Bangkok, Thailand</h4>
            <h4>GPA 3.5 - Second Honor</h4>
          </div>
        </div>
      </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'portfolio',
};
</script>

<style scoped>
  .main {
    overflow: scroll;
  }
  .cv {
    display: flex;
    flex-direction: column;
    margin:20px;
    padding: 15px;
    border: 1px solid lightgrey;
    border-radius: 10px;
    background-color: white;
  }
  .header {
    display: flex;
    flex: 0 0 150px;
    justify-content: center;
    align-items: center;
    font-size: 20px;
  }
  .section {
    display: flex;
    flex-direction: column;
    border: 1px solid lightgrey;
    margin: 10px;
    border-radius: 10px;
    flex-shrink: 0;
    overflow: hidden;
  }
  .sectionHeader {
    display: flex;
    align-items: center;
    font-size: 18px;
    padding-left: 20px;
    padding-top: 10px;
    padding-bottom: 5px;
    flex: 0 0 30px;
    background-color: gray;
    color:white;
    font-weight: 700;
  }
  .sectionBody {
    display: flex;
    flex: 1;
    padding: 20px;
  }
  .link {
    margin: 50px;
  }
  .github {
    height: 50px;
    width: 50px;
  }
  .techstacks {
    flex-wrap: wrap;
  }
  .techstack {
    display: flex;
    flex-shrink: 0;
    width: 450px;
    height: 100px;
    margin: 10px;
    border-top: 1px solid lightgrey;
    border-bottom: 1px solid lightgrey;
  }
  .techstackHeader {
    display: flex;
    flex: 0 0 100px;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
  }
  .techstackBody {
    flex: 1;
    margin-right: 20px;
    padding-top: 10px;
  }
  .techstackLogo {
    height: 50px;
    width: 50px;
    padding: 5px;
  }
  .educations {
    flex-direction: column;
  }
  .education {
    display: flex;
    flex-direction: column;
    margin-bottom: 10px;
  }

  h3 {
    margin: 0;
    margin-bottom: 10px;
  }

  h4 {
    margin: 0;
    margin-bottom: 10px;
  }

  ul {
    margin: 0;
    margin-bottom: 10px;
  }

  li {
    margin-bottom: 5px;
  }
</style>
