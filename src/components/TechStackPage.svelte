<script>
	import Logo from "./Logo.svelte";

</script>
<div class="h-fit   ">

    <div class="h-30 flex justify-center items-center">
        <p class="text-3xl">Programming Language</p>
    </div>

    <div class="h-30 flex justify-center">
        <div class="w-full md:w-3/6 flex justify-around items-center md:items-start">
            <Logo src="js.png" alt="javascript" isLink={false} size="15"/>
            <Logo src="go.svg" alt="golang" isLink={false} size="15"/>
            <Logo src="java.svg" alt="java" isLink={false} size="15"/>
            <Logo src="c.svg" alt="c" isLink={false} size="15"/>
            <Logo src="php.svg" alt="php" isLink={false} size="15"/>
        </div>
    </div>

    <div class="h-30 flex justify-center items-center">
        <p class="text-3xl">Framework</p>
    </div>

    <div class="h-30 flex justify-center">
        <div class="w-full md:w-3/6 flex justify-around items-center md:items-start">
            <Logo src="/framework/codeigniter.svg" alt="codeigniter" isLink={false} size="15"/>
            <Logo src="/framework/express.png" alt="express" isLink={false} size="15"/>
            <Logo src="/framework/react-2.svg" alt="react" isLink={false} size="15"/>
            <Logo src="/framework/spring.svg" alt="spring" isLink={false} size="15"/>
            <Logo src="/framework/svelte.svg" alt="svelte" isLink={false} size="15"/>
        </div>
    </div>

    <div class="h-30 flex justify-center items-center">
        <p class="text-3xl">Runtime</p>
    </div>

    <div class="h-30 flex justify-center">
        <div class="w-full md:w-3/6 flex justify-around items-center md:items-start">
            <Logo src="/runtime/docker.svg" alt="docker" isLink={false} size="15"/>
            <Logo src="/runtime/Linux.svg" alt="linux" isLink={false} size="15"/>
            <Logo src="/runtime/nodejs.svg" alt="nodeks" isLink={false} size="15"/>
        </div>
    </div>
</div>