<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12">
                <br>
                <button class="btn btn-primary" @click="currentComponent='appBlue'">Load Blue Template</button>
                <button class="btn btn-success" @click="currentComponent='appGreen'">Load Green Template</button>
                <button class="btn btn-danger" @click="currentComponent='appRed'">Load Red Template</button>
                <hr>
                <component :is="currentComponent">
                    <slot name="image"></slot>
                    <slot name="title" ></slot>
                    <slot name="poem" ></slot>
                    <slot name="author" ></slot>
                </component>
            </div>
        </div>
    </div>
</template>

<script>
    import Blue from './components/Blue.vue';
    import Green from './components/Green.vue';
    import Red from './components/Red.vue';

    export default {
        data: function(){
            return {
                currentComponent: 'appBlue'
            }
        },
        components: {
            appBlue: Blue,
            appGreen: Green,
            appRed: Red
        }
    }
</script>

<style>
    img{
        max-width: 20%;
        border-radius: 80%;
        box-shadow: 0 0 2px 1px rgba(0, 0, 0, 0.5);
    }
    h1{
        margin-bottom: 25px;
    }
    p {
        text-align: justify;
    }
    h3{
        text-align: right;
        font-style: italic;
    }
</style>
