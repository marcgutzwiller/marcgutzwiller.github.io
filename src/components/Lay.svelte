<script>
    import Layout from "svelte-fluid-layout";

    import Landing from "./Landing.svelte";
    import About from "./About.svelte";
    import Work from "./Work.svelte";
</script>

<Layout>

    <header slot="header" class="header">
        <Landing/>
    </header>

    <!--    <section slot="side1">-->
    <!--        <div class = "side1">-->
    <!--            <h1>side</h1>-->
    <!--        </div>-->
    <!--    </section>-->

    <main slot="main">
        <div class = "main">
            <About/>
            <Work/>
        </div>
    </main>

    <!--    <aside slot="side2">-->
    <!--        <div class = "side2">-->
    <!--            <h1>side right</h1>-->
    <!--        </div>-->
    <!--    </aside>-->

    <footer slot="footer">
        <div class = "footer">
            <!--            <h1>footer</h1>-->
        </div>
    </footer>

</Layout>

<style>
    @media (min-width: 768px) {
        .main {
            position: relative;
            top: 105vh;
            left: 10vw;
            width: 80vw;
            text-align: center;
            color: #d85a31;
        }
    }

    @media (max-width: 767px) {
        .main {
            position: relative;
            top: 105svh;
            left: 10vw;
            width: 80vw;
            text-align: center;
            color: #d85a31;
        }
    }
</style>