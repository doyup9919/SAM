
```python
import requests
webpage = requests.get("https://www.daangn.com/hot_articles")
print(webpage.text)
```

    <!DOCTYPE html>
    <html lang="ko">
    <head>
      <meta charset="utf-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
          <link rel="canonical" href="https://www.daangn.com/hot_articles" />
    
      <title>당근마켓 중고거래 | 당신 근처의 당근마켓</title>
    <meta name="description" content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." />
    <link rel="author" href="당근마켓" />
    <meta property="og:url" content="https://www.daangn.com/hot_articles" />
    <meta property="og:title" content="당근마켓 중고거래 | 당신 근처의 당근마켓" />
    <meta property="og:description" content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." />
    <meta property="og:site_name" content="당근마켓" />
    <meta property="og:image" content="https://www.daangn.com/images/meta/home/flea_market.png" />
    <meta property="og:type" content="article" />
    <meta property="og:locale" content="ko_KR" />
    <meta property="fb:app_id" content="1463621440622064" />
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:site" content="@danggeunmarket" />
    <meta name="twitter:title" content="당근마켓 중고거래 | 당신 근처의 당근마켓" />
    <meta name="twitter:description" content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." />
    <meta name="twitter:image" content="https://www.daangn.com/images/meta/home/flea_market.png" />
    <meta name="naver-site-verification" content="d1f8112731c18313535732cf2516d6401bfed40a" />
      <link href="/images/icons/shortcut_icon.png" rel="shortcut icon" type="image/x-icon">
      <link rel="shortcut icon" type="image/x-icon" href="https://d1unjqcospf8gs.cloudfront.net/favicon.ico" />
    
      
        <link rel="stylesheet" media="all" href="https://d1unjqcospf8gs.cloudfront.net/assets/home/articles/hot-76409f246af8ba6ca58659826685527e45104fd2b089dd053e6af97133bb193b.css" />
          <script src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base-a182b6524ddb27bbc6a0647ee4bc2b79384325e8bde2b0775b94c7573fd0d87e.js"></script>
    
      <link rel="apple-touch-icon" sizes="192x192" href="/images/icons/daangn_logo_192.png">
    
      <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
      <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->
      <meta name="csrf-param" content="authenticity_token" />
    <meta name="csrf-token" content="V7+iOLHEyQT/2Ut4wMN+VhI3TbtX2G1ljsYgXB/RuTFzMU2xFFCBnRyp1nF9whWvHl0FyGaLq86i47XtEBxb2g==" />
      <script>
        window.fbAsyncInit = function() {
          FB.init({
            appId      : '1463621440622064',
            xfbml      : true,
            version    : 'v2.4'
          });
        };
    
        (function(d, s, id){
          var js, fjs = d.getElementsByTagName(s)[0];
          if (d.getElementById(id)) {return;}
          js = d.createElement(s); js.id = id;
          js.src = "//connect.facebook.net/en_US/sdk.js";
          fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'facebook-jssdk'));
      </script>
      <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
                  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
                m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    
        ga('create', 'UA-64551386-2', 'auto');
         ga('set', 'dimension2', 'true');  ga('send', 'pageview'); </script>
      <!-- Facebook Pixel Code -->
      <script>
        !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
                n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
          n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
          t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
                document,'script','//connect.facebook.net/en_US/fbevents.js');
    
        fbq('init', '992961397411651');
        facebookClickEvent("PageView")
    
        function facebookClickEvent(eventName, data) {
          if (data !== undefined) {
              fbq('track', eventName, data)
          } else {
              fbq('track', eventName)
          }
        }
    
        function facebookClickEventWithPageMove(eventName, data, targetUrl) {
            facebookClickEvent(eventName, data);
            window.location.href = targetUrl;
        }
      </script>
      <noscript><img height="1" width="1" style="display:none"
                     src="https://www.facebook.com/tr?id=992961397411651&ev=PageView&noscript=1"
      /></noscript>
      <!-- End Facebook Pixel Code -->
      <!-- Google Tag Manager -->
      <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
          new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
          j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
          'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
      })(window,document,'script','dataLayer','GTM-PJSK4QL');</script>
      <!-- End Google Tag Manager -->
    
      <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Organization",
      "name": "당근마켓",
      "url": "https://www.daangn.com",
      "sameAs": [
        "https://www.facebook.com/daangn",
        "https://blog.naver.com/daangn",
        "https://www.youtube.com/channel/UC8tsBsQBuF7QybxgLmStihA",
        "https://twitter.com/daangnmarket",
        "https://www.instagram.com/daangnmarket",
        "https://apps.apple.com/kr/app/id1018769995",
        "https://play.google.com/store/apps/details?id=com.towneers.www"
      ],
      "logo": "https://www.daangn.com/logo.png"
    }
    </script>
    
    </head>
    <body class="hoian-kr">
    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PJSK4QL"
                      height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
    
    <!-- Appsflyer Smart Banner -->
    <script>
        !function(t,e,n,s,a,c,i,o,p){t.AppsFlyerSdkObject=a,t.AF=t.AF||function(){(t.AF.q=t.AF.q||[]).push([Date.now()].concat(Array.prototype.slice.call(arguments)))},t.AF.id=t.AF.id||i,t.AF.plugins={},o=e.createElement(n),p=e.getElementsByTagName(n)[0],o.async=1,o.src="https://websdk.appsflyer.com?"+(c.length>0?"st="+c.split(",").sort().join(",")+"&":"")+(i.length>0?"af_id="+i:""),p.parentNode.insertBefore(o,p)}(window,document,"script",0,"AF","banners",{banners: {key: "629f6f7a-a2a6-49c0-8d27-ffa48df1cd0e"}})
        AF('banners', 'showBanner')
    </script>
    <!-- End Appsflyer Smart Banner-->
    
    <header id="fixed-bar">
      <div id="fixed-bar-wrap">
        <h1 id="fixed-bar-logo-title">
          <a href="https://www.daangn.com/">
            <span class="sr-only">당근마켓</span>
            <img class="fixed-logo" alt="당근마켓" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg" />
    </a>    </h1>
    
        <section id="fixed-bar-search">
          <div class="search-input-wrap">
            <span class="sr-only">검색</span>
            <input type="text" name="header-search-input" id="header-search-input" class="fixed-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" />
            <button id="header-search-button">
              <img class="fixed-search-icon" alt="Search" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg" />
            </button>
          </div>
        </section>
        <section class="fixed-bar-menu">
          <div class="fixed-download-wrapper">
            <input id="fixed-menu-checkbox" type="checkbox" class="fixed-checkbox" />
            <label for="fixed-menu-checkbox" class="fixed-label">
              다운로드
              <svg class="menu-icon-svg" width="12" height="7" viewBox="0 0 12 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M1 1L6 6L11 1" stroke="#4D5159" strokeWidth="1.5" strokeLinecap="round" strokeLinejoin="round" />
              </svg>
            </label>
            <ul class="fixed-menu-ul">
              <li>
                <a target="_blank" class="menu-anchor" id="header-download-button-ios" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8">
                  <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg" />
                  <span>App Store</span>
    </a>          </li>
              <li>
                <a target="_blank" class="menu-anchor" id="header-download-button-android" href="https://play.google.com/store/apps/details?id=com.towneers.www">
                  <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg" />
                  <span>Google Play</span>
    </a>          </li>
            </ul>
          </div>
          <a href="https://chat.daangn.com" target="_blank">
            <button class="chat-button">
              <span class="button-text">당근채팅</span>
              <span class="button-beta">Beta</span>
            </button>
          </a>
        </section>
      </div>
    </header>
    
    <section id="content">
      <h1 class="head-title" id="hot-articles-head-title">
        
        
        중고거래 인기매물
      </h1>
    
      <nav id="hot-articles-navigation">
        <select name="region1" id="region1" onchange="changeRegion(&#39;r1&#39;, this.value)" class="hot-articles-nav-select"><option value="">지역을 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
        <select name="region2" id="region2" disabled="disabled" onchange="changeRegion(&#39;r2&#39;, this.value)" class="hot-articles-nav-select"><option value="">동네를 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    
      </nav>
    
      <section class="cards-wrap">
        <article class="card-top ">
      <a class="card-link " data-event-label="273865202" href="/articles/273865202">
        <div class="card-photo ">
            <img alt="삼성 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/da035d5794d5490a86e8596a2ff036db7a6811cde70b8e2cb5514a93f4c0d1af.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">삼성 제습기</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            대전 서구 갈마동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 47
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273972258" href="/articles/273972258">
        <div class="card-photo ">
            <img alt="🎈4단 경량 서랍장 2EA" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E5286230DC4F10CDC1187AF093DC98E700866C3F3CCE2D26B4097EC8E096EF02.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            전남 순천시 해룡면
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 21
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273869268" href="/articles/273869268">
        <div class="card-photo ">
            <img alt="마켓비 철제장수납장 드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1BF6CACC4CF68494129932B87B0C9B3A079DDE8C4BA714BD93E4BF5DAEBC10E8.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">마켓비 철제장수납장 드림</h2>
          <div class="card-price ">
            10원
          </div>
          <div class="card-region-name">
            제주 제주시 아라일동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 34
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274014399" href="/articles/274014399">
        <div class="card-photo ">
            <img alt="냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C9676D66084FD2EE00AE6C5D39B265627CB06197DEA6DADBC3EB2440A5FC6B82.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">냉장고</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            광주 광산구 첨단2동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 23
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274004001" href="/articles/274004001">
        <div class="card-photo ">
            <img alt="다이슨 v8 청소기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/01F393E5F51B4DA32C817F14A46279A25EE40968CCA57B6F81E0F64FC82E1CE6.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">다이슨 v8 청소기</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            경기도 성남시 분당구 구미동
          </div>
          <div class="card-counts">
              <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 15
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273925231" href="/articles/273925231">
        <div class="card-photo ">
            <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/22957C51EA63B0E40AC59188498B4AA82E6BC2B82E5037C378B32C4A08E33A8B.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">철제선반</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            대구 중구 남산동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 25
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273975070" href="/articles/273975070">
        <div class="card-photo ">
            <img alt="스팸팔아요~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/730795bbe314437630ed5f1dd80bb123e33532212a0d42c8919c49b0147521f9.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">스팸팔아요~</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            부산 사하구 다대동
          </div>
          <div class="card-counts">
              <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 10
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273921135" href="/articles/273921135">
        <div class="card-photo ">
            <img alt="lg 휘센 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4DDEF244CCD690065ED6EEB04BFDBB754DDA838F5BABDECFA933F07E9A9825B9.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">lg 휘센 제습기</h2>
          <div class="card-price ">
            80,000원
          </div>
          <div class="card-region-name">
            경남 창원시 성산구 상남동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 15
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274012057" href="/articles/274012057">
        <div class="card-photo ">
            <img alt="★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/88AFB93658556EA3DF8603FB9064D00328F5AE3A92B26B4674DB0E0E808B2ACE.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>
          <div class="card-price ">
            30,000원
          </div>
          <div class="card-region-name">
            대구 북구 침산2동
          </div>
          <div class="card-counts">
              <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 16
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273927308" href="/articles/273927308">
        <div class="card-photo ">
            <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/91B8FEE166411BBBF5B7E506CE227FA9A29E5BC3E7AFEC07C4CF2B5F7D1BC7A1.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">철제선반</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            대구 중구 남산동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273960102" href="/articles/273960102">
        <div class="card-photo ">
            <img alt="컨테이너 하우스판매!!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/44A07ADE16BFFEF44BCE2A7B873642B164EE8ABFD6C95C6D3B014853E9FE2742.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">컨테이너 하우스판매!!</h2>
          <div class="card-price ">
            1원
          </div>
          <div class="card-region-name">
            제주 제주시 아라동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 16
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273986259" href="/articles/273986259">
        <div class="card-photo ">
            <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/84C5D0E0419D18BF87CD30C53893A12E62D691E470F8E380F83329FFBCD36527.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">전자레인지</h2>
          <div class="card-price ">
            15,000원
          </div>
          <div class="card-region-name">
            제주 제주시 노형동
          </div>
          <div class="card-counts">
              <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 13
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273810590" href="/articles/273810590">
        <div class="card-photo ">
            <img alt="삼천리 자전거 (아동용의자 포함)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/83d71123f025e54536a6bca0d372ab46cce152425b2f57eeed4c2f67b23a8c0b.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>
          <div class="card-price ">
            30,000원
          </div>
          <div class="card-region-name">
            경기도 고양시 일산서구 대화동
          </div>
          <div class="card-counts">
              <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 28
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273983175" href="/articles/273983175">
        <div class="card-photo ">
            <img alt="3단 원목 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f11c004faa962d4469ab4106a84088f634ea5cac4ba39190993206355d6ae4d2.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">3단 원목 수납장</h2>
          <div class="card-price ">
            6,000원
          </div>
          <div class="card-region-name">
            강원도 원주시 무실동
          </div>
          <div class="card-counts">
              <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 13
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273975026" href="/articles/273975026">
        <div class="card-photo ">
            <img alt="자전거 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2B4B3C6F4446A9C51CB36786F9B098609E5F34109596B7DD73EE4867D6953E11.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">자전거 팔아요!</h2>
          <div class="card-price ">
            100,000원
          </div>
          <div class="card-region-name">
            대전 유성구 전민동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273960878" href="/articles/273960878">
        <div class="card-photo ">
            <img alt="가정용냉장고 오늘가저가시면 이만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1B6F5E18EFE2153B27172E95CBAF7F76059AEC37C337DAE74FD425010DCCE0C4.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            충남 서산시 석림동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="271724995" href="/articles/271724995">
        <div class="card-photo ">
            <img alt="철제선반입니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/bd0433f673914e540acb68455a3c4a79e84f6c6c07832f0586d72a629fd406d7.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">철제선반입니다.</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            부산 기장군 정관읍
          </div>
          <div class="card-counts">
              <span>
                관심 98
              </span>
            ∙
            <span>
                채팅 114
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273998510" href="/articles/273998510">
        <div class="card-photo ">
            <img alt="프리즘티비 65인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6E4F741C258E9D77750D8FB6C14FB3A13F90076FF7CCBB6C0028CC3B627B2E10.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">프리즘티비 65인지</h2>
          <div class="card-price ">
            150,000원
          </div>
          <div class="card-region-name">
            경기도 용인시 처인구 모현읍
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 14
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273967671" href="/articles/273967671">
        <div class="card-photo ">
            <img alt="alton bike 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/207f7faddb43218ab52890d4c91746e1c60335e4375753716f8e84d064f8220f.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">alton bike 자전거 판매합니다</h2>
          <div class="card-price ">
            40,000원
          </div>
          <div class="card-region-name">
            경기도 용인시 기흥구 마북동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274010791" href="/articles/274010791">
        <div class="card-photo ">
            <img alt="엘지냉장고 140리터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f38888dd068862f05de80d5cfdbb1ff5f3b4699848a679d5da032e18c6196624.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">엘지냉장고 140리터</h2>
          <div class="card-price ">
            40,000원
          </div>
          <div class="card-region-name">
            전북 전주시 덕진구 덕진동2가
          </div>
          <div class="card-counts">
              <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273918993" href="/articles/273918993">
        <div class="card-photo ">
            <img alt="선반 오처넌에 가져가용" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FDE15F69B168951D98CA92D19D20B00B86B2202BAE0A3CE615BB6B7D3050FC11.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">선반 오처넌에 가져가용</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            부산 동래구 사직제3동
          </div>
          <div class="card-counts">
              <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 15
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273950972" href="/articles/273950972">
        <div class="card-photo ">
            <img alt="게임용 컴퓨터 i5 4460 팝니다~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/48be7bb4c31571557ea3e56719e2825fabc31c7cdfec0a5d427188619815bfee.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>
          <div class="card-price ">
            140,000원
          </div>
          <div class="card-region-name">
            울산 남구 신정3동
          </div>
          <div class="card-counts">
              <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 19
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273972991" href="/articles/273972991">
        <div class="card-photo ">
            <img alt="에어 컴프레셔 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2C42C9231F12BE0483C53AE1B0E26682174C49EDB51CEB435BB48332062B86D5.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">에어 컴프레셔 판매합니다</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            울산 남구 삼산동
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 5
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274002275" href="/articles/274002275">
        <div class="card-photo ">
            <img alt="리락쿠마스프링카" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D8489065A1683C218D8C0497BD66C896455566A3C72399477ABF304C3CCC8EB7.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">리락쿠마스프링카</h2>
          <div class="card-price ">
            15,000원
          </div>
          <div class="card-region-name">
            경기도 파주시 목동동
          </div>
          <div class="card-counts">
              <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273987132" href="/articles/273987132">
        <div class="card-photo ">
            <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3AA48CE014E9A50F79E64F3FF902AF757494984144A3C6AA92C910A28B3213AA.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">전자렌지</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            경남 김해시 구산동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273995769" href="/articles/273995769">
        <div class="card-photo ">
            <img alt="접이식 캠핑 테이블 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6a3686dfc685327d4dfdf9de0e02df3578c4c7e313f3ee3af080082f27aa1851.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>
          <div class="card-price ">
            15,000원
          </div>
          <div class="card-region-name">
            경남 김해시 장유3동
          </div>
          <div class="card-counts">
              <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273983001" href="/articles/273983001">
        <div class="card-photo ">
            <img alt="캠핑 의자 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4009e629f8942bc08a37b9ada25c722ec809da043f538789b280a0a2b0524c64.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">캠핑 의자 팝니다.</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            부산 사상구 모라제1동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 11
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273878099" href="/articles/273878099">
        <div class="card-photo ">
            <img alt="이케아 철제선반 묶음 판매합니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/05F5DE0883E7D711D0A56B346DD260440D54973C35814344386342D7EEC6B8D3.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>
          <div class="card-price ">
            25,000원
          </div>
          <div class="card-region-name">
            강원도 춘천시 동면
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 17
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273786394" href="/articles/273786394">
        <div class="card-photo ">
            <img alt="자전거 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7e03864758cd2f63955b1fb7bfb41a62d03fd7ec49b4085372090afe42526d95.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">자전거 팝니다</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            울산 남구 신정동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 15
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274000929" href="/articles/274000929">
        <div class="card-photo ">
            <img alt="조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/B80112B786A8F3F8EDF5A6E766F96414ED2D0BE68DE89874A6E36EADFD50513D.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>
          <div class="card-price ">
            550,000원
          </div>
          <div class="card-region-name">
            경기도 용인시 수지구 죽전동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273892150" href="/articles/273892150">
        <div class="card-photo ">
            <img alt="[일렉트로룩스] 전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D4089CFB9D98BA6960E40AFDFC872A8C75A3AAB22A324648D296AD04F2F963BB.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            서울 서대문구 대현동
          </div>
          <div class="card-counts">
              <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 16
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273808111" href="/articles/273808111">
        <div class="card-photo ">
            <img alt="2~3인용 쇼파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E05C187B87D79645127289C66A7D5C8363001A99CBFFFD690E2A41B96AAD6698.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">2~3인용 쇼파</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            제주 제주시 이호이동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273982810" href="/articles/273982810">
        <div class="card-photo ">
            <img alt="파세코 Camp-27 난로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1844CB33DFAD69B8CB864C64CAC23AB7E34CABAD4005561720C615E82D14C955.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">파세코 Camp-27 난로</h2>
          <div class="card-price ">
            280,000원
          </div>
          <div class="card-region-name">
            인천 계양구 계산3동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274022028" href="/articles/274022028">
        <div class="card-photo ">
            <img alt="푸름이까꿍" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/43e238fb7d674d3d1acc8dd16eb1a3f6de29f3a7173b09cae1552dc08dbab117.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">푸름이까꿍</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            부산 북구 만덕제2동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273968766" href="/articles/273968766">
        <div class="card-photo ">
            <img alt="수박1통2~3kg 1통 3천원 2통5천원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2ea3525511ac7d8be93ac5e3b973dc1b5b8e3b8165170008cf041e60cb2344bc.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>
          <div class="card-price ">
            3,000원
          </div>
          <div class="card-region-name">
            충북 음성군 생극면
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273922139" href="/articles/273922139">
        <div class="card-photo ">
            <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DA91C69D5D93229ADEFEB59ED52818E85BF84EC5403447EB2E9EF615DDDF0F2D.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">전자렌지</h2>
          <div class="card-price ">
            15,000원
          </div>
          <div class="card-region-name">
            서울 동대문구 신설동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274005752" href="/articles/274005752">
        <div class="card-photo ">
            <img alt="편하게 쓰기 좋은 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9434336919CC8C4B4AE0AA852E14A2A5F3F11A8A50424CDB9C7383A0A70B27E6.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            인천 서구 검암동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273649558" href="/articles/273649558">
        <div class="card-photo ">
            <img alt="디월트 임팩트드라이버 DCF887P2A 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/AE703E015FF49B83C5EA7F46058D85B2015D6FDC6CE47598CBB2C518AB8362E7.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>
          <div class="card-price ">
            160,000원
          </div>
          <div class="card-region-name">
            강원도 원주시 원동
          </div>
          <div class="card-counts">
              <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 21
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273636900" href="/articles/273636900">
        <div class="card-photo ">
            <img alt="냉동고 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/60D0595365B3BA12AFCD71425432CC00CB59EA90C108A13CC0BEF25C6DE47000.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">냉동고 팔아요!</h2>
          <div class="card-price ">
            100,000원
          </div>
          <div class="card-region-name">
            서울 강남구 역삼2동
          </div>
          <div class="card-counts">
              <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 10
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273792490" href="/articles/273792490">
        <div class="card-photo ">
            <img alt="MTB 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/10d26d7590f6d22875a65a2337663b4894b52f12fc7f67a7feda3d6a9e9ac5eb.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">MTB 자전거 판매합니다</h2>
          <div class="card-price ">
            70,000원
          </div>
          <div class="card-region-name">
            경기도 파주시 운정1동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273843222" href="/articles/273843222">
        <div class="card-photo ">
            <img alt="네스프레소 커피머신" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3084582B2BC492DE01787B3FA998AFFD1B80B36D89CF0C708366BB3C4205F241.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">네스프레소 커피머신</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            경기도 용인시 수지구 상현동
          </div>
          <div class="card-counts">
              <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 13
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273869355" href="/articles/273869355">
        <div class="card-photo ">
            <img alt="아이패드 미니 2세대 32g" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D915CC0C94FA942A183567B54B5B5D4EFF5CF62D77C8184D0863C82DAEC50815.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">아이패드 미니 2세대 32g</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            서울 송파구 방이2동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 5
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273961825" href="/articles/273961825">
        <div class="card-photo ">
            <img alt="에어컨 수거해가시면 2만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/105CCC1F8D715A243EDB60BF217361923B9B600B3A4BFC82A3A17B3D0C067765.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">에어컨 수거해가시면 2만원</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            충남 서산시 석림동
          </div>
          <div class="card-counts">
              <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="271187738" href="/articles/271187738">
        <div class="card-photo ">
            <img alt="한샘 원목 철제 책장 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FF1123F4FC1F106BCB475E980CD40FD03C12DC9EA186F3C44B8C83BDE5DF029D.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            서울 동작구 흑석동
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273962285" href="/articles/273962285">
        <div class="card-photo ">
            <img alt="냉장고 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9d9fe431056c17482ec543f00e47dad6e02ac7227fb55e9cac37f79477def34a.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">냉장고 팝니다</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            전남 여수시 둔덕동
          </div>
          <div class="card-counts">
              <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273984751" href="/articles/273984751">
        <div class="card-photo ">
            <img alt="딤채 김치냉장고 드립니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/847c742c07e5438607152059f4bc77326baab027e8d8c3795bc60e5b2137bf84.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>
          <div class="card-price ">
            무료나눔
          </div>
          <div class="card-region-name">
            경기도 부천시 상1동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273987712" href="/articles/273987712">
        <div class="card-photo ">
            <img alt="삼성 냉난방기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E2F19693CA6462113B9D2426AB3254B69AC034E60174E606BF78CD6A62F6C701.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">삼성 냉난방기</h2>
          <div class="card-price ">
            400,000원
          </div>
          <div class="card-region-name">
            대구 수성구 수성4가동
          </div>
          <div class="card-counts">
              <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 10
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273869503" href="/articles/273869503">
        <div class="card-photo ">
            <img alt="이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/34129bac567170224e955da708d6de35caf817c921034717ef67490bf21e9ee7.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            경남 창원시 마산합포구 현동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273876104" href="/articles/273876104">
        <div class="card-photo ">
            <img alt="벤츠 골프백 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/5469ade3eb86dd407a46b279bfeec34898cea3b48bccf312fb9c65d60eaa788a.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">벤츠 골프백 판매합니다</h2>
          <div class="card-price ">
            40,000원
          </div>
          <div class="card-region-name">
            경기도 남양주시 별내동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273962891" href="/articles/273962891">
        <div class="card-photo ">
            <img alt="신세계상품권" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/8807D19A15756C05FECF99B6C5EC897C71512206EF57F40906D03F498E60DF5B.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">신세계상품권</h2>
          <div class="card-price ">
            45,000원
          </div>
          <div class="card-region-name">
            서울 강남구 역삼동
          </div>
          <div class="card-counts">
              <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273997532" href="/articles/273997532">
        <div class="card-photo ">
            <img alt="미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7a45cb368f9d5088a49c7ce5936a68535bfeb73395e797ad8f5a1b162a8812be.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>
          <div class="card-price ">
            800,000원
          </div>
          <div class="card-region-name">
            제주 제주시 조천읍
          </div>
          <div class="card-counts">
              <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273945035" href="/articles/273945035">
        <div class="card-photo ">
            <img alt="30인치 넘는 삼성 티비 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FC81D1AE7993ADB1A91905CB7155CBB6DBF2DA4F396AD024A340C326B862EBFC.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            경남 창원시 의창구 신월동
          </div>
          <div class="card-counts">
              <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 15
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273780489" href="/articles/273780489">
        <div class="card-photo ">
            <img alt="삼성32인치LED 티비겸모니터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/98ACB1173483236E2057DA3BED3CF980363A4AFB24DE008933FFCE4EFD958188.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            충북 청주시 청원구 우암동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273718765" href="/articles/273718765">
        <div class="card-photo ">
            <img alt="43인치 TV 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FA047E879738FB0D1B29DE97783D893E6DEF4F14B057616BDBBDAEBD361A6F40.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">43인치 TV 팝니다</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            서울 서대문구 홍제제3동
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273793234" href="/articles/273793234">
        <div class="card-photo ">
            <img alt="딤채 김치냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4C8FB14C2A3BB18B0A0DF5FCDF44A755C95FAF2D74C213C34E1F83FF148D0D2.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">딤채 김치냉장고</h2>
          <div class="card-price ">
            200,000원
          </div>
          <div class="card-region-name">
            경기도 파주시 운정3동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274006581" href="/articles/274006581">
        <div class="card-photo ">
            <img alt="프롬유 샤워핸들" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/58ED958764AAAFEF030B8454EA5A0754F3F35BB225FB7E8D592D938FED7840A2.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">프롬유 샤워핸들</h2>
          <div class="card-price ">
            35,000원
          </div>
          <div class="card-region-name">
            경기도 화성시 산척동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274019532" href="/articles/274019532">
        <div class="card-photo ">
            <img alt="반석스포츠 아령 3kg/5kg 세트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68604AF514546143D439B389483DEDBD48E246C9AD2478B84128901E1A10D964.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            대전 유성구 도룡동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273815819" href="/articles/273815819">
        <div class="card-photo ">
            <img alt="갤럭시탭 s6 lite 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/CE7FAA2CD5A30B1C7EAF7AC120D1A5B6C840D206D968A11794C7D5B576F6ADA3.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>
          <div class="card-price ">
            250,000원
          </div>
          <div class="card-region-name">
            경기도 남양주시 다산1동
          </div>
          <div class="card-counts">
              <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 10
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274005062" href="/articles/274005062">
        <div class="card-photo ">
            <img alt="몬테소리 레인보우 사운드 비즈 트리" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E8B876CEACE47741BDD360B73E03A9830D9A456044579429E14C58F012049F5C.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            경기도 수원시 권선구 당수동
          </div>
          <div class="card-counts">
              <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273959401" href="/articles/273959401">
        <div class="card-photo ">
            <img alt="갤럭시 노트 10 플러스 + 256기가 A급" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1ef2adc9192d1247239fe763a6523372727b638472d579ca90dcd6f922babe3a.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>
          <div class="card-price ">
            350,000원
          </div>
          <div class="card-region-name">
            경기도 고양시 일산동구 정발산동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 10
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273843776" href="/articles/273843776">
        <div class="card-photo ">
            <img alt="캣폴(캣타워) 가또블랑코 하이엔드" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/d99f99bc033a8311c56553a17b57f306998c61682682dabf6ac1a3b577bfe69b.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            서울 성북구 장위동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 11
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274023175" href="/articles/274023175">
        <div class="card-photo ">
            <img alt="신세계 상품권 만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/31A0B799D3E4A2A6C726613C1EFF292BD5BA052FD537FD397663A70AF2F503AE.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">신세계 상품권 만원</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            울산 남구 삼산동
          </div>
          <div class="card-counts">
              <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273572748" href="/articles/273572748">
        <div class="card-photo ">
            <img alt="장인한과 파지약과" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79B8387D6FD309E874D2099FC92E2BC0E054D700F53E5CD676E71ED8C6293C33.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">장인한과 파지약과</h2>
          <div class="card-price ">
            2,000원
          </div>
          <div class="card-region-name">
            경기도 구리시 수택3동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 14
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273794168" href="/articles/273794168">
        <div class="card-photo ">
            <img alt="원목의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e78b47286e61dfb5b2a2e4cc79a7db6af4bd3f3934ad7a94bf5bb88bf3444f22.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">원목의자</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            제주 서귀포시 서귀동
          </div>
          <div class="card-counts">
              <span>
                관심 13
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273506160" href="/articles/273506160">
        <div class="card-photo ">
            <img alt="엘지 드럼세탁기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39c8eee89806fadd22f7b9e89c6f6e7d500a175bac4cca9f0e3d00e4822b4196.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">엘지 드럼세탁기</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            서울 서초구 서초동
          </div>
          <div class="card-counts">
              <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 4
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274001821" href="/articles/274001821">
        <div class="card-photo ">
            <img alt="캐리어 클라윈드 138L 냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/460A4D7C5793B0EDA3467FFABAC75D96343D6552B6F929BAF609029ACC2190BD.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>
          <div class="card-price ">
            90,000원
          </div>
          <div class="card-region-name">
            서울 동대문구 용두동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 5
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273904456" href="/articles/273904456">
        <div class="card-photo ">
            <img alt="삼천리 자전거 20 스넬로 미니벨로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DF78DE0D36D30AED5A656B8F9FF49C4D8F2A446EC63EF32773A3D164020AA3D0.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>
          <div class="card-price ">
            30,000원
          </div>
          <div class="card-region-name">
            서울 송파구 잠실동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 4
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273899049" href="/articles/273899049">
        <div class="card-photo ">
            <img alt="수납 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/49C49B0EE59B0F73DCD852F95D406B7384AFFDE1CA0AB59503CEA5491AA83F65.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">수납 선반</h2>
          <div class="card-price ">
            5,000원
          </div>
          <div class="card-region-name">
            광주 서구 쌍촌동
          </div>
          <div class="card-counts">
              <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 5
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273754420" href="/articles/273754420">
        <div class="card-photo ">
            <img alt="그래픽카드 및 cpu" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/36e32e7f5a67eef732b0c19f19711bb7243ff1734bc7d1f5cc68e061da36fc55.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">그래픽카드 및 cpu</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            제주 제주시 아라동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 18
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273960264" href="/articles/273960264">
        <div class="card-photo ">
            <img alt="2인용 쇼파 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/35636482F4B888B12240D19A951F7A4496FCE1B5F5E7F5B5B88C5A802C5B3AB4.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">2인용 쇼파 </h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            제주 제주시 조천읍
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273956622" href="/articles/273956622">
        <div class="card-photo ">
            <img alt="i5-7500 32인치모니터 컴퓨터 셋트 팜니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C0EB2C9BCC2057D517B52C97903052BD731B6372741D9D0837518760A015F8BD.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>
          <div class="card-price ">
            500,000원
          </div>
          <div class="card-region-name">
            충남 천안시 서북구 두정동
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 1
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274009707" href="/articles/274009707">
        <div class="card-photo ">
            <img alt="책장 무료드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39b59bc6014b9366d01ea4c93fe4be305f4d9646321e39ff4b337ca4e7b8617e.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">책장 무료드림</h2>
          <div class="card-price ">
            무료나눔
          </div>
          <div class="card-region-name">
            대구 달서구 본리동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273734192" href="/articles/273734192">
        <div class="card-photo ">
            <img alt="UHD TV  모델명UN65NU7050FXKR  내놓아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/87a99c47e7e0d0e048806327638033f248214569226d25d1c2de8090b4e06e9d.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>
          <div class="card-price ">
            450,000원
          </div>
          <div class="card-region-name">
            제주 서귀포시 안덕면
          </div>
          <div class="card-counts">
              <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 7
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273972531" href="/articles/273972531">
        <div class="card-photo ">
            <img alt="이케아 선반을 무료로 드려요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/100DB9496625CB911682A344FCEE41FA0FD48338E5CFF169371549F1635D5D67.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">이케아 선반을 무료로 드려요</h2>
          <div class="card-price blank-price">
            -
          </div>
          <div class="card-region-name">
            경기도 안산시 단원구 선부1동
          </div>
          <div class="card-counts">
              <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273623778" href="/articles/273623778">
        <div class="card-photo ">
            <img alt="아람 자연이랑 전집 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C2DD4F67EBCE23DD9933E32AA970EE6A8BE00067FD0FA703C2D25ADE86C8A111.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">아람 자연이랑 전집 </h2>
          <div class="card-price ">
            70,000원
          </div>
          <div class="card-region-name">
            서울 강남구 대치1동
          </div>
          <div class="card-counts">
              <span>
                관심 17
              </span>
            ∙
            <span>
                채팅 20
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273962348" href="/articles/273962348">
        <div class="card-photo ">
            <img alt="알톤자전거21단" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/774409914ce1936adf8d482726e06e3a39870821c11bd91cde8f2e6f6013ea94.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">알톤자전거21단</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            서울 송파구 송파1동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273908814" href="/articles/273908814">
        <div class="card-photo ">
            <img alt="원룸 정리_ 책상,의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3FC3FA0F9D2A793F489E30E06E9E00BDC5D4EA34DB00D073A28C1216B968FB36.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">원룸 정리_ 책상,의자</h2>
          <div class="card-price ">
            15,000원
          </div>
          <div class="card-region-name">
            부산 부산진구 부전동
          </div>
          <div class="card-counts">
              <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 5
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273978876" href="/articles/273978876">
        <div class="card-photo ">
            <img alt="전자렌지 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68550D76BA1CC4FD76FF442E547B17135DB42A00EF5F82B43DE4FF4D22835B2C.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">전자렌지 팔아요</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            대전 유성구 구암동
          </div>
          <div class="card-counts">
              <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273198719" href="/articles/273198719">
        <div class="card-photo ">
            <img alt="삼성냉장고 상태좋습니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/00e7811fc6746aea408e14711ed4d1e937bd7cd2b1e81bfeb7738d076b1d8737.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">삼성냉장고 상태좋습니다</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            부산 사상구 주례동
          </div>
          <div class="card-counts">
              <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 21
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274024826" href="/articles/274024826">
        <div class="card-photo ">
            <img alt="선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6AA9F9BCC36E47CD2C1DFAE51969C435DA2EF4560A787DBDC74C256D41B8788C.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">선반</h2>
          <div class="card-price ">
            9,000원
          </div>
          <div class="card-region-name">
            경남 진주시 호탄동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 17
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273920668" href="/articles/273920668">
        <div class="card-photo ">
            <img alt="안방그릴(연기안나는 전기그릴)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/21A48D6C5A5BE833055724CF260F8D21244EFE6220264012019B88019DBE33AA.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>
          <div class="card-price ">
            100,000원
          </div>
          <div class="card-region-name">
            광주 서구 화정2동
          </div>
          <div class="card-counts">
              <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 4
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274000811" href="/articles/274000811">
        <div class="card-photo ">
            <img alt="숀리 바이크 실내자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79FA3C4A067A48344D69C4EA48783F7D0135BA1B444D4E26BD0291162E37501D.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">숀리 바이크 실내자전거</h2>
          <div class="card-price ">
            50,000원
          </div>
          <div class="card-region-name">
            경북 구미시 봉곡동
          </div>
          <div class="card-counts">
              <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 6
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274011505" href="/articles/274011505">
        <div class="card-photo ">
            <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3a720aea0080c736ae65e82644582af4f949e2801fe3043e141008a23e52e519.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">전자레인지</h2>
          <div class="card-price ">
            7,000원
          </div>
          <div class="card-region-name">
            충남 천안시 동남구 신방동
          </div>
          <div class="card-counts">
              <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273894828" href="/articles/273894828">
        <div class="card-photo ">
            <img alt="알톤전기자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4F7C5F656D7FB042486D22D0AA3F766792F3DA5A34ACA8413EAC0FBA1277499.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">알톤전기자전거</h2>
          <div class="card-price ">
            300,000원
          </div>
          <div class="card-region-name">
            서울 동대문구 답십리동
          </div>
          <div class="card-counts">
              <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273843713" href="/articles/273843713">
        <div class="card-photo ">
            <img alt="이케아 철제 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/18D633E7264B7B1FAEAE281432721888C9ABB644EBC530798B03B5474F31AC3E.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">이케아 철제 선반</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            경남 창원시 성산구 반림동
          </div>
          <div class="card-counts">
              <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 22
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273956856" href="/articles/273956856">
        <div class="card-photo ">
            <img alt="3인용소파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/50aeabaf787472b725905babce0df5a53ba9360f01f058a965e6abb9943097bc.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">3인용소파</h2>
          <div class="card-price ">
            70,000원
          </div>
          <div class="card-region-name">
            부산 수영구 망미제2동
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 8
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="274006145" href="/articles/274006145">
        <div class="card-photo ">
            <img alt="에듀테이블" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/b45e21bdc0bffc0b97a27f284057fa7c55fae74f04cfe54e7268d2c5d6c84a36.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">에듀테이블</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            전북 전주시 덕진구 송천동2가
          </div>
          <div class="card-counts">
              <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273860081" href="/articles/273860081">
        <div class="card-photo ">
            <img alt="캠핑매트 에어포스 에어매트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e11104a3d21f69dba73a3429d5f348319325349cd58e070a7e0b0b4f5523ced6.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>
          <div class="card-price ">
            150,000원
          </div>
          <div class="card-region-name">
            경기도 수원시 영통구 매탄1동
          </div>
          <div class="card-counts">
              <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 2
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273935179" href="/articles/273935179">
        <div class="card-photo ">
            <img alt="LG 냉장고 (566리터)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68efdee818ecd0546590913b7f611dded1ed835155af92384eda15c5141bac4b.webp?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">LG 냉장고 (566리터)</h2>
          <div class="card-price ">
            70,000원
          </div>
          <div class="card-region-name">
            경기도 화성시 향남읍
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 12
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273892310" href="/articles/273892310">
        <div class="card-photo ">
            <img alt="방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/565B9C7C477F683844CB4D39FC321CA7808E3754A2429953A20D11E009960C15.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>
          <div class="card-price ">
            9,000원
          </div>
          <div class="card-region-name">
            서울 강남구 압구정동
          </div>
          <div class="card-counts">
              <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273987830" href="/articles/273987830">
        <div class="card-photo ">
            <img alt="아이두젠 헥사타프" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/0750A7891C444592553BA5A89BB630786D6BA4FC5BBCC65A017ADC4C3C50AC40.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">아이두젠 헥사타프</h2>
          <div class="card-price ">
            20,000원
          </div>
          <div class="card-region-name">
            경기도 군포시 도마교동
          </div>
          <div class="card-counts">
              <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 9
              </span>
          </div>
        </div>
    </a></article>
    <article class="card-top ">
      <a class="card-link " data-event-label="273971674" href="/articles/273971674">
        <div class="card-photo ">
            <img alt="3단 접이식 메트리스 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3E48CDE679DADCDA82154FB4785B7F2A1B32AB23FE3339AF0481F71533AC501D.jpg?q=82&amp;s=300x300&amp;t=crop" />
        </div>
        <div class="card-desc">
          <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>
          <div class="card-price ">
            10,000원
          </div>
          <div class="card-region-name">
            부산 강서구 명지1동
          </div>
          <div class="card-counts">
              <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 4
              </span>
          </div>
        </div>
    </a></article>
    
      </section>
    
      <section id="hot-articles-go-download">
        <h3>
            더 구경하고 싶나요?
        </h3>
        <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>
        <div id="hot-articles-download-buttons">
            <a target="_blank" class="download-button" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8">
              <div class="home-apple-store-bar-white"></div>
              <div class="download-text">App Store</div>
    </a>        <a target="_blank" class="download-button" href="https://play.google.com/store/apps/details?id=com.towneers.www">
              <div class="home-google-play-bar-white"></div>
              <div class="download-text">Google Play</div>
    </a>    </div>
      </section>
    </section>
    <script type="text/javascript" charset="utf-8">
      function changeRegion(key, value){
        var url_array
        if(window.location.pathname === "/hot_articles" && window.location.href.match(/\?/)) {
          url_array = window.location.href.split('?')[1].split(/(?:r1|&?r2)=/)
          url_array.unshift("")
        } else {
          url_array = window.location.pathname.split('/')
        }
        var keys = { r1: 2, r2: 3, r3: 4 }
        url_array[keys[key]] = value
        url_array[1] = 'region'
          if(key == 'r2' && decodeURI(url_array[2]) == "세종특별자치시") {
            url_array[4] = value
            url_array[3] = "_"
          }
        if(key == 'r1') { url_array.splice(3, 2) }
        if(key == 'r2' && url_array[3] !== "_") { url_array.splice(4, 1) }
        window.location.href = window.location.origin + url_array.join('/')
      }
    </script>
    
    <footer id="footer">
      <div class="footer-container">
        <div class="footer-top">
          <div class="footer-logo"></div>
          <ul class="footer-list">
            <li class="footer-list-item"><a class="link-highlight" href="/trust">믿을 수 있는 중고거래</a></li>
            <li class="footer-list-item"><a class="link-highlight" href="https://cs.kr.karrotmarket.com/wv/faqs">자주 묻는 질문</a></li>
          </ul>
          <ul class="footer-list">
            <li class="footer-list-item"><a target="_blank" class="link-highlight" href="https://ad.daangn.com/">광고주센터</a></li>
            <li class="footer-list-item">
              <a target="_blank" class="ga-click" data-event-category="town_link_from" data-event-action="hot_articles" data-event-label="footer_town" href="https://town.daangn.com">동네가게</a>
            </li>
          </ul>
          <ul class="footer-list">
            <li class="footer-list-item"><a target="_blank" href="https://team.daangn.com/">회사 소개</a></li>
            <li class="footer-list-item"><a target="_blank" href="https://team.daangn.com/jobs/">채용</a></li>
          </ul>
          <ul class="footer-list policy">
            <li class="footer-list-item"><a target="_blank" href="https://policy.daangn.com/terms.html">이용약관</a></li>
            <li class="footer-list-item"><a target="_blank" href="https://policy.daangn.com/privacy.html">개인정보처리방침</a></li>
            <li class="footer-list-item"><a target="_blank" href="https://policy.daangn.com/location.html">위치기반서비스 이용약관</a></li>
          </ul>
        </div>
        <div class="footer-bottom">
          <div id="copyright">
            <ul class="copyright-list">
              <li class="copyright-list-item">고객문의 <a href="mailto:cs@daangnservice.com">cs@daangnservice.com</a></li>
              <li class="copyright-list-item">제휴문의 <a href="mailto:contact@daangn.com">contact@daangn.com</a></li>
            </ul>
            <ul class="copyright-list">
              <li class="copyright-list-item">지역광고 <a href="mailto:ad@daangn.com">ad@daangn.com</a></li>
              <li class="copyright-list-item">PR문의 <a href="mailto:pr@daangn.com">pr@daangn.com</a></li>
            </ul>
            <ul class="copyright-list copyright-list-light">
              <li class="copyright-list-item"><address>서울특별시 구로구 디지털로 30길 28 609호 (당근서비스)</address></li>
              <li class="copyright-list-item">사업자 등록번호 : 375-87-00088</li>
              <li class="copyright-list-item">직업정보제공사업 신고번호 : J1200020200016</li>
            </ul>
            <div id="social">
              <ul class="social-list">
                <li class="social-list-item">
                  <a target="_blank" class="footer-social-link" href="https://www.facebook.com/daangn">
                    <img alt="facebook" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-facebook-0563f4a93852d073b41f13b8bcabb03d47af3bb3a6755cdfedd8a73686c7f18c.svg" />
                    <span class="sr-only">facebook</span>
    </a>            </li>
                <li class="social-list-item">
                  <a target="_blank" class="footer-social-link" href="https://www.instagram.com/daangnmarket/">
                    <img alt="instagram" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-instagram-2f6c88a461597907c114b7ce28eab053fcae791ed26417915fefb6f7c9f95756.svg" />
                    <span class="sr-only">instagram</span>
    </a>            </li>
                <li class="social-list-item">
                  <a target="_blank" class="footer-social-link" href="https://blog.naver.com/daangn">
                    <img alt="blog" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-blog-e1b0d512d1766a6962ec5bbb5b0803d2a6a9c55ad97db5ba9eebb76013caceba.svg" />
                    <span class="sr-only">blog</span>
    </a>            </li>
                <li class="global-links">
                  <img src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-global-2f53678b428ec623cefd07a90dd7777f3e55fc0433918f645d7d75ace6ff1fc3.png" width="24" height="24" />
                  <select id="global-links-select">
                    <option value="kr">한국</option>
                    <option value="https://uk.karrotmarket.com">영국</option>
                    <option value="https://ca.karrotmarket.com">캐나다</option>
                    <option value="https://us.karrotmarket.com">미국</option>
                    <option value="https://jp.karrotmarket.com">일본</option>
                </select>
                </li>
              </ul>
            </div>
            <div class="copyright-text">©Danggeun Market Inc.</div>
          </div>
        </div>
      </div>
    </footer>
    
    
    </body>
    </html>
    
    


