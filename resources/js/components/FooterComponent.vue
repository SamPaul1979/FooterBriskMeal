<template>
    <div class="container footerBlock" >
        Footer
</div>



</footer>
   

</template>

<script>
    export default {
        mounted() {
            console.log('Footer Component mounted.')
        }
    }
</script>

<style scoped>
.strong-footer-chef {
    color: black;

}
.svg-footer

.footer-mobile-download {
    font-family: sofia-pro, "Helvetica Neue", Arial, sans-serif;
    margin: 16px;
    text-align: center;
    text-decoration: underline;
    font-weight: 400;
    font-size: 22px;
    line-height: 24px;
    color: inherit;
    
}
.google {
    padding-left: 15px;
}

.footer-menu-greenchef {
  text-align: left;
  margin-right: 100px;
  margin-left: 100px;

}

.socialmedia {
    display: flex;
    
} 

.greencheffooter {
    display: flex;
    padding-right: 50px;
}

.footerbottom {
    display: flex;
    margin-right: 30px;
    text-decoration: underline;
}

.instagram {
    margin-left: 35px;
}

footer {
    border-top: 1px solid rgb(204, 204, 204);
    font-family: "Source Sans Pro", Helvetica, Arial, sans-serif;
    line-height: 24px;
    color: #222;
    box-sizing: border-box;
    background-color: rgb(255, 255, 255);
    display: flex;
    border-top: 1px solid rgb(204, 204, 204);
    flex-direction: column;
    margin-bottom: 0px;

    
}

@media  screen and (max-width: 1400px) {
.footer-mobile {
    display: none;
    
}    
}



@media  screen and (max-width: 768px) {
    .footer-mobile {
        display: block;
    }
    
}

.footer-bold-title {
    color: rgb(34, 34, 34);
    font-family: "Source Sans Pro", Helvetica, Arial, sans-serif;
    margin: 0px;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
}






.briskunderline {
    text-decoration: underline;
    padding-top: 12px;
}

.helpAll {
    text-align: left;
}
.helpunderline {
    text-decoration: underline;
    padding-top: 12px;
    
}

.accordionmenu {
    padding-bottom: 4px;
    text-align: left;
    text-decoration: underline;
    
}

.footer-menu {
    display: flex;
    justify-content: space-between;
    color: inherit;
    font-family: "Source Sans Pro", Helvetica, Arial, sans-serif;
    margin-top: 50px;
    margin-bottom: 70px;
    font-weight: 400;
    font-size: 14px;
    
}

@media  screen and (max-width: 768px) {
    .footer-menu {
        display: none;
    }
    
}

.footer-menu-left {
    display: flex;
    

}




    

.download {
    text-align: left;
    
}







.footerbottomall {
    display: flex;
    padding: 28px;
    border-top: 1px solid rgb(204, 204, 204);
    justify-content: space-around;

    

}

.manage {
    margin-right: 100px;
    display: flex;
}

@media  screen and (max-width: 768px) {
    .manage {
        display: none;
    }
    
}


</style>
