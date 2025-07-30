<script>
	import Logo from "./Logo.svelte";
	import Project from "./Project.svelte";

</script>
<div class="h-fit bg-[#EEE]">
    <div class="h-30 flex justify-center items-center">
        <p class="text-5xl font-bold">Projects</p>
    </div>

    <div class="h-fit p-5 grid grid-cols-3 gap-10 justify-items-center">

        <Project
            title="Comdel"
            desc="a SaaS to help YouTube content creator for deleting comments that promoting gambling sites"
            techStack={["go", "svelte", "psql"]}
            link="https://github.com/KeyzarRasya/comdel"
            img="comdel.png"
        />

        <Project 
            title="Ngingo"
            desc="AI-Driven Reverse Proxy and Docker orchestra using Go Programming Language"
            techStack={["docker", "go"]}
            link="https://github.com/KeyzarRasya/ngingo"
            img="ngingo.png"
        />

        <Project 
            title="Lativa"
            desc="Web to track national politician assets and liabilities by using image and then tracking it LKHPN Data"
            techStack={["nodejs", "react-2"]}
            link="https://gemastik.vercel.app/"
            img="lativa.png"
        />

        <Project 
            title="ManageFranch"
            desc="tools for monitoring raw material, financial report, and ordering raw material to make business operational run very well"
            techStack={["nodejs","react-2"]}
            link="https://managefranch-client.vercel.app/"
            img="mf.png"
        />

        <Project 
            title="Landing Page"
            desc="a Landing Page for coffee shop to build understanding of how Svelte framework works"
            techStack={["svelte"]}
            link="https://porto-coffee-shop.vercel.app/"
            img="porto.png"
        />

        <Project 
            title="YouTube Video"
            desc="starting youtube channel to teaching of my knowledge in Programming and Embedded System with Baremetal C"
            techStack={["c", "go"]}
            link="https://www.youtube.com/@keyzarrasya3416/videos"
            img="youtube.png"
        />

        <Project 
            title="Privator API"
            desc="a runner up winning project in Turnamen Sains Data National to help streamer or content creator hide their personal information to prevent leaks"
            techStack={["mongo", "nodejs"]}
            link="https://github.com/KeyzarRasya/ServerPrivator"
            img="privator.png"
        />

        <Project 
            title="EnviroFund API"
            desc="a java application for last semester project aiming to raise a fund money for better envirovment"
            techStack={["java", "spring"]}
            link="https://github.com/KeyzarRasya/EnviroFund"
            img="enviro.png"
        />
    </div>
</div>