```python
import requests
from bs4 import BeautifulSoup
webpage = requests.get("https://www.daangn.com/hot_articles")
soup = BeautifulSoup(webpage.content, "html.parser")
print(soup)
```

    <!DOCTYPE html>
    
    <html lang="ko">
    <head>
    <meta charset="utf-8"/>
    <meta content="IE=edge" http-equiv="X-UA-Compatible"/>
    <meta content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no" name="viewport"/>
    <link href="https://www.daangn.com/hot_articles" rel="canonical"/>
    <title>당근마켓 중고거래 | 당신 근처의 당근마켓</title>
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." name="description">
    <link href="당근마켓" rel="author"/>
    <meta content="https://www.daangn.com/hot_articles" property="og:url">
    <meta content="당근마켓 중고거래 | 당신 근처의 당근마켓" property="og:title">
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." property="og:description"/>
    <meta content="당근마켓" property="og:site_name"/>
    <meta content="https://www.daangn.com/images/meta/home/flea_market.png" property="og:image"/>
    <meta content="article" property="og:type"/>
    <meta content="ko_KR" property="og:locale"/>
    <meta content="1463621440622064" property="fb:app_id"/>
    <meta content="summary_large_image" name="twitter:card"/>
    <meta content="@danggeunmarket" name="twitter:site"/>
    <meta content="당근마켓 중고거래 | 당신 근처의 당근마켓" name="twitter:title"/>
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." name="twitter:description"/>
    <meta content="https://www.daangn.com/images/meta/home/flea_market.png" name="twitter:image"/>
    <meta content="d1f8112731c18313535732cf2516d6401bfed40a" name="naver-site-verification"/>
    <link href="/images/icons/shortcut_icon.png" rel="shortcut icon" type="image/x-icon"/>
    <link href="https://d1unjqcospf8gs.cloudfront.net/favicon.ico" rel="shortcut icon" type="image/x-icon">
    <link href="https://d1unjqcospf8gs.cloudfront.net/assets/home/articles/hot-76409f246af8ba6ca58659826685527e45104fd2b089dd053e6af97133bb193b.css" media="all" rel="stylesheet"/>
    <script src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base-a182b6524ddb27bbc6a0647ee4bc2b79384325e8bde2b0775b94c7573fd0d87e.js"></script>
    <link href="/images/icons/daangn_logo_192.png" rel="apple-touch-icon" sizes="192x192"/>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->
    <meta content="authenticity_token" name="csrf-param"/>
    <meta content="u3KG84YcReIJ0Msd8mlG6T/aYodEKU5+Dz4l7QPp2tiUC0b24Z12Vj5TBot85lU96zE7BLHHLn9sYrfKNZzoSA==" name="csrf-token"/>
    <script>
        window.fbAsyncInit = function() {
          FB.init({
            appId      : '1463621440622064',
            xfbml      : true,
            version    : 'v2.4'
          });
        };
    
        (function(d, s, id){
          var js, fjs = d.getElementsByTagName(s)[0];
          if (d.getElementById(id)) {return;}
          js = d.createElement(s); js.id = id;
          js.src = "//connect.facebook.net/en_US/sdk.js";
          fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'facebook-jssdk'));
      </script>
    <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
                  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
                m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    
        ga('create', 'UA-64551386-2', 'auto');
         ga('set', 'dimension2', 'true');  ga('send', 'pageview'); </script>
    <!-- Facebook Pixel Code -->
    <script>
        !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
                n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
          n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
          t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
                document,'script','//connect.facebook.net/en_US/fbevents.js');
    
        fbq('init', '992961397411651');
        facebookClickEvent("PageView")
    
        function facebookClickEvent(eventName, data) {
          if (data !== undefined) {
              fbq('track', eventName, data)
          } else {
              fbq('track', eventName)
          }
        }
    
        function facebookClickEventWithPageMove(eventName, data, targetUrl) {
            facebookClickEvent(eventName, data);
            window.location.href = targetUrl;
        }
      </script>
    <noscript><img height="1" src="https://www.facebook.com/tr?id=992961397411651&amp;ev=PageView&amp;noscript=1" style="display:none" width="1"/></noscript>
    <!-- End Facebook Pixel Code -->
    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
          new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
          j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
          'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
      })(window,document,'script','dataLayer','GTM-PJSK4QL');</script>
    <!-- End Google Tag Manager -->
    <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Organization",
      "name": "당근마켓",
      "url": "https://www.daangn.com",
      "sameAs": [
        "https://www.facebook.com/daangn",
        "https://blog.naver.com/daangn",
        "https://www.youtube.com/channel/UC8tsBsQBuF7QybxgLmStihA",
        "https://twitter.com/daangnmarket",
        "https://www.instagram.com/daangnmarket",
        "https://apps.apple.com/kr/app/id1018769995",
        "https://play.google.com/store/apps/details?id=com.towneers.www"
      ],
      "logo": "https://www.daangn.com/logo.png"
    }
    </script>
    </link></meta></meta></meta></head>
    <body class="hoian-kr">
    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe height="0" src="https://www.googletagmanager.com/ns.html?id=GTM-PJSK4QL" style="display:none;visibility:hidden" width="0"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
    <!-- Appsflyer Smart Banner -->
    <script>
        !function(t,e,n,s,a,c,i,o,p){t.AppsFlyerSdkObject=a,t.AF=t.AF||function(){(t.AF.q=t.AF.q||[]).push([Date.now()].concat(Array.prototype.slice.call(arguments)))},t.AF.id=t.AF.id||i,t.AF.plugins={},o=e.createElement(n),p=e.getElementsByTagName(n)[0],o.async=1,o.src="https://websdk.appsflyer.com?"+(c.length>0?"st="+c.split(",").sort().join(",")+"&":"")+(i.length>0?"af_id="+i:""),p.parentNode.insertBefore(o,p)}(window,document,"script",0,"AF","banners",{banners: {key: "629f6f7a-a2a6-49c0-8d27-ffa48df1cd0e"}})
        AF('banners', 'showBanner')
    </script>
    <!-- End Appsflyer Smart Banner-->
    <header id="fixed-bar">
    <div id="fixed-bar-wrap">
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    </div>
    </header>
    <section id="content">
    <h1 class="head-title" id="hot-articles-head-title">
        
        
        중고거래 인기매물
      </h1>
    <nav id="hot-articles-navigation">
    <select class="hot-articles-nav-select" id="region1" name="region1" onchange="changeRegion('r1', this.value)"><option value="">지역을 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    <select class="hot-articles-nav-select" disabled="disabled" id="region2" name="region2" onchange="changeRegion('r2', this.value)"><option value="">동네를 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    </nav>
    <section class="cards-wrap">
    <article class="card-top">
    <a class="card-link" data-event-label="273865202" href="/articles/273865202">
    <div class="card-photo">
    <img alt="삼성 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/da035d5794d5490a86e8596a2ff036db7a6811cde70b8e2cb5514a93f4c0d1af.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 제습기</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 서구 갈마동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 47
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972258" href="/articles/273972258">
    <div class="card-photo">
    <img alt="🎈4단 경량 서랍장 2EA" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E5286230DC4F10CDC1187AF093DC98E700866C3F3CCE2D26B4097EC8E096EF02.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            전남 순천시 해룡면
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869268" href="/articles/273869268">
    <div class="card-photo">
    <img alt="마켓비 철제장수납장 드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1BF6CACC4CF68494129932B87B0C9B3A079DDE8C4BA714BD93E4BF5DAEBC10E8.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">마켓비 철제장수납장 드림</h2>
    <div class="card-price">
            10원
          </div>
    <div class="card-region-name">
            제주 제주시 아라일동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 34
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274014399" href="/articles/274014399">
    <div class="card-photo">
    <img alt="냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C9676D66084FD2EE00AE6C5D39B265627CB06197DEA6DADBC3EB2440A5FC6B82.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            광주 광산구 첨단2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 23
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274004001" href="/articles/274004001">
    <div class="card-photo">
    <img alt="다이슨 v8 청소기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/01F393E5F51B4DA32C817F14A46279A25EE40968CCA57B6F81E0F64FC82E1CE6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">다이슨 v8 청소기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경기도 성남시 분당구 구미동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273925231" href="/articles/273925231">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/22957C51EA63B0E40AC59188498B4AA82E6BC2B82E5037C378B32C4A08E33A8B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 25
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975070" href="/articles/273975070">
    <div class="card-photo">
    <img alt="스팸팔아요~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/730795bbe314437630ed5f1dd80bb123e33532212a0d42c8919c49b0147521f9.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">스팸팔아요~</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 사하구 다대동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273921135" href="/articles/273921135">
    <div class="card-photo">
    <img alt="lg 휘센 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4DDEF244CCD690065ED6EEB04BFDBB754DDA838F5BABDECFA933F07E9A9825B9.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">lg 휘센 제습기</h2>
    <div class="card-price">
            80,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 상남동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274012057" href="/articles/274012057">
    <div class="card-photo">
    <img alt="★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/88AFB93658556EA3DF8603FB9064D00328F5AE3A92B26B4674DB0E0E808B2ACE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            대구 북구 침산2동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273927308" href="/articles/273927308">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/91B8FEE166411BBBF5B7E506CE227FA9A29E5BC3E7AFEC07C4CF2B5F7D1BC7A1.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960102" href="/articles/273960102">
    <div class="card-photo">
    <img alt="컨테이너 하우스판매!!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/44A07ADE16BFFEF44BCE2A7B873642B164EE8ABFD6C95C6D3B014853E9FE2742.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">컨테이너 하우스판매!!</h2>
    <div class="card-price">
            1원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273986259" href="/articles/273986259">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/84C5D0E0419D18BF87CD30C53893A12E62D691E470F8E380F83329FFBCD36527.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            제주 제주시 노형동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273810590" href="/articles/273810590">
    <div class="card-photo">
    <img alt="삼천리 자전거 (아동용의자 포함)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/83d71123f025e54536a6bca0d372ab46cce152425b2f57eeed4c2f67b23a8c0b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산서구 대화동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 28
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983175" href="/articles/273983175">
    <div class="card-photo">
    <img alt="3단 원목 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f11c004faa962d4469ab4106a84088f634ea5cac4ba39190993206355d6ae4d2.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 원목 수납장</h2>
    <div class="card-price">
            6,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 무실동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975026" href="/articles/273975026">
    <div class="card-photo">
    <img alt="자전거 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2B4B3C6F4446A9C51CB36786F9B098609E5F34109596B7DD73EE4867D6953E11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            대전 유성구 전민동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960878" href="/articles/273960878">
    <div class="card-photo">
    <img alt="가정용냉장고 오늘가저가시면 이만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1B6F5E18EFE2153B27172E95CBAF7F76059AEC37C337DAE74FD425010DCCE0C4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271724995" href="/articles/271724995">
    <div class="card-photo">
    <img alt="철제선반입니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/bd0433f673914e540acb68455a3c4a79e84f6c6c07832f0586d72a629fd406d7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반입니다.</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 기장군 정관읍
          </div>
    <div class="card-counts">
    <span>
                관심 98
              </span>
            ∙
            <span>
                채팅 114
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273998510" href="/articles/273998510">
    <div class="card-photo">
    <img alt="프리즘티비 65인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6E4F741C258E9D77750D8FB6C14FB3A13F90076FF7CCBB6C0028CC3B627B2E10.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프리즘티비 65인지</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 처인구 모현읍
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273967671" href="/articles/273967671">
    <div class="card-photo">
    <img alt="alton bike 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/207f7faddb43218ab52890d4c91746e1c60335e4375753716f8e84d064f8220f.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">alton bike 자전거 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 기흥구 마북동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274010791" href="/articles/274010791">
    <div class="card-photo">
    <img alt="엘지냉장고 140리터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f38888dd068862f05de80d5cfdbb1ff5f3b4699848a679d5da032e18c6196624.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지냉장고 140리터</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 덕진동2가
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273918993" href="/articles/273918993">
    <div class="card-photo">
    <img alt="선반 오처넌에 가져가용" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FDE15F69B168951D98CA92D19D20B00B86B2202BAE0A3CE615BB6B7D3050FC11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반 오처넌에 가져가용</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 동래구 사직제3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273950972" href="/articles/273950972">
    <div class="card-photo">
    <img alt="게임용 컴퓨터 i5 4460 팝니다~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/48be7bb4c31571557ea3e56719e2825fabc31c7cdfec0a5d427188619815bfee.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>
    <div class="card-price">
            140,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정3동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 19
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972991" href="/articles/273972991">
    <div class="card-photo">
    <img alt="에어 컴프레셔 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2C42C9231F12BE0483C53AE1B0E26682174C49EDB51CEB435BB48332062B86D5.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어 컴프레셔 판매합니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274002275" href="/articles/274002275">
    <div class="card-photo">
    <img alt="리락쿠마스프링카" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D8489065A1683C218D8C0497BD66C896455566A3C72399477ABF304C3CCC8EB7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">리락쿠마스프링카</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 목동동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987132" href="/articles/273987132">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3AA48CE014E9A50F79E64F3FF902AF757494984144A3C6AA92C910A28B3213AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 김해시 구산동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273995769" href="/articles/273995769">
    <div class="card-photo">
    <img alt="접이식 캠핑 테이블 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6a3686dfc685327d4dfdf9de0e02df3578c4c7e313f3ee3af080082f27aa1851.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경남 김해시 장유3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983001" href="/articles/273983001">
    <div class="card-photo">
    <img alt="캠핑 의자 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4009e629f8942bc08a37b9ada25c722ec809da043f538789b280a0a2b0524c64.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑 의자 팝니다.</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 사상구 모라제1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273878099" href="/articles/273878099">
    <div class="card-photo">
    <img alt="이케아 철제선반 묶음 판매합니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/05F5DE0883E7D711D0A56B346DD260440D54973C35814344386342D7EEC6B8D3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>
    <div class="card-price">
            25,000원
          </div>
    <div class="card-region-name">
            강원도 춘천시 동면
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273786394" href="/articles/273786394">
    <div class="card-photo">
    <img alt="자전거 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7e03864758cd2f63955b1fb7bfb41a62d03fd7ec49b4085372090afe42526d95.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000929" href="/articles/274000929">
    <div class="card-photo">
    <img alt="조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/B80112B786A8F3F8EDF5A6E766F96414ED2D0BE68DE89874A6E36EADFD50513D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>
    <div class="card-price">
            550,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 죽전동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892150" href="/articles/273892150">
    <div class="card-photo">
    <img alt="[일렉트로룩스] 전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D4089CFB9D98BA6960E40AFDFC872A8C75A3AAB22A324648D296AD04F2F963BB.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 대현동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273808111" href="/articles/273808111">
    <div class="card-photo">
    <img alt="2~3인용 쇼파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E05C187B87D79645127289C66A7D5C8363001A99CBFFFD690E2A41B96AAD6698.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2~3인용 쇼파</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 이호이동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273982810" href="/articles/273982810">
    <div class="card-photo">
    <img alt="파세코 Camp-27 난로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1844CB33DFAD69B8CB864C64CAC23AB7E34CABAD4005561720C615E82D14C955.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">파세코 Camp-27 난로</h2>
    <div class="card-price">
            280,000원
          </div>
    <div class="card-region-name">
            인천 계양구 계산3동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274022028" href="/articles/274022028">
    <div class="card-photo">
    <img alt="푸름이까꿍" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/43e238fb7d674d3d1acc8dd16eb1a3f6de29f3a7173b09cae1552dc08dbab117.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">푸름이까꿍</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            부산 북구 만덕제2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273968766" href="/articles/273968766">
    <div class="card-photo">
    <img alt="수박1통2~3kg 1통 3천원 2통5천원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2ea3525511ac7d8be93ac5e3b973dc1b5b8e3b8165170008cf041e60cb2344bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>
    <div class="card-price">
            3,000원
          </div>
    <div class="card-region-name">
            충북 음성군 생극면
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273922139" href="/articles/273922139">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DA91C69D5D93229ADEFEB59ED52818E85BF84EC5403447EB2E9EF615DDDF0F2D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 신설동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005752" href="/articles/274005752">
    <div class="card-photo">
    <img alt="편하게 쓰기 좋은 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9434336919CC8C4B4AE0AA852E14A2A5F3F11A8A50424CDB9C7383A0A70B27E6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            인천 서구 검암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273649558" href="/articles/273649558">
    <div class="card-photo">
    <img alt="디월트 임팩트드라이버 DCF887P2A 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/AE703E015FF49B83C5EA7F46058D85B2015D6FDC6CE47598CBB2C518AB8362E7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>
    <div class="card-price">
            160,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 원동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273636900" href="/articles/273636900">
    <div class="card-photo">
    <img alt="냉동고 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/60D0595365B3BA12AFCD71425432CC00CB59EA90C108A13CC0BEF25C6DE47000.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉동고 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼2동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273792490" href="/articles/273792490">
    <div class="card-photo">
    <img alt="MTB 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/10d26d7590f6d22875a65a2337663b4894b52f12fc7f67a7feda3d6a9e9ac5eb.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">MTB 자전거 판매합니다</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정1동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843222" href="/articles/273843222">
    <div class="card-photo">
    <img alt="네스프레소 커피머신" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3084582B2BC492DE01787B3FA998AFFD1B80B36D89CF0C708366BB3C4205F241.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">네스프레소 커피머신</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 상현동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869355" href="/articles/273869355">
    <div class="card-photo">
    <img alt="아이패드 미니 2세대 32g" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D915CC0C94FA942A183567B54B5B5D4EFF5CF62D77C8184D0863C82DAEC50815.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이패드 미니 2세대 32g</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 송파구 방이2동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273961825" href="/articles/273961825">
    <div class="card-photo">
    <img alt="에어컨 수거해가시면 2만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/105CCC1F8D715A243EDB60BF217361923B9B600B3A4BFC82A3A17B3D0C067765.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어컨 수거해가시면 2만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271187738" href="/articles/271187738">
    <div class="card-photo">
    <img alt="한샘 원목 철제 책장 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FF1123F4FC1F106BCB475E980CD40FD03C12DC9EA186F3C44B8C83BDE5DF029D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 동작구 흑석동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962285" href="/articles/273962285">
    <div class="card-photo">
    <img alt="냉장고 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9d9fe431056c17482ec543f00e47dad6e02ac7227fb55e9cac37f79477def34a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            전남 여수시 둔덕동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273984751" href="/articles/273984751">
    <div class="card-photo">
    <img alt="딤채 김치냉장고 드립니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/847c742c07e5438607152059f4bc77326baab027e8d8c3795bc60e5b2137bf84.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            경기도 부천시 상1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987712" href="/articles/273987712">
    <div class="card-photo">
    <img alt="삼성 냉난방기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E2F19693CA6462113B9D2426AB3254B69AC034E60174E606BF78CD6A62F6C701.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 냉난방기</h2>
    <div class="card-price">
            400,000원
          </div>
    <div class="card-region-name">
            대구 수성구 수성4가동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869503" href="/articles/273869503">
    <div class="card-photo">
    <img alt="이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/34129bac567170224e955da708d6de35caf817c921034717ef67490bf21e9ee7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            경남 창원시 마산합포구 현동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273876104" href="/articles/273876104">
    <div class="card-photo">
    <img alt="벤츠 골프백 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/5469ade3eb86dd407a46b279bfeec34898cea3b48bccf312fb9c65d60eaa788a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">벤츠 골프백 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 별내동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962891" href="/articles/273962891">
    <div class="card-photo">
    <img alt="신세계상품권" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/8807D19A15756C05FECF99B6C5EC897C71512206EF57F40906D03F498E60DF5B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계상품권</h2>
    <div class="card-price">
            45,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273997532" href="/articles/273997532">
    <div class="card-photo">
    <img alt="미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7a45cb368f9d5088a49c7ce5936a68535bfeb73395e797ad8f5a1b162a8812be.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>
    <div class="card-price">
            800,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273945035" href="/articles/273945035">
    <div class="card-photo">
    <img alt="30인치 넘는 삼성 티비 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FC81D1AE7993ADB1A91905CB7155CBB6DBF2DA4F396AD024A340C326B862EBFC.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경남 창원시 의창구 신월동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273780489" href="/articles/273780489">
    <div class="card-photo">
    <img alt="삼성32인치LED 티비겸모니터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/98ACB1173483236E2057DA3BED3CF980363A4AFB24DE008933FFCE4EFD958188.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            충북 청주시 청원구 우암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273718765" href="/articles/273718765">
    <div class="card-photo">
    <img alt="43인치 TV 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FA047E879738FB0D1B29DE97783D893E6DEF4F14B057616BDBBDAEBD361A6F40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">43인치 TV 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 홍제제3동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273793234" href="/articles/273793234">
    <div class="card-photo">
    <img alt="딤채 김치냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4C8FB14C2A3BB18B0A0DF5FCDF44A755C95FAF2D74C213C34E1F83FF148D0D2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고</h2>
    <div class="card-price">
            200,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정3동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006581" href="/articles/274006581">
    <div class="card-photo">
    <img alt="프롬유 샤워핸들" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/58ED958764AAAFEF030B8454EA5A0754F3F35BB225FB7E8D592D938FED7840A2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프롬유 샤워핸들</h2>
    <div class="card-price">
            35,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 산척동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274019532" href="/articles/274019532">
    <div class="card-photo">
    <img alt="반석스포츠 아령 3kg/5kg 세트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68604AF514546143D439B389483DEDBD48E246C9AD2478B84128901E1A10D964.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 도룡동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273815819" href="/articles/273815819">
    <div class="card-photo">
    <img alt="갤럭시탭 s6 lite 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/CE7FAA2CD5A30B1C7EAF7AC120D1A5B6C840D206D968A11794C7D5B576F6ADA3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>
    <div class="card-price">
            250,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 다산1동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005062" href="/articles/274005062">
    <div class="card-photo">
    <img alt="몬테소리 레인보우 사운드 비즈 트리" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E8B876CEACE47741BDD360B73E03A9830D9A456044579429E14C58F012049F5C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 권선구 당수동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273959401" href="/articles/273959401">
    <div class="card-photo">
    <img alt="갤럭시 노트 10 플러스 + 256기가 A급" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1ef2adc9192d1247239fe763a6523372727b638472d579ca90dcd6f922babe3a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>
    <div class="card-price">
            350,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산동구 정발산동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843776" href="/articles/273843776">
    <div class="card-photo">
    <img alt="캣폴(캣타워) 가또블랑코 하이엔드" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/d99f99bc033a8311c56553a17b57f306998c61682682dabf6ac1a3b577bfe69b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 성북구 장위동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274023175" href="/articles/274023175">
    <div class="card-photo">
    <img alt="신세계 상품권 만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/31A0B799D3E4A2A6C726613C1EFF292BD5BA052FD537FD397663A70AF2F503AE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계 상품권 만원</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273572748" href="/articles/273572748">
    <div class="card-photo">
    <img alt="장인한과 파지약과" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79B8387D6FD309E874D2099FC92E2BC0E054D700F53E5CD676E71ED8C6293C33.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">장인한과 파지약과</h2>
    <div class="card-price">
            2,000원
          </div>
    <div class="card-region-name">
            경기도 구리시 수택3동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273794168" href="/articles/273794168">
    <div class="card-photo">
    <img alt="원목의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e78b47286e61dfb5b2a2e4cc79a7db6af4bd3f3934ad7a94bf5bb88bf3444f22.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원목의자</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 서귀동
          </div>
    <div class="card-counts">
    <span>
                관심 13
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273506160" href="/articles/273506160">
    <div class="card-photo">
    <img alt="엘지 드럼세탁기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39c8eee89806fadd22f7b9e89c6f6e7d500a175bac4cca9f0e3d00e4822b4196.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지 드럼세탁기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서초구 서초동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274001821" href="/articles/274001821">
    <div class="card-photo">
    <img alt="캐리어 클라윈드 138L 냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/460A4D7C5793B0EDA3467FFABAC75D96343D6552B6F929BAF609029ACC2190BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>
    <div class="card-price">
            90,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 용두동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273904456" href="/articles/273904456">
    <div class="card-photo">
    <img alt="삼천리 자전거 20 스넬로 미니벨로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DF78DE0D36D30AED5A656B8F9FF49C4D8F2A446EC63EF32773A3D164020AA3D0.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            서울 송파구 잠실동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273899049" href="/articles/273899049">
    <div class="card-photo">
    <img alt="수납 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/49C49B0EE59B0F73DCD852F95D406B7384AFFDE1CA0AB59503CEA5491AA83F65.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수납 선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            광주 서구 쌍촌동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273754420" href="/articles/273754420">
    <div class="card-photo">
    <img alt="그래픽카드 및 cpu" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/36e32e7f5a67eef732b0c19f19711bb7243ff1734bc7d1f5cc68e061da36fc55.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">그래픽카드 및 cpu</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 18
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960264" href="/articles/273960264">
    <div class="card-photo">
    <img alt="2인용 쇼파 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/35636482F4B888B12240D19A951F7A4496FCE1B5F5E7F5B5B88C5A802C5B3AB4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2인용 쇼파 </h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956622" href="/articles/273956622">
    <div class="card-photo">
    <img alt="i5-7500 32인치모니터 컴퓨터 셋트 팜니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C0EB2C9BCC2057D517B52C97903052BD731B6372741D9D0837518760A015F8BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>
    <div class="card-price">
            500,000원
          </div>
    <div class="card-region-name">
            충남 천안시 서북구 두정동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 1
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274009707" href="/articles/274009707">
    <div class="card-photo">
    <img alt="책장 무료드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39b59bc6014b9366d01ea4c93fe4be305f4d9646321e39ff4b337ca4e7b8617e.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">책장 무료드림</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            대구 달서구 본리동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273734192" href="/articles/273734192">
    <div class="card-photo">
    <img alt="UHD TV  모델명UN65NU7050FXKR  내놓아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/87a99c47e7e0d0e048806327638033f248214569226d25d1c2de8090b4e06e9d.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>
    <div class="card-price">
            450,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 안덕면
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972531" href="/articles/273972531">
    <div class="card-photo">
    <img alt="이케아 선반을 무료로 드려요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/100DB9496625CB911682A344FCEE41FA0FD48338E5CFF169371549F1635D5D67.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 선반을 무료로 드려요</h2>
    <div class="card-price blank-price">
            -
          </div>
    <div class="card-region-name">
            경기도 안산시 단원구 선부1동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273623778" href="/articles/273623778">
    <div class="card-photo">
    <img alt="아람 자연이랑 전집 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C2DD4F67EBCE23DD9933E32AA970EE6A8BE00067FD0FA703C2D25ADE86C8A111.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아람 자연이랑 전집 </h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            서울 강남구 대치1동
          </div>
    <div class="card-counts">
    <span>
                관심 17
              </span>
            ∙
            <span>
                채팅 20
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962348" href="/articles/273962348">
    <div class="card-photo">
    <img alt="알톤자전거21단" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/774409914ce1936adf8d482726e06e3a39870821c11bd91cde8f2e6f6013ea94.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤자전거21단</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 송파구 송파1동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273908814" href="/articles/273908814">
    <div class="card-photo">
    <img alt="원룸 정리_ 책상,의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3FC3FA0F9D2A793F489E30E06E9E00BDC5D4EA34DB00D073A28C1216B968FB36.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원룸 정리_ 책상,의자</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            부산 부산진구 부전동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273978876" href="/articles/273978876">
    <div class="card-photo">
    <img alt="전자렌지 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68550D76BA1CC4FD76FF442E547B17135DB42A00EF5F82B43DE4FF4D22835B2C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지 팔아요</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 구암동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273198719" href="/articles/273198719">
    <div class="card-photo">
    <img alt="삼성냉장고 상태좋습니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/00e7811fc6746aea408e14711ed4d1e937bd7cd2b1e81bfeb7738d076b1d8737.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성냉장고 상태좋습니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            부산 사상구 주례동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274024826" href="/articles/274024826">
    <div class="card-photo">
    <img alt="선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6AA9F9BCC36E47CD2C1DFAE51969C435DA2EF4560A787DBDC74C256D41B8788C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반</h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            경남 진주시 호탄동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273920668" href="/articles/273920668">
    <div class="card-photo">
    <img alt="안방그릴(연기안나는 전기그릴)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/21A48D6C5A5BE833055724CF260F8D21244EFE6220264012019B88019DBE33AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            광주 서구 화정2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000811" href="/articles/274000811">
    <div class="card-photo">
    <img alt="숀리 바이크 실내자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79FA3C4A067A48344D69C4EA48783F7D0135BA1B444D4E26BD0291162E37501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">숀리 바이크 실내자전거</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경북 구미시 봉곡동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274011505" href="/articles/274011505">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3a720aea0080c736ae65e82644582af4f949e2801fe3043e141008a23e52e519.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            7,000원
          </div>
    <div class="card-region-name">
            충남 천안시 동남구 신방동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273894828" href="/articles/273894828">
    <div class="card-photo">
    <img alt="알톤전기자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4F7C5F656D7FB042486D22D0AA3F766792F3DA5A34ACA8413EAC0FBA1277499.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤전기자전거</h2>
    <div class="card-price">
            300,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 답십리동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843713" href="/articles/273843713">
    <div class="card-photo">
    <img alt="이케아 철제 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/18D633E7264B7B1FAEAE281432721888C9ABB644EBC530798B03B5474F31AC3E.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제 선반</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 반림동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 22
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956856" href="/articles/273956856">
    <div class="card-photo">
    <img alt="3인용소파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/50aeabaf787472b725905babce0df5a53ba9360f01f058a965e6abb9943097bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3인용소파</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            부산 수영구 망미제2동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006145" href="/articles/274006145">
    <div class="card-photo">
    <img alt="에듀테이블" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/b45e21bdc0bffc0b97a27f284057fa7c55fae74f04cfe54e7268d2c5d6c84a36.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에듀테이블</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 송천동2가
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273860081" href="/articles/273860081">
    <div class="card-photo">
    <img alt="캠핑매트 에어포스 에어매트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e11104a3d21f69dba73a3429d5f348319325349cd58e070a7e0b0b4f5523ced6.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 영통구 매탄1동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 2
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273935179" href="/articles/273935179">
    <div class="card-photo">
    <img alt="LG 냉장고 (566리터)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68efdee818ecd0546590913b7f611dded1ed835155af92384eda15c5141bac4b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">LG 냉장고 (566리터)</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 향남읍
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892310" href="/articles/273892310">
    <div class="card-photo">
    <img alt="방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/565B9C7C477F683844CB4D39FC321CA7808E3754A2429953A20D11E009960C15.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            서울 강남구 압구정동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987830" href="/articles/273987830">
    <div class="card-photo">
    <img alt="아이두젠 헥사타프" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/0750A7891C444592553BA5A89BB630786D6BA4FC5BBCC65A017ADC4C3C50AC40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이두젠 헥사타프</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            경기도 군포시 도마교동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273971674" href="/articles/273971674">
    <div class="card-photo">
    <img alt="3단 접이식 메트리스 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3E48CDE679DADCDA82154FB4785B7F2A1B32AB23FE3339AF0481F71533AC501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 강서구 명지1동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    </section>
    <section id="hot-articles-go-download">
    <h3>
            더 구경하고 싶나요?
        </h3>
    <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>
    <div id="hot-articles-download-buttons">
    <a class="download-button" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" target="_blank">
    <div class="home-apple-store-bar-white"></div>
    <div class="download-text">App Store</div>
    </a> <a class="download-button" href="https://play.google.com/store/apps/details?id=com.towneers.www" target="_blank">
    <div class="home-google-play-bar-white"></div>
    <div class="download-text">Google Play</div>
    </a> </div>
    </section>
    </section>
    <script charset="utf-8" type="text/javascript">
      function changeRegion(key, value){
        var url_array
        if(window.location.pathname === "/hot_articles" && window.location.href.match(/\?/)) {
          url_array = window.location.href.split('?')[1].split(/(?:r1|&?r2)=/)
          url_array.unshift("")
        } else {
          url_array = window.location.pathname.split('/')
        }
        var keys = { r1: 2, r2: 3, r3: 4 }
        url_array[keys[key]] = value
        url_array[1] = 'region'
          if(key == 'r2' && decodeURI(url_array[2]) == "세종특별자치시") {
            url_array[4] = value
            url_array[3] = "_"
          }
        if(key == 'r1') { url_array.splice(3, 2) }
        if(key == 'r2' && url_array[3] !== "_") { url_array.splice(4, 1) }
        window.location.href = window.location.origin + url_array.join('/')
      }
    </script>
    <footer id="footer">
    <div class="footer-container">
    <div class="footer-top">
    <div class="footer-logo"></div>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="/trust">믿을 수 있는 중고거래</a></li>
    <li class="footer-list-item"><a class="link-highlight" href="https://cs.kr.karrotmarket.com/wv/faqs">자주 묻는 질문</a></li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="https://ad.daangn.com/" target="_blank">광고주센터</a></li>
    <li class="footer-list-item">
    <a class="ga-click" data-event-action="hot_articles" data-event-category="town_link_from" data-event-label="footer_town" href="https://town.daangn.com" target="_blank">동네가게</a>
    </li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a href="https://team.daangn.com/" target="_blank">회사 소개</a></li>
    <li class="footer-list-item"><a href="https://team.daangn.com/jobs/" target="_blank">채용</a></li>
    </ul>
    <ul class="footer-list policy">
    <li class="footer-list-item"><a href="https://policy.daangn.com/terms.html" target="_blank">이용약관</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/privacy.html" target="_blank">개인정보처리방침</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/location.html" target="_blank">위치기반서비스 이용약관</a></li>
    </ul>
    </div>
    <div class="footer-bottom">
    <div id="copyright">
    <ul class="copyright-list">
    <li class="copyright-list-item">고객문의 <a href="mailto:cs@daangnservice.com">cs@daangnservice.com</a></li>
    <li class="copyright-list-item">제휴문의 <a href="mailto:contact@daangn.com">contact@daangn.com</a></li>
    </ul>
    <ul class="copyright-list">
    <li class="copyright-list-item">지역광고 <a href="mailto:ad@daangn.com">ad@daangn.com</a></li>
    <li class="copyright-list-item">PR문의 <a href="mailto:pr@daangn.com">pr@daangn.com</a></li>
    </ul>
    <ul class="copyright-list copyright-list-light">
    <li class="copyright-list-item"><address>서울특별시 구로구 디지털로 30길 28 609호 (당근서비스)</address></li>
    <li class="copyright-list-item">사업자 등록번호 : 375-87-00088</li>
    <li class="copyright-list-item">직업정보제공사업 신고번호 : J1200020200016</li>
    </ul>
    <div id="social">
    <ul class="social-list">
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.facebook.com/daangn" target="_blank">
    <img alt="facebook" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-facebook-0563f4a93852d073b41f13b8bcabb03d47af3bb3a6755cdfedd8a73686c7f18c.svg"/>
    <span class="sr-only">facebook</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.instagram.com/daangnmarket/" target="_blank">
    <img alt="instagram" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-instagram-2f6c88a461597907c114b7ce28eab053fcae791ed26417915fefb6f7c9f95756.svg"/>
    <span class="sr-only">instagram</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://blog.naver.com/daangn" target="_blank">
    <img alt="blog" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-blog-e1b0d512d1766a6962ec5bbb5b0803d2a6a9c55ad97db5ba9eebb76013caceba.svg"/>
    <span class="sr-only">blog</span>
    </a> </li>
    <li class="global-links">
    <img height="24" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-global-2f53678b428ec623cefd07a90dd7777f3e55fc0433918f645d7d75ace6ff1fc3.png" width="24"/>
    <select id="global-links-select">
    <option value="kr">한국</option>
    <option value="https://uk.karrotmarket.com">영국</option>
    <option value="https://ca.karrotmarket.com">캐나다</option>
    <option value="https://us.karrotmarket.com">미국</option>
    <option value="https://jp.karrotmarket.com">일본</option>
    </select>
    </li>
    </ul>
    </div>
    <div class="copyright-text">©Danggeun Market Inc.</div>
    </div>
    </div>
    </div>
    </footer>
    </body>
    </html>
    
    


