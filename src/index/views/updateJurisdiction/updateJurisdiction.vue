
<template>
    <div :style="{ position : 'relative' }" >

            <RECTANGLE  class = 'BIC-hWQZKirC'/> 

            <TEXTCODE  class = 'BIC-DniZaich' :value="'角色权限'"/> 

            <TEXTCODE  class = 'BIC-TKCmTYAm' :value="'角色名称：'"/> 

            <INPUT  class = 'BIC-MccAWEtT'/> 

            <TEXTCODE  class = 'BIC-aXCtdDce' :value="'权限选择'"/> 

            <RECTANGLE  class = 'BIC-HxjJtpmG'/> 

            <CHECKBOX  class = 'BIC-xjTzWrhn'/> 

            <BUTTON  class = 'BIC-YwXTTJbT'/> 

            <BUTTON  class = 'BIC-tcikcjXp'/> 

    </div>
</template>

<script>
import RECTANGLE from '../../components/RECTANGLE/RECTANGLE' 
import TEXTCODE from '../../components/TEXTCODE/TEXTCODE' 
import INPUT from '../../components/INPUT/INPUT' 
import CHECKBOX from '../../components/CHECKBOX/CHECKBOX' 
import BUTTON from '../../components/BUTTON/BUTTON' 

export default {
  components: {
     RECTANGLE, 
     TEXTCODE, 
     INPUT, 
     CHECKBOX, 
     BUTTON, 

  }
}
</script>

<style scoped>

.BIC-hWQZKirC{
                width: 862px;
                height: 701px; 
                position: absolute; 
                left: 78px; 
                top: 56px;
            } 
.BIC-DniZaich{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 135px; 
                top: 93px;
            } 
.BIC-TKCmTYAm{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 240px; 
                top: 188px;
            } 
.BIC-MccAWEtT{
                width: 269px;
                height: 40px; 
                position: absolute; 
                left: 314px; 
                top: 180px;
            } 
.BIC-aXCtdDce{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 240px; 
                top: 274px;
            } 
.BIC-HxjJtpmG{
                width: 429px;
                height: 322px; 
                position: absolute; 
                left: 313px; 
                top: 265px;
            } 
.BIC-xjTzWrhn{
                width: 211px;
                height: 20px; 
                position: absolute; 
                left: 336px; 
                top: 281px;
            } 
.BIC-YwXTTJbT{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 620px; 
                top: 676px;
            } 
.BIC-tcikcjXp{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 775px; 
                top: 676px;
            } 

</style>
