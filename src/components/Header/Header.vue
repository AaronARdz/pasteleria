<template>
    <div class="container">
        <div class="row">
            <div class="col-12 col-md-6">
                <div class="align-self-center">
                    <div class="mt-5 header__text"> 
                        <div class="w-100 mx-auto">
                        <h1>Que se te antoja?</h1>     
                        </div>
                            <router-link
                            class="float-left"
                            to="/contact"
                            ><div class="btn btn-primary">Button</div>
                            </router-link>
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-6">
                <div class="text-center">
                    <img src="" alt="" style="max-width: 100%">
                </div>
            </div>
        </div>
    </div>

</template>

<script>
export default {
    data() {
        return {
            hover: false
        }
    }
}
</script>

<style scoped>
.header__text p {
    font-weight: 300;
}

h1 {
  font-weight: 700;
  font-size: 5em;
  color: #fff4f4;
  text-shadow: 0px 4px 4px rgba(1, 1, 1, 0.76);
}
.bg-yummy {
    
}

</style>