```python
print(soup.p)
```

    <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>
    


```python
print(soup.p.string)
```

    당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!
    


```python
print(soup.h1)
```

    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    


```python
for child in soup.ul.children:
    print(child)
```

    
    
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    
    
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    
    
    


```python
for parent in soup.ul.parents:
    print(parent)
```

    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    <div id="fixed-bar-wrap">
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    </div>
    <header id="fixed-bar">
    <div id="fixed-bar-wrap">
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    </div>
    </header>
    <body class="hoian-kr">
    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe height="0" src="https://www.googletagmanager.com/ns.html?id=GTM-PJSK4QL" style="display:none;visibility:hidden" width="0"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
    <!-- Appsflyer Smart Banner -->
    <script>
        !function(t,e,n,s,a,c,i,o,p){t.AppsFlyerSdkObject=a,t.AF=t.AF||function(){(t.AF.q=t.AF.q||[]).push([Date.now()].concat(Array.prototype.slice.call(arguments)))},t.AF.id=t.AF.id||i,t.AF.plugins={},o=e.createElement(n),p=e.getElementsByTagName(n)[0],o.async=1,o.src="https://websdk.appsflyer.com?"+(c.length>0?"st="+c.split(",").sort().join(",")+"&":"")+(i.length>0?"af_id="+i:""),p.parentNode.insertBefore(o,p)}(window,document,"script",0,"AF","banners",{banners: {key: "629f6f7a-a2a6-49c0-8d27-ffa48df1cd0e"}})
        AF('banners', 'showBanner')
    </script>
    <!-- End Appsflyer Smart Banner-->
    <header id="fixed-bar">
    <div id="fixed-bar-wrap">
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    </div>
    </header>
    <section id="content">
    <h1 class="head-title" id="hot-articles-head-title">
        
        
        중고거래 인기매물
      </h1>
    <nav id="hot-articles-navigation">
    <select class="hot-articles-nav-select" id="region1" name="region1" onchange="changeRegion('r1', this.value)"><option value="">지역을 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    <select class="hot-articles-nav-select" disabled="disabled" id="region2" name="region2" onchange="changeRegion('r2', this.value)"><option value="">동네를 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    </nav>
    <section class="cards-wrap">
    <article class="card-top">
    <a class="card-link" data-event-label="273865202" href="/articles/273865202">
    <div class="card-photo">
    <img alt="삼성 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/da035d5794d5490a86e8596a2ff036db7a6811cde70b8e2cb5514a93f4c0d1af.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 제습기</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 서구 갈마동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 47
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972258" href="/articles/273972258">
    <div class="card-photo">
    <img alt="🎈4단 경량 서랍장 2EA" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E5286230DC4F10CDC1187AF093DC98E700866C3F3CCE2D26B4097EC8E096EF02.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            전남 순천시 해룡면
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869268" href="/articles/273869268">
    <div class="card-photo">
    <img alt="마켓비 철제장수납장 드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1BF6CACC4CF68494129932B87B0C9B3A079DDE8C4BA714BD93E4BF5DAEBC10E8.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">마켓비 철제장수납장 드림</h2>
    <div class="card-price">
            10원
          </div>
    <div class="card-region-name">
            제주 제주시 아라일동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 34
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274014399" href="/articles/274014399">
    <div class="card-photo">
    <img alt="냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C9676D66084FD2EE00AE6C5D39B265627CB06197DEA6DADBC3EB2440A5FC6B82.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            광주 광산구 첨단2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 23
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274004001" href="/articles/274004001">
    <div class="card-photo">
    <img alt="다이슨 v8 청소기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/01F393E5F51B4DA32C817F14A46279A25EE40968CCA57B6F81E0F64FC82E1CE6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">다이슨 v8 청소기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경기도 성남시 분당구 구미동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273925231" href="/articles/273925231">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/22957C51EA63B0E40AC59188498B4AA82E6BC2B82E5037C378B32C4A08E33A8B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 25
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975070" href="/articles/273975070">
    <div class="card-photo">
    <img alt="스팸팔아요~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/730795bbe314437630ed5f1dd80bb123e33532212a0d42c8919c49b0147521f9.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">스팸팔아요~</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 사하구 다대동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273921135" href="/articles/273921135">
    <div class="card-photo">
    <img alt="lg 휘센 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4DDEF244CCD690065ED6EEB04BFDBB754DDA838F5BABDECFA933F07E9A9825B9.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">lg 휘센 제습기</h2>
    <div class="card-price">
            80,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 상남동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274012057" href="/articles/274012057">
    <div class="card-photo">
    <img alt="★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/88AFB93658556EA3DF8603FB9064D00328F5AE3A92B26B4674DB0E0E808B2ACE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            대구 북구 침산2동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273927308" href="/articles/273927308">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/91B8FEE166411BBBF5B7E506CE227FA9A29E5BC3E7AFEC07C4CF2B5F7D1BC7A1.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960102" href="/articles/273960102">
    <div class="card-photo">
    <img alt="컨테이너 하우스판매!!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/44A07ADE16BFFEF44BCE2A7B873642B164EE8ABFD6C95C6D3B014853E9FE2742.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">컨테이너 하우스판매!!</h2>
    <div class="card-price">
            1원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273986259" href="/articles/273986259">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/84C5D0E0419D18BF87CD30C53893A12E62D691E470F8E380F83329FFBCD36527.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            제주 제주시 노형동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273810590" href="/articles/273810590">
    <div class="card-photo">
    <img alt="삼천리 자전거 (아동용의자 포함)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/83d71123f025e54536a6bca0d372ab46cce152425b2f57eeed4c2f67b23a8c0b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산서구 대화동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 28
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983175" href="/articles/273983175">
    <div class="card-photo">
    <img alt="3단 원목 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f11c004faa962d4469ab4106a84088f634ea5cac4ba39190993206355d6ae4d2.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 원목 수납장</h2>
    <div class="card-price">
            6,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 무실동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975026" href="/articles/273975026">
    <div class="card-photo">
    <img alt="자전거 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2B4B3C6F4446A9C51CB36786F9B098609E5F34109596B7DD73EE4867D6953E11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            대전 유성구 전민동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960878" href="/articles/273960878">
    <div class="card-photo">
    <img alt="가정용냉장고 오늘가저가시면 이만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1B6F5E18EFE2153B27172E95CBAF7F76059AEC37C337DAE74FD425010DCCE0C4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271724995" href="/articles/271724995">
    <div class="card-photo">
    <img alt="철제선반입니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/bd0433f673914e540acb68455a3c4a79e84f6c6c07832f0586d72a629fd406d7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반입니다.</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 기장군 정관읍
          </div>
    <div class="card-counts">
    <span>
                관심 98
              </span>
            ∙
            <span>
                채팅 114
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273998510" href="/articles/273998510">
    <div class="card-photo">
    <img alt="프리즘티비 65인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6E4F741C258E9D77750D8FB6C14FB3A13F90076FF7CCBB6C0028CC3B627B2E10.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프리즘티비 65인지</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 처인구 모현읍
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273967671" href="/articles/273967671">
    <div class="card-photo">
    <img alt="alton bike 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/207f7faddb43218ab52890d4c91746e1c60335e4375753716f8e84d064f8220f.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">alton bike 자전거 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 기흥구 마북동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274010791" href="/articles/274010791">
    <div class="card-photo">
    <img alt="엘지냉장고 140리터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f38888dd068862f05de80d5cfdbb1ff5f3b4699848a679d5da032e18c6196624.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지냉장고 140리터</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 덕진동2가
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273918993" href="/articles/273918993">
    <div class="card-photo">
    <img alt="선반 오처넌에 가져가용" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FDE15F69B168951D98CA92D19D20B00B86B2202BAE0A3CE615BB6B7D3050FC11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반 오처넌에 가져가용</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 동래구 사직제3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273950972" href="/articles/273950972">
    <div class="card-photo">
    <img alt="게임용 컴퓨터 i5 4460 팝니다~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/48be7bb4c31571557ea3e56719e2825fabc31c7cdfec0a5d427188619815bfee.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>
    <div class="card-price">
            140,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정3동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 19
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972991" href="/articles/273972991">
    <div class="card-photo">
    <img alt="에어 컴프레셔 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2C42C9231F12BE0483C53AE1B0E26682174C49EDB51CEB435BB48332062B86D5.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어 컴프레셔 판매합니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274002275" href="/articles/274002275">
    <div class="card-photo">
    <img alt="리락쿠마스프링카" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D8489065A1683C218D8C0497BD66C896455566A3C72399477ABF304C3CCC8EB7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">리락쿠마스프링카</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 목동동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987132" href="/articles/273987132">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3AA48CE014E9A50F79E64F3FF902AF757494984144A3C6AA92C910A28B3213AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 김해시 구산동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273995769" href="/articles/273995769">
    <div class="card-photo">
    <img alt="접이식 캠핑 테이블 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6a3686dfc685327d4dfdf9de0e02df3578c4c7e313f3ee3af080082f27aa1851.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경남 김해시 장유3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983001" href="/articles/273983001">
    <div class="card-photo">
    <img alt="캠핑 의자 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4009e629f8942bc08a37b9ada25c722ec809da043f538789b280a0a2b0524c64.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑 의자 팝니다.</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 사상구 모라제1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273878099" href="/articles/273878099">
    <div class="card-photo">
    <img alt="이케아 철제선반 묶음 판매합니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/05F5DE0883E7D711D0A56B346DD260440D54973C35814344386342D7EEC6B8D3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>
    <div class="card-price">
            25,000원
          </div>
    <div class="card-region-name">
            강원도 춘천시 동면
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273786394" href="/articles/273786394">
    <div class="card-photo">
    <img alt="자전거 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7e03864758cd2f63955b1fb7bfb41a62d03fd7ec49b4085372090afe42526d95.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000929" href="/articles/274000929">
    <div class="card-photo">
    <img alt="조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/B80112B786A8F3F8EDF5A6E766F96414ED2D0BE68DE89874A6E36EADFD50513D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>
    <div class="card-price">
            550,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 죽전동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892150" href="/articles/273892150">
    <div class="card-photo">
    <img alt="[일렉트로룩스] 전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D4089CFB9D98BA6960E40AFDFC872A8C75A3AAB22A324648D296AD04F2F963BB.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 대현동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273808111" href="/articles/273808111">
    <div class="card-photo">
    <img alt="2~3인용 쇼파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E05C187B87D79645127289C66A7D5C8363001A99CBFFFD690E2A41B96AAD6698.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2~3인용 쇼파</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 이호이동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273982810" href="/articles/273982810">
    <div class="card-photo">
    <img alt="파세코 Camp-27 난로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1844CB33DFAD69B8CB864C64CAC23AB7E34CABAD4005561720C615E82D14C955.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">파세코 Camp-27 난로</h2>
    <div class="card-price">
            280,000원
          </div>
    <div class="card-region-name">
            인천 계양구 계산3동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274022028" href="/articles/274022028">
    <div class="card-photo">
    <img alt="푸름이까꿍" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/43e238fb7d674d3d1acc8dd16eb1a3f6de29f3a7173b09cae1552dc08dbab117.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">푸름이까꿍</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            부산 북구 만덕제2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273968766" href="/articles/273968766">
    <div class="card-photo">
    <img alt="수박1통2~3kg 1통 3천원 2통5천원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2ea3525511ac7d8be93ac5e3b973dc1b5b8e3b8165170008cf041e60cb2344bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>
    <div class="card-price">
            3,000원
          </div>
    <div class="card-region-name">
            충북 음성군 생극면
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273922139" href="/articles/273922139">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DA91C69D5D93229ADEFEB59ED52818E85BF84EC5403447EB2E9EF615DDDF0F2D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 신설동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005752" href="/articles/274005752">
    <div class="card-photo">
    <img alt="편하게 쓰기 좋은 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9434336919CC8C4B4AE0AA852E14A2A5F3F11A8A50424CDB9C7383A0A70B27E6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            인천 서구 검암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273649558" href="/articles/273649558">
    <div class="card-photo">
    <img alt="디월트 임팩트드라이버 DCF887P2A 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/AE703E015FF49B83C5EA7F46058D85B2015D6FDC6CE47598CBB2C518AB8362E7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>
    <div class="card-price">
            160,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 원동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273636900" href="/articles/273636900">
    <div class="card-photo">
    <img alt="냉동고 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/60D0595365B3BA12AFCD71425432CC00CB59EA90C108A13CC0BEF25C6DE47000.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉동고 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼2동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273792490" href="/articles/273792490">
    <div class="card-photo">
    <img alt="MTB 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/10d26d7590f6d22875a65a2337663b4894b52f12fc7f67a7feda3d6a9e9ac5eb.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">MTB 자전거 판매합니다</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정1동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843222" href="/articles/273843222">
    <div class="card-photo">
    <img alt="네스프레소 커피머신" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3084582B2BC492DE01787B3FA998AFFD1B80B36D89CF0C708366BB3C4205F241.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">네스프레소 커피머신</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 상현동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869355" href="/articles/273869355">
    <div class="card-photo">
    <img alt="아이패드 미니 2세대 32g" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D915CC0C94FA942A183567B54B5B5D4EFF5CF62D77C8184D0863C82DAEC50815.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이패드 미니 2세대 32g</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 송파구 방이2동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273961825" href="/articles/273961825">
    <div class="card-photo">
    <img alt="에어컨 수거해가시면 2만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/105CCC1F8D715A243EDB60BF217361923B9B600B3A4BFC82A3A17B3D0C067765.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어컨 수거해가시면 2만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271187738" href="/articles/271187738">
    <div class="card-photo">
    <img alt="한샘 원목 철제 책장 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FF1123F4FC1F106BCB475E980CD40FD03C12DC9EA186F3C44B8C83BDE5DF029D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 동작구 흑석동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962285" href="/articles/273962285">
    <div class="card-photo">
    <img alt="냉장고 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9d9fe431056c17482ec543f00e47dad6e02ac7227fb55e9cac37f79477def34a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            전남 여수시 둔덕동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273984751" href="/articles/273984751">
    <div class="card-photo">
    <img alt="딤채 김치냉장고 드립니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/847c742c07e5438607152059f4bc77326baab027e8d8c3795bc60e5b2137bf84.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            경기도 부천시 상1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987712" href="/articles/273987712">
    <div class="card-photo">
    <img alt="삼성 냉난방기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E2F19693CA6462113B9D2426AB3254B69AC034E60174E606BF78CD6A62F6C701.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 냉난방기</h2>
    <div class="card-price">
            400,000원
          </div>
    <div class="card-region-name">
            대구 수성구 수성4가동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869503" href="/articles/273869503">
    <div class="card-photo">
    <img alt="이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/34129bac567170224e955da708d6de35caf817c921034717ef67490bf21e9ee7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            경남 창원시 마산합포구 현동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273876104" href="/articles/273876104">
    <div class="card-photo">
    <img alt="벤츠 골프백 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/5469ade3eb86dd407a46b279bfeec34898cea3b48bccf312fb9c65d60eaa788a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">벤츠 골프백 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 별내동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962891" href="/articles/273962891">
    <div class="card-photo">
    <img alt="신세계상품권" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/8807D19A15756C05FECF99B6C5EC897C71512206EF57F40906D03F498E60DF5B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계상품권</h2>
    <div class="card-price">
            45,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273997532" href="/articles/273997532">
    <div class="card-photo">
    <img alt="미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7a45cb368f9d5088a49c7ce5936a68535bfeb73395e797ad8f5a1b162a8812be.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>
    <div class="card-price">
            800,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273945035" href="/articles/273945035">
    <div class="card-photo">
    <img alt="30인치 넘는 삼성 티비 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FC81D1AE7993ADB1A91905CB7155CBB6DBF2DA4F396AD024A340C326B862EBFC.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경남 창원시 의창구 신월동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273780489" href="/articles/273780489">
    <div class="card-photo">
    <img alt="삼성32인치LED 티비겸모니터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/98ACB1173483236E2057DA3BED3CF980363A4AFB24DE008933FFCE4EFD958188.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            충북 청주시 청원구 우암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273718765" href="/articles/273718765">
    <div class="card-photo">
    <img alt="43인치 TV 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FA047E879738FB0D1B29DE97783D893E6DEF4F14B057616BDBBDAEBD361A6F40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">43인치 TV 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 홍제제3동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273793234" href="/articles/273793234">
    <div class="card-photo">
    <img alt="딤채 김치냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4C8FB14C2A3BB18B0A0DF5FCDF44A755C95FAF2D74C213C34E1F83FF148D0D2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고</h2>
    <div class="card-price">
            200,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정3동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006581" href="/articles/274006581">
    <div class="card-photo">
    <img alt="프롬유 샤워핸들" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/58ED958764AAAFEF030B8454EA5A0754F3F35BB225FB7E8D592D938FED7840A2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프롬유 샤워핸들</h2>
    <div class="card-price">
            35,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 산척동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274019532" href="/articles/274019532">
    <div class="card-photo">
    <img alt="반석스포츠 아령 3kg/5kg 세트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68604AF514546143D439B389483DEDBD48E246C9AD2478B84128901E1A10D964.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 도룡동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273815819" href="/articles/273815819">
    <div class="card-photo">
    <img alt="갤럭시탭 s6 lite 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/CE7FAA2CD5A30B1C7EAF7AC120D1A5B6C840D206D968A11794C7D5B576F6ADA3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>
    <div class="card-price">
            250,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 다산1동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005062" href="/articles/274005062">
    <div class="card-photo">
    <img alt="몬테소리 레인보우 사운드 비즈 트리" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E8B876CEACE47741BDD360B73E03A9830D9A456044579429E14C58F012049F5C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 권선구 당수동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273959401" href="/articles/273959401">
    <div class="card-photo">
    <img alt="갤럭시 노트 10 플러스 + 256기가 A급" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1ef2adc9192d1247239fe763a6523372727b638472d579ca90dcd6f922babe3a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>
    <div class="card-price">
            350,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산동구 정발산동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843776" href="/articles/273843776">
    <div class="card-photo">
    <img alt="캣폴(캣타워) 가또블랑코 하이엔드" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/d99f99bc033a8311c56553a17b57f306998c61682682dabf6ac1a3b577bfe69b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 성북구 장위동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274023175" href="/articles/274023175">
    <div class="card-photo">
    <img alt="신세계 상품권 만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/31A0B799D3E4A2A6C726613C1EFF292BD5BA052FD537FD397663A70AF2F503AE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계 상품권 만원</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273572748" href="/articles/273572748">
    <div class="card-photo">
    <img alt="장인한과 파지약과" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79B8387D6FD309E874D2099FC92E2BC0E054D700F53E5CD676E71ED8C6293C33.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">장인한과 파지약과</h2>
    <div class="card-price">
            2,000원
          </div>
    <div class="card-region-name">
            경기도 구리시 수택3동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273794168" href="/articles/273794168">
    <div class="card-photo">
    <img alt="원목의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e78b47286e61dfb5b2a2e4cc79a7db6af4bd3f3934ad7a94bf5bb88bf3444f22.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원목의자</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 서귀동
          </div>
    <div class="card-counts">
    <span>
                관심 13
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273506160" href="/articles/273506160">
    <div class="card-photo">
    <img alt="엘지 드럼세탁기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39c8eee89806fadd22f7b9e89c6f6e7d500a175bac4cca9f0e3d00e4822b4196.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지 드럼세탁기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서초구 서초동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274001821" href="/articles/274001821">
    <div class="card-photo">
    <img alt="캐리어 클라윈드 138L 냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/460A4D7C5793B0EDA3467FFABAC75D96343D6552B6F929BAF609029ACC2190BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>
    <div class="card-price">
            90,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 용두동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273904456" href="/articles/273904456">
    <div class="card-photo">
    <img alt="삼천리 자전거 20 스넬로 미니벨로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DF78DE0D36D30AED5A656B8F9FF49C4D8F2A446EC63EF32773A3D164020AA3D0.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            서울 송파구 잠실동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273899049" href="/articles/273899049">
    <div class="card-photo">
    <img alt="수납 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/49C49B0EE59B0F73DCD852F95D406B7384AFFDE1CA0AB59503CEA5491AA83F65.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수납 선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            광주 서구 쌍촌동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273754420" href="/articles/273754420">
    <div class="card-photo">
    <img alt="그래픽카드 및 cpu" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/36e32e7f5a67eef732b0c19f19711bb7243ff1734bc7d1f5cc68e061da36fc55.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">그래픽카드 및 cpu</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 18
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960264" href="/articles/273960264">
    <div class="card-photo">
    <img alt="2인용 쇼파 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/35636482F4B888B12240D19A951F7A4496FCE1B5F5E7F5B5B88C5A802C5B3AB4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2인용 쇼파 </h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956622" href="/articles/273956622">
    <div class="card-photo">
    <img alt="i5-7500 32인치모니터 컴퓨터 셋트 팜니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C0EB2C9BCC2057D517B52C97903052BD731B6372741D9D0837518760A015F8BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>
    <div class="card-price">
            500,000원
          </div>
    <div class="card-region-name">
            충남 천안시 서북구 두정동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 1
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274009707" href="/articles/274009707">
    <div class="card-photo">
    <img alt="책장 무료드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39b59bc6014b9366d01ea4c93fe4be305f4d9646321e39ff4b337ca4e7b8617e.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">책장 무료드림</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            대구 달서구 본리동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273734192" href="/articles/273734192">
    <div class="card-photo">
    <img alt="UHD TV  모델명UN65NU7050FXKR  내놓아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/87a99c47e7e0d0e048806327638033f248214569226d25d1c2de8090b4e06e9d.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>
    <div class="card-price">
            450,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 안덕면
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972531" href="/articles/273972531">
    <div class="card-photo">
    <img alt="이케아 선반을 무료로 드려요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/100DB9496625CB911682A344FCEE41FA0FD48338E5CFF169371549F1635D5D67.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 선반을 무료로 드려요</h2>
    <div class="card-price blank-price">
            -
          </div>
    <div class="card-region-name">
            경기도 안산시 단원구 선부1동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273623778" href="/articles/273623778">
    <div class="card-photo">
    <img alt="아람 자연이랑 전집 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C2DD4F67EBCE23DD9933E32AA970EE6A8BE00067FD0FA703C2D25ADE86C8A111.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아람 자연이랑 전집 </h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            서울 강남구 대치1동
          </div>
    <div class="card-counts">
    <span>
                관심 17
              </span>
            ∙
            <span>
                채팅 20
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962348" href="/articles/273962348">
    <div class="card-photo">
    <img alt="알톤자전거21단" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/774409914ce1936adf8d482726e06e3a39870821c11bd91cde8f2e6f6013ea94.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤자전거21단</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 송파구 송파1동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273908814" href="/articles/273908814">
    <div class="card-photo">
    <img alt="원룸 정리_ 책상,의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3FC3FA0F9D2A793F489E30E06E9E00BDC5D4EA34DB00D073A28C1216B968FB36.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원룸 정리_ 책상,의자</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            부산 부산진구 부전동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273978876" href="/articles/273978876">
    <div class="card-photo">
    <img alt="전자렌지 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68550D76BA1CC4FD76FF442E547B17135DB42A00EF5F82B43DE4FF4D22835B2C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지 팔아요</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 구암동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273198719" href="/articles/273198719">
    <div class="card-photo">
    <img alt="삼성냉장고 상태좋습니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/00e7811fc6746aea408e14711ed4d1e937bd7cd2b1e81bfeb7738d076b1d8737.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성냉장고 상태좋습니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            부산 사상구 주례동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274024826" href="/articles/274024826">
    <div class="card-photo">
    <img alt="선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6AA9F9BCC36E47CD2C1DFAE51969C435DA2EF4560A787DBDC74C256D41B8788C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반</h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            경남 진주시 호탄동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273920668" href="/articles/273920668">
    <div class="card-photo">
    <img alt="안방그릴(연기안나는 전기그릴)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/21A48D6C5A5BE833055724CF260F8D21244EFE6220264012019B88019DBE33AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            광주 서구 화정2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000811" href="/articles/274000811">
    <div class="card-photo">
    <img alt="숀리 바이크 실내자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79FA3C4A067A48344D69C4EA48783F7D0135BA1B444D4E26BD0291162E37501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">숀리 바이크 실내자전거</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경북 구미시 봉곡동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274011505" href="/articles/274011505">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3a720aea0080c736ae65e82644582af4f949e2801fe3043e141008a23e52e519.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            7,000원
          </div>
    <div class="card-region-name">
            충남 천안시 동남구 신방동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273894828" href="/articles/273894828">
    <div class="card-photo">
    <img alt="알톤전기자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4F7C5F656D7FB042486D22D0AA3F766792F3DA5A34ACA8413EAC0FBA1277499.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤전기자전거</h2>
    <div class="card-price">
            300,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 답십리동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843713" href="/articles/273843713">
    <div class="card-photo">
    <img alt="이케아 철제 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/18D633E7264B7B1FAEAE281432721888C9ABB644EBC530798B03B5474F31AC3E.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제 선반</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 반림동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 22
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956856" href="/articles/273956856">
    <div class="card-photo">
    <img alt="3인용소파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/50aeabaf787472b725905babce0df5a53ba9360f01f058a965e6abb9943097bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3인용소파</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            부산 수영구 망미제2동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006145" href="/articles/274006145">
    <div class="card-photo">
    <img alt="에듀테이블" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/b45e21bdc0bffc0b97a27f284057fa7c55fae74f04cfe54e7268d2c5d6c84a36.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에듀테이블</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 송천동2가
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273860081" href="/articles/273860081">
    <div class="card-photo">
    <img alt="캠핑매트 에어포스 에어매트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e11104a3d21f69dba73a3429d5f348319325349cd58e070a7e0b0b4f5523ced6.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 영통구 매탄1동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 2
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273935179" href="/articles/273935179">
    <div class="card-photo">
    <img alt="LG 냉장고 (566리터)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68efdee818ecd0546590913b7f611dded1ed835155af92384eda15c5141bac4b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">LG 냉장고 (566리터)</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 향남읍
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892310" href="/articles/273892310">
    <div class="card-photo">
    <img alt="방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/565B9C7C477F683844CB4D39FC321CA7808E3754A2429953A20D11E009960C15.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            서울 강남구 압구정동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987830" href="/articles/273987830">
    <div class="card-photo">
    <img alt="아이두젠 헥사타프" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/0750A7891C444592553BA5A89BB630786D6BA4FC5BBCC65A017ADC4C3C50AC40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이두젠 헥사타프</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            경기도 군포시 도마교동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273971674" href="/articles/273971674">
    <div class="card-photo">
    <img alt="3단 접이식 메트리스 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3E48CDE679DADCDA82154FB4785B7F2A1B32AB23FE3339AF0481F71533AC501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 강서구 명지1동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    </section>
    <section id="hot-articles-go-download">
    <h3>
            더 구경하고 싶나요?
        </h3>
    <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>
    <div id="hot-articles-download-buttons">
    <a class="download-button" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" target="_blank">
    <div class="home-apple-store-bar-white"></div>
    <div class="download-text">App Store</div>
    </a> <a class="download-button" href="https://play.google.com/store/apps/details?id=com.towneers.www" target="_blank">
    <div class="home-google-play-bar-white"></div>
    <div class="download-text">Google Play</div>
    </a> </div>
    </section>
    </section>
    <script charset="utf-8" type="text/javascript">
      function changeRegion(key, value){
        var url_array
        if(window.location.pathname === "/hot_articles" && window.location.href.match(/\?/)) {
          url_array = window.location.href.split('?')[1].split(/(?:r1|&?r2)=/)
          url_array.unshift("")
        } else {
          url_array = window.location.pathname.split('/')
        }
        var keys = { r1: 2, r2: 3, r3: 4 }
        url_array[keys[key]] = value
        url_array[1] = 'region'
          if(key == 'r2' && decodeURI(url_array[2]) == "세종특별자치시") {
            url_array[4] = value
            url_array[3] = "_"
          }
        if(key == 'r1') { url_array.splice(3, 2) }
        if(key == 'r2' && url_array[3] !== "_") { url_array.splice(4, 1) }
        window.location.href = window.location.origin + url_array.join('/')
      }
    </script>
    <footer id="footer">
    <div class="footer-container">
    <div class="footer-top">
    <div class="footer-logo"></div>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="/trust">믿을 수 있는 중고거래</a></li>
    <li class="footer-list-item"><a class="link-highlight" href="https://cs.kr.karrotmarket.com/wv/faqs">자주 묻는 질문</a></li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="https://ad.daangn.com/" target="_blank">광고주센터</a></li>
    <li class="footer-list-item">
    <a class="ga-click" data-event-action="hot_articles" data-event-category="town_link_from" data-event-label="footer_town" href="https://town.daangn.com" target="_blank">동네가게</a>
    </li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a href="https://team.daangn.com/" target="_blank">회사 소개</a></li>
    <li class="footer-list-item"><a href="https://team.daangn.com/jobs/" target="_blank">채용</a></li>
    </ul>
    <ul class="footer-list policy">
    <li class="footer-list-item"><a href="https://policy.daangn.com/terms.html" target="_blank">이용약관</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/privacy.html" target="_blank">개인정보처리방침</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/location.html" target="_blank">위치기반서비스 이용약관</a></li>
    </ul>
    </div>
    <div class="footer-bottom">
    <div id="copyright">
    <ul class="copyright-list">
    <li class="copyright-list-item">고객문의 <a href="mailto:cs@daangnservice.com">cs@daangnservice.com</a></li>
    <li class="copyright-list-item">제휴문의 <a href="mailto:contact@daangn.com">contact@daangn.com</a></li>
    </ul>
    <ul class="copyright-list">
    <li class="copyright-list-item">지역광고 <a href="mailto:ad@daangn.com">ad@daangn.com</a></li>
    <li class="copyright-list-item">PR문의 <a href="mailto:pr@daangn.com">pr@daangn.com</a></li>
    </ul>
    <ul class="copyright-list copyright-list-light">
    <li class="copyright-list-item"><address>서울특별시 구로구 디지털로 30길 28 609호 (당근서비스)</address></li>
    <li class="copyright-list-item">사업자 등록번호 : 375-87-00088</li>
    <li class="copyright-list-item">직업정보제공사업 신고번호 : J1200020200016</li>
    </ul>
    <div id="social">
    <ul class="social-list">
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.facebook.com/daangn" target="_blank">
    <img alt="facebook" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-facebook-0563f4a93852d073b41f13b8bcabb03d47af3bb3a6755cdfedd8a73686c7f18c.svg"/>
    <span class="sr-only">facebook</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.instagram.com/daangnmarket/" target="_blank">
    <img alt="instagram" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-instagram-2f6c88a461597907c114b7ce28eab053fcae791ed26417915fefb6f7c9f95756.svg"/>
    <span class="sr-only">instagram</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://blog.naver.com/daangn" target="_blank">
    <img alt="blog" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-blog-e1b0d512d1766a6962ec5bbb5b0803d2a6a9c55ad97db5ba9eebb76013caceba.svg"/>
    <span class="sr-only">blog</span>
    </a> </li>
    <li class="global-links">
    <img height="24" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-global-2f53678b428ec623cefd07a90dd7777f3e55fc0433918f645d7d75ace6ff1fc3.png" width="24"/>
    <select id="global-links-select">
    <option value="kr">한국</option>
    <option value="https://uk.karrotmarket.com">영국</option>
    <option value="https://ca.karrotmarket.com">캐나다</option>
    <option value="https://us.karrotmarket.com">미국</option>
    <option value="https://jp.karrotmarket.com">일본</option>
    </select>
    </li>
    </ul>
    </div>
    <div class="copyright-text">©Danggeun Market Inc.</div>
    </div>
    </div>
    </div>
    </footer>
    </body>
    <html lang="ko">
    <head>
    <meta charset="utf-8"/>
    <meta content="IE=edge" http-equiv="X-UA-Compatible"/>
    <meta content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no" name="viewport"/>
    <link href="https://www.daangn.com/hot_articles" rel="canonical"/>
    <title>당근마켓 중고거래 | 당신 근처의 당근마켓</title>
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." name="description">
    <link href="당근마켓" rel="author"/>
    <meta content="https://www.daangn.com/hot_articles" property="og:url">
    <meta content="당근마켓 중고거래 | 당신 근처의 당근마켓" property="og:title">
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." property="og:description"/>
    <meta content="당근마켓" property="og:site_name"/>
    <meta content="https://www.daangn.com/images/meta/home/flea_market.png" property="og:image"/>
    <meta content="article" property="og:type"/>
    <meta content="ko_KR" property="og:locale"/>
    <meta content="1463621440622064" property="fb:app_id"/>
    <meta content="summary_large_image" name="twitter:card"/>
    <meta content="@danggeunmarket" name="twitter:site"/>
    <meta content="당근마켓 중고거래 | 당신 근처의 당근마켓" name="twitter:title"/>
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." name="twitter:description"/>
    <meta content="https://www.daangn.com/images/meta/home/flea_market.png" name="twitter:image"/>
    <meta content="d1f8112731c18313535732cf2516d6401bfed40a" name="naver-site-verification"/>
    <link href="/images/icons/shortcut_icon.png" rel="shortcut icon" type="image/x-icon"/>
    <link href="https://d1unjqcospf8gs.cloudfront.net/favicon.ico" rel="shortcut icon" type="image/x-icon">
    <link href="https://d1unjqcospf8gs.cloudfront.net/assets/home/articles/hot-76409f246af8ba6ca58659826685527e45104fd2b089dd053e6af97133bb193b.css" media="all" rel="stylesheet"/>
    <script src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base-a182b6524ddb27bbc6a0647ee4bc2b79384325e8bde2b0775b94c7573fd0d87e.js"></script>
    <link href="/images/icons/daangn_logo_192.png" rel="apple-touch-icon" sizes="192x192"/>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->
    <meta content="authenticity_token" name="csrf-param"/>
    <meta content="u3KG84YcReIJ0Msd8mlG6T/aYodEKU5+Dz4l7QPp2tiUC0b24Z12Vj5TBot85lU96zE7BLHHLn9sYrfKNZzoSA==" name="csrf-token"/>
    <script>
        window.fbAsyncInit = function() {
          FB.init({
            appId      : '1463621440622064',
            xfbml      : true,
            version    : 'v2.4'
          });
        };
    
        (function(d, s, id){
          var js, fjs = d.getElementsByTagName(s)[0];
          if (d.getElementById(id)) {return;}
          js = d.createElement(s); js.id = id;
          js.src = "//connect.facebook.net/en_US/sdk.js";
          fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'facebook-jssdk'));
      </script>
    <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
                  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
                m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    
        ga('create', 'UA-64551386-2', 'auto');
         ga('set', 'dimension2', 'true');  ga('send', 'pageview'); </script>
    <!-- Facebook Pixel Code -->
    <script>
        !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
                n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
          n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
          t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
                document,'script','//connect.facebook.net/en_US/fbevents.js');
    
        fbq('init', '992961397411651');
        facebookClickEvent("PageView")
    
        function facebookClickEvent(eventName, data) {
          if (data !== undefined) {
              fbq('track', eventName, data)
          } else {
              fbq('track', eventName)
          }
        }
    
        function facebookClickEventWithPageMove(eventName, data, targetUrl) {
            facebookClickEvent(eventName, data);
            window.location.href = targetUrl;
        }
      </script>
    <noscript><img height="1" src="https://www.facebook.com/tr?id=992961397411651&amp;ev=PageView&amp;noscript=1" style="display:none" width="1"/></noscript>
    <!-- End Facebook Pixel Code -->
    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
          new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
          j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
          'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
      })(window,document,'script','dataLayer','GTM-PJSK4QL');</script>
    <!-- End Google Tag Manager -->
    <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Organization",
      "name": "당근마켓",
      "url": "https://www.daangn.com",
      "sameAs": [
        "https://www.facebook.com/daangn",
        "https://blog.naver.com/daangn",
        "https://www.youtube.com/channel/UC8tsBsQBuF7QybxgLmStihA",
        "https://twitter.com/daangnmarket",
        "https://www.instagram.com/daangnmarket",
        "https://apps.apple.com/kr/app/id1018769995",
        "https://play.google.com/store/apps/details?id=com.towneers.www"
      ],
      "logo": "https://www.daangn.com/logo.png"
    }
    </script>
    </link></meta></meta></meta></head>
    <body class="hoian-kr">
    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe height="0" src="https://www.googletagmanager.com/ns.html?id=GTM-PJSK4QL" style="display:none;visibility:hidden" width="0"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
    <!-- Appsflyer Smart Banner -->
    <script>
        !function(t,e,n,s,a,c,i,o,p){t.AppsFlyerSdkObject=a,t.AF=t.AF||function(){(t.AF.q=t.AF.q||[]).push([Date.now()].concat(Array.prototype.slice.call(arguments)))},t.AF.id=t.AF.id||i,t.AF.plugins={},o=e.createElement(n),p=e.getElementsByTagName(n)[0],o.async=1,o.src="https://websdk.appsflyer.com?"+(c.length>0?"st="+c.split(",").sort().join(",")+"&":"")+(i.length>0?"af_id="+i:""),p.parentNode.insertBefore(o,p)}(window,document,"script",0,"AF","banners",{banners: {key: "629f6f7a-a2a6-49c0-8d27-ffa48df1cd0e"}})
        AF('banners', 'showBanner')
    </script>
    <!-- End Appsflyer Smart Banner-->
    <header id="fixed-bar">
    <div id="fixed-bar-wrap">
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    </div>
    </header>
    <section id="content">
    <h1 class="head-title" id="hot-articles-head-title">
        
        
        중고거래 인기매물
      </h1>
    <nav id="hot-articles-navigation">
    <select class="hot-articles-nav-select" id="region1" name="region1" onchange="changeRegion('r1', this.value)"><option value="">지역을 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    <select class="hot-articles-nav-select" disabled="disabled" id="region2" name="region2" onchange="changeRegion('r2', this.value)"><option value="">동네를 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    </nav>
    <section class="cards-wrap">
    <article class="card-top">
    <a class="card-link" data-event-label="273865202" href="/articles/273865202">
    <div class="card-photo">
    <img alt="삼성 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/da035d5794d5490a86e8596a2ff036db7a6811cde70b8e2cb5514a93f4c0d1af.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 제습기</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 서구 갈마동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 47
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972258" href="/articles/273972258">
    <div class="card-photo">
    <img alt="🎈4단 경량 서랍장 2EA" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E5286230DC4F10CDC1187AF093DC98E700866C3F3CCE2D26B4097EC8E096EF02.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            전남 순천시 해룡면
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869268" href="/articles/273869268">
    <div class="card-photo">
    <img alt="마켓비 철제장수납장 드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1BF6CACC4CF68494129932B87B0C9B3A079DDE8C4BA714BD93E4BF5DAEBC10E8.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">마켓비 철제장수납장 드림</h2>
    <div class="card-price">
            10원
          </div>
    <div class="card-region-name">
            제주 제주시 아라일동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 34
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274014399" href="/articles/274014399">
    <div class="card-photo">
    <img alt="냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C9676D66084FD2EE00AE6C5D39B265627CB06197DEA6DADBC3EB2440A5FC6B82.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            광주 광산구 첨단2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 23
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274004001" href="/articles/274004001">
    <div class="card-photo">
    <img alt="다이슨 v8 청소기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/01F393E5F51B4DA32C817F14A46279A25EE40968CCA57B6F81E0F64FC82E1CE6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">다이슨 v8 청소기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경기도 성남시 분당구 구미동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273925231" href="/articles/273925231">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/22957C51EA63B0E40AC59188498B4AA82E6BC2B82E5037C378B32C4A08E33A8B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 25
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975070" href="/articles/273975070">
    <div class="card-photo">
    <img alt="스팸팔아요~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/730795bbe314437630ed5f1dd80bb123e33532212a0d42c8919c49b0147521f9.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">스팸팔아요~</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 사하구 다대동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273921135" href="/articles/273921135">
    <div class="card-photo">
    <img alt="lg 휘센 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4DDEF244CCD690065ED6EEB04BFDBB754DDA838F5BABDECFA933F07E9A9825B9.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">lg 휘센 제습기</h2>
    <div class="card-price">
            80,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 상남동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274012057" href="/articles/274012057">
    <div class="card-photo">
    <img alt="★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/88AFB93658556EA3DF8603FB9064D00328F5AE3A92B26B4674DB0E0E808B2ACE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            대구 북구 침산2동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273927308" href="/articles/273927308">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/91B8FEE166411BBBF5B7E506CE227FA9A29E5BC3E7AFEC07C4CF2B5F7D1BC7A1.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960102" href="/articles/273960102">
    <div class="card-photo">
    <img alt="컨테이너 하우스판매!!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/44A07ADE16BFFEF44BCE2A7B873642B164EE8ABFD6C95C6D3B014853E9FE2742.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">컨테이너 하우스판매!!</h2>
    <div class="card-price">
            1원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273986259" href="/articles/273986259">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/84C5D0E0419D18BF87CD30C53893A12E62D691E470F8E380F83329FFBCD36527.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            제주 제주시 노형동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273810590" href="/articles/273810590">
    <div class="card-photo">
    <img alt="삼천리 자전거 (아동용의자 포함)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/83d71123f025e54536a6bca0d372ab46cce152425b2f57eeed4c2f67b23a8c0b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산서구 대화동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 28
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983175" href="/articles/273983175">
    <div class="card-photo">
    <img alt="3단 원목 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f11c004faa962d4469ab4106a84088f634ea5cac4ba39190993206355d6ae4d2.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 원목 수납장</h2>
    <div class="card-price">
            6,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 무실동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975026" href="/articles/273975026">
    <div class="card-photo">
    <img alt="자전거 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2B4B3C6F4446A9C51CB36786F9B098609E5F34109596B7DD73EE4867D6953E11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            대전 유성구 전민동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960878" href="/articles/273960878">
    <div class="card-photo">
    <img alt="가정용냉장고 오늘가저가시면 이만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1B6F5E18EFE2153B27172E95CBAF7F76059AEC37C337DAE74FD425010DCCE0C4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271724995" href="/articles/271724995">
    <div class="card-photo">
    <img alt="철제선반입니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/bd0433f673914e540acb68455a3c4a79e84f6c6c07832f0586d72a629fd406d7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반입니다.</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 기장군 정관읍
          </div>
    <div class="card-counts">
    <span>
                관심 98
              </span>
            ∙
            <span>
                채팅 114
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273998510" href="/articles/273998510">
    <div class="card-photo">
    <img alt="프리즘티비 65인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6E4F741C258E9D77750D8FB6C14FB3A13F90076FF7CCBB6C0028CC3B627B2E10.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프리즘티비 65인지</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 처인구 모현읍
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273967671" href="/articles/273967671">
    <div class="card-photo">
    <img alt="alton bike 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/207f7faddb43218ab52890d4c91746e1c60335e4375753716f8e84d064f8220f.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">alton bike 자전거 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 기흥구 마북동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274010791" href="/articles/274010791">
    <div class="card-photo">
    <img alt="엘지냉장고 140리터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f38888dd068862f05de80d5cfdbb1ff5f3b4699848a679d5da032e18c6196624.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지냉장고 140리터</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 덕진동2가
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273918993" href="/articles/273918993">
    <div class="card-photo">
    <img alt="선반 오처넌에 가져가용" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FDE15F69B168951D98CA92D19D20B00B86B2202BAE0A3CE615BB6B7D3050FC11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반 오처넌에 가져가용</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 동래구 사직제3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273950972" href="/articles/273950972">
    <div class="card-photo">
    <img alt="게임용 컴퓨터 i5 4460 팝니다~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/48be7bb4c31571557ea3e56719e2825fabc31c7cdfec0a5d427188619815bfee.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>
    <div class="card-price">
            140,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정3동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 19
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972991" href="/articles/273972991">
    <div class="card-photo">
    <img alt="에어 컴프레셔 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2C42C9231F12BE0483C53AE1B0E26682174C49EDB51CEB435BB48332062B86D5.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어 컴프레셔 판매합니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274002275" href="/articles/274002275">
    <div class="card-photo">
    <img alt="리락쿠마스프링카" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D8489065A1683C218D8C0497BD66C896455566A3C72399477ABF304C3CCC8EB7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">리락쿠마스프링카</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 목동동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987132" href="/articles/273987132">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3AA48CE014E9A50F79E64F3FF902AF757494984144A3C6AA92C910A28B3213AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 김해시 구산동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273995769" href="/articles/273995769">
    <div class="card-photo">
    <img alt="접이식 캠핑 테이블 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6a3686dfc685327d4dfdf9de0e02df3578c4c7e313f3ee3af080082f27aa1851.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경남 김해시 장유3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983001" href="/articles/273983001">
    <div class="card-photo">
    <img alt="캠핑 의자 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4009e629f8942bc08a37b9ada25c722ec809da043f538789b280a0a2b0524c64.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑 의자 팝니다.</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 사상구 모라제1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273878099" href="/articles/273878099">
    <div class="card-photo">
    <img alt="이케아 철제선반 묶음 판매합니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/05F5DE0883E7D711D0A56B346DD260440D54973C35814344386342D7EEC6B8D3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>
    <div class="card-price">
            25,000원
          </div>
    <div class="card-region-name">
            강원도 춘천시 동면
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273786394" href="/articles/273786394">
    <div class="card-photo">
    <img alt="자전거 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7e03864758cd2f63955b1fb7bfb41a62d03fd7ec49b4085372090afe42526d95.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000929" href="/articles/274000929">
    <div class="card-photo">
    <img alt="조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/B80112B786A8F3F8EDF5A6E766F96414ED2D0BE68DE89874A6E36EADFD50513D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>
    <div class="card-price">
            550,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 죽전동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892150" href="/articles/273892150">
    <div class="card-photo">
    <img alt="[일렉트로룩스] 전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D4089CFB9D98BA6960E40AFDFC872A8C75A3AAB22A324648D296AD04F2F963BB.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 대현동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273808111" href="/articles/273808111">
    <div class="card-photo">
    <img alt="2~3인용 쇼파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E05C187B87D79645127289C66A7D5C8363001A99CBFFFD690E2A41B96AAD6698.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2~3인용 쇼파</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 이호이동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273982810" href="/articles/273982810">
    <div class="card-photo">
    <img alt="파세코 Camp-27 난로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1844CB33DFAD69B8CB864C64CAC23AB7E34CABAD4005561720C615E82D14C955.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">파세코 Camp-27 난로</h2>
    <div class="card-price">
            280,000원
          </div>
    <div class="card-region-name">
            인천 계양구 계산3동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274022028" href="/articles/274022028">
    <div class="card-photo">
    <img alt="푸름이까꿍" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/43e238fb7d674d3d1acc8dd16eb1a3f6de29f3a7173b09cae1552dc08dbab117.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">푸름이까꿍</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            부산 북구 만덕제2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273968766" href="/articles/273968766">
    <div class="card-photo">
    <img alt="수박1통2~3kg 1통 3천원 2통5천원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2ea3525511ac7d8be93ac5e3b973dc1b5b8e3b8165170008cf041e60cb2344bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>
    <div class="card-price">
            3,000원
          </div>
    <div class="card-region-name">
            충북 음성군 생극면
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273922139" href="/articles/273922139">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DA91C69D5D93229ADEFEB59ED52818E85BF84EC5403447EB2E9EF615DDDF0F2D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 신설동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005752" href="/articles/274005752">
    <div class="card-photo">
    <img alt="편하게 쓰기 좋은 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9434336919CC8C4B4AE0AA852E14A2A5F3F11A8A50424CDB9C7383A0A70B27E6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            인천 서구 검암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273649558" href="/articles/273649558">
    <div class="card-photo">
    <img alt="디월트 임팩트드라이버 DCF887P2A 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/AE703E015FF49B83C5EA7F46058D85B2015D6FDC6CE47598CBB2C518AB8362E7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>
    <div class="card-price">
            160,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 원동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273636900" href="/articles/273636900">
    <div class="card-photo">
    <img alt="냉동고 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/60D0595365B3BA12AFCD71425432CC00CB59EA90C108A13CC0BEF25C6DE47000.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉동고 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼2동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273792490" href="/articles/273792490">
    <div class="card-photo">
    <img alt="MTB 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/10d26d7590f6d22875a65a2337663b4894b52f12fc7f67a7feda3d6a9e9ac5eb.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">MTB 자전거 판매합니다</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정1동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843222" href="/articles/273843222">
    <div class="card-photo">
    <img alt="네스프레소 커피머신" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3084582B2BC492DE01787B3FA998AFFD1B80B36D89CF0C708366BB3C4205F241.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">네스프레소 커피머신</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 상현동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869355" href="/articles/273869355">
    <div class="card-photo">
    <img alt="아이패드 미니 2세대 32g" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D915CC0C94FA942A183567B54B5B5D4EFF5CF62D77C8184D0863C82DAEC50815.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이패드 미니 2세대 32g</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 송파구 방이2동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273961825" href="/articles/273961825">
    <div class="card-photo">
    <img alt="에어컨 수거해가시면 2만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/105CCC1F8D715A243EDB60BF217361923B9B600B3A4BFC82A3A17B3D0C067765.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어컨 수거해가시면 2만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271187738" href="/articles/271187738">
    <div class="card-photo">
    <img alt="한샘 원목 철제 책장 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FF1123F4FC1F106BCB475E980CD40FD03C12DC9EA186F3C44B8C83BDE5DF029D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 동작구 흑석동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962285" href="/articles/273962285">
    <div class="card-photo">
    <img alt="냉장고 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9d9fe431056c17482ec543f00e47dad6e02ac7227fb55e9cac37f79477def34a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            전남 여수시 둔덕동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273984751" href="/articles/273984751">
    <div class="card-photo">
    <img alt="딤채 김치냉장고 드립니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/847c742c07e5438607152059f4bc77326baab027e8d8c3795bc60e5b2137bf84.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            경기도 부천시 상1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987712" href="/articles/273987712">
    <div class="card-photo">
    <img alt="삼성 냉난방기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E2F19693CA6462113B9D2426AB3254B69AC034E60174E606BF78CD6A62F6C701.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 냉난방기</h2>
    <div class="card-price">
            400,000원
          </div>
    <div class="card-region-name">
            대구 수성구 수성4가동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869503" href="/articles/273869503">
    <div class="card-photo">
    <img alt="이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/34129bac567170224e955da708d6de35caf817c921034717ef67490bf21e9ee7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            경남 창원시 마산합포구 현동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273876104" href="/articles/273876104">
    <div class="card-photo">
    <img alt="벤츠 골프백 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/5469ade3eb86dd407a46b279bfeec34898cea3b48bccf312fb9c65d60eaa788a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">벤츠 골프백 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 별내동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962891" href="/articles/273962891">
    <div class="card-photo">
    <img alt="신세계상품권" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/8807D19A15756C05FECF99B6C5EC897C71512206EF57F40906D03F498E60DF5B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계상품권</h2>
    <div class="card-price">
            45,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273997532" href="/articles/273997532">
    <div class="card-photo">
    <img alt="미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7a45cb368f9d5088a49c7ce5936a68535bfeb73395e797ad8f5a1b162a8812be.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>
    <div class="card-price">
            800,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273945035" href="/articles/273945035">
    <div class="card-photo">
    <img alt="30인치 넘는 삼성 티비 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FC81D1AE7993ADB1A91905CB7155CBB6DBF2DA4F396AD024A340C326B862EBFC.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경남 창원시 의창구 신월동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273780489" href="/articles/273780489">
    <div class="card-photo">
    <img alt="삼성32인치LED 티비겸모니터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/98ACB1173483236E2057DA3BED3CF980363A4AFB24DE008933FFCE4EFD958188.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            충북 청주시 청원구 우암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273718765" href="/articles/273718765">
    <div class="card-photo">
    <img alt="43인치 TV 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FA047E879738FB0D1B29DE97783D893E6DEF4F14B057616BDBBDAEBD361A6F40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">43인치 TV 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 홍제제3동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273793234" href="/articles/273793234">
    <div class="card-photo">
    <img alt="딤채 김치냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4C8FB14C2A3BB18B0A0DF5FCDF44A755C95FAF2D74C213C34E1F83FF148D0D2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고</h2>
    <div class="card-price">
            200,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정3동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006581" href="/articles/274006581">
    <div class="card-photo">
    <img alt="프롬유 샤워핸들" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/58ED958764AAAFEF030B8454EA5A0754F3F35BB225FB7E8D592D938FED7840A2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프롬유 샤워핸들</h2>
    <div class="card-price">
            35,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 산척동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274019532" href="/articles/274019532">
    <div class="card-photo">
    <img alt="반석스포츠 아령 3kg/5kg 세트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68604AF514546143D439B389483DEDBD48E246C9AD2478B84128901E1A10D964.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 도룡동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273815819" href="/articles/273815819">
    <div class="card-photo">
    <img alt="갤럭시탭 s6 lite 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/CE7FAA2CD5A30B1C7EAF7AC120D1A5B6C840D206D968A11794C7D5B576F6ADA3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>
    <div class="card-price">
            250,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 다산1동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005062" href="/articles/274005062">
    <div class="card-photo">
    <img alt="몬테소리 레인보우 사운드 비즈 트리" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E8B876CEACE47741BDD360B73E03A9830D9A456044579429E14C58F012049F5C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 권선구 당수동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273959401" href="/articles/273959401">
    <div class="card-photo">
    <img alt="갤럭시 노트 10 플러스 + 256기가 A급" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1ef2adc9192d1247239fe763a6523372727b638472d579ca90dcd6f922babe3a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>
    <div class="card-price">
            350,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산동구 정발산동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843776" href="/articles/273843776">
    <div class="card-photo">
    <img alt="캣폴(캣타워) 가또블랑코 하이엔드" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/d99f99bc033a8311c56553a17b57f306998c61682682dabf6ac1a3b577bfe69b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 성북구 장위동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274023175" href="/articles/274023175">
    <div class="card-photo">
    <img alt="신세계 상품권 만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/31A0B799D3E4A2A6C726613C1EFF292BD5BA052FD537FD397663A70AF2F503AE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계 상품권 만원</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273572748" href="/articles/273572748">
    <div class="card-photo">
    <img alt="장인한과 파지약과" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79B8387D6FD309E874D2099FC92E2BC0E054D700F53E5CD676E71ED8C6293C33.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">장인한과 파지약과</h2>
    <div class="card-price">
            2,000원
          </div>
    <div class="card-region-name">
            경기도 구리시 수택3동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273794168" href="/articles/273794168">
    <div class="card-photo">
    <img alt="원목의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e78b47286e61dfb5b2a2e4cc79a7db6af4bd3f3934ad7a94bf5bb88bf3444f22.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원목의자</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 서귀동
          </div>
    <div class="card-counts">
    <span>
                관심 13
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273506160" href="/articles/273506160">
    <div class="card-photo">
    <img alt="엘지 드럼세탁기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39c8eee89806fadd22f7b9e89c6f6e7d500a175bac4cca9f0e3d00e4822b4196.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지 드럼세탁기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서초구 서초동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274001821" href="/articles/274001821">
    <div class="card-photo">
    <img alt="캐리어 클라윈드 138L 냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/460A4D7C5793B0EDA3467FFABAC75D96343D6552B6F929BAF609029ACC2190BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>
    <div class="card-price">
            90,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 용두동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273904456" href="/articles/273904456">
    <div class="card-photo">
    <img alt="삼천리 자전거 20 스넬로 미니벨로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DF78DE0D36D30AED5A656B8F9FF49C4D8F2A446EC63EF32773A3D164020AA3D0.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            서울 송파구 잠실동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273899049" href="/articles/273899049">
    <div class="card-photo">
    <img alt="수납 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/49C49B0EE59B0F73DCD852F95D406B7384AFFDE1CA0AB59503CEA5491AA83F65.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수납 선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            광주 서구 쌍촌동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273754420" href="/articles/273754420">
    <div class="card-photo">
    <img alt="그래픽카드 및 cpu" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/36e32e7f5a67eef732b0c19f19711bb7243ff1734bc7d1f5cc68e061da36fc55.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">그래픽카드 및 cpu</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 18
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960264" href="/articles/273960264">
    <div class="card-photo">
    <img alt="2인용 쇼파 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/35636482F4B888B12240D19A951F7A4496FCE1B5F5E7F5B5B88C5A802C5B3AB4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2인용 쇼파 </h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956622" href="/articles/273956622">
    <div class="card-photo">
    <img alt="i5-7500 32인치모니터 컴퓨터 셋트 팜니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C0EB2C9BCC2057D517B52C97903052BD731B6372741D9D0837518760A015F8BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>
    <div class="card-price">
            500,000원
          </div>
    <div class="card-region-name">
            충남 천안시 서북구 두정동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 1
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274009707" href="/articles/274009707">
    <div class="card-photo">
    <img alt="책장 무료드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39b59bc6014b9366d01ea4c93fe4be305f4d9646321e39ff4b337ca4e7b8617e.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">책장 무료드림</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            대구 달서구 본리동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273734192" href="/articles/273734192">
    <div class="card-photo">
    <img alt="UHD TV  모델명UN65NU7050FXKR  내놓아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/87a99c47e7e0d0e048806327638033f248214569226d25d1c2de8090b4e06e9d.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>
    <div class="card-price">
            450,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 안덕면
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972531" href="/articles/273972531">
    <div class="card-photo">
    <img alt="이케아 선반을 무료로 드려요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/100DB9496625CB911682A344FCEE41FA0FD48338E5CFF169371549F1635D5D67.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 선반을 무료로 드려요</h2>
    <div class="card-price blank-price">
            -
          </div>
    <div class="card-region-name">
            경기도 안산시 단원구 선부1동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273623778" href="/articles/273623778">
    <div class="card-photo">
    <img alt="아람 자연이랑 전집 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C2DD4F67EBCE23DD9933E32AA970EE6A8BE00067FD0FA703C2D25ADE86C8A111.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아람 자연이랑 전집 </h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            서울 강남구 대치1동
          </div>
    <div class="card-counts">
    <span>
                관심 17
              </span>
            ∙
            <span>
                채팅 20
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962348" href="/articles/273962348">
    <div class="card-photo">
    <img alt="알톤자전거21단" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/774409914ce1936adf8d482726e06e3a39870821c11bd91cde8f2e6f6013ea94.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤자전거21단</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 송파구 송파1동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273908814" href="/articles/273908814">
    <div class="card-photo">
    <img alt="원룸 정리_ 책상,의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3FC3FA0F9D2A793F489E30E06E9E00BDC5D4EA34DB00D073A28C1216B968FB36.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원룸 정리_ 책상,의자</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            부산 부산진구 부전동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273978876" href="/articles/273978876">
    <div class="card-photo">
    <img alt="전자렌지 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68550D76BA1CC4FD76FF442E547B17135DB42A00EF5F82B43DE4FF4D22835B2C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지 팔아요</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 구암동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273198719" href="/articles/273198719">
    <div class="card-photo">
    <img alt="삼성냉장고 상태좋습니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/00e7811fc6746aea408e14711ed4d1e937bd7cd2b1e81bfeb7738d076b1d8737.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성냉장고 상태좋습니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            부산 사상구 주례동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274024826" href="/articles/274024826">
    <div class="card-photo">
    <img alt="선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6AA9F9BCC36E47CD2C1DFAE51969C435DA2EF4560A787DBDC74C256D41B8788C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반</h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            경남 진주시 호탄동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273920668" href="/articles/273920668">
    <div class="card-photo">
    <img alt="안방그릴(연기안나는 전기그릴)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/21A48D6C5A5BE833055724CF260F8D21244EFE6220264012019B88019DBE33AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            광주 서구 화정2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000811" href="/articles/274000811">
    <div class="card-photo">
    <img alt="숀리 바이크 실내자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79FA3C4A067A48344D69C4EA48783F7D0135BA1B444D4E26BD0291162E37501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">숀리 바이크 실내자전거</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경북 구미시 봉곡동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274011505" href="/articles/274011505">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3a720aea0080c736ae65e82644582af4f949e2801fe3043e141008a23e52e519.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            7,000원
          </div>
    <div class="card-region-name">
            충남 천안시 동남구 신방동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273894828" href="/articles/273894828">
    <div class="card-photo">
    <img alt="알톤전기자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4F7C5F656D7FB042486D22D0AA3F766792F3DA5A34ACA8413EAC0FBA1277499.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤전기자전거</h2>
    <div class="card-price">
            300,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 답십리동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843713" href="/articles/273843713">
    <div class="card-photo">
    <img alt="이케아 철제 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/18D633E7264B7B1FAEAE281432721888C9ABB644EBC530798B03B5474F31AC3E.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제 선반</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 반림동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 22
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956856" href="/articles/273956856">
    <div class="card-photo">
    <img alt="3인용소파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/50aeabaf787472b725905babce0df5a53ba9360f01f058a965e6abb9943097bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3인용소파</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            부산 수영구 망미제2동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006145" href="/articles/274006145">
    <div class="card-photo">
    <img alt="에듀테이블" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/b45e21bdc0bffc0b97a27f284057fa7c55fae74f04cfe54e7268d2c5d6c84a36.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에듀테이블</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 송천동2가
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273860081" href="/articles/273860081">
    <div class="card-photo">
    <img alt="캠핑매트 에어포스 에어매트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e11104a3d21f69dba73a3429d5f348319325349cd58e070a7e0b0b4f5523ced6.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 영통구 매탄1동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 2
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273935179" href="/articles/273935179">
    <div class="card-photo">
    <img alt="LG 냉장고 (566리터)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68efdee818ecd0546590913b7f611dded1ed835155af92384eda15c5141bac4b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">LG 냉장고 (566리터)</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 향남읍
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892310" href="/articles/273892310">
    <div class="card-photo">
    <img alt="방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/565B9C7C477F683844CB4D39FC321CA7808E3754A2429953A20D11E009960C15.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            서울 강남구 압구정동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987830" href="/articles/273987830">
    <div class="card-photo">
    <img alt="아이두젠 헥사타프" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/0750A7891C444592553BA5A89BB630786D6BA4FC5BBCC65A017ADC4C3C50AC40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이두젠 헥사타프</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            경기도 군포시 도마교동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273971674" href="/articles/273971674">
    <div class="card-photo">
    <img alt="3단 접이식 메트리스 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3E48CDE679DADCDA82154FB4785B7F2A1B32AB23FE3339AF0481F71533AC501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 강서구 명지1동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    </section>
    <section id="hot-articles-go-download">
    <h3>
            더 구경하고 싶나요?
        </h3>
    <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>
    <div id="hot-articles-download-buttons">
    <a class="download-button" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" target="_blank">
    <div class="home-apple-store-bar-white"></div>
    <div class="download-text">App Store</div>
    </a> <a class="download-button" href="https://play.google.com/store/apps/details?id=com.towneers.www" target="_blank">
    <div class="home-google-play-bar-white"></div>
    <div class="download-text">Google Play</div>
    </a> </div>
    </section>
    </section>
    <script charset="utf-8" type="text/javascript">
      function changeRegion(key, value){
        var url_array
        if(window.location.pathname === "/hot_articles" && window.location.href.match(/\?/)) {
          url_array = window.location.href.split('?')[1].split(/(?:r1|&?r2)=/)
          url_array.unshift("")
        } else {
          url_array = window.location.pathname.split('/')
        }
        var keys = { r1: 2, r2: 3, r3: 4 }
        url_array[keys[key]] = value
        url_array[1] = 'region'
          if(key == 'r2' && decodeURI(url_array[2]) == "세종특별자치시") {
            url_array[4] = value
            url_array[3] = "_"
          }
        if(key == 'r1') { url_array.splice(3, 2) }
        if(key == 'r2' && url_array[3] !== "_") { url_array.splice(4, 1) }
        window.location.href = window.location.origin + url_array.join('/')
      }
    </script>
    <footer id="footer">
    <div class="footer-container">
    <div class="footer-top">
    <div class="footer-logo"></div>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="/trust">믿을 수 있는 중고거래</a></li>
    <li class="footer-list-item"><a class="link-highlight" href="https://cs.kr.karrotmarket.com/wv/faqs">자주 묻는 질문</a></li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="https://ad.daangn.com/" target="_blank">광고주센터</a></li>
    <li class="footer-list-item">
    <a class="ga-click" data-event-action="hot_articles" data-event-category="town_link_from" data-event-label="footer_town" href="https://town.daangn.com" target="_blank">동네가게</a>
    </li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a href="https://team.daangn.com/" target="_blank">회사 소개</a></li>
    <li class="footer-list-item"><a href="https://team.daangn.com/jobs/" target="_blank">채용</a></li>
    </ul>
    <ul class="footer-list policy">
    <li class="footer-list-item"><a href="https://policy.daangn.com/terms.html" target="_blank">이용약관</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/privacy.html" target="_blank">개인정보처리방침</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/location.html" target="_blank">위치기반서비스 이용약관</a></li>
    </ul>
    </div>
    <div class="footer-bottom">
    <div id="copyright">
    <ul class="copyright-list">
    <li class="copyright-list-item">고객문의 <a href="mailto:cs@daangnservice.com">cs@daangnservice.com</a></li>
    <li class="copyright-list-item">제휴문의 <a href="mailto:contact@daangn.com">contact@daangn.com</a></li>
    </ul>
    <ul class="copyright-list">
    <li class="copyright-list-item">지역광고 <a href="mailto:ad@daangn.com">ad@daangn.com</a></li>
    <li class="copyright-list-item">PR문의 <a href="mailto:pr@daangn.com">pr@daangn.com</a></li>
    </ul>
    <ul class="copyright-list copyright-list-light">
    <li class="copyright-list-item"><address>서울특별시 구로구 디지털로 30길 28 609호 (당근서비스)</address></li>
    <li class="copyright-list-item">사업자 등록번호 : 375-87-00088</li>
    <li class="copyright-list-item">직업정보제공사업 신고번호 : J1200020200016</li>
    </ul>
    <div id="social">
    <ul class="social-list">
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.facebook.com/daangn" target="_blank">
    <img alt="facebook" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-facebook-0563f4a93852d073b41f13b8bcabb03d47af3bb3a6755cdfedd8a73686c7f18c.svg"/>
    <span class="sr-only">facebook</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.instagram.com/daangnmarket/" target="_blank">
    <img alt="instagram" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-instagram-2f6c88a461597907c114b7ce28eab053fcae791ed26417915fefb6f7c9f95756.svg"/>
    <span class="sr-only">instagram</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://blog.naver.com/daangn" target="_blank">
    <img alt="blog" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-blog-e1b0d512d1766a6962ec5bbb5b0803d2a6a9c55ad97db5ba9eebb76013caceba.svg"/>
    <span class="sr-only">blog</span>
    </a> </li>
    <li class="global-links">
    <img height="24" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-global-2f53678b428ec623cefd07a90dd7777f3e55fc0433918f645d7d75ace6ff1fc3.png" width="24"/>
    <select id="global-links-select">
    <option value="kr">한국</option>
    <option value="https://uk.karrotmarket.com">영국</option>
    <option value="https://ca.karrotmarket.com">캐나다</option>
    <option value="https://us.karrotmarket.com">미국</option>
    <option value="https://jp.karrotmarket.com">일본</option>
    </select>
    </li>
    </ul>
    </div>
    <div class="copyright-text">©Danggeun Market Inc.</div>
    </div>
    </div>
    </div>
    </footer>
    </body>
    </html>
    <!DOCTYPE html>
    
    <html lang="ko">
    <head>
    <meta charset="utf-8"/>
    <meta content="IE=edge" http-equiv="X-UA-Compatible"/>
    <meta content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no" name="viewport"/>
    <link href="https://www.daangn.com/hot_articles" rel="canonical"/>
    <title>당근마켓 중고거래 | 당신 근처의 당근마켓</title>
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." name="description">
    <link href="당근마켓" rel="author"/>
    <meta content="https://www.daangn.com/hot_articles" property="og:url">
    <meta content="당근마켓 중고거래 | 당신 근처의 당근마켓" property="og:title">
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." property="og:description"/>
    <meta content="당근마켓" property="og:site_name"/>
    <meta content="https://www.daangn.com/images/meta/home/flea_market.png" property="og:image"/>
    <meta content="article" property="og:type"/>
    <meta content="ko_KR" property="og:locale"/>
    <meta content="1463621440622064" property="fb:app_id"/>
    <meta content="summary_large_image" name="twitter:card"/>
    <meta content="@danggeunmarket" name="twitter:site"/>
    <meta content="당근마켓 중고거래 | 당신 근처의 당근마켓" name="twitter:title"/>
    <meta content="당근마켓에서 거래되는 인기 중고 매물을 소개합니다. 지금 당근마켓에서 거래되고 있는 다양한 매물을 구경해보세요." name="twitter:description"/>
    <meta content="https://www.daangn.com/images/meta/home/flea_market.png" name="twitter:image"/>
    <meta content="d1f8112731c18313535732cf2516d6401bfed40a" name="naver-site-verification"/>
    <link href="/images/icons/shortcut_icon.png" rel="shortcut icon" type="image/x-icon"/>
    <link href="https://d1unjqcospf8gs.cloudfront.net/favicon.ico" rel="shortcut icon" type="image/x-icon">
    <link href="https://d1unjqcospf8gs.cloudfront.net/assets/home/articles/hot-76409f246af8ba6ca58659826685527e45104fd2b089dd053e6af97133bb193b.css" media="all" rel="stylesheet"/>
    <script src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base-a182b6524ddb27bbc6a0647ee4bc2b79384325e8bde2b0775b94c7573fd0d87e.js"></script>
    <link href="/images/icons/daangn_logo_192.png" rel="apple-touch-icon" sizes="192x192"/>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->
    <meta content="authenticity_token" name="csrf-param"/>
    <meta content="u3KG84YcReIJ0Msd8mlG6T/aYodEKU5+Dz4l7QPp2tiUC0b24Z12Vj5TBot85lU96zE7BLHHLn9sYrfKNZzoSA==" name="csrf-token"/>
    <script>
        window.fbAsyncInit = function() {
          FB.init({
            appId      : '1463621440622064',
            xfbml      : true,
            version    : 'v2.4'
          });
        };
    
        (function(d, s, id){
          var js, fjs = d.getElementsByTagName(s)[0];
          if (d.getElementById(id)) {return;}
          js = d.createElement(s); js.id = id;
          js.src = "//connect.facebook.net/en_US/sdk.js";
          fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'facebook-jssdk'));
      </script>
    <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
                  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
                m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    
        ga('create', 'UA-64551386-2', 'auto');
         ga('set', 'dimension2', 'true');  ga('send', 'pageview'); </script>
    <!-- Facebook Pixel Code -->
    <script>
        !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
                n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
          n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
          t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
                document,'script','//connect.facebook.net/en_US/fbevents.js');
    
        fbq('init', '992961397411651');
        facebookClickEvent("PageView")
    
        function facebookClickEvent(eventName, data) {
          if (data !== undefined) {
              fbq('track', eventName, data)
          } else {
              fbq('track', eventName)
          }
        }
    
        function facebookClickEventWithPageMove(eventName, data, targetUrl) {
            facebookClickEvent(eventName, data);
            window.location.href = targetUrl;
        }
      </script>
    <noscript><img height="1" src="https://www.facebook.com/tr?id=992961397411651&amp;ev=PageView&amp;noscript=1" style="display:none" width="1"/></noscript>
    <!-- End Facebook Pixel Code -->
    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
          new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
          j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
          'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
      })(window,document,'script','dataLayer','GTM-PJSK4QL');</script>
    <!-- End Google Tag Manager -->
    <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Organization",
      "name": "당근마켓",
      "url": "https://www.daangn.com",
      "sameAs": [
        "https://www.facebook.com/daangn",
        "https://blog.naver.com/daangn",
        "https://www.youtube.com/channel/UC8tsBsQBuF7QybxgLmStihA",
        "https://twitter.com/daangnmarket",
        "https://www.instagram.com/daangnmarket",
        "https://apps.apple.com/kr/app/id1018769995",
        "https://play.google.com/store/apps/details?id=com.towneers.www"
      ],
      "logo": "https://www.daangn.com/logo.png"
    }
    </script>
    </link></meta></meta></meta></head>
    <body class="hoian-kr">
    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe height="0" src="https://www.googletagmanager.com/ns.html?id=GTM-PJSK4QL" style="display:none;visibility:hidden" width="0"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
    <!-- Appsflyer Smart Banner -->
    <script>
        !function(t,e,n,s,a,c,i,o,p){t.AppsFlyerSdkObject=a,t.AF=t.AF||function(){(t.AF.q=t.AF.q||[]).push([Date.now()].concat(Array.prototype.slice.call(arguments)))},t.AF.id=t.AF.id||i,t.AF.plugins={},o=e.createElement(n),p=e.getElementsByTagName(n)[0],o.async=1,o.src="https://websdk.appsflyer.com?"+(c.length>0?"st="+c.split(",").sort().join(",")+"&":"")+(i.length>0?"af_id="+i:""),p.parentNode.insertBefore(o,p)}(window,document,"script",0,"AF","banners",{banners: {key: "629f6f7a-a2a6-49c0-8d27-ffa48df1cd0e"}})
        AF('banners', 'showBanner')
    </script>
    <!-- End Appsflyer Smart Banner-->
    <header id="fixed-bar">
    <div id="fixed-bar-wrap">
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    </div>
    </header>
    <section id="content">
    <h1 class="head-title" id="hot-articles-head-title">
        
        
        중고거래 인기매물
      </h1>
    <nav id="hot-articles-navigation">
    <select class="hot-articles-nav-select" id="region1" name="region1" onchange="changeRegion('r1', this.value)"><option value="">지역을 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    <select class="hot-articles-nav-select" disabled="disabled" id="region2" name="region2" onchange="changeRegion('r2', this.value)"><option value="">동네를 선택하세요</option><option value="서울특별시">서울특별시</option>
    <option value="부산광역시">부산광역시</option>
    <option value="대구광역시">대구광역시</option>
    <option value="인천광역시">인천광역시</option>
    <option value="광주광역시">광주광역시</option>
    <option value="대전광역시">대전광역시</option>
    <option value="울산광역시">울산광역시</option>
    <option value="세종특별자치시">세종특별자치시</option>
    <option value="경기도">경기도</option>
    <option value="강원도">강원도</option>
    <option value="충청북도">충청북도</option>
    <option value="충청남도">충청남도</option>
    <option value="전라북도">전라북도</option>
    <option value="전라남도">전라남도</option>
    <option value="경상북도">경상북도</option>
    <option value="경상남도">경상남도</option>
    <option value="제주특별자치도">제주특별자치도</option>
    <option value="집현동">집현동</option></select>
    </nav>
    <section class="cards-wrap">
    <article class="card-top">
    <a class="card-link" data-event-label="273865202" href="/articles/273865202">
    <div class="card-photo">
    <img alt="삼성 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/da035d5794d5490a86e8596a2ff036db7a6811cde70b8e2cb5514a93f4c0d1af.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 제습기</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 서구 갈마동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 47
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972258" href="/articles/273972258">
    <div class="card-photo">
    <img alt="🎈4단 경량 서랍장 2EA" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E5286230DC4F10CDC1187AF093DC98E700866C3F3CCE2D26B4097EC8E096EF02.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            전남 순천시 해룡면
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869268" href="/articles/273869268">
    <div class="card-photo">
    <img alt="마켓비 철제장수납장 드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1BF6CACC4CF68494129932B87B0C9B3A079DDE8C4BA714BD93E4BF5DAEBC10E8.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">마켓비 철제장수납장 드림</h2>
    <div class="card-price">
            10원
          </div>
    <div class="card-region-name">
            제주 제주시 아라일동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 34
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274014399" href="/articles/274014399">
    <div class="card-photo">
    <img alt="냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C9676D66084FD2EE00AE6C5D39B265627CB06197DEA6DADBC3EB2440A5FC6B82.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            광주 광산구 첨단2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 23
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274004001" href="/articles/274004001">
    <div class="card-photo">
    <img alt="다이슨 v8 청소기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/01F393E5F51B4DA32C817F14A46279A25EE40968CCA57B6F81E0F64FC82E1CE6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">다이슨 v8 청소기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경기도 성남시 분당구 구미동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273925231" href="/articles/273925231">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/22957C51EA63B0E40AC59188498B4AA82E6BC2B82E5037C378B32C4A08E33A8B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 25
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975070" href="/articles/273975070">
    <div class="card-photo">
    <img alt="스팸팔아요~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/730795bbe314437630ed5f1dd80bb123e33532212a0d42c8919c49b0147521f9.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">스팸팔아요~</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 사하구 다대동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273921135" href="/articles/273921135">
    <div class="card-photo">
    <img alt="lg 휘센 제습기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4DDEF244CCD690065ED6EEB04BFDBB754DDA838F5BABDECFA933F07E9A9825B9.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">lg 휘센 제습기</h2>
    <div class="card-price">
            80,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 상남동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274012057" href="/articles/274012057">
    <div class="card-photo">
    <img alt="★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/88AFB93658556EA3DF8603FB9064D00328F5AE3A92B26B4674DB0E0E808B2ACE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            대구 북구 침산2동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273927308" href="/articles/273927308">
    <div class="card-photo">
    <img alt="철제선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/91B8FEE166411BBBF5B7E506CE227FA9A29E5BC3E7AFEC07C4CF2B5F7D1BC7A1.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            대구 중구 남산동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960102" href="/articles/273960102">
    <div class="card-photo">
    <img alt="컨테이너 하우스판매!!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/44A07ADE16BFFEF44BCE2A7B873642B164EE8ABFD6C95C6D3B014853E9FE2742.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">컨테이너 하우스판매!!</h2>
    <div class="card-price">
            1원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273986259" href="/articles/273986259">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/84C5D0E0419D18BF87CD30C53893A12E62D691E470F8E380F83329FFBCD36527.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            제주 제주시 노형동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273810590" href="/articles/273810590">
    <div class="card-photo">
    <img alt="삼천리 자전거 (아동용의자 포함)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/83d71123f025e54536a6bca0d372ab46cce152425b2f57eeed4c2f67b23a8c0b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산서구 대화동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 28
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983175" href="/articles/273983175">
    <div class="card-photo">
    <img alt="3단 원목 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f11c004faa962d4469ab4106a84088f634ea5cac4ba39190993206355d6ae4d2.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 원목 수납장</h2>
    <div class="card-price">
            6,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 무실동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273975026" href="/articles/273975026">
    <div class="card-photo">
    <img alt="자전거 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2B4B3C6F4446A9C51CB36786F9B098609E5F34109596B7DD73EE4867D6953E11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            대전 유성구 전민동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960878" href="/articles/273960878">
    <div class="card-photo">
    <img alt="가정용냉장고 오늘가저가시면 이만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1B6F5E18EFE2153B27172E95CBAF7F76059AEC37C337DAE74FD425010DCCE0C4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271724995" href="/articles/271724995">
    <div class="card-photo">
    <img alt="철제선반입니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/bd0433f673914e540acb68455a3c4a79e84f6c6c07832f0586d72a629fd406d7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">철제선반입니다.</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 기장군 정관읍
          </div>
    <div class="card-counts">
    <span>
                관심 98
              </span>
            ∙
            <span>
                채팅 114
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273998510" href="/articles/273998510">
    <div class="card-photo">
    <img alt="프리즘티비 65인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6E4F741C258E9D77750D8FB6C14FB3A13F90076FF7CCBB6C0028CC3B627B2E10.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프리즘티비 65인지</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 처인구 모현읍
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273967671" href="/articles/273967671">
    <div class="card-photo">
    <img alt="alton bike 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/207f7faddb43218ab52890d4c91746e1c60335e4375753716f8e84d064f8220f.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">alton bike 자전거 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 기흥구 마북동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274010791" href="/articles/274010791">
    <div class="card-photo">
    <img alt="엘지냉장고 140리터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/f38888dd068862f05de80d5cfdbb1ff5f3b4699848a679d5da032e18c6196624.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지냉장고 140리터</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 덕진동2가
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273918993" href="/articles/273918993">
    <div class="card-photo">
    <img alt="선반 오처넌에 가져가용" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FDE15F69B168951D98CA92D19D20B00B86B2202BAE0A3CE615BB6B7D3050FC11.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반 오처넌에 가져가용</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            부산 동래구 사직제3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273950972" href="/articles/273950972">
    <div class="card-photo">
    <img alt="게임용 컴퓨터 i5 4460 팝니다~" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/48be7bb4c31571557ea3e56719e2825fabc31c7cdfec0a5d427188619815bfee.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>
    <div class="card-price">
            140,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정3동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 19
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972991" href="/articles/273972991">
    <div class="card-photo">
    <img alt="에어 컴프레셔 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2C42C9231F12BE0483C53AE1B0E26682174C49EDB51CEB435BB48332062B86D5.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어 컴프레셔 판매합니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274002275" href="/articles/274002275">
    <div class="card-photo">
    <img alt="리락쿠마스프링카" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D8489065A1683C218D8C0497BD66C896455566A3C72399477ABF304C3CCC8EB7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">리락쿠마스프링카</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 목동동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987132" href="/articles/273987132">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3AA48CE014E9A50F79E64F3FF902AF757494984144A3C6AA92C910A28B3213AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 김해시 구산동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273995769" href="/articles/273995769">
    <div class="card-photo">
    <img alt="접이식 캠핑 테이블 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6a3686dfc685327d4dfdf9de0e02df3578c4c7e313f3ee3af080082f27aa1851.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            경남 김해시 장유3동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273983001" href="/articles/273983001">
    <div class="card-photo">
    <img alt="캠핑 의자 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/4009e629f8942bc08a37b9ada25c722ec809da043f538789b280a0a2b0524c64.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑 의자 팝니다.</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 사상구 모라제1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273878099" href="/articles/273878099">
    <div class="card-photo">
    <img alt="이케아 철제선반 묶음 판매합니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/05F5DE0883E7D711D0A56B346DD260440D54973C35814344386342D7EEC6B8D3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>
    <div class="card-price">
            25,000원
          </div>
    <div class="card-region-name">
            강원도 춘천시 동면
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273786394" href="/articles/273786394">
    <div class="card-photo">
    <img alt="자전거 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7e03864758cd2f63955b1fb7bfb41a62d03fd7ec49b4085372090afe42526d95.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">자전거 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            울산 남구 신정동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000929" href="/articles/274000929">
    <div class="card-photo">
    <img alt="조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/B80112B786A8F3F8EDF5A6E766F96414ED2D0BE68DE89874A6E36EADFD50513D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>
    <div class="card-price">
            550,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 죽전동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892150" href="/articles/273892150">
    <div class="card-photo">
    <img alt="[일렉트로룩스] 전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D4089CFB9D98BA6960E40AFDFC872A8C75A3AAB22A324648D296AD04F2F963BB.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 대현동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273808111" href="/articles/273808111">
    <div class="card-photo">
    <img alt="2~3인용 쇼파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E05C187B87D79645127289C66A7D5C8363001A99CBFFFD690E2A41B96AAD6698.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2~3인용 쇼파</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 이호이동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273982810" href="/articles/273982810">
    <div class="card-photo">
    <img alt="파세코 Camp-27 난로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1844CB33DFAD69B8CB864C64CAC23AB7E34CABAD4005561720C615E82D14C955.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">파세코 Camp-27 난로</h2>
    <div class="card-price">
            280,000원
          </div>
    <div class="card-region-name">
            인천 계양구 계산3동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274022028" href="/articles/274022028">
    <div class="card-photo">
    <img alt="푸름이까꿍" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/43e238fb7d674d3d1acc8dd16eb1a3f6de29f3a7173b09cae1552dc08dbab117.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">푸름이까꿍</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            부산 북구 만덕제2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273968766" href="/articles/273968766">
    <div class="card-photo">
    <img alt="수박1통2~3kg 1통 3천원 2통5천원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/2ea3525511ac7d8be93ac5e3b973dc1b5b8e3b8165170008cf041e60cb2344bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>
    <div class="card-price">
            3,000원
          </div>
    <div class="card-region-name">
            충북 음성군 생극면
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273922139" href="/articles/273922139">
    <div class="card-photo">
    <img alt="전자렌지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DA91C69D5D93229ADEFEB59ED52818E85BF84EC5403447EB2E9EF615DDDF0F2D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 신설동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005752" href="/articles/274005752">
    <div class="card-photo">
    <img alt="편하게 쓰기 좋은 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9434336919CC8C4B4AE0AA852E14A2A5F3F11A8A50424CDB9C7383A0A70B27E6.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            인천 서구 검암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273649558" href="/articles/273649558">
    <div class="card-photo">
    <img alt="디월트 임팩트드라이버 DCF887P2A 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/AE703E015FF49B83C5EA7F46058D85B2015D6FDC6CE47598CBB2C518AB8362E7.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>
    <div class="card-price">
            160,000원
          </div>
    <div class="card-region-name">
            강원도 원주시 원동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273636900" href="/articles/273636900">
    <div class="card-photo">
    <img alt="냉동고 팔아요!" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/60D0595365B3BA12AFCD71425432CC00CB59EA90C108A13CC0BEF25C6DE47000.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉동고 팔아요!</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼2동
          </div>
    <div class="card-counts">
    <span>
                관심 19
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273792490" href="/articles/273792490">
    <div class="card-photo">
    <img alt="MTB 자전거 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/10d26d7590f6d22875a65a2337663b4894b52f12fc7f67a7feda3d6a9e9ac5eb.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">MTB 자전거 판매합니다</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정1동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843222" href="/articles/273843222">
    <div class="card-photo">
    <img alt="네스프레소 커피머신" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3084582B2BC492DE01787B3FA998AFFD1B80B36D89CF0C708366BB3C4205F241.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">네스프레소 커피머신</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 용인시 수지구 상현동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 13
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869355" href="/articles/273869355">
    <div class="card-photo">
    <img alt="아이패드 미니 2세대 32g" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/D915CC0C94FA942A183567B54B5B5D4EFF5CF62D77C8184D0863C82DAEC50815.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이패드 미니 2세대 32g</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 송파구 방이2동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273961825" href="/articles/273961825">
    <div class="card-photo">
    <img alt="에어컨 수거해가시면 2만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/105CCC1F8D715A243EDB60BF217361923B9B600B3A4BFC82A3A17B3D0C067765.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에어컨 수거해가시면 2만원</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            충남 서산시 석림동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="271187738" href="/articles/271187738">
    <div class="card-photo">
    <img alt="한샘 원목 철제 책장 선반 수납장" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FF1123F4FC1F106BCB475E980CD40FD03C12DC9EA186F3C44B8C83BDE5DF029D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            서울 동작구 흑석동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962285" href="/articles/273962285">
    <div class="card-photo">
    <img alt="냉장고 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/9d9fe431056c17482ec543f00e47dad6e02ac7227fb55e9cac37f79477def34a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">냉장고 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            전남 여수시 둔덕동
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273984751" href="/articles/273984751">
    <div class="card-photo">
    <img alt="딤채 김치냉장고 드립니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/847c742c07e5438607152059f4bc77326baab027e8d8c3795bc60e5b2137bf84.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            경기도 부천시 상1동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987712" href="/articles/273987712">
    <div class="card-photo">
    <img alt="삼성 냉난방기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E2F19693CA6462113B9D2426AB3254B69AC034E60174E606BF78CD6A62F6C701.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성 냉난방기</h2>
    <div class="card-price">
            400,000원
          </div>
    <div class="card-region-name">
            대구 수성구 수성4가동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273869503" href="/articles/273869503">
    <div class="card-photo">
    <img alt="이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/34129bac567170224e955da708d6de35caf817c921034717ef67490bf21e9ee7.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            경남 창원시 마산합포구 현동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273876104" href="/articles/273876104">
    <div class="card-photo">
    <img alt="벤츠 골프백 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/5469ade3eb86dd407a46b279bfeec34898cea3b48bccf312fb9c65d60eaa788a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">벤츠 골프백 판매합니다</h2>
    <div class="card-price">
            40,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 별내동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962891" href="/articles/273962891">
    <div class="card-photo">
    <img alt="신세계상품권" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/8807D19A15756C05FECF99B6C5EC897C71512206EF57F40906D03F498E60DF5B.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계상품권</h2>
    <div class="card-price">
            45,000원
          </div>
    <div class="card-region-name">
            서울 강남구 역삼동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273997532" href="/articles/273997532">
    <div class="card-photo">
    <img alt="미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다." src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/7a45cb368f9d5088a49c7ce5936a68535bfeb73395e797ad8f5a1b162a8812be.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>
    <div class="card-price">
            800,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273945035" href="/articles/273945035">
    <div class="card-photo">
    <img alt="30인치 넘는 삼성 티비 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FC81D1AE7993ADB1A91905CB7155CBB6DBF2DA4F396AD024A340C326B862EBFC.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경남 창원시 의창구 신월동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 15
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273780489" href="/articles/273780489">
    <div class="card-photo">
    <img alt="삼성32인치LED 티비겸모니터" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/98ACB1173483236E2057DA3BED3CF980363A4AFB24DE008933FFCE4EFD958188.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            충북 청주시 청원구 우암동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273718765" href="/articles/273718765">
    <div class="card-photo">
    <img alt="43인치 TV 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/FA047E879738FB0D1B29DE97783D893E6DEF4F14B057616BDBBDAEBD361A6F40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">43인치 TV 팝니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서대문구 홍제제3동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273793234" href="/articles/273793234">
    <div class="card-photo">
    <img alt="딤채 김치냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4C8FB14C2A3BB18B0A0DF5FCDF44A755C95FAF2D74C213C34E1F83FF148D0D2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">딤채 김치냉장고</h2>
    <div class="card-price">
            200,000원
          </div>
    <div class="card-region-name">
            경기도 파주시 운정3동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006581" href="/articles/274006581">
    <div class="card-photo">
    <img alt="프롬유 샤워핸들" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/58ED958764AAAFEF030B8454EA5A0754F3F35BB225FB7E8D592D938FED7840A2.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">프롬유 샤워핸들</h2>
    <div class="card-price">
            35,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 산척동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274019532" href="/articles/274019532">
    <div class="card-photo">
    <img alt="반석스포츠 아령 3kg/5kg 세트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68604AF514546143D439B389483DEDBD48E246C9AD2478B84128901E1A10D964.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 도룡동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273815819" href="/articles/273815819">
    <div class="card-photo">
    <img alt="갤럭시탭 s6 lite 판매합니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/CE7FAA2CD5A30B1C7EAF7AC120D1A5B6C840D206D968A11794C7D5B576F6ADA3.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>
    <div class="card-price">
            250,000원
          </div>
    <div class="card-region-name">
            경기도 남양주시 다산1동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274005062" href="/articles/274005062">
    <div class="card-photo">
    <img alt="몬테소리 레인보우 사운드 비즈 트리" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/E8B876CEACE47741BDD360B73E03A9830D9A456044579429E14C58F012049F5C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 권선구 당수동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273959401" href="/articles/273959401">
    <div class="card-photo">
    <img alt="갤럭시 노트 10 플러스 + 256기가 A급" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/1ef2adc9192d1247239fe763a6523372727b638472d579ca90dcd6f922babe3a.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>
    <div class="card-price">
            350,000원
          </div>
    <div class="card-region-name">
            경기도 고양시 일산동구 정발산동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 10
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843776" href="/articles/273843776">
    <div class="card-photo">
    <img alt="캣폴(캣타워) 가또블랑코 하이엔드" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/d99f99bc033a8311c56553a17b57f306998c61682682dabf6ac1a3b577bfe69b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 성북구 장위동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 11
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274023175" href="/articles/274023175">
    <div class="card-photo">
    <img alt="신세계 상품권 만원" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/31A0B799D3E4A2A6C726613C1EFF292BD5BA052FD537FD397663A70AF2F503AE.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">신세계 상품권 만원</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            울산 남구 삼산동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273572748" href="/articles/273572748">
    <div class="card-photo">
    <img alt="장인한과 파지약과" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79B8387D6FD309E874D2099FC92E2BC0E054D700F53E5CD676E71ED8C6293C33.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">장인한과 파지약과</h2>
    <div class="card-price">
            2,000원
          </div>
    <div class="card-region-name">
            경기도 구리시 수택3동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 14
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273794168" href="/articles/273794168">
    <div class="card-photo">
    <img alt="원목의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e78b47286e61dfb5b2a2e4cc79a7db6af4bd3f3934ad7a94bf5bb88bf3444f22.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원목의자</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 서귀동
          </div>
    <div class="card-counts">
    <span>
                관심 13
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273506160" href="/articles/273506160">
    <div class="card-photo">
    <img alt="엘지 드럼세탁기" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39c8eee89806fadd22f7b9e89c6f6e7d500a175bac4cca9f0e3d00e4822b4196.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">엘지 드럼세탁기</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 서초구 서초동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274001821" href="/articles/274001821">
    <div class="card-photo">
    <img alt="캐리어 클라윈드 138L 냉장고" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/460A4D7C5793B0EDA3467FFABAC75D96343D6552B6F929BAF609029ACC2190BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>
    <div class="card-price">
            90,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 용두동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273904456" href="/articles/273904456">
    <div class="card-photo">
    <img alt="삼천리 자전거 20 스넬로 미니벨로" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/DF78DE0D36D30AED5A656B8F9FF49C4D8F2A446EC63EF32773A3D164020AA3D0.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>
    <div class="card-price">
            30,000원
          </div>
    <div class="card-region-name">
            서울 송파구 잠실동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273899049" href="/articles/273899049">
    <div class="card-photo">
    <img alt="수납 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/49C49B0EE59B0F73DCD852F95D406B7384AFFDE1CA0AB59503CEA5491AA83F65.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">수납 선반</h2>
    <div class="card-price">
            5,000원
          </div>
    <div class="card-region-name">
            광주 서구 쌍촌동
          </div>
    <div class="card-counts">
    <span>
                관심 12
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273754420" href="/articles/273754420">
    <div class="card-photo">
    <img alt="그래픽카드 및 cpu" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/36e32e7f5a67eef732b0c19f19711bb7243ff1734bc7d1f5cc68e061da36fc55.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">그래픽카드 및 cpu</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            제주 제주시 아라동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 18
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273960264" href="/articles/273960264">
    <div class="card-photo">
    <img alt="2인용 쇼파 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/35636482F4B888B12240D19A951F7A4496FCE1B5F5E7F5B5B88C5A802C5B3AB4.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">2인용 쇼파 </h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            제주 제주시 조천읍
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 3
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956622" href="/articles/273956622">
    <div class="card-photo">
    <img alt="i5-7500 32인치모니터 컴퓨터 셋트 팜니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C0EB2C9BCC2057D517B52C97903052BD731B6372741D9D0837518760A015F8BD.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>
    <div class="card-price">
            500,000원
          </div>
    <div class="card-region-name">
            충남 천안시 서북구 두정동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 1
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274009707" href="/articles/274009707">
    <div class="card-photo">
    <img alt="책장 무료드림" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/39b59bc6014b9366d01ea4c93fe4be305f4d9646321e39ff4b337ca4e7b8617e.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">책장 무료드림</h2>
    <div class="card-price">
            무료나눔
          </div>
    <div class="card-region-name">
            대구 달서구 본리동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273734192" href="/articles/273734192">
    <div class="card-photo">
    <img alt="UHD TV  모델명UN65NU7050FXKR  내놓아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/87a99c47e7e0d0e048806327638033f248214569226d25d1c2de8090b4e06e9d.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>
    <div class="card-price">
            450,000원
          </div>
    <div class="card-region-name">
            제주 서귀포시 안덕면
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273972531" href="/articles/273972531">
    <div class="card-photo">
    <img alt="이케아 선반을 무료로 드려요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/100DB9496625CB911682A344FCEE41FA0FD48338E5CFF169371549F1635D5D67.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 선반을 무료로 드려요</h2>
    <div class="card-price blank-price">
            -
          </div>
    <div class="card-region-name">
            경기도 안산시 단원구 선부1동
          </div>
    <div class="card-counts">
    <span>
                관심 7
              </span>
            ∙
            <span>
                채팅 7
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273623778" href="/articles/273623778">
    <div class="card-photo">
    <img alt="아람 자연이랑 전집 " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/C2DD4F67EBCE23DD9933E32AA970EE6A8BE00067FD0FA703C2D25ADE86C8A111.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아람 자연이랑 전집 </h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            서울 강남구 대치1동
          </div>
    <div class="card-counts">
    <span>
                관심 17
              </span>
            ∙
            <span>
                채팅 20
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273962348" href="/articles/273962348">
    <div class="card-photo">
    <img alt="알톤자전거21단" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/774409914ce1936adf8d482726e06e3a39870821c11bd91cde8f2e6f6013ea94.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤자전거21단</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            서울 송파구 송파1동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273908814" href="/articles/273908814">
    <div class="card-photo">
    <img alt="원룸 정리_ 책상,의자" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3FC3FA0F9D2A793F489E30E06E9E00BDC5D4EA34DB00D073A28C1216B968FB36.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">원룸 정리_ 책상,의자</h2>
    <div class="card-price">
            15,000원
          </div>
    <div class="card-region-name">
            부산 부산진구 부전동
          </div>
    <div class="card-counts">
    <span>
                관심 10
              </span>
            ∙
            <span>
                채팅 5
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273978876" href="/articles/273978876">
    <div class="card-photo">
    <img alt="전자렌지 팔아요" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68550D76BA1CC4FD76FF442E547B17135DB42A00EF5F82B43DE4FF4D22835B2C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자렌지 팔아요</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            대전 유성구 구암동
          </div>
    <div class="card-counts">
    <span>
                관심 2
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273198719" href="/articles/273198719">
    <div class="card-photo">
    <img alt="삼성냉장고 상태좋습니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/00e7811fc6746aea408e14711ed4d1e937bd7cd2b1e81bfeb7738d076b1d8737.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">삼성냉장고 상태좋습니다</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            부산 사상구 주례동
          </div>
    <div class="card-counts">
    <span>
                관심 8
              </span>
            ∙
            <span>
                채팅 21
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274024826" href="/articles/274024826">
    <div class="card-photo">
    <img alt="선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/6AA9F9BCC36E47CD2C1DFAE51969C435DA2EF4560A787DBDC74C256D41B8788C.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">선반</h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            경남 진주시 호탄동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 17
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273920668" href="/articles/273920668">
    <div class="card-photo">
    <img alt="안방그릴(연기안나는 전기그릴)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/21A48D6C5A5BE833055724CF260F8D21244EFE6220264012019B88019DBE33AA.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>
    <div class="card-price">
            100,000원
          </div>
    <div class="card-region-name">
            광주 서구 화정2동
          </div>
    <div class="card-counts">
    <span>
                관심 5
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274000811" href="/articles/274000811">
    <div class="card-photo">
    <img alt="숀리 바이크 실내자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/79FA3C4A067A48344D69C4EA48783F7D0135BA1B444D4E26BD0291162E37501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">숀리 바이크 실내자전거</h2>
    <div class="card-price">
            50,000원
          </div>
    <div class="card-region-name">
            경북 구미시 봉곡동
          </div>
    <div class="card-counts">
    <span>
                관심 1
              </span>
            ∙
            <span>
                채팅 6
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274011505" href="/articles/274011505">
    <div class="card-photo">
    <img alt="전자레인지" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3a720aea0080c736ae65e82644582af4f949e2801fe3043e141008a23e52e519.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">전자레인지</h2>
    <div class="card-price">
            7,000원
          </div>
    <div class="card-region-name">
            충남 천안시 동남구 신방동
          </div>
    <div class="card-counts">
    <span>
                관심 0
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273894828" href="/articles/273894828">
    <div class="card-photo">
    <img alt="알톤전기자전거" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/A4F7C5F656D7FB042486D22D0AA3F766792F3DA5A34ACA8413EAC0FBA1277499.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">알톤전기자전거</h2>
    <div class="card-price">
            300,000원
          </div>
    <div class="card-region-name">
            서울 동대문구 답십리동
          </div>
    <div class="card-counts">
    <span>
                관심 15
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273843713" href="/articles/273843713">
    <div class="card-photo">
    <img alt="이케아 철제 선반" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/18D633E7264B7B1FAEAE281432721888C9ABB644EBC530798B03B5474F31AC3E.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">이케아 철제 선반</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            경남 창원시 성산구 반림동
          </div>
    <div class="card-counts">
    <span>
                관심 14
              </span>
            ∙
            <span>
                채팅 22
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273956856" href="/articles/273956856">
    <div class="card-photo">
    <img alt="3인용소파" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/50aeabaf787472b725905babce0df5a53ba9360f01f058a965e6abb9943097bc.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3인용소파</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            부산 수영구 망미제2동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 8
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="274006145" href="/articles/274006145">
    <div class="card-photo">
    <img alt="에듀테이블" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/b45e21bdc0bffc0b97a27f284057fa7c55fae74f04cfe54e7268d2c5d6c84a36.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">에듀테이블</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            전북 전주시 덕진구 송천동2가
          </div>
    <div class="card-counts">
    <span>
                관심 3
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273860081" href="/articles/273860081">
    <div class="card-photo">
    <img alt="캠핑매트 에어포스 에어매트" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/e11104a3d21f69dba73a3429d5f348319325349cd58e070a7e0b0b4f5523ced6.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>
    <div class="card-price">
            150,000원
          </div>
    <div class="card-region-name">
            경기도 수원시 영통구 매탄1동
          </div>
    <div class="card-counts">
    <span>
                관심 11
              </span>
            ∙
            <span>
                채팅 2
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273935179" href="/articles/273935179">
    <div class="card-photo">
    <img alt="LG 냉장고 (566리터)" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/68efdee818ecd0546590913b7f611dded1ed835155af92384eda15c5141bac4b.webp?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">LG 냉장고 (566리터)</h2>
    <div class="card-price">
            70,000원
          </div>
    <div class="card-region-name">
            경기도 화성시 향남읍
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 12
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273892310" href="/articles/273892310">
    <div class="card-photo">
    <img alt="방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ " src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/565B9C7C477F683844CB4D39FC321CA7808E3754A2429953A20D11E009960C15.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>
    <div class="card-price">
            9,000원
          </div>
    <div class="card-region-name">
            서울 강남구 압구정동
          </div>
    <div class="card-counts">
    <span>
                관심 6
              </span>
            ∙
            <span>
                채팅 16
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273987830" href="/articles/273987830">
    <div class="card-photo">
    <img alt="아이두젠 헥사타프" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/0750A7891C444592553BA5A89BB630786D6BA4FC5BBCC65A017ADC4C3C50AC40.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">아이두젠 헥사타프</h2>
    <div class="card-price">
            20,000원
          </div>
    <div class="card-region-name">
            경기도 군포시 도마교동
          </div>
    <div class="card-counts">
    <span>
                관심 4
              </span>
            ∙
            <span>
                채팅 9
              </span>
    </div>
    </div>
    </a></article>
    <article class="card-top">
    <a class="card-link" data-event-label="273971674" href="/articles/273971674">
    <div class="card-photo">
    <img alt="3단 접이식 메트리스 팝니다" src="https://dnvefa72aowie.cloudfront.net/origin/article/202108/3E48CDE679DADCDA82154FB4785B7F2A1B32AB23FE3339AF0481F71533AC501D.jpg?q=82&amp;s=300x300&amp;t=crop"/>
    </div>
    <div class="card-desc">
    <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>
    <div class="card-price">
            10,000원
          </div>
    <div class="card-region-name">
            부산 강서구 명지1동
          </div>
    <div class="card-counts">
    <span>
                관심 9
              </span>
            ∙
            <span>
                채팅 4
              </span>
    </div>
    </div>
    </a></article>
    </section>
    <section id="hot-articles-go-download">
    <h3>
            더 구경하고 싶나요?
        </h3>
    <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>
    <div id="hot-articles-download-buttons">
    <a class="download-button" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" target="_blank">
    <div class="home-apple-store-bar-white"></div>
    <div class="download-text">App Store</div>
    </a> <a class="download-button" href="https://play.google.com/store/apps/details?id=com.towneers.www" target="_blank">
    <div class="home-google-play-bar-white"></div>
    <div class="download-text">Google Play</div>
    </a> </div>
    </section>
    </section>
    <script charset="utf-8" type="text/javascript">
      function changeRegion(key, value){
        var url_array
        if(window.location.pathname === "/hot_articles" && window.location.href.match(/\?/)) {
          url_array = window.location.href.split('?')[1].split(/(?:r1|&?r2)=/)
          url_array.unshift("")
        } else {
          url_array = window.location.pathname.split('/')
        }
        var keys = { r1: 2, r2: 3, r3: 4 }
        url_array[keys[key]] = value
        url_array[1] = 'region'
          if(key == 'r2' && decodeURI(url_array[2]) == "세종특별자치시") {
            url_array[4] = value
            url_array[3] = "_"
          }
        if(key == 'r1') { url_array.splice(3, 2) }
        if(key == 'r2' && url_array[3] !== "_") { url_array.splice(4, 1) }
        window.location.href = window.location.origin + url_array.join('/')
      }
    </script>
    <footer id="footer">
    <div class="footer-container">
    <div class="footer-top">
    <div class="footer-logo"></div>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="/trust">믿을 수 있는 중고거래</a></li>
    <li class="footer-list-item"><a class="link-highlight" href="https://cs.kr.karrotmarket.com/wv/faqs">자주 묻는 질문</a></li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a class="link-highlight" href="https://ad.daangn.com/" target="_blank">광고주센터</a></li>
    <li class="footer-list-item">
    <a class="ga-click" data-event-action="hot_articles" data-event-category="town_link_from" data-event-label="footer_town" href="https://town.daangn.com" target="_blank">동네가게</a>
    </li>
    </ul>
    <ul class="footer-list">
    <li class="footer-list-item"><a href="https://team.daangn.com/" target="_blank">회사 소개</a></li>
    <li class="footer-list-item"><a href="https://team.daangn.com/jobs/" target="_blank">채용</a></li>
    </ul>
    <ul class="footer-list policy">
    <li class="footer-list-item"><a href="https://policy.daangn.com/terms.html" target="_blank">이용약관</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/privacy.html" target="_blank">개인정보처리방침</a></li>
    <li class="footer-list-item"><a href="https://policy.daangn.com/location.html" target="_blank">위치기반서비스 이용약관</a></li>
    </ul>
    </div>
    <div class="footer-bottom">
    <div id="copyright">
    <ul class="copyright-list">
    <li class="copyright-list-item">고객문의 <a href="mailto:cs@daangnservice.com">cs@daangnservice.com</a></li>
    <li class="copyright-list-item">제휴문의 <a href="mailto:contact@daangn.com">contact@daangn.com</a></li>
    </ul>
    <ul class="copyright-list">
    <li class="copyright-list-item">지역광고 <a href="mailto:ad@daangn.com">ad@daangn.com</a></li>
    <li class="copyright-list-item">PR문의 <a href="mailto:pr@daangn.com">pr@daangn.com</a></li>
    </ul>
    <ul class="copyright-list copyright-list-light">
    <li class="copyright-list-item"><address>서울특별시 구로구 디지털로 30길 28 609호 (당근서비스)</address></li>
    <li class="copyright-list-item">사업자 등록번호 : 375-87-00088</li>
    <li class="copyright-list-item">직업정보제공사업 신고번호 : J1200020200016</li>
    </ul>
    <div id="social">
    <ul class="social-list">
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.facebook.com/daangn" target="_blank">
    <img alt="facebook" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-facebook-0563f4a93852d073b41f13b8bcabb03d47af3bb3a6755cdfedd8a73686c7f18c.svg"/>
    <span class="sr-only">facebook</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://www.instagram.com/daangnmarket/" target="_blank">
    <img alt="instagram" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-instagram-2f6c88a461597907c114b7ce28eab053fcae791ed26417915fefb6f7c9f95756.svg"/>
    <span class="sr-only">instagram</span>
    </a> </li>
    <li class="social-list-item">
    <a class="footer-social-link" href="https://blog.naver.com/daangn" target="_blank">
    <img alt="blog" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-blog-e1b0d512d1766a6962ec5bbb5b0803d2a6a9c55ad97db5ba9eebb76013caceba.svg"/>
    <span class="sr-only">blog</span>
    </a> </li>
    <li class="global-links">
    <img height="24" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/footer/icon-global-2f53678b428ec623cefd07a90dd7777f3e55fc0433918f645d7d75ace6ff1fc3.png" width="24"/>
    <select id="global-links-select">
    <option value="kr">한국</option>
    <option value="https://uk.karrotmarket.com">영국</option>
    <option value="https://ca.karrotmarket.com">캐나다</option>
    <option value="https://us.karrotmarket.com">미국</option>
    <option value="https://jp.karrotmarket.com">일본</option>
    </select>
    </li>
    </ul>
    </div>
    <div class="copyright-text">©Danggeun Market Inc.</div>
    </div>
    </div>
    </div>
    </footer>
    </body>
    </html>
    
    


