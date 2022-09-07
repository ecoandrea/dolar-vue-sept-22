<script setup>
import axios from 'axios'

const getData = async () => {
  try{
const {data} = await axios.get("https://api-dolar-olg2.onrender.com")
  } catch (error) {
    console.log(error)
  }
}

getData()
</script>

<template>
  <h1>Api Dolar</h1>
</template>