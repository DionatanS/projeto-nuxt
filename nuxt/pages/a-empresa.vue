<template>
    <div>
        <div class="bg-gray-100">
            <div class="container mx-auto flex items-center space-x-4 h-10">
                <nuxt-link :to="{ name: 'a-empresa', params: {} }">A empresa</nuxt-link>
                <nuxt-link :to="{ name: 'servicos', params: {} }">Serviços</nuxt-link>
                <nuxt-link :to="{ name: 'produtos', params: {} }">Produtos</nuxt-link>
            </div>
        </div>

        <div>
            <div class="container mx-auto">
                <h1 class="text-lg font-bold">Empresa</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus reiciendis et magni consequuntur harum! Voluptatem animi quasi repellendus explicabo sequi molestias, voluptatibus cupiditate odio reprehenderit dolorem molestiae totam ab dolores!</p>
            </div>
        </div>
    </div>    
</template>

<script>
    export default {
        name:'',

        data() {
            return {
            };
        },

        methods: {},
    };

</script>