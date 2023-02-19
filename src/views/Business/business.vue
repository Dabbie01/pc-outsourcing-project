<!--
 * @Author: Dabbie 2310734576@qq.com
 * @Date: 2023-02-19 16:15:30
 * @LastEditors: Dabbie 2310734576@qq.com
 * @LastEditTime: 2023-02-19 17:41:33
 * @FilePath: \vue-xhc-master\src\views\Business\business.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div>
    <navmenu></navmenu>
    <businessslider></businessslider>
    <businessField></businessField>
    <moreServer></moreServer>
    <medicalPlatform></medicalPlatform>
    <institution></institution>
  </div>
</template>

<script type="text/ecmascript-6">
  import navmenu from '@/components/navMenu/navmenu.vue'
  import businessslider from '@/components/business-slide/business-slide.vue'
  import businessField from '@/components/business-field/business-field.vue'
  import moreServer from '@/components/more-server/more-server.vue'
  import medicalPlatform from '@/components/medical-platform/medical-platform.vue'
  import institution from '@/components/institution/institution.vue'
  export default {
    components: {
      navmenu,
      businessslider,
      businessField,
      moreServer,
      medicalPlatform,
      institution
    }
  }
</script>

<style>


</style>
