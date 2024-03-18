<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">PILIHLAH BUKU YANG INGIN ANDA BACA</h2>
                <div class="my-3">
                    <input type="search" class="form-contol rounded-5" placeholder="mau baca apa hari ini ?">
                </div>
                <div class="my-3 text-muted">menampilkan 3 dari 3</div>
                <div class="row">
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <nuxt-link to="rincian-buku/">
                                <img src="~/assets/img/cover1 (1).jpg" class="cover" alt="cover 1">
                                </nuxt-link>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <nuxt-link to="http://localhost:3000/rincian-buku/buku2">
                                <img src="~/assets/img/cover2 (1).jpg" class="cover" alt="cover 2">   
                                </nuxt-link>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <nuxt-link to="http://localhost:3000/rincian-buku/buku3">
                                <img src="~/assets/img/cover3 (2).jpg" class="cover" alt="cover 3">
                                </nuxt-link>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <nuxt-link to="http://localhost:3000/">
                    <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">kembali</button>
                </nuxt-link>
    </div>
</template>
