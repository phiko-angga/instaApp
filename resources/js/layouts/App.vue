<template>
    <div>  
        <router-view></router-view>
        
    </div>
  </template>
  
  <script>
  export default {

    data(){
        return{
            video: "https://www.w3schools.com/tags/movie.mp4"
        }
    },
    watch: {
        $route() {
            $("#navbarCollapse").collapse("hide");
        },
    },
  };
  </script>