
<template>
    <div :style="{ position : 'relative' }" >

            <RECTANGLE  class = 'BIC-ZdbPCkkm'/> 

            <TEXTCODE  class = 'BIC-cZZscKAe' :value="'新增数据表'"/> 

            <INPUT  class = 'BIC-DamSPJYp'/> 

            <TEXTCODE  class = 'BIC-EFHBBMDe' :value="'数据源：'"/> 

            <TEXTCODE  class = 'BIC-ffByAWDC' :value="'数据表：'"/> 

            <INPUT  class = 'BIC-ebryNSBD'/> 

            <TEXTCODE  class = 'BIC-JfbZPGHc' :value="'字段命名：'"/> 

            <BUTTON  class = 'BIC-tdsaifSc'/> 

            <BUTTON  class = 'BIC-EDTksabH'/> 

    </div>
</template>

<script>
import RECTANGLE from '../../components/RECTANGLE/RECTANGLE' 
import TEXTCODE from '../../components/TEXTCODE/TEXTCODE' 
import INPUT from '../../components/INPUT/INPUT' 
import BUTTON from '../../components/BUTTON/BUTTON' 

export default {
  components: {
     RECTANGLE, 
     TEXTCODE, 
     INPUT, 
     BUTTON, 

  }
}
</script>

<style scoped>

.BIC-ZdbPCkkm{
                width: 794px;
                height: 504px; 
                position: absolute; 
                left: 59px; 
                top: 41px;
            } 
.BIC-cZZscKAe{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 86px; 
                top: 61px;
            } 
.BIC-DamSPJYp{
                width: 248px;
                height: 40px; 
                position: absolute; 
                left: 194px; 
                top: 140px;
            } 
.BIC-EFHBBMDe{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 132px; 
                top: 148px;
            } 
.BIC-ffByAWDC{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 132px; 
                top: 224px;
            } 
.BIC-ebryNSBD{
                width: 249px;
                height: 40px; 
                position: absolute; 
                left: 193px; 
                top: 216px;
            } 
.BIC-JfbZPGHc{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 131px; 
                top: 311px;
            } 
.BIC-tdsaifSc{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 609px; 
                top: 489px;
            } 
.BIC-EDTksabH{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 735px; 
                top: 489px;
            } 

</style>
