<template>
  <d2-container :filename="filename" type="card">
    <d2-module-index :banner="banner"/>
  </d2-container>
</template>

<script>
export default {
  data () {
    return {
      filename: __filename,
      banner: {
        title: 'PLAYGROUND',
        subTitle: '在这里可以测试一些 D2Admin 的系统功能'
      }
    }
  }
}
</script>
