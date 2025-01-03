<script setup>
useHead({
  title: 'Data Pokok SMKN 4 TASIKMALAYA',
});

</script>

<template>
    <div class="container">
        <div class="row p-5">
            <div class="col-sm-6 mb-3 mb-sm-0 p-1">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Nama Sekolah : {{ ns }}</h5>
                    </div>
                </div>
            </div>
            <div class="col-sm-6 p-1">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">NPSN : {{ np }} </h5>
                    </div>
                </div>
            </div>
            <div class="col-sm-6 p-1">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Pendirian : {{ berdiri }} </h5>
                    </div>
                </div>
            </div>
            <div class="col-sm-6 p-1">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Akredetasi : {{ a }}</h5>
                    </div>
                </div>
            </div>
            <div class="col-sm-12 p-1">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Alamat : SMKN 4 Tasikmalaya. Jl Depok Kel. Sukamenak Kec. Purbaratu Kota Tasikmalaya 46196.</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default{
    name:"jumlah",
    data:function(){
        return {
            ns : 'SMKN 4 TASIKMALAYA',
            np : '20276063',
            a : 'A',
            berdiri :'	06 Februari 2012'

        }
    }
}

</script>