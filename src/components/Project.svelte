<script lang="ts">
    import Logo from "./Logo.svelte";

    interface LogoTech {
        name: string;
        src: string;
        isLink: boolean;
    }

    export let title: string;
    export let desc: string;
    export let techStack: string[];
    export let img: string;
    export let link: string;

    let logoTech: LogoTech[] = [];

    techStack.forEach(t => {
            logoTech.push({
                name:t,
                src:`/techstack/${t}.svg`,
                isLink:false,
            })
    })

    const onClicked = () => {
        window.location.href = link
    }


</script>

<div class="h-fit w-80 bg-white rounded-sm shadow-2xl shadow-gray-500">
    <div class="img-project h-40"
        style="background-image: url('/projects/{img}'); background-size: cover; background-position: center;"
    >

    </div>
    <div class=" p-3">
        <p class=" font-bold font-sans text-xl">{title}</p>
        <p class="text-sm text-[#333] mt-2">{desc}</p>
    </div>
    <div class="p-3">
        <p class="font-bold">Tech Stack</p>
        <div class="flex items-center ">
            {#each logoTech as tech}
                <Logo src={tech.src} alt={tech.name} isLink={tech.isLink}/>
            {/each}
        </div>
    </div>
    <div class="p-5 w-full">
        <button class="border w-full h-15 flex bg-gray-800 text-white font-bold items-center justify-center"
            onclick={onClicked}
        >
            See this Project
        </button>
    </div>
</div>
