<script setup lang="ts">
import { reactive } from "vue";
import ChessPiece from "./components/ChessPiece.vue";

const activePiece = reactive({ type: "king", location: [1, 1] });
</script>

<template>
  <h1>Hello</h1>
  <ChessPiece :piece="activePiece" />
</template>

<style scoped></style>
