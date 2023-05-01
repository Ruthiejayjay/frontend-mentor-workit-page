<template>
    <section class="relative -mt-16 w-full overflow-hidden">
        <div class="relative z-10 mx-auto  mt-32 flex gap-8 justify-center content">
            <div class="mt-20 texts-first">
                <div class="flex flex-col w-52 items-center text-dark-purple">
                    <div
                        class="flex justify-center items-center w-8 h-8 bg-white border border-davy-grey rounded-full text-center">
                        <h1 class="font-semibold">1</h1>
                    </div>
                    <div class="mt-6">
                        <h2 class="font-black text-xl">Actionable insights</h2>
                    </div>
                    <p class="text-xs text-center"> Optimize your products, improve customer satisfaction and stay ahead of
                        the
                        competition
                        with our product data analytics.</p>
                </div>
            </div>
            <div class="mt-20 texts">
                <div class="flex flex-col w-52 items-center text-dark-purple">
                    <div
                        class="flex justify-center items-center w-8 h-8 bg-white border border-davy-grey rounded-full text-center">
                        <h1 class="font-semibold">2</h1>
                    </div>
                    <div class="mt-6">
                        <h2 class="font-black">Data-driven decisions</h2>
                    </div>
                    <p class="text-xs text-center">Make data-driven decisions with our product data analytics. Our
                        AI-generated reports
                        help
                        you unlock insights hidden in your product data.</p>
                </div>
            </div>
            <div class="mt-20 texts">
                <div class="flex flex-col w-52 items-center text-dark-purple">
                    <div
                        class="flex justify-center items-center w-8 h-8 bg-white border border-davy-grey rounded-full text-center">
                        <h1 class="font-semibold">3</h1>
                    </div>
                    <div class="mt-6">
                        <h2 class="font-black text-xl">Always affordable</h2>
                    </div>
                    <p class="text-xs text-center">Always affordable pricing that scales with your business. Get top-quality
                        product
                        data
                        analytics services without hidden costs or unexpected fees.</p>
                </div>

            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    height: 100vh;
}

section:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #FCF8FF;
    border-radius: 0 0 50% 50% / 0 0 100% 100%;
    transform: scaleX(2);
}

/* mobile only */

@media only screen and (max-width: 480px) {

    section {
        height: 150vh;
        margin-top: -60px;
    }

    section:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: #FCF8FF;
        border-radius: 0 0 50% 50% / 0 0 100% 100%;
        transform: scaleX(4);
    }

    .content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
    }

    .texts-first {
        margin-top: 100px;
    }

    .texts {
        margin-top: 0;
    }
}
</style>