```python
for d in soup.div.children:
    print(d)
```

    
    
    <h1 id="fixed-bar-logo-title">
    <a href="https://www.daangn.com/">
    <span class="sr-only">당근마켓</span>
    <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
    </a> </h1>
    
    
    <section id="fixed-bar-search">
    <div class="search-input-wrap">
    <span class="sr-only">검색</span>
    <input class="fixed-search-input" id="header-search-input" name="header-search-input" placeholder="동네 이름, 물품명 등을 검색해보세요!" type="text"/>
    <button id="header-search-button">
    <img alt="Search" class="fixed-search-icon" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/search-icon-7008edd4f9aaa32188f55e65258f1c1905d7a9d1a3ca2a07ae809b5535380f14.svg"/>
    </button>
    </div>
    </section>
    
    
    <section class="fixed-bar-menu">
    <div class="fixed-download-wrapper">
    <input class="fixed-checkbox" id="fixed-menu-checkbox" type="checkbox"/>
    <label class="fixed-label" for="fixed-menu-checkbox">
              다운로드
              <svg class="menu-icon-svg" fill="none" height="7" viewbox="0 0 12 7" width="12" xmlns="http://www.w3.org/2000/svg">
    <path d="M1 1L6 6L11 1" stroke="#4D5159" strokelinecap="round" strokelinejoin="round" strokewidth="1.5"></path>
    </svg>
    </label>
    <ul class="fixed-menu-ul">
    <li>
    <a class="menu-anchor" href="https://itunes.apple.com/kr/app/pangyojangteo/id1018769995?l=ko&amp;ls=1&amp;mt=8" id="header-download-button-ios" target="_blank">
    <img alt="App Store" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/apple-store-3a664174124650d63cae365bc55586fc5ff27b822b1b97788fc4af77d73d00c8.svg"/>
    <span>App Store</span>
    </a> </li>
    <li>
    <a class="menu-anchor" href="https://play.google.com/store/apps/details?id=com.towneers.www" id="header-download-button-android" target="_blank">
    <img alt="Google Play" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/google-play-c9ad0fc573cd01e2b982df5de6709a3d8d7cec8d9b58a5c08db7da0b92a32a75.svg"/>
    <span>Google Play</span>
    </a> </li>
    </ul>
    </div>
    <a href="https://chat.daangn.com" target="_blank">
    <button class="chat-button">
    <span class="button-text">당근채팅</span>
    <span class="button-beta">Beta</span>
    </button>
    </a>
    </section>
    
    
    


