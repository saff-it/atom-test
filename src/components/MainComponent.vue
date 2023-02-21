<template>
  <main>

    <!-- filters' bar  -->
    <section class="container d-flex flex-column my-4 ms_first-section">

      <div class="row align-items-center">
        <h2 class="m-0">Tutti i temi</h2>
      </div>

      <div class="ms_filter-btns">
        <ul>
          <li>Ambiente</li>
          <li>Economia</li>
          <li>Mondo</li>
          <li>Non Profit</li>
          <li>Politica</li>
          <li>Società</li>
          <li>Welfare</li>
        </ul>
      </div>

    </section>

    <!-- section - line 1  -->
    <section class="container p-0">
      <div>

        <div class="ms_top-box">
          <img src="https://loremflickr.com/1900/1200?random=10" alt="article-img">

          <div class="ms_absolute-paragraph">
            <ParagraphBox />
          </div>
        </div>

      </div>
    </section>

    <!-- section - line 2  -->
    <section class="container">
      <div class="row">
        <div class="col-12 col-lg-8 mt-3 ms_line-2-square-mquery">

          <div class="ms_line-2-square">

            <div class="ms_line-2-square-img">
              <img src="https://loremflickr.com/1900/1200?random=6" alt="article-img">
            </div>

            <div class="ms_line-2-absolute-text mt-2">
              <ParagraphBox />
            </div>

          </div>

        </div>

        <div class="col-12 col-lg-4 ms_line-2-boxes-mquery">

          <div class="border-bottom border-top border-dark ms_line-2-top-square">
            <img class="d-none" src="https://loremflickr.com/1900/1200?random=4" alt="article-img">
            <ParagraphBox class="ms_smaller-paragraph" />
          </div>

          <div class="ms_line-2-bottom-square">
            <img class="d-none" src="https://loremflickr.com/1900/1200?random=5" alt="article-img">
            <ParagraphBox class="ms_smaller-paragraph " />
          </div>

        </div>
      </div>






    </section>

    <!-- section - line 3  -->
    <section class="container ms_line-3-container">
      <div class="ms_line-3-text">
        <h5>Il tuo supporto è fondamentale</h5>
        <span>Dai il tuo contributo <i class="bi bi-arrow-right"></i></span>
      </div>
    </section>

    <!-- section - line 4  -->
    <section class="container">
      <div class="row">

        <div class="col-12 col-lg-4 ms_red-square ms_square-sizing">
          <ParagraphBox class="mt-2 ms_smaller-text" />
        </div>

        <div class="col-12 col-lg-4 ms_square-sizing">
          <img class="d-none" src="https://loremflickr.com/1900/1200?random=12" alt="article-img">
          
          <ParagraphBox class="mt-2 ms_smaller-text" />
        </div>

        <div class="col-12 col-lg-4 ms_square-sizing">
          <img class="d-none" src="https://loremflickr.com/1900/1200?random=13" alt="article-img">
          
          <ParagraphBox class="mt-2 ms_smaller-text" />
        </div>

      </div>
    </section>

    <!-- section - line 5  -->
    <section></section>

    <!-- section - line 6  -->

    
  </main>
</template>

<script>
import ParagraphBox from '../components/ParagraphBox.vue'

export default {
  name: 'MainContainer',
  components: {
    ParagraphBox,

  }
}
</script>

<style lang="scss">
// filters bar 

div.ms_filter-btns ul {
  list-style: none;
  height: 100%;
  margin-top: 5px;
  padding: 0;
  display: flex;
  align-items: center;
  flex-wrap: wrap;

  li {
    display: inline-block;
    margin: 8px 6px 0 0;
    font-weight: bold;
    font-size: 0.7rem;
    border: 1px solid;
    box-shadow: 1.5px 1.5px black;
    padding: 5px 8px;
    border-radius: 3px;
  }
}

// section - line 1

div.ms_top-box {
  width: 100%;
  height: 350px;
  position: relative;

  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  div.ms_absolute-paragraph {
    position: absolute;
    left: 25px;
    top: 150px;
    color: white;
  }
}

// section - line 2 

div.ms_line-2-square {
  width: 100%;

  div.ms_line-2-square-img {
    width: 100%;

    img {
      width: 100%;

    }
  }
}

.ms_smaller-paragraph {
  margin-top: 10px;

  h5 {
    font-size: 0.8rem;
    font-weight: bolder;
  }
}

// section - line 3 
.ms_line-3-container {
  background-color: blanchedalmond;
  border-top: 1px solid black;
  border-bottom: 1px solid black;


  div.ms_line-3-text {
    height: 120px;
    display: flex;
    flex-direction: column;
    justify-content: center;


    h5 {
      width: 85%;
      font-weight: bold;
      margin-left: 10px;
    }

    span {
      font-size: 0.7rem;
      font-weight: bold;
    }

  }
}

// section - line 4 

.ms_red-square {
  background-color: red;
  color: white;
}

.ms_smaller-text {
  border-bottom: 1px solid black;
  
  h5 {
    font-size: 0.8rem;
    font-weight: bold;
  }
}



</style>