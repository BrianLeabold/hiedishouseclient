<template>
  <div class="container mb-3">
    <div>
      <h1 class="title">Fresh and up to date information</h1>
      <article>
        <h2 class="subtitle mx-auto w-full">5% complete</h2>
        <div id="progress">
          <div id="percentage"></div>
        </div>
        <div id="updates" class="content">
          <p class="mx-3">
            As the build date approaches (10/12/19), there are still a few details to work out.
            The site is prepped and we are anxiously awaiting delivery of the materials.
          </p>
          <div class="date bold text-center italic">Updated 10/5/2019</div>
          <ul class="todo w-full md:w-1/3">
            <li class="complete mx-2">Prep site for build</li>
            <li class="mx-2">Materials delivered</li>
            <li class="mx-2">Frame and install floor joist</li>
            <li class="mx-2">Install OSB sub-floor</li>
            <li class="mx-2">Frame and erect walls</li>
            <li class="mx-2">Apply exterior moisture barrier</li>
            <li class="mx-2">Cut and install roof rafters</li>
            <li class="mx-2">Sheet roof</li>
            <li class="mx-2">Sheet walls</li>
            <li class="mx-2">Install windows and door</li>
            <li class="mx-2">Install skylights</li>
            <li class="mx-2">Install roofing materials</li>
            <li class="mx-2">Rough in electric</li>
            <li class="mx-2">Install insulation</li>
            <li class="mx-2">Hang drywall</li>
            <li class="mx-2">Apply 3 coats of joint compound</li>
            <li class="mx-2">Paint, paint and paint some more</li>
            <li class="mx-2">Install flooring and cabinet</li>
            <li class="mx-2">Paint and install trim</li>
            <li class="mx-2">Install electrical fixtures and outlets</li>
          </ul>
        </div>
      </article>
    </div>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: `Updates - Heidi's House`,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: `Fresh and up to date information`
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
#progress {
  width: 80%;
  height: 25px;
  border-radius: 5px;
  border: 1px solid gold;
  text-align: center;
  align-items: center;
  margin: 10px auto;
}
#percentage {
  width: 5%;
  height: 100%;
  background: gold;
  border-radius: 4px;
}

#updates {
  text-align: left;
}
.date {
  color: chocolate;
}
.todo {
  list-style: none;
  margin: 15px auto;
  padding: 0;
  border-radius: 15px;
}
li {
  padding: 10px;
  background: #f3f3f3;
  border-radius: 5px;
  text-align: left;
  margin-top: 5px;
}
.complete {
  text-decoration: line-through;
}
</style>