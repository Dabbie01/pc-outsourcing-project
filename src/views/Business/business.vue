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
  import businessslider from '@/components/business_slide/business_slide.vue'
  import businessField from '@/components/business_field/business_field.vue'
  import moreServer from '@/components/more_server/more_server.vue'
  import medicalPlatform from '@/components/medical_platform/medical_platform.vue'
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
