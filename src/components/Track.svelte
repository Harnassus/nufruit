<script>

</script>

<div class="w-screen">
    <div class="flex justify-between max-w-[1024px] mx-auto mt-[10em]">
        <div class="text-[#130F49] relative">
            <div class="flex flex-col gap-10">
                    <h1 class="text-[80px] leading-none-1  font-bold">
                    Track<br />
                    anywhere,<br />
                    anytime.<br /></h1>

                <div class="card-container w-[300px] ml-20">
                    <div 
                        class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-4 ">
                        <img src="assets/banana.png" class="w-[102px] h-[97px]" alt="">
                        <div class="flex flex-col items-center justify-center gap-1">
                            <h2 class="font-bold">Banana</h2>
                        <p class="opacity-40">Without skin</p>
                        </div>
                    </div>
                    <div 
                        class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-4 ">
                        <img src="assets/banana.png" class="w-[102px] h-[97px]" alt="">
                        <div class="flex flex-col items-center justify-center gap-1">
                            <h2 class="font-bold">Banana Bread</h2>
                        <p class="opacity-40">Backing Mix</p>
                        </div>
                    </div>
                    <div 
                        class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-4 ">
                        <img src="assets/taco.png" class="w-[102px] h-[97px]" alt="">
                        <div class="flex flex-col items-center justify-center gap-1">
                            <h2 class="font-bold">Taco 5 Ripe</h2>
                        <p class="opacity-40">Ready Bananas</p>
                        </div>
                    </div>
                    <div 
                        class="flex flex-col h-[226px] w-[148px] bg-white items-center justify-center gap-4 ">
                        <img src="assets/bottle.png" class="w-[34px] h-[97px]" alt="">
                        <div class="flex flex-col items-center justify-center gap-1">
                            <h2 class="font-bold">Flavour Mild</h2>
                        <p class="opacity-40">Plant based</p>
                        </div>
                    </div>
                </div>
            </div>
          
                <svg class="z-[-1] absolute wavy-bg" width="782" height="889" viewBox="0 0 782 889" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path opacity="0.8" fill-rule="evenodd" clip-rule="evenodd" d="M600.516 604.504C546.826 692.71 566.739 835.735 472.657 878.33C379.278 920.608 283.905 819.981 185.102 792.582C89.116 765.964 -23.8375 787.548 -97.2995 720.274C-174.164 649.886 -205.825 539.255 -205.308 435.063C-204.81 334.908 -155.288 243.33 -94.5354 163.719C-37.9901 89.6196 33.2093 17.3823 125.164 2.00143C211.189 -12.3878 280.145 71.3159 366.012 86.6841C463.564 104.144 574.311 40.6387 655.846 96.9808C740.955 155.793 791.486 270.141 780.278 372.948C769.421 472.531 652.596 518.943 600.516 604.504Z" fill="#FEDFB1"
                    />
                </svg> 
            
        </div>

        <div class="flex flex-col text-[#130F49] gap-[7em]">
            <h4 class="opacity-40 text-4xl w-[392px]">
                Over 250,000 foods with photos. Plus barcode scanning App.
            </h4>

            <div class="flex items-start gap-10">
            <img src="assets/percent.svg" alt=""> 

            <div class="flex flex-col gap-6 mt-6">
                <h5 class="font-bold text-2xl">Our Well Balanced</h5>
                <p class="text-xl opacity-40 w-[304px]">
                    Goal is the one we recommend for most people. However, if you have specific dietary requirements.
                </p>
            </div>
            </div>

            <div class="flex items-start gap-10">
            <img src="assets/barcode.svg" alt=""> 
            <div class="flex flex-col gap-6 mt-6">
                <h5 class="font-bold text-2xl">Barcode Scanner</h5>
                <p class="text-xl opacity-40 w-[304px]">
                App on your phone or tablet. Or keep a food diary online via the website – whichever suits you best.
                </p>
            </div>
            </div>
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
    margin-top: 3em;
    align-self: start;
    justify-self: center;
   }
   .card-container > div:nth-of-type(3){
    margin-top: -3em;
   }
   .card-container > div:nth-of-type(4){
    
    align-self: center;
    justify-self: center;
   }
   .wavy-bg{
    top: 20%;
    right: -20%;
   }
</style>