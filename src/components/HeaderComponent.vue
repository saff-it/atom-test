<template>
    <header class="container p-0">

        <div class="ms_empty-box">
            <div class="ms_empty-box-disappear d-none">
                <ul>
                    <li>Contribuisci</li>
                    <li>Abbonamenti</li>
                </ul>
            </div>

            <div class="ms_header-avatar ms_empty-box-disappear d-none">
                <i class="bi bi-person"></i>
                <span>Accedi</span>
            </div>
        </div>

        <div class="row ms_header-btns">
            <div class="col-6 text-center p-0">
                <div class="ms_header-btn border-end border-dark">
                    <h6>Contribuisci</h6>
                </div>
            </div>

            <div class="col-6 text-center p-0">
                <div class="ms_header-btn">
                    <h6>Abbonati</h6>
                </div>
            </div>
        </div>

        <div class="row justify-content-between ms_header-icons">
            <div class="col-6 ms_header-icon">
                <i class="bi bi-list"></i>
            </div>

            <div class="col-6 ms_header-icon">
                <i class="bi bi-search"></i>
            </div>
        </div>

        <nav class="ms_header-nav d-none">
            <ul>
                <li>Tutti i temi</li>
                <li>Ambiente</li>
                <li>Economia</li>
                <li>Mondo</li>
                <li>Non Profit</li>
                <li>Politica</li>
                <li>Società</li>
                <li>Welfare</li>
            </ul>

            <div class="ms_nav-icons">
                <span>Aa</span>
                <i class="bi bi-image"></i>
            </div>
        </nav>

    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../styles/general.scss";
@import "../styles/mediaQuery.scss";

div.ms_empty-box {
    height: 30px;
    display: flex;
    justify-content: space-between;
    border: 1px solid black;
    border-bottom: none;

    ul{
        list-style: none;
        height: 100%;
        padding: 0;
        margin-left: 15px;
        display: flex;
        align-items: center;


        li{
            display: inline-block;
            margin: 5px;
            font-weight: bold;
            font-size: 0.5rem;
        }
    }

    div.ms_header-avatar{
        font-weight: bold;
        margin-right: 20px;

        i{
            font-size: 0.9rem;
            margin-right: 4px;
            vertical-align: middle;

        }

        span{
            font-size: 0.5rem;
            vertical-align: middle;
        }
    }
}

div.ms_header-btns {
    height: 30px;
    border: 1px solid black;
    display: flex;
    align-items: center;
    margin: 0;


    div.ms_header-btn {
        // border-right: 1px solid black;
        height: 30px;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;

        h6 {
            font-size: 0.7rem;
            vertical-align: middle;
            margin: 0;
        }
    }
}

div.ms_header-icons{
    height: 35px;
    border-bottom: 1px solid black;
    margin: 0;


    div.ms_header-icon{
        width: 35px;
        height: 100%;
        display: flex;
        align-items: center;
        border-right: 1px solid black;
        border-left: 1px solid black;

        i{
            color: red;
            text-align: center;
            width: 100%;
            font-size: 0.8rem;
        }
    }
    
}

nav.ms_header-nav{
    display: flex;
    justify-content: space-between;
    height: 50px;
    width: 100%;
    border-bottom: 1px solid black;
    border-right: 1px solid black;
    border-left: 1px solid black;
    // padding: 0;

    ul{
        list-style: none;
        height: 100%;
        margin: 0;
        padding: 20px;
        display: flex;
        align-items: center;


        li{
            display: inline-block;
            margin-right: 25px;
            font-weight: bold;
            font-size: 0.9rem;
        }
    }

    div.ms_nav-icons{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 70px;

        span{
            font-size: 0.7rem;
            margin-right: 5px;
        }
    }
}



</style>