
<template>
    <div :style="{ position : 'relative' }" >

            <RECTANGLE  class = 'BIC-CaNZdefB'/> 

            <TEXTCODE  class = 'BIC-WPEytXSz' :value="'修改数据表'"/> 

            <TEXTCODE  class = 'BIC-mkcptakZ' :value="'数据源：'"/> 

            <TEXTCODE  class = 'BIC-WWXwynJW' :value="'数据表：'"/> 

            <TEXTCODE  class = 'BIC-NztaTWbd' :value="'字段命名：'"/> 

            <BUTTON  class = 'BIC-DRKWddsx'/> 

            <BUTTON  class = 'BIC-NETxFJQZ'/> 

            <TEXTCODE  class = 'BIC-awCxAStH' :value="'BA数据库'"/> 

            <TEXTCODE  class = 'BIC-jtGnnYXZ' :value="'ODS_BA_0_BA_gaap'"/> 

    </div>
</template>

<script>
import RECTANGLE from '../../components/RECTANGLE/RECTANGLE' 
import TEXTCODE from '../../components/TEXTCODE/TEXTCODE' 
import BUTTON from '../../components/BUTTON/BUTTON' 

export default {
  components: {
     RECTANGLE, 
     TEXTCODE, 
     BUTTON, 

  }
}
</script>

<style scoped>

.BIC-CaNZdefB{
                width: 794px;
                height: 504px; 
                position: absolute; 
                left: 59px; 
                top: 41px;
            } 
.BIC-WPEytXSz{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 86px; 
                top: 61px;
            } 
.BIC-mkcptakZ{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 132px; 
                top: 148px;
            } 
.BIC-WWXwynJW{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 132px; 
                top: 224px;
            } 
.BIC-NztaTWbd{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 131px; 
                top: 311px;
            } 
.BIC-DRKWddsx{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 609px; 
                top: 489px;
            } 
.BIC-NETxFJQZ{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 735px; 
                top: 489px;
            } 
.BIC-awCxAStH{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 192px; 
                top: 148px;
            } 
.BIC-jtGnnYXZ{
                width: 210px;
                height: 25px; 
                position: absolute; 
                left: 192px; 
                top: 224px;
            } 

</style>
