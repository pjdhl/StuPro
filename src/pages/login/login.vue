<template>
  <div>
      <Login :title="title" :otherTitle="otherTitle" :router="router" ></Login>
  </div>
</template>
<script>
import Login from "@c/common/loginAndreg/bussinessLogin";
export default {
  components: {
    Login,
  },
  data() {
    return {
        title:"登录",
        otherTitle:"注册",
        router:"reg"
    }
  }
}
</script>

