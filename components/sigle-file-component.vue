<template>
  <div class="hello">
    {{msg}}
  </div>
</template>

<script>
export default { //데이터의 ES2015 export 기능.
  name: 'hello',
  data () {
    return {
      msg: 'Vue.js 앱에 오신걸 환영합니다'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
<!-- 빌드도구 : 웹팩이나 브라우저리파이 같은 도구들을 사용해야 .vue 코드를 빌드할 수있다. 이 도구들은 필요한 모든 빌드 도구를 포함하고 있다.--!>