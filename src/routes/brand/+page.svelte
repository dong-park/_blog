<script>
    export let title = 'dongpark.land | Brand'
    export let summary = ''
</script>

<svelte:head>
    <title>{title}</title>
    <meta name="description" content={summary}/>
</svelte:head>

<main>
    <h1>Brand</h1>
    <div class="company" data-animate="" data-animate-speed="slow">
        <div class="flex justify-between items-center mb-4">
            <div>
                <h1 class="">이랜드리테일</h1>
                <div class="text-sm">Backend팀</div>
            </div>
            <div>
                <div class="text-sm">2022.04 ~ 재직중</div>
            </div>
        </div>
        <div class="flex-col space-y-4 ml-2">
            <div class="group">
                <div class="summary">
                    <h2>이랜드옥션</h2>
                    <h3>실시간 경매 서비스</h3>
                </div>
                <ul class="">
                    <li>옥션을 진행하기 위한 데이터 <b>모델</b>을 설계하고, 해당 데이터를 처리하는 <b>API</b>를 구현했습니다.</li>
                    <li>경매 참여자가 입찰을 하는 과정을 처리하기 위해 Redis Pubsub과 Celery를 이용하여 <b>실시간 데이터 전송</b> 기능을 개발했습니다.</li>
                    <li>그룹사 내에서 통합적으로 로그인할 수 있도록 OAuth 컨셉을 이용하여 <b>인증 체계</b>를 구현했습니다.</li>
                    <li>개인정보 유출을 방지하기 위해 <b>개인정보를 단방향으로 암호화</b>하고, 애플리케이션 내에서 복호화하는 기능을 구현했습니다.</li>
                    <li>프로젝트를 실행하기 위한 <b>클라우드 서버 환경</b>을 구축하고 어플리케이션 배포를 위한 <b>파이프라인</b>을 구축했습니다.</li>
                </ul>
            </div>
            <div class="group">
                <div class="summary">
                    <h2>이랜드갤러리</h2>
                    <h3>미술품 온라인 판매 플랫폼</h3>
                </div>
                <ul>
                    <li>PHP 기반 갤러리 사이트에서 <b>Django 기반으로 전환</b>하는 작업을 수행했습니다.</li>
                    <li>기존 갤러리 사이트의 데이터를 Django model로 변환하고, 데이터를 처리하는 <b>API를 개발</b>했습니다.</li>
                    <li>미술품의 <b>색깔별 카테고리화</b>를 머신러닝 기술을 이용하여 자동화하는 기능을 개발했습니다.</li>
                    <li>관리자 페이지를 개선하고 엑셀 입력/출력, 맞춤법 검사와 간편한 이미지 업로드 위젯 등 <b>사용성 개선</b>에 기여 했습니다.</li>

                </ul>
            </div>
            <div class="group">
                <div class="summary">
                    <h2>WILLWILL</h2>
                    <h3>미술품 조각투자 서비스</h3>
                </div>
                <ul>
                    <li>Klaytn 블록체인 기반의 지갑을 생성하고, KIP17 규격에 따라 NFT 10여 건을 발행했습니다.</li>
                    <li>Nuxt.js 프레임워크를 기반으로 관리자 페이지를 개발했습니다.</li>
                    <li>그룹사 내에서 통합적으로 로그인할 수 있도록 OAuth 컨셉을 이용하여 인증 체계를 구현했습니다.</li>
                    <li>JWT 토큰을 HTTP Only 방식으로 발행하고 저장하여 인증과 권한을 처리했습니다.</li>
                    <li>플랫폼 오픈 후 B2B 고객의 요구 사항을 충족하기 위해 외부 플랫폼 API와 연동하고, 배치 작업을 개발하여 적용했습니다.</li>
                </ul>
            </div>

        </div>
    </div>
    <div class="company" data-animate="" data-animate-speed="slow">
        <div class="flex justify-between items-center mb-4">
            <div>
                <h1 class="">글로카로카</h1>
                <div class="text-sm">개발팀</div>
            </div>
            <div>
                <div class="text-sm">2021.05 ~ 2022.01</div>
            </div>
        </div>
        <div class="flex-col space-y-4 ml-2">
            <div class="group">
                <div class="summary">
                    <h2>글로카로카</h2>
                    <h3>공유 주거 플랫폼</h3>
                </div>
                <ul>
                    <li>공유 주거 플랫폼 서비스를 위한 <b>API</b>를 개발했습니다.</li>
                    <li>프로젝트를 실행하기 위한 <b>클라우드 서버 환경</b>을 구축하고 어플리케이션 배포를 위한 <b>파이프라인</b>을 구축했습니다.</li>
                    <li>세금계산거 발행 및 예약 결제를 위한 <b>외부 플랫폼 API</b>와 연동하는 기능을 개발했습니다.</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="company" data-animate="" data-animate-speed="slow">
        <div class="flex justify-between items-center mb-4">
            <div>
                <h1 class="">당근영어</h1>
                <div class="text-sm">솔루션개발팀</div>
            </div>
            <div>
                <div class="text-sm">2020.06 ~ 2021.05</div>
            </div>
        </div>
        <div class="flex-col space-y-4 ml-2">
            <div class="group">
                <div class="summary">
                    <h2>당근농장</h2>
                    <h3>당근영어 컨텐츠 통합 어플리케이션</h3>
                </div>
                <ul>
                    <li>자사에서 서비스하는 영여교육 유/무료 컨텐츠를 통합하여 제공하는 <b>어플리케이션</b>을 개발했습니다.</li>
                    <li>컨텐츠를 제공하기 위한 Spring Boot 기반 <b>API</b>를 개발했습니다.</li>
                    <li>Ionic 환경에 맞춰 <b>모바일 어플리케이션</b> 개발에 참여했습니다.</li>
                    <li>데일리라이팅, 로이터통신 뉴스와 같은 이용한 Vue.js기반의 <b>웹뷰 어플리케이션</b> 개발 했습니다.</li>
                    <li>프로젝트를 실행하기 위한 <b>클라우드 서버 환경</b>을 구축하고 어플리케이션 배포를 위한 <b>파이프라인</b>을 구축했습니다.</li>
                </ul>
                <div class="summary">
                    <h2>삼성물산 용어 사전집</h2>
                    <h3>영어 학습 어플리케이션</h3>
                </div>
                <ul>
                    <li>삼성물산에서 제공하는 영어 학습 컨텐츠를 제공하는 <b>어플리케이션</b>을 외주 개발에 참여했습니다.</li>
                    <li>컨텐츠를 제공하기 위한 Spring Boot 기반 <b>API</b>를 개발했습니다.</li>
                    <li>Ionic Vue3 환경으로 크로스플랫폼 <b>어플리케이션</b> 개발에 참여했습니다.</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="company" data-animate="" data-animate-speed="slow">
        <div class="flex justify-between items-center mb-4">
            <div>
                <h1 class="">주식회사 위메스</h1>
                <div class="text-sm">개발팀</div>
            </div>
            <div>
                <div class="text-sm">2018.11 ~ 2020.04</div>
            </div>
        </div>
        <div class="flex-col space-y-4 ml-2">
            <div class="group">
                <div class="summary">
                    <h2>난공매니저</h2>
                    <h3>독서실 원생관리 LMS</h3>
                </div>
                <ul>
                    <li>독서실 원생관리를 위한 <b>LMS 웹 어플리케이션</b>을 개발했습니다.</li>
                    <li>원생의 납부 이력과 좌석 <b>이용 이력을 관리</b>하는 기능을 개발했습니다.</li>
                    <li>상용 솔루션에서 자사로 <b>데이터 마이그레이션</b>을 진행했습니다.</li>
                    <li>QR코드를 활용한 출결관리용 <b>라즈베리파이 디바이스</b>와 API개발을 담당했습니다.</li>
                    <li>난공매니저 시스템과 연동가능한 키오스크 디바이스에 VAN사 <b>카드결제 연동</b>을 담당했습니다.</li>
                    <li>기타 PHP 기반 원생 커뮤니티 사이트의 Redis를 활용한 댓글알림 기능을 개발했습니다.</li>
                </ul>
                <div class="summary">
                    <h2>성적관리자동화</h2>
                    <h3>스파르타 독서실 성적관리 자동화</h3>
                </div>
                <ul>
                    <li>솔루션 비용 절감을 위해 스파르타 독서실 성적관리를 위한 <b>웹 어플리케이션</b>을 개발했습니다.</li>
                    <li>OMR리더기에서 산출되는 데이터를 <b>파싱</b>하여 데이터베이스에 저장하는 기능을 개발했습니다.</li>
                    <li>원생별로 월간,주간,일간 성적을 조회할 수 있는 기능을 개발했습니다.</li>
                </ul>
            </div>
        </div>
    </div>
</main>

<style lang="scss">
  .company {
    @apply my-4;

    h1 {
      @apply text-lg;
    }

  }

  h1 {
    @apply text-2xl;
    @apply font-bold;
  }

  .group {
    //@apply py-2;

    h1 {
      @apply mb-0;
    }

    h2 {
      //@apply bg-gray-300;
      @apply font-bold;
      //@apply p-2;
    }

    ul {
      @apply ml-4;

      li {
        @apply list-disc;
      }
    }
  }

  .summary {
    @apply flex;
    @apply space-x-2;
    @apply items-center;

    h3 {
      @apply text-sm;
      @apply text-gray-500;
    }
  }
</style>
