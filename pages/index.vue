<template>
  <div>
    <div class="container mx-auto">
      <h1 class="font-bold text-center title">Unsanctioned Pro</h1>
      <div class="grid grid-cols-1 gap-1 md:grid-cols-2 md:gap-2 mt-16">
        <div class="logo mx-auto">
          <img src="~/assets/images/logo.png" alt="" class="mx-auto"/>
          <h3 class="text-white text-center">UP 13: I.Y.K.Y.K. <br>
          Friday June 18th, 2021 <br>
          Pro Wrestling Supershow <br>
          King of Clubs | 6252 Busch Blvd<br>
          Start Time: 11:10pm
          </h3>
        </div>
        <div
          class="grid grid-cols-2 lg:grid-cols-4 gap-1 sm:gap-4 justify-items-center content-center links p-2 md:p-0"
        >
          <a href="https://www.instagram.com/unsanctionedpro/" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M11.984 16.815c2.596 0 4.706-2.111 4.706-4.707 0-1.409-.623-2.674-1.606-3.538-.346-.303-.735-.556-1.158-.748-.593-.27-1.249-.421-1.941-.421s-1.349.151-1.941.421c-.424.194-.814.447-1.158.749-.985.864-1.608 2.129-1.608 3.538 0 2.595 2.112 4.706 4.706 4.706zm.016-8.184c1.921 0 3.479 1.557 3.479 3.478 0 1.921-1.558 3.479-3.479 3.479s-3.479-1.557-3.479-3.479c0-1.921 1.558-3.478 3.479-3.478zm5.223.369h6.777v10.278c0 2.608-2.114 4.722-4.722 4.722h-14.493c-2.608 0-4.785-2.114-4.785-4.722v-10.278h6.747c-.544.913-.872 1.969-.872 3.109 0 3.374 2.735 6.109 6.109 6.109s6.109-2.735 6.109-6.109c.001-1.14-.327-2.196-.87-3.109zm2.055-9h-12.278v5h-1v-5h-1v5h-1v-4.923c-.346.057-.682.143-1 .27v4.653h-1v-4.102c-1.202.857-2 2.246-2 3.824v3.278h7.473c1.167-1.282 2.798-2 4.511-2 1.722 0 3.351.725 4.511 2h7.505v-3.278c0-2.608-2.114-4.722-4.722-4.722zm2.722 5.265c0 .406-.333.735-.745.735h-2.511c-.411 0-.744-.329-.744-.735v-2.53c0-.406.333-.735.744-.735h2.511c.412 0 .745.329.745.735v2.53z"
                />
              </svg>
              <h3 class="text-center text-white">Instagram</h3>
              </div
          ></a>
          <a href="https://twitter.com/unsanctionedpro/" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"
                />
              </svg>
              <h3 class="text-center text-white">Twitter</h3>
              </div
          ></a>
          <a href="https://www.facebook.com/unsanctionedpro/" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"
                />
              </svg>
              <h3 class="text-center text-white">Facebook</h3>
              </div
          ></a>
          <a href="https://www.patreon.com/unsanctionedpro/" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <img src="~/assets/images/patreon-1.png" alt="" />
              <h3 class="text-center text-white">Patreon</h3>
              </div
          ></a>
          <a href="https://www.youtube.com/channel/UCUzTM58FKxtTDtr17Cta76A" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"
                />
              </svg>
              <h3 class="text-center text-white">Youtube</h3>
              </div
          ></a>
          <a href="https://www.deathmatchworldwide.com/category/unsanctioned-pro" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M6.496 22.004h10.942v2h-10.942v-2zm-3.744-.35l-2.435-.571-.317 1.35 2.435.571.317-1.35zm18.496 0l2.435-.571.317 1.35-2.435.571-.317-1.35zm-3.253-.432h-12.009v-9.218l-2.664 9-3.019-.721 3.681-16.279 4.003-1.727v-1.242s1.414-1.022 4.004-1.031c2.589-.009 4.003 1.001 4.003 1.001v1.27l4.003 1.729 3.694 16.27-3.003.73-2.693-9v9.218zm-6.004-20.217c1.657 0 3.002.338 3.002.755 0 .416-1.345.754-3.002.754-1.657 0-3.003-.338-3.003-.754 0-.417 1.346-.755 3.003-.755z"
                />
              </svg>
              <h3 class="text-center text-white">Deathmatch WorldWide</h3>
              </div
          ></a>
          <a href="https://unsanctionedpro.bigcartel.com/" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M19 24h-14v-16l-2 1.084-3-3.612 6-5.472h12l6 5.505-3 3.647-2-1.152v16zm-11-23h8c-.365 1.846-1.792 3.5-4 3.5s-3.635-1.708-4-3.5z"
                />
              </svg>
              <h3 class="text-center text-white">Merch</h3>
              </div
          ></a>
          <a href="https://paradigmprowrestling.ticketspice.com/owappwup-triple-threat---pro-wrestling-in-columbus-oh" target="_blank" rel="noopener noreferrer"
            ><div class="socialMedia">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M13.777 19.49l-.466 1.739-12.569-3.378c-.447-.119-.742-.523-.742-.965l.035-.26c.626-2.338 2.22-8.286 2.847-10.625.143-.533.691-.85 1.224-.707 2.381.638 7.892 2.12 12.571 3.371l-.473 1.768.965.262.474-1.772 5.613 1.501c.446.12.741.524.741.966l-.034.259-2.847 10.61c-.12.446-.525.741-.966.741l-.26-.034-5.613-1.478.465-1.736-.965-.262zm5.665 1.301l.259-.966-2.716-.717-.259.966 2.716.717zm-5.406-2.267l.965.261.444-1.658-.965-.262-.444 1.659zm-8.907-4.783l2.594-1.037-2.384-2.386.822-.328 4.03 1.727 2.055-.822c.542-.22 1.399-.081 1.563.329l.028.215c-.034.403-.481.917-.932 1.101l-2.057.822-1.727 4.029-.823.329.083-3.372-2.594 1.038-.614 1.199-.575.23-.044-1.89-1.271-1.399.575-.231 1.271.446zm15.349 3.186l.259-.966-2.717-.717-.259.966 2.717.717zm-5.739-1.028l.965.262.503-1.876-.965-.261-.503 1.875zm6.257-.904l.259-.966-2.717-.717-.259.966 2.717.717zm-5.495-1.937l.964.261.445-1.659-.965-.261-.444 1.659zm6.012.005l.259-.966-2.717-.716-.258.965 2.716.717zm-14.083-8.681l12.528-3.348.259-.034c.442 0 .846.294.966.741l1.833 6.828-15.586-4.187z"
                />
              </svg>
              <h3 class="text-center text-white">Tickets</h3>
              </div
          ></a>
        </div>
      
      </div>
    </div>

    <footer class="h-10 w-full md:absolute bottom-0 sticky pt-2 mt-2">
      <p class="text-center">
        &copy;
        <span id="copyright">
          <script>
            document
              .getElementById("copyright")
              .appendChild(document.createTextNode(new Date().getFullYear()));
          </script>
        </span>
        Unsanctioned Pro || Columbus, OH
      </p>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

html {
  background-color: black;
}

.socialMedia {
  height: 120px;
  width: 120px;
  margin: 1rem 1rem;
}

.title {
  color: #84cc16;
}

.links{
  margin-bottom: 1rem;
}

h3{
  font-size: 14px;
  font-family: 'Press Start 2P', cursive;
}

footer {
  background-color: #84cc16;
}

footer > p {
  color: white;
}

svg {
  fill: #84cc16;
  height: 100%;
  width: 100%;
}

a:hover{
  transform: scale(1.1);
}

.socialMedia > img {
  height: 100%;
  width: 100%;
}
</style>
