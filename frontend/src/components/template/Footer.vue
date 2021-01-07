<template>
    <footer class="footer">
        <span>Copyright <strong>Fontinelle</strong>  © 2020</span>
    </footer>
</template>

<script>
export default {
    nome: "Footer"
}
</script>

<style>
    .footer{
        grid-area: footer;
        background-color: #ddd;
        color: #333;

        display: flex;
        align-items: center;
        justify-content: flex-end;
        padding-right: 10px;
    }
</style>