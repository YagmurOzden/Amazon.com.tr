<template>
    <div class="div">
        <b-row class="row1">
            <b-col class="col-1"> 
                <i class="fa fa-bars" style="color:white; font-size:34px;"></i>
            </b-col>
            <b-col class="col-1">
               <router-link to="/">
                             <a>
                                <img src="../assets/pic_amazon.png" width=100px style="margin-right: 200px;">
                            </a>
                </router-link>
            </b-col>
            <b-col class="col-4">
                <b-row>
                    <b-col cols="5">
                        <select aria-describedby="searchDropdownDescription" class="nav-search-dropdown searchSelect" 
                            data-nav-digest="0wsxXrBG0/pT/iqluXUXN0Rn2Zw=" 
                            data-nav-selected="0" id="searchDropdownBox" name="url"
                             style="display: block; top: 0px; height:35px" tabindex="5" title="Şurada ara:">
                                <option selected="selected" value="search-alias=aps">Tüm Kategoriler</option>
                                <option value="search-alias=baby">Bebek</option>
                                <option value="search-alias=computers">Bilgisayarlar</option>
                                <option value="search-alias=electronics">Elektronik</option>
                                <option value="search-alias=home">Ev</option>
                                <option value="search-alias=kitchen">Ev ve Mutfak</option>
                                <option value="search-alias=stripbooks">Kitaplar</option>
                                <option value="search-alias=fashion">Moda</option>
                                <option value="search-alias=office-products">Ofis Ürünleri</option>
                                <option value="search-alias=toys">Oyuncaklar ve Oyunlar</option>
                                <option value="search-alias=videogames">PC ve Video Oyunları</option>
                                <option value="search-alias=sports">Spor</option>
                                <option value="search-alias=diy">Yapı Market</option>
                            </select>
                    </b-col>

                  

                    <b-col cols="4"> 
                        <div class="topnav">
                            <div class="search-container">
                                <form action="/action_page.php">
                                <input type="text" placeholder="..." name="search">
                                  <button type="submit"><i class="fa fa-search"></i></button>
                                </form>
                            </div>
                        </div>
                    </b-col>

                 
                   
                    
              
                </b-row>
                  
            </b-col>
            <b-col class="col-2">
              
            </b-col>
            <b-col class="col-2">
               <router-link to="/">
                             <a>
                                <img src="../assets/pic_amazon.png" width=100px style="margin-right: 200px;">
                            </a>
                </router-link>
            </b-col>
            <b-col class="col-1">
              <router-link to="/">
                             <a>
                                <img src="../assets/pic_amazon.png" width=100px style="margin-right: 200px;">
                            </a>
                </router-link>
            </b-col>

        </b-row>

        <b-row class="row2">

        </b-row>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <meta name="viewport" content="width=device-width, initial-scale=1">
    </div>

</template>

<script>
    export default {

        data() {
                return {
                    header_visibility: true,

                }
            },
            methods: {
                header() {
                        this.header_visibility = false;
                    },

                    openNav() {
                        document.getElementById("YanMenuModa").style.width = "0";
                        document.getElementById("YanMenuElektronik").style.width = "0";
                        document.getElementById("YanMenu").style.width = "350px";
                    },

                    openModa() {
                        document.getElementById("YanMenu").style.width = "0";
                        document.getElementById("YanMenuElektronik").style.width = "0";
                        document.getElementById("YanMenuModa").style.width = "350px";
                    },

                    openElektronik() {
                        document.getElementById("YanMenu").style.width = "0";
                        document.getElementById("YanMenuModa").style.width = "0";
                        document.getElementById("YanMenuElektronik").style.width = "350px";
                    },

                    closeNav() {
                        document.getElementById("YanMenu").style.width = "0";
                        document.getElementById("YanMenuModa").style.width = "0";
                        document.getElementById("YanMenuElektronik").style.width = "0";
                    }
            }

    }
</script>

<style>
    .row1 {
        background-color: #232f3e;
    }


    * {box-sizing: border-box;}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #232f3e;
}

.topnav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #2196F3;
  color: white;
}

.topnav .search-container {
  float: right;
}

.topnav input[type=text] {
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  border: none;
}

.topnav .search-container button {
  float: right;
  padding: 6px 10px;
  margin-top: 8px;
  margin-right: 16px;
  background: #ddd;
  font-size: 17px;
  border: none;
  cursor: pointer;
}


@media screen and (max-width: 600px) {
  .topnav .search-container {
    float: none;
  }
  .topnav a, .topnav input[type=text], .topnav .search-container button {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type=text] {
    border: 1px solid #ccc;  
  }
}

</style>
       <!-- <span class="fa fa-bars"
                    role="img" style="
                                        color:white;
                                        font-size:30px;
                                        cursor:pointer; 
                                        margin-left:-150px; 
                                        border:1px 
                                        solid white; 
                                        border-radius: 3px solid white; 
                                        font-size: 25px;     
                                        width: 38px; 
                                        height: 36px;" 
                                        v-on:click="openNav()">

                    </span>
                    <span role="img" 
                        class=" fa fa-bars" 
                        style=" font-size: 25px; cursor: 
                                color:black;
                                pointer; margin-left: -150px; 
                                border: 1px solid white;
                                border-radius: 3px;
                                ">
                    </span> -->