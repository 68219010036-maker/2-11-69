<template>
    <h2 class="mb-4">ยินดีต้อนรับ {{ state.user.full_name }}</h2>
    <v-card class="pa-4" max-width="600">
        <p>บทบาท: <strong> {{ roleNames[state.user.role] }}</strong></p>
        <p>หน้านี้จะเป็นหน้าชั่วคราว Login อันหลักจะอยู่ในขั้น 6-7 ในคู่มือ</p>
    </v-card>
</template>

<script setup>
import { state, roleNames} from '../api'
</script>