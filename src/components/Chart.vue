<template>
  <div>
   <header>Chart Gallary</header>
   <div class="mainContainer">
   <div>
   <img src="https://quickchart.io/chart?c={type:'pie',data:{labels:['Hindusim','Buddhism','Sikhism','Chienese','Juddaism','Crishtianity','Islam','Indegenous','Unaffilated'], datasets:[{data:['13','6','0','6','0','31','22','6','16']}]}}" alt="">
   <p>Religion Population Percentage% In World</p>
</div>
<div>
  <img src="https://quickchart.io/chart?bkg=white&c={type:%27bar%27,data:{labels:[2011,2012,2013,2014,2015,2016,2017],datasets:[{label:%27Forest Loss%27,data:[0,5,10,15,20,25,30]}]}}"alt="">
  <p>Tree cover loss in milion hectares in 2017</p>
</div>
<div>
  <img src="https://quickchart.io/chart?c={type:'bar',data:{labels:['January','February', 'March','April', 'May'], datasets:[{label:'Dogs',data:[50,60,70,180,190]},{label:'Cats',data:[100,200,300,400,500]}]}}"" alt="">
</div>
<div>
  <img src="https://quickchart.io/chart?c={type:'doughnut',data:{labels:['State universities','Deemed universities','Central universities','State Private universities', 'Other'],datasets:[{data:[46,31,16,6,1]}]},options:{plugins:{doughnutlabel:{labels:[{text:'550',font:{size:20}},{text:'total'}]}}}}" alt="">
  <p>Universities Percentage% In India</p>
</div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Chart',
  data:()=>({
    picture:"",
    graph:""
  
  }),
  methods:{
    
  }
  

    
  }
  


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header{
  height:50px;
  background-color:blue;
  color:white;
  font-weight:bold;
  font-size:20px;
}
.mainContainer{
width:100%;
height:calc(100% - 50px)
}
.mainContainer div{
  height:200px;
  width:250px;
  outline:5px blue;
}
img{
  height:300px;
  width:300px;

}
.mainContainer{
  display:flex;
  flex-wrap:wrap;
}
.mainContainer div{
  height:400px;
  width:485px;
  border:5px solid blue;
}
</style>
