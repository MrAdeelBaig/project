<template>
<div class="footer">
    <h2>Ujrat App</h2>
    <p>Copyrights 2022</p>
</div>
</template>
<script>
export default{
    name: 'Footer'
}
</script>
<style>
/* Style the header with a grey background and some padding */
.footer {
  overflow: hidden;
  height: 100px;
}


/* Add media queries for responsiveness - when the screen is 500px wide or less, stack the links on top of each other */
@media screen and (max-width: 500px) {
  .footer{
    float: none;
    display: block;
    text-align: left;
  }
  .footer {
    float: none;
  }
}

</style>