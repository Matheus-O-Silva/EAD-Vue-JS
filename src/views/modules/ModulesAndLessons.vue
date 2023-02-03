<template>
    <div>
        <div class="pageTitle">
            <span class="title">Meu Curso</span>
            <span class="dots">
                <span></span>
                <span></span>
                <span></span>
            </span>
        </div>

        <div class="content">
            <div class="container">

                <modules/>

                <div class="right">
                    <div class="content">

                        <player/>

                        <supports-lesson></supports-lesson>

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Modules from './components/Modules.vue'
import Player from './components/Player.vue'
import SupportsLesson from './components/Supports.vue'

export default {
    name: 'ModulesAndLessons',
    components: {
        Modules,
        Player,
        SupportsLesson
    }
}

</script>