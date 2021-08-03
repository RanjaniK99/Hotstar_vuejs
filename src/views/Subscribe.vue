<template>
    <div>
        <center>
       <div class="text-white">
           <h5>Subscribe to get more out of Disney+Hotstar</h5> 
        </div>
        <div class="box">
        <div class="tbl">
            <center>
                <table>
                    <tr class=" border-bottom b1">
                        <th></th>
                        <th><button class="bg-success rounded bt">FREE</button></th>
                        <th><button class="bg-warning ms-4  rounded  bt">VIP</button></th>
                        <th><button class="bg-info  rounded ms-3 bt">PREMIUM</button></th>
                   </tr>
                   <tr class="border-bottom ">
                       
                       <td class="size">Unlimited Live</td>
                       <td align="center" class="color:white">&#10006;</td>
                       <td align="center" class="color:white">&#10004;</td>
                       <td align="center" class="color:white">&#10004;</td>
                   </tr>
                   <tr class="line"></tr>
                   <tr  class="border-bottom ">
                    <td class="size">Hotstar Specials & Star serials before TV</td>
                    <td align="center" class="color:white">&#10006;</td>
                       <td align="center" class="color:white">&#10004;</td>
                       <td align="center" class="color:white">&#10004;</td>
                </tr>
                <tr class="line"></tr>
                <tr  class="border-bottom ">
                    <td class="size">Multiplex & new Indian movies</td>
                    <td align="center" class="color:white">&#10006;</td>
                       <td align="center" class="color:white">&#10004;</td>
                       <td align="center" class="color:white">&#10004;</td>
                </tr><tr class="line"></tr>
                
                <tr  class="border-bottom ">
                    <td class="size">Disney+ movies, Hollywood movies & Kids content <br>
                     <span class="c2">   Dubbed in  हिन्दी   ಕನ್ನಡ   বাংলা   తెలుగు</span></td>
                     <td align="center" class="color:white">&#10006;</td>
                    <td class="sub1">Only Dubbed</td>
                    <td class="sub1">English + Dubbed</td>
                </tr><tr class="line"></tr>
                <tr  class="border-bottom ">
                    <td class="size">English shows & Disney+ Originals</td>
                    <td align="center" style="color:white">&#10006;</td>
                    <td align="center" style="color:white">&#10006;</td>
                    <td align="center" style="color:white">&#10004;</td>
                </tr><tr class="line"></tr>
                <tr  class="border-bottom ">
                    <td class="size">Ad free entertainment</td>
                    <td align="center" class="color:white">&#10006;</td>
                    <td align="center" class="color:white">&#10006;</td>
                    <td align="center" class="color:white">&#10004;</td>
                </tr><tr class="line"></tr>
                <tr  class="border-bottom ">
                    <td class="size">Screens you can watch on</td>
                    <td align="center" class="color:white">1</td>
                    <td align="center" class="color:white">1</td>
                    <td align="center" class="color:white">2</td>
                </tr><tr class="line"></tr>
                <tr  class="border-bottom ">
                    <td class="size">Video quality</td>
                    <td class="sub1">SD</td>
                    <td class="sub1">HD</td>
                    <td class="sub1">4K</td>
                </tr><tr class="line"></tr>

                </table>
            </center>
           <br>
        </div>
        <div class="content">
            <div class="txt1">
                <span><button class="bg-success  rounded">VIP</button></span>&nbsp;&nbsp;
                <br>
                <span>₹399/Year</span>
            </div>&nbsp;
            <div class="txt1">
                <span><button  class="bg-warning  rounded">PREMIUM</button></span>&nbsp;&nbsp;
               <br>
                <span>₹1499/Year</span>
            </div>&nbsp;
            <div class="txt1">
                <span><button  class="bg-info  rounded">PREMIUM</button></span>&nbsp;&nbsp;
                <br>
                <span>₹299/Month</span>
            </div>
        </div><br>
        <div class="content2">
          <h4 align="center">CONTINUE</h4>
        </div>
        </div>
        </center>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style>
   .subtit {
  text-align: center;
  text-decoration: none;
  font-size: 28;
  color: white;
  font-weight: bold;
  
}
body {
  background-color: #00264d;
  font-family: "Roboto", "HelveticaNeue-Light", sans-serif;
}

.box {
  height:450px;
  width: 700px;
  text-align: center;
  font-size: 18px;
  font-family: sans-serif;
  background: #27385a;
  color: #fff;
  border-radius: 10px;
}
.c2 {
  color: blue;
}
.bt{
  font-size:13px;
}
.size {
  font-size: 15px;
  color: white;
}

.sub1 {
  text-align: center;
  font-size: 12px;
  color: white;
}
.txt1 {
  border: 2px solid rgb(77, 77, 99);
  border-radius: 10px;
  width: 220px;
  height: 60px;
  display: inline-block;
  font-size: 16px;
  padding-top: 3px;
}
.txt1:hover {
  cursor: pointer;
  background-color: rgb(132, 180, 189);
}
.content2 {
  border: 1px solid #27385a;
  background: rgb(38, 82, 226);
  height: 40px;
  padding-top: 5px;
  border-radius: 10px;
}
.content2 {
  cursor: pointer;
}
@media screen and (min-width: 250px) and (max-width: 380px) {
  .box {
  height:670px;
  width: 380px;
 
}}
@media screen and (min-width: 381px) and (max-width: 550px) {
  .box {
  height:650px;
  width: 420px;
}
}
</style>