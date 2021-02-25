<template functional>
  <div class="p-grid p-d-flex p-ai-center">
    <div class="p-col-12 p-md-7">
      <div class="presentation">
        <img src="/emilianocorreia.jpeg" />
        <span>Emiliano Correia</span>
        <h1>Fullstack Javascript Developer</h1>
        <h2>Vuejs Specialist</h2>
        <div class="presentation__social-midias">
          <a href="https://github.com/emilianoamorim" target="_blank">
            <img
              width="30"
              src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjwhRE9DVFlQRSBzdmcgIFBVQkxJQyAnLS8vVzNDLy9EVEQgU1ZHIDEuMC8vRU4nICAnaHR0cDovL3d3dy53My5vcmcvVFIvMjAwMS9SRUMtU1ZHLTIwMDEwOTA0L0RURC9zdmcxMC5kdGQnPjxzdmcgZW5hYmxlLWJhY2tncm91bmQ9Im5ldyAwIDAgMzIgMzIiIGhlaWdodD0iMzJweCIgaWQ9IkxheWVyXzEiIHZlcnNpb249IjEuMCIgdmlld0JveD0iMCAwIDMyIDMyIiB3aWR0aD0iMzJweCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayI+PHBhdGggY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTYuMDAzLDBDNy4xNywwLDAuMDA4LDcuMTYyLDAuMDA4LDE1Ljk5NyAgYzAsNy4wNjcsNC41ODIsMTMuMDYzLDEwLjk0LDE1LjE3OWMwLjgsMC4xNDYsMS4wNTItMC4zMjgsMS4wNTItMC43NTJjMC0wLjM4LDAuMDA4LTEuNDQyLDAtMi43NzcgIGMtNC40NDksMC45NjctNS4zNzEtMi4xMDctNS4zNzEtMi4xMDdjLTAuNzI3LTEuODQ4LTEuNzc1LTIuMzQtMS43NzUtMi4zNGMtMS40NTItMC45OTIsMC4xMDktMC45NzMsMC4xMDktMC45NzMgIGMxLjYwNSwwLjExMywyLjQ1MSwxLjY0OSwyLjQ1MSwxLjY0OWMxLjQyNywyLjQ0MywzLjc0MywxLjczNyw0LjY1NCwxLjMyOWMwLjE0Ni0xLjAzNCwwLjU2LTEuNzM5LDEuMDE3LTIuMTM5ICBjLTMuNTUyLTAuNDA0LTcuMjg2LTEuNzc2LTcuMjg2LTcuOTA2YzAtMS43NDcsMC42MjMtMy4xNzQsMS42NDYtNC4yOTJDNy4yOCwxMC40NjQsNi43Myw4LjgzNyw3LjYwMiw2LjYzNCAgYzAsMCwxLjM0My0wLjQzLDQuMzk4LDEuNjQxYzEuMjc2LTAuMzU1LDIuNjQ1LTAuNTMyLDQuMDA1LTAuNTM4YzEuMzU5LDAuMDA2LDIuNzI3LDAuMTgzLDQuMDA1LDAuNTM4ICBjMy4wNTUtMi4wNyw0LjM5Ni0xLjY0MSw0LjM5Ni0xLjY0MWMwLjg3MiwyLjIwMywwLjMyMywzLjgzLDAuMTU5LDQuMjM0YzEuMDIzLDEuMTE4LDEuNjQ0LDIuNTQ1LDEuNjQ0LDQuMjkyICBjMCw2LjE0Ni0zLjc0LDcuNDk4LTcuMzA0LDcuODkzQzE5LjQ3OSwyMy41NDgsMjAsMjQuNTA4LDIwLDI2YzAsMiwwLDMuOTAyLDAsNC40MjhjMCwwLjQyOCwwLjI1OCwwLjkwMSwxLjA3LDAuNzQ2ICBDMjcuNDIyLDI5LjA1NSwzMiwyMy4wNjIsMzIsMTUuOTk3QzMyLDcuMTYyLDI0LjgzOCwwLDE2LjAwMywweiIgZmlsbD0iIzE4MTYxNiIgZmlsbC1ydWxlPSJldmVub2RkIi8+PGcvPjxnLz48Zy8+PGcvPjxnLz48Zy8+PC9zdmc+"
            />
          </a>
          <a
            href="https://www.linkedin.com/in/emilianocorreia/"
            target="_blank"
          >
            <img
              width="30"
              src="data:image/png;base64,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"
            />
          </a>
          <a
            href="https://api.whatsapp.com/send?phone=5521965076602&text=Hello!"
            target="_blank"
          >
            <img
              width="34"
              src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgaGVpZ2h0PSI1Ni42OTM0cHgiIGlkPSJMYXllcl8xIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1Ni42OTM0IDU2LjY5MzQ7IiB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCA1Ni42OTM0IDU2LjY5MzQiIHdpZHRoPSI1Ni42OTM0cHgiIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxnPjxwYXRoIGQ9Ik0yOS43NTE4LDE2LjE3MzRjLTYuNzc2NiwwLTEyLjI4NzksNS41MTA4LTEyLjI5MDUsMTIuMjg0NGMtMC4wMDEsMi4zMjE0LDAuNjQ4Niw0LjU4MjEsMS44NzgzLDYuNTM4MWwwLjI5MjIsMC40NjQ4ICAgbC0xLjI0MTEsNC41MzM0bDQuNjQ5OC0xLjIxOTdsMC40NDg1LDAuMjY2MmMxLjg4NjMsMS4xMTkzLDQuMDQ4NSwxLjcxMTYsNi4yNTI5LDEuNzEyNWgwLjAwNSAgIGM2Ljc3MTUsMCwxMi4yODI2LTUuNTExMywxMi4yODUzLTEyLjI4NTVjMC4wMDEzLTMuMjgyNi0xLjI3NTQtNi4zNjkzLTMuNTk0OC04LjY5MTUgICBDMzYuMTE3OSwxNy40NTQxLDMzLjAzMzIsMTYuMTc0NCwyOS43NTE4LDE2LjE3MzR6IE0zNi45NzgxLDMzLjczOTljLTAuMzA3NywwLjg2MjYtMS43ODMzLDEuNjUtMi40OTI5LDEuNzU2ICAgYy0wLjYzNjQsMC4wOTUyLTEuNDQxNSwwLjEzNDgtMi4zMjYyLTAuMTQ2M2MtMC41MzY0LTAuMTcwMi0xLjIyNDMtMC4zOTc1LTIuMTA1NS0wLjc3OCAgIGMtMy43MDQ5LTEuNTk5OC02LjEyNDYtNS4zMzAxLTYuMzA5Mi01LjU3NjdjLTAuMTg0Ni0wLjI0NjQtMS41MDgxLTIuMDAyNi0xLjUwODEtMy44MjA2YzAtMS44MTc3LDAuOTU0Mi0yLjcxMTMsMS4yOTI3LTMuMDgxMSAgIGMwLjMzODQtMC4zNjk2LDAuNzM4Ni0wLjQ2MjEsMC45ODQ4LTAuNDYyMWMwLjI0NjIsMCwwLjQ5MjcsMC4wMDIzLDAuNzA3OCwwLjAxM2MwLjIyNjcsMC4wMTE1LDAuNTMxMi0wLjA4NjEsMC44MzExLDAuNjM0ICAgYzAuMzA3NywwLjczOTYsMS4wNDYzLDIuNTU3NSwxLjEzODcsMi43NDI0YzAuMDkyNCwwLjE4NDgsMC4xNTM5LDAuNDAwNSwwLjAzMDgsMC42NDdjLTAuMTIzMSwwLjI0NjMtMC4xODQ2LDAuNDAwNS0wLjM2OTMsMC42MTYxICAgYy0wLjE4NDYsMC4yMTU3LTAuMzg3OSwwLjQ4MTUtMC41NTQsMC42NDdjLTAuMTg0OSwwLjE4NDItMC4zNzc0LDAuMzg0MS0wLjE2MiwwLjc1MzdjMC4yMTU1LDAuMzY5OSwwLjk1NjcsMS41NzkyLDIuMDU0NywyLjU1ODYgICBjMS40MTA2LDEuMjU4MiwyLjYwMDcsMS42NDgyLDIuOTcsMS44MzMxYzAuMzY5MywwLjE4NSwwLjU4NDgsMC4xNTM5LDAuODAwMi0wLjA5MjRjMC4yMTU1LTAuMjQ2NSwwLjkyMzMtMS4wNzg1LDEuMTY5NS0xLjQ0ODIgICBjMC4yNDYyLTAuMzY5NiwwLjQ5MjQtMC4zMDgsMC44MzA5LTAuMTg0OGMwLjMzODUsMC4xMjM0LDIuMTU0NCwxLjAxNjcsMi41MjM3LDEuMjAxNWMwLjM2OTMsMC4xODQ5LDAuNjE1NSwwLjI3NzQsMC43MDc4LDAuNDMxNSAgIEMzNy4yODU5LDMyLjEzNzUsMzcuMjg1OSwzMi44NzcsMzYuOTc4MSwzMy43Mzk5eiIvPjxwYXRoIGQ9Ik0yOS4yMDY2LDQuMzczNmMtMTMuNTk5NiwwLTI0LjYyNSwxMS4wMjM0LTI0LjYyNSwyNC42MjNzMTEuMDI1NCwyNC42MjUsMjQuNjI1LDI0LjYyNSAgIGMxMy41OTg2LDAsMjQuNjI0LTExLjAyNTQsMjQuNjI0LTI0LjYyNVM0Mi44MDUyLDQuMzczNiwyOS4yMDY2LDQuMzczNnogTTI5Ljc0Nyw0My4yNDk2ICAgQzI5Ljc0NjUsNDMuMjQ5NiwyOS43NDczLDQzLjI0OTYsMjkuNzQ3LDQzLjI0OTZoLTAuMDA2MWMtMi40NzM4LTAuMDAwOS00LjkwNDctMC42MjE2LTcuMDYzNS0xLjc5OTFsLTcuODM1NywyLjA1NTRsMi4wOTctNy42NTk0ICAgYy0xLjI5MzUtMi4yNDE2LTEuOTc0MS00Ljc4NDMtMS45NzMtNy4zODk1YzAuMDAzMi04LjE0OTYsNi42MzQxLTE0Ljc4LDE0Ljc4MTItMTQuNzhjMy45NTQsMC4wMDE2LDcuNjY1MywxLjU0MDksMTAuNDU1OSw0LjMzNDggICBjMi43OTA3LDIuNzkzOCw0LjMyNjgsNi41MDc0LDQuMzI1MywxMC40NTdDNDQuNTI0NiwzNi42MTg1LDM3Ljg5MzMsNDMuMjQ5NiwyOS43NDcsNDMuMjQ5NnoiLz48L2c+PC9zdmc+"
            />
          </a>
        </div>
      </div>
    </div>
    <div class="p-col-12 p-md-5">
      <div class="about-us">
        <p>
          Developer for over 7 years, I worked with teams on large and small
          projects always adding knowledge and helping to create and scale
          applications and incredible products.
        </p>
        <p>
          In my spare time I work as a full stack javascript developer and
          consultant.
        </p>
        <h3>technologies</h3>
        <div class="about-us__technologies">
          <img width="40" height="40" src="/nodejs.png" />
          <img width="40" height="40" src="/typescript.png" />
          <img width="40" height="40" src="/webpack.png" />
          <img width="40" height="40" src="/vuejs.png" />
          <img width="40" height="40" src="/quasar.png" />
          <img width="40" height="40" src="/sass.png" />
          <img width="40" height="40" src="/git.png" />
          <img width="50" height="45" src="/docker.png" />
          <img width="50" height="45" src="/mongodb.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.p-grid {
  height: 100vh;
}
.presentation {
  display: flex;
  flex-direction: column;
  align-items: center;
  &__social-midias {
    margin: 10px 0 0;
    & img {
      &:last-child {
        cursor: pointer;
      }
      margin: 7px;
    }
  }
  & > img {
    width: 20%;
    border-radius: 200px;
    margin: 0 0 20px;
    @media (max-width: 576px) {
      width: 60%;
    }
  }
  & > span {
    font-family: "Aileron Light";
    font-size: 1.5em;
    @media (max-width: 576px) {
      font-size: 2em;
    }
  }
  & h1 {
    font-family: "Aileron Black";
    font-size: 2.3em;
    margin: 0;
    text-align: center !important;
    color: #333333;
    @media (max-width: 576px) {
      font-size: 1.1em;
    }
  }
  & h2 {
    font-family: "Aileron Black";
    font-size: 2em;
    margin: 0;
    background: #42b883;
    background: -webkit-linear-gradient(to right, #42b883 32%, #35495e 79%);
    background: -moz-linear-gradient(to right, #42b883 32%, #35495e 79%);
    background: linear-gradient(to right, #42b883 32%, #35495e 79%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    @media (max-width: 576px) {
      font-size: 1.8em;
    }
  }
}
.about-us {
  & p {
    font-family: "Aileron Light";
    font-size: 1.1em;
    line-height: 28px;
    @media (max-width: 576px) {
      font-size: 1em;
    }
  }
  & h3 {
    font-family: "Aileron Heavy";
  }
  &__technologies {
    display: flex;
    @media (max-width: 576px) {
      flex-wrap: wrap;
      justify-content: center;
    }
    & img {
      margin: 8px;
      -webkit-touch-callout: none;
      -webkit-user-select: none;
      -khtml-user-select: none;
      -moz-user-select: none;
      -ms-user-select: none;
      user-select: none;
    }
  }
}
</style>