```python
print(soup.find_all("h2"))
```

    [<h2 class="card-title">삼성 제습기</h2>, <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>, <h2 class="card-title">마켓비 철제장수납장 드림</h2>, <h2 class="card-title">냉장고</h2>, <h2 class="card-title">다이슨 v8 청소기</h2>, <h2 class="card-title">철제선반</h2>, <h2 class="card-title">스팸팔아요~</h2>, <h2 class="card-title">lg 휘센 제습기</h2>, <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>, <h2 class="card-title">철제선반</h2>, <h2 class="card-title">컨테이너 하우스판매!!</h2>, <h2 class="card-title">전자레인지</h2>, <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>, <h2 class="card-title">3단 원목 수납장</h2>, <h2 class="card-title">자전거 팔아요!</h2>, <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>, <h2 class="card-title">철제선반입니다.</h2>, <h2 class="card-title">프리즘티비 65인지</h2>, <h2 class="card-title">alton bike 자전거 판매합니다</h2>, <h2 class="card-title">엘지냉장고 140리터</h2>, <h2 class="card-title">선반 오처넌에 가져가용</h2>, <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>, <h2 class="card-title">에어 컴프레셔 판매합니다</h2>, <h2 class="card-title">리락쿠마스프링카</h2>, <h2 class="card-title">전자렌지</h2>, <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>, <h2 class="card-title">캠핑 의자 팝니다.</h2>, <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>, <h2 class="card-title">자전거 팝니다</h2>, <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>, <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>, <h2 class="card-title">2~3인용 쇼파</h2>, <h2 class="card-title">파세코 Camp-27 난로</h2>, <h2 class="card-title">푸름이까꿍</h2>, <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>, <h2 class="card-title">전자렌지</h2>, <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>, <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>, <h2 class="card-title">냉동고 팔아요!</h2>, <h2 class="card-title">MTB 자전거 판매합니다</h2>, <h2 class="card-title">네스프레소 커피머신</h2>, <h2 class="card-title">아이패드 미니 2세대 32g</h2>, <h2 class="card-title">에어컨 수거해가시면 2만원</h2>, <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>, <h2 class="card-title">냉장고 팝니다</h2>, <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>, <h2 class="card-title">삼성 냉난방기</h2>, <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>, <h2 class="card-title">벤츠 골프백 판매합니다</h2>, <h2 class="card-title">신세계상품권</h2>, <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>, <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>, <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>, <h2 class="card-title">43인치 TV 팝니다</h2>, <h2 class="card-title">딤채 김치냉장고</h2>, <h2 class="card-title">프롬유 샤워핸들</h2>, <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>, <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>, <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>, <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>, <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>, <h2 class="card-title">신세계 상품권 만원</h2>, <h2 class="card-title">장인한과 파지약과</h2>, <h2 class="card-title">원목의자</h2>, <h2 class="card-title">엘지 드럼세탁기</h2>, <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>, <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>, <h2 class="card-title">수납 선반</h2>, <h2 class="card-title">그래픽카드 및 cpu</h2>, <h2 class="card-title">2인용 쇼파 </h2>, <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>, <h2 class="card-title">책장 무료드림</h2>, <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>, <h2 class="card-title">이케아 선반을 무료로 드려요</h2>, <h2 class="card-title">아람 자연이랑 전집 </h2>, <h2 class="card-title">알톤자전거21단</h2>, <h2 class="card-title">원룸 정리_ 책상,의자</h2>, <h2 class="card-title">전자렌지 팔아요</h2>, <h2 class="card-title">삼성냉장고 상태좋습니다</h2>, <h2 class="card-title">선반</h2>, <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>, <h2 class="card-title">숀리 바이크 실내자전거</h2>, <h2 class="card-title">전자레인지</h2>, <h2 class="card-title">알톤전기자전거</h2>, <h2 class="card-title">이케아 철제 선반</h2>, <h2 class="card-title">3인용소파</h2>, <h2 class="card-title">에듀테이블</h2>, <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>, <h2 class="card-title">LG 냉장고 (566리터)</h2>, <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>, <h2 class="card-title">아이두젠 헥사타프</h2>, <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>]
    


