<template>
    <div id="app">

        <div class="container">

            <br>

            <div class="row">
                <header class="page-header" style="text-align: center;">
                    <h1 class="logo">Kolindo</h1>
                    <p class="subtitle">Platform Tiket Konser Lokal Indonesia</p>
                </header>
            </div>

            <br>

            <div class="row">

                <!-- Sidebar -->
                <div class="col-2">
                    <aside class="page-sidebar box">
                        <h3 class="heading">Search Band</h3>
                        <input type="search" class="form-control" placeholder="e.g. Slank" role="searchbox" v-model="filter">
                        
                        <br>
                    </aside>
                </div>

                <!-- Card Body -->
                <div class="col-10">
                    <main class="page-content">
                        <div class="row">
                            <div class="col">
                                <div class="card" style="width: 18rem;">
                                    <img src="@/assets/Slank.jpg" class="card-img-top">
                                    <div class="card-body">
                                        <h5 class="card-title">Konser Berdendang</h5>
                                        <p class="card-text">Bali - Slank</p>
                                        <p class="card-footer">Rp 150.000</p>
                                        <router-link :to="{ name: 'detailTicket' }" class="btn btn-md btn-success">Pesan Tiket</router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="card" style="width: 18rem;">
                                    <img src="@/assets/Slank.jpg" class="card-img-top">
                                    <div class="card-body">
                                        <h5 class="card-title">Konser Berdendang</h5>
                                        <p class="card-text">Bali - Slank</p>
                                        <p class="card-footer">Rp 150.000</p>
                                        <router-link :to="{ name: 'detailTicket' }" class="btn btn-md btn-success">Pesan Tiket</router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="card" style="width: 18rem;">
                                    <img src="@/assets/Slank.jpg" class="card-img-top">
                                    <div class="card-body">
                                        <h5 class="card-title">Konser Berdendang</h5>
                                        <p class="card-text">Bali - Slank</p>
                                        <p class="card-footer">Rp 150.000</p>
                                        <router-link :to="{ name: 'detailTicket' }" class="btn btn-md btn-success">Lihat Detail</router-link>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </main>
                </div>
            </div>
        </div>

    </div>
</template>

<script>

export default {
    setup(){
        const option = null
        const filter = null
        const range = 50

        return{
            option,
            filter,
            range,
        }
    }
}
</script>

<style>

</style>
