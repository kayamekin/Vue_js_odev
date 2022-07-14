<template>

    <div class="col-6">
        <p>Sunucu bilgisi {{ status }}</p>
    </div>
</template>

<script>
export default {
    data: function () {
        return {
            status: "pasif"
        }
    }

}
</script>