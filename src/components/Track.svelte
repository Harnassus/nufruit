<script>

</script>

<div class="flex">
    <div>
        <h1>
            Track<br />
            anywhere,<br />
            anytime.<br />
        </h1>
        <div class="card-container w-[350px] bg-black">
            <div class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-2">
                <img src="assets/banana.png" class="w-[102px] h-[97px]" alt="">
                <h2>Banana</h2>
                <p>Without skin</p>
            </div>
             <div class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-2">
                <img src="assets/banana.png" class="w-[102px] h-[97px]" alt="">
                <h2>Banana Bread</h2>
                <p>Backing Mix</p>
            </div>
             <div class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-2">
                <img src="assets/taco.png" class="w-[102px] h-[97px]" alt="">
                <h2>Taco 5 Ripe</h2>
                <p>Ready Bananas</p>
            </div>
             <div class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-2">
                <img src="assets/bottle.png" class="w-[32px] h-[97px]" alt="">
                <h2>Flavour Mild</h2>
                <p>Plant based</p>
            </div>
        </div>
    </div>
    <div>
        <p>
            Over 250,000 foods with photos. Plus barcode scanning App.
        </p>
        <div>
           <img src="" alt=""> 
        </div>
    </div>
</div>

<style>
    .card-container{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 1em;
   }
   .card-container > div{
    border-radius: 25px;
   }
   .card-container > div:nth-of-type(2){
    grid-column: 2;
    grid-row: 1 / 3 ;
    align-self: center;
    justify-self: center;
   }
   .card-container > div:nth-of-type(4){
    grid-column: 2;
    grid-row: 2 / 20;
    align-self: center;
    justify-self: center;
   }
</style>