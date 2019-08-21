<template>
    <div class="home">
        <FaceCheck image="./face.bmp" @onCheckFailed="onCheckFailed"></FaceCheck>
    </div>
</template>

<script>
    // @ is an alias to /src
    import FaceCheck from "../components/FaceCheck";

    export default {
        name: 'home',
        components: {
            FaceCheck
        },
        methods: {
            onCheckFailed(distance) {
                console.info('failed!'+distance)
            }
        }
    }
</script>
