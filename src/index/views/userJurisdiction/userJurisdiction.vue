
<template>
    <div :style="{ position : 'relative' }" >

            <TEXTCODE  class = 'BIC-GyWCQDyM' :value="'角色权限管理'"/> 

            <BUTTON  class = 'BIC-NKnnfKQM'/> 

            <BUTTON  class = 'BIC-dWPaaRXH'/> 

            <RECTANGLE  class = 'BIC-sGHRwGbi'/> 

            <TEXTCODE  class = 'BIC-XRNFmcTc' :value="'角色'"/> 

            <SELECT  class = 'BIC-RMdeYCFy'/> 

            <TEXTCODE  class = 'BIC-xZfGxjtN' :value="'状态'"/> 

            <SELECT  class = 'BIC-MWGsdxKK'/> 

            <BUTTON  class = 'BIC-wTysXffY'/> 

            <BUTTON  class = 'BIC-NWbdDFaR'/> 

            <TABLE  class = 'BIC-AJTNDamP'/> 

            <PAGINATION  class = 'BIC-pDWWKdFJ'/> 

    </div>
</template>

<script>
import TEXTCODE from '../../components/TEXTCODE/TEXTCODE' 
import BUTTON from '../../components/BUTTON/BUTTON' 
import RECTANGLE from '../../components/RECTANGLE/RECTANGLE' 
import SELECT from '../../components/SELECT/SELECT' 
import TABLE from '../../components/TABLE/TABLE' 
import PAGINATION from '../../components/PAGINATION/PAGINATION' 

export default {
  components: {
     TEXTCODE, 
     BUTTON, 
     RECTANGLE, 
     SELECT, 
     TABLE, 
     PAGINATION, 

  }
}
</script>

<style scoped>

.BIC-GyWCQDyM{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 39px; 
                top: 23px;
            } 
.BIC-NKnnfKQM{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 1032px; 
                top: 26px;
            } 
.BIC-dWPaaRXH{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 1171px; 
                top: 26px;
            } 
.BIC-sGHRwGbi{
                width: 1245px;
                height: 106px; 
                position: absolute; 
                left: 59px; 
                top: 81px;
            } 
.BIC-XRNFmcTc{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 80px; 
                top: 121px;
            } 
.BIC-RMdeYCFy{
                width: 180px;
                height: 40px; 
                position: absolute; 
                left: 130px; 
                top: 112px;
            } 
.BIC-xZfGxjtN{
                width: 90px;
                height: 25px; 
                position: absolute; 
                left: 381px; 
                top: 121px;
            } 
.BIC-MWGsdxKK{
                width: 180px;
                height: 40px; 
                position: absolute; 
                left: 426px; 
                top: 114px;
            } 
.BIC-wTysXffY{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 931px; 
                top: 107px;
            } 
.BIC-NWbdDFaR{
                width: 98px;
                height: 40px; 
                position: absolute; 
                left: 1057px; 
                top: 107px;
            } 
.BIC-AJTNDamP{
                width: 1243px;
                height: 240px; 
                position: absolute; 
                left: 60px; 
                top: 231px;
            } 
.BIC-pDWWKdFJ{
                width: 280px;
                height: 30px; 
                position: absolute; 
                left: 1017px; 
                top: 528px;
            } 

</style>
