<template>
  <div>
    <div class="container mx-auto">
      <h1 class="font-bold text-center title">Unsanctioned Pro</h1>
      <div class="grid grid-cols-1 gap-1 md:grid-cols-2 md:gap-2 mt-16">
        <div class="logo mx-auto">
          <img src="~/assets/images/logo.png" alt="" />
        </div>
        <div class="grid grid-cols-4 gap-1 sm:gap-4 justify-items-center content-center">
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
          <a href="http://" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">Test</div></a
          >
        </div>
      </div>
    </div>
    
    <footer class="h-10 w-full md:absolute bottom-0 pt-2 mt-2">
      <p class="text-center">
        &copy;
        <span id="copyright">
          <script>
            document
              .getElementById("copyright")
              .appendChild(document.createTextNode(new Date().getFullYear()));
          </script>
        </span>
        Unsanctioned Pro
      </p>
    </footer>
  
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

html {
  background-color: black;
}

.socialMedia {
  background-color: white;
  height: 120px;
  width: 120px;
}

.title {
  color: #84cc16;
}

footer {
  background-color: #84cc16;
}

footer > p {
  color: white;
}
</style>
