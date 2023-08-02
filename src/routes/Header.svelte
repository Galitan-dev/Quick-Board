<script lang="ts">
    import { PUBLIC_GITHUB_REPOSITORY } from '$env/static/public';
    import logo from '$lib/images/logo.svg';
    import github from '$lib/images/github.png';
</script>

<header>
    <img src={logo} alt="Quick-Board logo" />
    <h1>Quick-Board</h1>
    <a target="_blank" href={PUBLIC_GITHUB_REPOSITORY}><img src={github} alt="github logo" /></a>
</header>

<style lang="less">
    header {
        height: 50px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 0 20px;
        background-color: #fff9;
        margin-bottom: 30px;
    }

    img {
        height: 35px;
    }
</style>
