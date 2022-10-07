<script>
    import Magnify from "svelte-material-icons/Magnify.svelte";
</script>

<div class="w-screen h-[70px] p-5">
    <div class="w-full max-w-[1224px] mx-auto flex justify-between items-center">
        <h1>NE</h1>
        <nav class="flex gap-20 items-center">
                <li>About Us</li>
                <li>Mortgages</li>
                <li>Buy A Home</li>
                <li>Refinance</li>
                <button class="bg-black py-2 px-4 text-white rounded-3xl">Apply Now</button>
                <button class="flex text-black"> <Magnify height="30px" width="35px" /></button>
               
        </nav>
    </div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Aclonica&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');

    *{
        font-family: 'Poppins', sans-serif;
    }

    h1{
        font-family: 'Aclonica', sans-serif;
        font-weight: 400;
        font-size: 50px;
        line-height: 57px;
    }
    li{
        text-decoration: none;
        list-style-type: none;
    }
</style>