<script>
    import Header from "../components/Header.svelte";

    export let title = 'dongpark.land'
    export let summary = ''
    // export let publishedAt = ''
</script>

<svelte:head>
    <title>{title}</title>
    <meta name="description" content={summary}/>
</svelte:head>

<main>

    <div class="flex-col">
        <div class="flex items-end">
            <img src="favicon.png" alt="favicon" class="h-14 me">
        </div>
        <div class="flex items-center space-x-1">
            <h1>박동환</h1>
            <span class="text-sm">dongpark</span>
        </div>

    </div>

    <div data-animate="" data-animate-speed="slow">
        <!-- 소개 -->
        <div class="my-7 space-y-2">
            <p>
                프레임워크 보다는 프로그래밍 언어와 같이 <b>일하는 방식</b>을 더 고민합니다.
                사람들이 많이 사용하는 <b>서비스</b>를 만들며 보람을 느끼고, <b>비즈니스 요구사항</b>을 빠르게 구현하는데 익숙합니다.
                백엔드 엔지니어 보다는, 서비스에 오너십을 가지고 <b>가꾸는 사람</b>이 되려 노력합니다.
            </p>
            <p>
                현재 이랜드리테일 에서
                <b><a class="external-link" href="https://www.kakaocorp.com/page/" target="_blank">이랜드갤러리</a></b>
                를 개발하고 있습니다.
            </p>
        </div>

        <!-- 현재 -->
        <div class="">
            <div data-animate="" class="flex gap-0.5"><a style="--lv-wait: 1;"
                                                         class="rounded p-1 transition-colors hover:bg-selection hover:text-body"
                                                         href="https://github.com/bepyan" target="_blank">
                <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                    <path fill="currentColor"
                          d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5c.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34c-.46-1.16-1.11-1.47-1.11-1.47c-.91-.62.07-.6.07-.6c1 .07 1.53 1.03 1.53 1.03c.87 1.52 2.34 1.07 2.91.83c.09-.65.35-1.09.63-1.34c-2.22-.25-4.55-1.11-4.55-4.92c0-1.11.38-2 1.03-2.71c-.1-.25-.45-1.29.1-2.64c0 0 .84-.27 2.75 1.02c.79-.22 1.65-.33 2.5-.33c.85 0 1.71.11 2.5.33c1.91-1.29 2.75-1.02 2.75-1.02c.55 1.35.2 2.39.1 2.64c.65.71 1.03 1.6 1.03 2.71c0 3.82-2.34 4.66-4.57 4.91c.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2Z"></path>
                </svg>
            </a><a style="--lv-wait: 1;" class="rounded p-1 transition-colors hover:bg-selection hover:text-body"
                   href="mailto:rakddh@gmail.com">
                <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                    <path fill="currentColor"
                          d="M12 22q-2.075 0-3.9-.788t-3.175-2.137q-1.35-1.35-2.137-3.175T2 12q0-2.075.788-3.9t2.137-3.175q1.35-1.35 3.175-2.137T12 2q2.075 0 3.9.788t3.175 2.137q1.35 1.35 2.138 3.175T22 12v1.45q0 1.475-1.012 2.513T18.5 17q-.875 0-1.65-.375t-1.3-1.075q-.725.725-1.638 1.088T12 17q-2.075 0-3.538-1.463T7 12q0-2.075 1.463-3.538T12 7q2.075 0 3.538 1.463T17 12v1.45q0 .65.425 1.1T18.5 15q.65 0 1.075-.45t.425-1.1V12q0-3.35-2.325-5.675T12 4Q8.65 4 6.325 6.325T4 12q0 3.35 2.325 5.675T12 20h5v2h-5Zm0-7q1.25 0 2.125-.875T15 12q0-1.25-.875-2.125T12 9q-1.25 0-2.125.875T9 12q0 1.25.875 2.125T12 15Z"></path>
                </svg>
            </a><a style="--lv-wait: 1;"
                   class="flex items-center gap-1 rounded p-1 transition-colors hover:bg-selection hover:text-body"
                   href="https://bepyan.notion.site/Frontend-Developer-69fd245161734c1793e8df78dffe705c?pvs=4"
                   target="_blank">
                <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 15 15">
                    <path fill="currentColor"
                          d="M3.258 3.117c.42.341.577.315 1.366.262l7.433-.446c.158 0 .027-.157-.026-.183l-1.235-.893c-.236-.184-.551-.394-1.155-.341l-7.198.525c-.262.026-.315.157-.21.262l1.025.814Zm.446 1.732v7.821c0 .42.21.578.683.552l8.17-.473c.472-.026.525-.315.525-.656V4.324c0-.34-.131-.525-.42-.499l-8.538.499c-.315.026-.42.184-.42.525Zm8.065.42c.052.236 0 .472-.237.499l-.394.078v5.774c-.341.184-.657.29-.92.29c-.42 0-.525-.132-.84-.526L6.803 7.342v3.911l.815.184s0 .472-.657.472l-1.812.105c-.053-.105 0-.367.184-.42l.472-.13V6.292L5.15 6.24c-.053-.236.078-.577.446-.604l1.944-.13L10.22 9.6V5.978l-.683-.079c-.053-.289.157-.499.42-.525l1.813-.105Zm-9.93-3.937L9.326.781c.919-.08 1.155-.026 1.733.394l2.39 1.68c.395.288.526.367.526.682v9.212c0 .578-.21.92-.946.971l-8.694.525c-.552.027-.815-.052-1.104-.42l-1.76-2.283c-.315-.42-.446-.735-.446-1.103V2.25c0-.472.21-.866.814-.918Z"></path>
                </svg>
            </a></div>
        </div>

        <!-- 나의 공간 -->
        <div class="my-7 flex">
            <div data-animate="" class="flex flex-col">
                <div style="--lv-wait: 2;">
                    <a class="link font-bold external-link w-[75px]" href="/brand">Brand</a>
                    <span class="ml-3 text-sm">그간 저의 발자취와 이력입니다.</span>
                </div>
                <div style="--lv-wait: 2;">
                    <a class="link font-bold external-link w-[75px]" href="/media">Project</a>
                    <span class="ml-3 text-sm">프로젝트를 소개합니다.</span>
                </div>
                <div style="--lv-wait: 2;">
                    <a class="link font-bold external-link w-[75px]" href="/brand">Note</a>
                    <span class="ml-3 text-sm">생각과 기록을 모았습니다.</span>
                </div>
            </div>
        </div>
    </div>
</main>

<style lang="scss">

  .me:hover {

  }

</style>
