<script>
export default {
  name: "App",
  data() {
    return {
      story: [
        "The Call of Cthulhu and Other Weird Stories",
        "The Shadow Over Innsmouth",
        "The Whisperer in Darkness",
        "The Silver Key and Through the Gates of the Silver Key",
        "The Shadow Out of Time",
        "The Mound",
        "The Dunwich Horror",
        "At the Mountains of Madness",
        "The Dream-Quest of Unknown Kadath",
        "Imprisoned with the Pharaohs",
      ],
    };
  },
};
</script>

<template>
  <div id="wrap">
    <div id="content" class="story-list">
      <h1 class="h1">Various works of H.P. Lovecraft</h1>
      <h3 v-for="story in story" :key="story.id" class="h3">{{ story }}</h3>
    </div>
  </div>
</template>

<style>
.h1 {
  color: #111;
  margin: 10px;
}
.h3 {
  margin: 10px;
}
.story-list {
  color: white;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  text-align: center;
}

/* #wrap {
    float: left;
    position: relative;
    left: 50%;
}

#content {
    float: left;
    position: relative;
    left: -50%;
} */
</style>
