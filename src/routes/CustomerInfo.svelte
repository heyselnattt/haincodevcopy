<script>
    import FieldWithValue from "../components/FieldWithValue.svelte";
    import HomeNavbar from "../components/HomeNavbar.svelte";
</script>

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Karla:wght@600&display=swap" rel="stylesheet"/>
</svelte:head>

<HomeNavbar/>

<div class="container">
    <div class="columns  pt-5 is-multiline">
        <div class="column is-4 has-text-centered">
            <a class="btn-txt button is-link is-rounded" href="Customers">
                <img class="img1" src="back.png" alt="back"/>
                <p class="ml-3">
                   Back
                </p>
            </a>
        </div>
        <div class="column is-4  ml-6">
            <p class="text has-text-link">
                Customer's Information
            </p>
        </div>
        <div class="column is-3">
            <a class="btn-txt button is-link is-rounded" href="/">
                <p class="ml-5 mr-5">
                   Edit
                </p>
            </a>
        </div>

        <div class="column is-12"></div>
        <div class="column is-12"></div>
        <div class="column is-12"></div>
        <FieldWithValue name="Name" value="Taylor Swift"/>
        <FieldWithValue name="Contact No." value="09123456789"/>
        <div class="column is-12"></div>
        <FieldWithValue name="Email" value="taylorswift@gmail.com"/>
        <FieldWithValue name="Password" value="*****"/>
    </div>
</div>

<style>
    .text {
        font-family: 'Karla', sans-serif;
        font-size: 40px;
    }
    .btn-txt {
        font-size: 20px;
        font-family: 'Karla', sans-serif;
    }
    .img1 {
        width: 20px;
    }
</style>