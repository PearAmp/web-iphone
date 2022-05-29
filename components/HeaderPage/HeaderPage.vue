<template>
<div class="container">
   <div class="nav">
       <ul class="nav-list nav-list-mobile">
           <li class="nav-item">
               <div class="mobile-menu">
                   <span class="line line-top"></span>
                   <span class="line line-bottom"></span>
               </div>
           </li>
           <li class="nav-item">
               <a href="#" class="nav-link nav-link-apple"></a>
           </li>
           <li class="nav-item">
               <a href="#" class="nav-link nav-link-bag"></a>
           </li>
       </ul>

       <!-- ========mobile ======== -->
       <ul class="nav-list nav-list-larger">
           
           <li class="nav-item nav-item-hidden">
               <a href="#" class="nav-link nav-link-apple"></a>
           </li>
           <li class="nav-item">
               <a href="#" class="nav-link nav-link-bag"></a>
           </li>
       </ul>
   </div>
</div>
  
</template>

<script>
export default {
    name: 'HeaderPage'

}
</script>

<style lang="scss" scoped>

.container {
    background-color: aqua;
    width: 100%;
    max-width: 1420px;
    

}
</style>