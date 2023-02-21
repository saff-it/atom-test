<template>
  <div>

    <span class="ms_box-tag">Migranti</span>
    <h5>Roccella Jonica, la Lampedusa che l'Italia ignora</h5>
    
    <div class="d-flex my-4 ms_mquery-big-screen">
        <div class="ms_box-avatar-container">
            <img src="https://loremflickr.com/150/150?random=1" alt="avatar">
        </div>

        <div class="ms_box-author-details">
            <span class="ms_box-date">Di Alex BIBI</span>
            <span>29 luglio</span>
        </div>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

div.ms_box-avatar-container{
    width: 30px;
    display: flex;
    align-items: center;

    img{
        width: 100%;
        border-radius: 50%;
    }
}
span.ms_box-tag{
    font-size: 0.6rem;
    font-weight: bold;
    border: 1px solid;
    box-shadow: 1.5px 1.5px black;
    padding: 2px 6px;
    border-radius: 2px;
    background-color: white;
    color: black;
}

h5{
    width: 80%;
    margin: 15px 0;
}

div.ms_box-author-details{
    line-height: 14px;
    display: flex;
    flex-direction: column;
    justify-content: center;

    span{
        font-size: 0.5rem;
        margin-left: 8px;
    }

    span.ms_box-date{
        font-size: 0.7rem;

    }
    
}

</style>