```python
soup.find_all(attrs={'class':'card-title'})
```




    [<h2 class="card-title">삼성 제습기</h2>,
     <h2 class="card-title">🎈4단 경량 서랍장 2EA</h2>,
     <h2 class="card-title">마켓비 철제장수납장 드림</h2>,
     <h2 class="card-title">냉장고</h2>,
     <h2 class="card-title">다이슨 v8 청소기</h2>,
     <h2 class="card-title">철제선반</h2>,
     <h2 class="card-title">스팸팔아요~</h2>,
     <h2 class="card-title">lg 휘센 제습기</h2>,
     <h2 class="card-title">★ 앤틱 사이드 미니 콘솔 / 협탁 /코너장 ★ </h2>,
     <h2 class="card-title">철제선반</h2>,
     <h2 class="card-title">컨테이너 하우스판매!!</h2>,
     <h2 class="card-title">전자레인지</h2>,
     <h2 class="card-title">삼천리 자전거 (아동용의자 포함)</h2>,
     <h2 class="card-title">3단 원목 수납장</h2>,
     <h2 class="card-title">자전거 팔아요!</h2>,
     <h2 class="card-title">가정용냉장고 오늘가저가시면 이만원</h2>,
     <h2 class="card-title">철제선반입니다.</h2>,
     <h2 class="card-title">프리즘티비 65인지</h2>,
     <h2 class="card-title">alton bike 자전거 판매합니다</h2>,
     <h2 class="card-title">엘지냉장고 140리터</h2>,
     <h2 class="card-title">선반 오처넌에 가져가용</h2>,
     <h2 class="card-title">게임용 컴퓨터 i5 4460 팝니다~</h2>,
     <h2 class="card-title">에어 컴프레셔 판매합니다</h2>,
     <h2 class="card-title">리락쿠마스프링카</h2>,
     <h2 class="card-title">전자렌지</h2>,
     <h2 class="card-title">접이식 캠핑 테이블 판매합니다</h2>,
     <h2 class="card-title">캠핑 의자 팝니다.</h2>,
     <h2 class="card-title">이케아 철제선반 묶음 판매합니다.</h2>,
     <h2 class="card-title">자전거 팝니다</h2>,
     <h2 class="card-title">조립형 PC CPU:I7-7700k 그래픽카드:GTX1060 6GB 판매</h2>,
     <h2 class="card-title">[일렉트로룩스] 전자레인지</h2>,
     <h2 class="card-title">2~3인용 쇼파</h2>,
     <h2 class="card-title">파세코 Camp-27 난로</h2>,
     <h2 class="card-title">푸름이까꿍</h2>,
     <h2 class="card-title">수박1통2~3kg 1통 3천원 2통5천원</h2>,
     <h2 class="card-title">전자렌지</h2>,
     <h2 class="card-title">편하게 쓰기 좋은 선반 수납장</h2>,
     <h2 class="card-title">디월트 임팩트드라이버 DCF887P2A 팝니다.</h2>,
     <h2 class="card-title">냉동고 팔아요!</h2>,
     <h2 class="card-title">MTB 자전거 판매합니다</h2>,
     <h2 class="card-title">네스프레소 커피머신</h2>,
     <h2 class="card-title">아이패드 미니 2세대 32g</h2>,
     <h2 class="card-title">에어컨 수거해가시면 2만원</h2>,
     <h2 class="card-title">한샘 원목 철제 책장 선반 수납장</h2>,
     <h2 class="card-title">냉장고 팝니다</h2>,
     <h2 class="card-title">딤채 김치냉장고 드립니다.</h2>,
     <h2 class="card-title">삼성 냉난방기</h2>,
     <h2 class="card-title">이케아 휠리스 선반(틈새선반, 화분 진열 등 사용 가능)</h2>,
     <h2 class="card-title">벤츠 골프백 판매합니다</h2>,
     <h2 class="card-title">신세계상품권</h2>,
     <h2 class="card-title">미사용 세제품 스타리온 업소용 냉동.냉장고 팝니다.</h2>,
     <h2 class="card-title">30인치 넘는 삼성 티비 팔아요</h2>,
     <h2 class="card-title">삼성32인치LED 티비겸모니터</h2>,
     <h2 class="card-title">43인치 TV 팝니다</h2>,
     <h2 class="card-title">딤채 김치냉장고</h2>,
     <h2 class="card-title">프롬유 샤워핸들</h2>,
     <h2 class="card-title">반석스포츠 아령 3kg/5kg 세트</h2>,
     <h2 class="card-title">갤럭시탭 s6 lite 판매합니다</h2>,
     <h2 class="card-title">몬테소리 레인보우 사운드 비즈 트리</h2>,
     <h2 class="card-title">갤럭시 노트 10 플러스 + 256기가 A급</h2>,
     <h2 class="card-title">캣폴(캣타워) 가또블랑코 하이엔드</h2>,
     <h2 class="card-title">신세계 상품권 만원</h2>,
     <h2 class="card-title">장인한과 파지약과</h2>,
     <h2 class="card-title">원목의자</h2>,
     <h2 class="card-title">엘지 드럼세탁기</h2>,
     <h2 class="card-title">캐리어 클라윈드 138L 냉장고</h2>,
     <h2 class="card-title">삼천리 자전거 20 스넬로 미니벨로</h2>,
     <h2 class="card-title">수납 선반</h2>,
     <h2 class="card-title">그래픽카드 및 cpu</h2>,
     <h2 class="card-title">2인용 쇼파 </h2>,
     <h2 class="card-title">i5-7500 32인치모니터 컴퓨터 셋트 팜니다</h2>,
     <h2 class="card-title">책장 무료드림</h2>,
     <h2 class="card-title">UHD TV  모델명UN65NU7050FXKR  내놓아요</h2>,
     <h2 class="card-title">이케아 선반을 무료로 드려요</h2>,
     <h2 class="card-title">아람 자연이랑 전집 </h2>,
     <h2 class="card-title">알톤자전거21단</h2>,
     <h2 class="card-title">원룸 정리_ 책상,의자</h2>,
     <h2 class="card-title">전자렌지 팔아요</h2>,
     <h2 class="card-title">삼성냉장고 상태좋습니다</h2>,
     <h2 class="card-title">선반</h2>,
     <h2 class="card-title">안방그릴(연기안나는 전기그릴)</h2>,
     <h2 class="card-title">숀리 바이크 실내자전거</h2>,
     <h2 class="card-title">전자레인지</h2>,
     <h2 class="card-title">알톤전기자전거</h2>,
     <h2 class="card-title">이케아 철제 선반</h2>,
     <h2 class="card-title">3인용소파</h2>,
     <h2 class="card-title">에듀테이블</h2>,
     <h2 class="card-title">캠핑매트 에어포스 에어매트</h2>,
     <h2 class="card-title">LG 냉장고 (566리터)</h2>,
     <h2 class="card-title">방탄소년단 굿즈 판매, 처분, 양도 합니다‼️ </h2>,
     <h2 class="card-title">아이두젠 헥사타프</h2>,
     <h2 class="card-title">3단 접이식 메트리스 팝니다</h2>]




```python
soup.find_all(['h1', 'p'])
```




    [<h1 id="fixed-bar-logo-title">
     <a href="https://www.daangn.com/">
     <span class="sr-only">당근마켓</span>
     <img alt="당근마켓" class="fixed-logo" src="https://d1unjqcospf8gs.cloudfront.net/assets/home/base/header/logo-basic-24b18257ac4ef693c02233bf21e9cb7ecbf43ebd8d5b40c24d99e14094a44c81.svg"/>
     </a> </h1>,
     <h1 class="head-title" id="hot-articles-head-title">
         
         
         중고거래 인기매물
       </h1>,
     <p>당근마켓 앱에서 따뜻한 거래를 직접 경험해보세요!</p>]




```python

```
