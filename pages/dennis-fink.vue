<template>
  <div>
    <div class="logo">
      <svg
        version="1.1"
        id="Ebene_1"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        x="0px"
        y="0px"
        viewBox="0 0 477.4 222.6"
        style="enable-background:new 0 0 477.4 222.6;"
        xml:space="preserve"
      >
        <path d="M109.2,84.1v-48c0.3-6.3,5.5-11.4,11.9-11.4c8,0,11.9,5.3,11.9,11.9l-0.1,47.5h23.7V36.6c0-19.7-8.3-36.6-30.9-36.6
                                c-5.2,0-12,2.8-16.6,6.6V1H85.4v83.1H109.2z"></path>
        <path d="M189.9,128.8h23.7v-23.7h-23.7v-21h-23.7v69.5c0,19.7,13.1,35.6,35.6,35.6l0,0v0c6.9,0,13.2-1.6,18.6-4.7l-9.8-22.1
                                l-0.1-0.1c-2.2,2.2-5.3,3.2-8.7,3.2v0c-8,0-11.9-5.3-11.9-11.9h0.1V128.8z"></path>
        <path d="M287.1,105.1l-20.3,45.7l-20.3-45.7h-24.9l32.8,73.7l-5.2,11.8c-1.8,3.9-4.5,6-7.4,6.6v0h-15.3v25.4h15.3
                                c9.7,0,20.3-6.6,26.5-19.2l43.6-98.2H287.1z"></path>
        <path d="M451.7,133.1l-30.1,9.1c1.1-10.7,6-19.3,15.9-19.7C444,122.2,449.1,127.2,451.7,133.1z M422.8,158l54.7-16.5
                                c0,0-3-15-10.6-23.4c-6.7-7.4-13.6-13.7-29-14c-21.6-0.4-39.2,19-39.2,42.5c0,23.5,17.5,42.5,39.2,42.5c18.4,0,33.8-13.8,38-32.3
                                h-22.7c-1.9,7.7-6.6,13-15.3,13.1C425.1,170,422.8,158,422.8,158z"></path>
        <path d="M366.1,152c0,6.7-3.9,12.1-11.9,12.1c-6.4,0-11.6-5.2-11.9-11.6v-12.2c0.3-6.3,5.5-11.4,11.9-11.4c8,0,11.9,5.3,11.9,11.9
                                V152z M342.3,110.8v-5.7h-23.7v117.4h23.7v-40c4.2,4.5,11.5,6.7,16.6,6.7c22.5,0,30.9-17.2,30.9-37.2v-11.2
                                c0-19.7-8.5-36.7-30.9-36.7C349.3,104.1,342.3,110.8,342.3,110.8z"></path>
        <path d="M47.5,1v48c-0.3,6.3-5.5,11.4-11.9,11.4c-8,0-11.9-5.3-11.9-11.9L23.7,1H0v47.5c0,19.7,8.3,36.6,30.9,36.6
                                c5.2,0,12-2.8,16.6-6.6v5.6h23.7V1H47.5z"></path>
      </svg>
    </div>
    <div class="employee-container">
      <div class="employee">
        <figure>
          <img
            src="/untype_dennis.png"
            alt=""
          >
        </figure>
        <div>
          <strong>Dennis Fink</strong><br>
          <span>Webentwicklung</span><br><br>
          <a href="mailto:dennis@untype.agency">dennis@untype.agency</a><br>
          <a href="tel:+491606091990">0160 609 1990</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style>
body,
figure {
  margin: 0;
}
body {
  font-family: "Public Sans", sans-serif;
  font-size: 20px;
  line-height: 1.4;
}

img {
  width: 100%;
}

.employee-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem 4rem 4rem;
  text-align: left;
}

figure {
  margin-bottom: 2rem;
}

a {
  color: inherit;
}

.logo {
  max-width: 100px;
  margin: 0 auto;
  margin-top: 2rem;
}
</style>