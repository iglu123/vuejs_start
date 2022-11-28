<template>
  <div>
    <div :style="style1">스타일 바인딩:글씨는 red, 폰트크기:30px</div>
    <div style="color: greenyellow; font-size: 30px">
      스타일 바인딩:글씨는 green, 폰트크기:30px
    </div>
    <div :style="style2">스타일 바인딩:글씨는 blue, 폰트크기:30px</div>
    <button @click="style1.color = 'orange'">색상바꾸기</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      style1: {
        color: 'red',
        fontSize: '30px'
      },
      style2: {
        color: 'blue',
        fontSize: '30px'
      }
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
