<template>
  <div class="container">
    <div id="content">
      <h1 class="title">Our Mission</h1>
      <h2
        class="subtitle"
      >WAG Healing’s focus is mutual healing of animal and person through relationship.</h2>
      <div id="mission">
        <p class="mx-3 my-2">
          <img
            class="float-right m-1"
            src="../static/android-chrome-512x512.png"
            alt="Mack and Stella"
          />
          WAG Healing Animal Sanctuary is a place where both animals and people can come to rest,
          renew and rebuild their lives. We believe that animals, people and nature must be acknowledged
          as partners to support a community that is committed to healing, growth and healthy connection.
        </p>

        <p class="mx-3 my-2">
          “Walk With Me” hosts retreats at WAG Healing's animal sanctuary. WAG Healing is located on 3.14
          acres in the Dehesa Valley. Whether you want to get away or to spend time with animals or you're
          just looking to create a new perspective on your life, you'll find a place to rest, renew and
          rebuild your life at our mindful retreat with animals.The uniqueness of our retreat is that it
          is built on the bond with animals.
        </p>

        <p class="mx-3 my-2">
          We partnered with a unique space for animals so that people
          and animals could work together toward healing and transformation. All animals at WAG Healing
          are rescued and Julie has worked with holistic techniques to assist them in recovering, enabling
          them to be adopted or live out their lives at the sanctuary. This is exactly why they make good
          retreat partners to renew your life. You will come away from this program with a new perspective
          on your experiences and a renewed sense of compassion for yourself and others.
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: `Our Mission -Heidi's House`,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: `WAG Healing’s focus is mutual healing of animal and person through relationship.`
        },
        {
          hid: 'author',
          name: 'author',
          content: 'Brian Leabold'
        }
      ]
    }
  }
}
</script>
<style scoped>
#mission {
  text-align: left;
  padding: 10px;
}
</style>