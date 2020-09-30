<template>
  <div class="bg-img1 size1 flex-w flex-c-m p-t-55 p-b-55 p-l-15 p-r-15" style="background-image: url('images/bg01.jpg');">
    <div class="wsize1 bor1 bg1 p-t-175 p-b-45 p-l-15 p-r-15 respon1">
      <p class="txt-center m1-txt1 p-t-33 p-b-68">
        Our website is under construction
      </p>

      <div class="wsize2 flex-w flex-c hsize1 cd100">
        <div class="flex-col-c-m size2 how-countdown">
          <span class="l1-txt1 p-b-9 days">35</span>
          <span class="s1-txt1">Days</span>
        </div>

        <div class="flex-col-c-m size2 how-countdown">
          <span class="l1-txt1 p-b-9 hours">17</span>
          <span class="s1-txt1">Hours</span>
        </div>

        <div class="flex-col-c-m size2 how-countdown">
          <span class="l1-txt1 p-b-9 minutes">50</span>
          <span class="s1-txt1">Minutes</span>
        </div>

        <div class="flex-col-c-m size2 how-countdown">
          <span class="l1-txt1 p-b-9 seconds">39</span>
          <span class="s1-txt1">Seconds</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.title {
    font-family:
        'Quicksand',
        'Source Sans Pro',
        -apple-system,
        BlinkMacSystemFont,
        'Segoe UI',
        Roboto,
        'Helvetica Neue',
        Arial,
        sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
}

.subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
}

.links {
    padding-top: 15px;
}
</style>
