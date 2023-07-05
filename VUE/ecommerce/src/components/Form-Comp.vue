<template>
    <form action="">
        <div>
            <input class="form-control" v-model="firstName" type="text" placeholder="Enter your firstName" required>
        </div>

        <div>
            <input class="form-control my-3" v-model="lastName" type="text" placeholder="Enter your lastName" required>
        </div>

        <div>
            <label class="form-control mb-3">
                {{ firstName }} {{ lastName }}</label>
        </div>

        <div>
            <button class="btn-success" type="button" @click="displayData">Submit</button>
        </div>
    </form>
</template>

<script>
export default {
    Data () {
    return {
        firstName: null,
        lastName: null
    }
},
methods: {
    displayData(){
        document.querySelector('#output').textContent = '${firstName} ${lastName}'
    }
}
}
</script>

<style>

</style>