<template>

    <div class="container row">
        <left-comp></left-comp>
        <right-comp></right-comp>
    </div>

</template>

<script>

import LeftComp from "./LeftComp.vue"
import RightComp from "./RightComp.vue"

export default {
    components: {
        "left-comp": LeftComp,
        "right-comp": RightComp,
    }
}
</script>