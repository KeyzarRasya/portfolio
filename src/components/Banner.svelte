<script>
	import Logo from "./Logo.svelte";

</script>
<div class="h-screen w-full bg-[#EEE]">
    <div class="h-1/12 flex justify-center">
        <div class="w-3/6 h-full">

        </div>
    </div>

    <div class="h-11/12 w-screen flex flex-col md:flex-row justify-center items-center">
        <div class="h-3/6 md:h-full  w-3/6 md:w-3/6 flex justify-center items-center">
            <img src="/profil.png" alt="" class=" h-50 md:h-100 w-100 rounded-full bg-gradient-to-t from-gray-900 via-gray-800 to-gray-700 shadow-2xl shadow-gray-500">
        </div>

        <div class="h-3/6  md:h-full w-5/6 md:w-3/6  flex flex-col justify-start md:justify-center ">
            <div class=" h-4/6 md:h-2/6  flex flex-col items-center md:items-start">
                <h1 class="text-center md:text-start text-5xl font-bold">Keyzar Rasya Athallah</h1>
                <p class="text-center md:text-start mt-5 text-2xl">Backend Developer</p>
                <div class="h-2/6 w-4/6 md:w-2/6  flex justify-around items-center md:items-end">
                    <Logo size="10" src="/github.png" alt="github" isLink={true} href="https://github.com/KeyzarRasya" />
                    <Logo size="10" src="/linkedin.png" alt="linkedin" isLink={true} href="https://www.linkedin.com/in/keyzar-athallah/" />
                    <Logo size="10" src="/instagram.png" alt="insragram" isLink={true} href="https://instagram.com/keyzarathallah" />
                    <Logo size="10" src="/email.png" alt="email" isLink={true} href="mailto:keyzar.r.athallah@gmail.com" />
                </div>
            </div>
        </div>
    </div>
</div>