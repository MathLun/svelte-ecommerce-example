
<div class="slide-promo">
    <div class="product">1</div>
    <div class="product">2</div>
    <div class="product">3</div>
    <div class="product">4</div>
    <div class="product">5</div>
</div>

<style>
    @media (max-width: 1200px) {
        .slide-promo {
            overflow: hidden;
            display: flex;
            align-items: center;
            width: 100%;
            height: 400px;
            flex: none;
            flex-flow: row nowrap;
            scroll-snap-type: x mandatory;
            scrollbar-width: none;
        }

        .slide-promo > div {
            flex: none;
            width: 98%;
            height: 300px;
            margin: 0 10px;
            background-color: orangered;
            border: 1px solid #ddd;
            scroll-snap-align: center;
        }
    }
</style>

