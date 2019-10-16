<template>
  <div id="YearViewer">
      <p>
          Click on "View by Year" to see where I was year by year!
      </p>
  </div>
</template>

<script>

var count = 0
const pics = [
  "./assets/personal-pic.png"
]

export default {
  name: 'YearViewer',
  props: {
      msg: String
  },
  data: function () {
    return pics[count]
  },
  methods: {
    nextPic: function () {
      count++

    }
  }
}
</script>


<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b984;
}
</style>