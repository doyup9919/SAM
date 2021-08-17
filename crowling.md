```python
from bs4 import BeautifulSoup

html = '''
<html>
    <table border=1> 
        <tr>
            <td> 항목 </td> 
            <td> 2013 </td> 
            <td> 2014 </td> 
            <td> 2015 </td>
        </tr> 
        <tr>
            <td> 매출액 </td> 
            <td> 100 </td> 
            <td> 200 </td>
            <td> 300 </td>
        </tr> 
    </table>
</html> 
'''
soup = BeautifulSoup(html, 'html5lib') 
result = soup.select('td') 
print(result)
```

    [<td> 항목 </td>, <td> 2013 </td>, <td> 2014 </td>, <td> 2015 </td>, <td> 매출액 </td>, <td> 100 </td>, <td> 200 </td>, <td> 300 </td>]
    


```python
from bs4 import BeautifulSoup

html = '''
<html>
    <table border=1> 
        <tr>
            <td> 항목 </td> 
            <td> 2013 </td> 
            <td> 2014 </td> 
            <td> 2015 </td>
        </tr> 
        <tr>
            <td> 매출액 </td> 
            <td> 100 </td> 
            <td> 200 </td>
            <td> 300 </td>
        </tr> 
    </table>
</html> 
'''
soup = BeautifulSoup(html, 'html5lib') 
result = soup.select('td:nth-of-type(1)') 
print(result)
```

    [<td> 항목 </td>, <td> 매출액 </td>]
    


```python
from bs4 import BeautifulSoup

html = '''
<ul>
    <li> 100 </li> 
    <li> 200 </li>
</ul> 
<ol>
    <li> 300 </li> 
    <li> 400 </li>
</ol>
'''
soup = BeautifulSoup(html, 'html5lib') 
result = soup.select('ul li')
print(result)
```

    [<li> 100 </li>, <li> 200 </li>]
    


```python
from bs4 import BeautifulSoup

html = '''
<ul>
    <li> 100 </li> 
    <li> 200 </li>
</ul> 
<ol>
    <li> 300 </li> 
    <li> 400 </li>
</ol>
'''
soup = BeautifulSoup(html, 'html5lib') 
result = soup.select('ul li')
for r in result: 
    print(r.text)
    
```

     100 
     200 
    


```python
import requests

response = requests.get("http://companyinfo.stock.naver.com/v1/company/c1010001.aspx?cmp_cd=035720")
print(response.text)
```

    
    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
    <html lang="ko">
    <head>
    	<title>온라인기업정보 - 기업모니터 - 기업개요(카카오)</title>
    	<link rel="shortcut icon" href="/favicon.ico" />
    	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
    	<script language="javascript" src="/include/domain.js" type="text/javascript"></script>
    	<!--[if (!IE) | (gt IE 8)]>
        	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />
        <![endif]-->
    	<!--[if IE 6]>
                <link href="/include/only_ie6.css" type="text/css" rel="stylesheet"/>
            <![endif]-->
    	<!--[if lt IE 8]>
                <link href="/include/lt_ie8.css" type="text/css" rel="stylesheet"/>
            <![endif]-->
    	<link href="/v1/include/css?v=q7Pq73b9jj00gmFmOVUSxzXv_5FtLNW9qxkqFwJqh-g1" rel="stylesheet"/>
    
    	<link href="/v1/include/css1?v=2Kc54WAY0-YKwI0WYHBphRe4FmbyttZ0_0A_hAhAjHc1" rel="stylesheet"/>
    
        <link href="/v1/include/csscrawler?v=6j20PRFQZOF_cQY1MTrT5fNOJtefGKtxcpjZjx7qRS01" rel="stylesheet"/>
    
    	<script src="/v1/include/js?v=U028CNZfaQK4QM5ihHTNuPdTF4Yf3vkW_HgPMgDaUrs1"></script>
    
    	<link href="/v1/include/sitecss?v=NO2scjWyURrcKuALmuSFc8_aZjVlTCHcs6O-cPNOjtk1" rel="stylesheet"/>
    
    	<!-- Global site tag (gtag.js) - Google Analytics -->
    	<script async src="https://www.googletagmanager.com/gtag/js?id=UA-74989022-7"></script>
    	<script>
    	  window.dataLayer = window.dataLayer || [];
    	  function gtag(){dataLayer.push(arguments);}
    	  gtag('js', new Date());
    
    	  gtag('config', 'UA-74989022-7');
    	</script>
    </head>
    <body oncontextmenu="return false">
    <div class="body-section">
    	<form id="Form1" method="post">
    		<div id="all_contentWrap">
    			<!--all_contentWrap-->
    			<div id="contentWrap">
    				<input type="hidden" id="printZone"><input type="hidden" id="cssZone">
    				<!-- search -->
    				<div id="header-menu">
    					<input name="hd_cmp_cd" type="hidden" id="hd_cmp_cd" value="035720" />
    					<input type="hidden" id="cmp_cd" />
    					<input type="hidden" id="hidCMP_CD" name="hidCMP_CD" value="035720" />
    					<input type="hidden" id="hiddenfinGubun" value="IFRSL" />
    					<input type="hidden" id="chartType" name="chartType" value="svg" />
    					<input type="hidden" id="rootImageUrl" name="rootImageUrl" value="http://companyinfo.stock.naver.com" />
    					
    <div class="wrapper-menu">
    	<span class="blank"></span>
    	<dl class="menu">
    		<dt class='on'><a href="../company/c1010001.aspx?cmp_cd=035720&cn=">기업현황</a> </dt>
    		<dt class=' line-left'><a href="../company/c1020001.aspx?cmp_cd=035720&cn=">기업개요</a></dt>
    		<dt class=' line-left'><a href="../company/c1030001.aspx?cmp_cd=035720&cn=">재무분석</a></dt>
    		<dt class=' line-left'><a href="../company/c1040001.aspx?cmp_cd=035720&cn=">투자지표</a></dt>
    		<dt class=' line-left'><a href="../company/c1050001.aspx?cmp_cd=035720&cn=">컨센서스</a></dt>
    		<dt class=' line-left'><a href="../company/c1060001.aspx?cmp_cd=035720&cn=">업종분석</a></dt>
    		<dt class=' line-left'><a href="../company/c1090001.aspx?cmp_cd=035720&cn=">섹터분석</a></dt>
    		<dt class=' line-left'><a href="../company/c1070001.aspx?cmp_cd=035720&cn=">지분현황</a></dt>
    		<dt class="right"><a class="print" href="javascript:winPrint('720');"><span class="icon-sprite icon-print"></span>인쇄</a></dt>
    	</dl>
    </div>
    <div class="table-menu-shadow"></div>
    
    				</div>
    				<div id="pArea" class="MinWidthContainer">
    					
    <div class="wrapper-table">
    	<div class="cmp-table-div">
    		<table class="cmp-table">
    			<tr class="cmp-table-row">
    				<td class="cmp-table-cell td0101">
    					<dl>
    						<dt>
    							<span class="name">카카오</span>
    							<a class="cEm" title="[홈페이지] www.kakaocorp.com" href="http://www.kakaocorp.com" target="comPage"><img src="/images/icon_home.gif" hspace="3" align="absmiddle"></a>
    							<a class="cEm" title="[대표전화] 1577-3321,1577-37 &#13;[주식담당] 02-6718-1082"><img src="/images/icon_tel.gif" hspace="1" align="absmiddle"></a>
    							<b class="num">035720</b>
    						</dt>
    						<dt class="line-left">Kakao</dt>
    						<dt class="line-left">KOSPI : 서비스업</dt>
    						<dt class="line-left">WICS : 양방향미디어와서비스</dt>
    					</dl>
    				</td>
    			</tr>
    			<tr class="cmp-table-row">
    				<td class="cmp-table-cell td0201">
    					<div>&nbsp;</div>
    				</td>
    			</tr>
    			<tr class="cmp-table-row">
    				<td class="cmp-table-cell td0301">
    					<dl>
    						
    						<dt>EPS <b class="num">687</b></dt>
    						<dt class="line-left">BPS <b class="num">15,428</b></dt>
    						<dt class="line-left">PER <b class="num">212.49</b></dt>
    						<dt class="line-left">업종PER <b class="num">8.50</b></dt>
    						<dt class="line-left">PBR <b class="num">9.46</b></dt>
    						<dt class="line-left">현금배당수익률 <b class="num">0.02%</b></dt>
    						<dt class="right">12월 결산</dt>
    						
    					</dl>
    				</td>
    			</tr>
    		</table>
    	</div>
    </div>
    <div class="exp">
    	<dl>
    		<dt class="left">* <b>PER</b>: 전일 보통주 수정주가 / 최근 분기 EPS(TTM)</dt>
    		<dt class="right">* <b>현금배당수익률</b>: 최근 결산 수정DPS(현금) / 전일 보통주 수정주가</dt>
    		<dt class="left">* <b>PBR</b>: 전일 보통주 수정주가 / 최근 분기 BPS(TTM)</dt>
    		<dt class="right">* <b>WICS</b>: WISE Industry Classification Standard, modified by FnGuide</dt>
    		<dt class="left">* <b>TTM</b>: 최근 4분기 합산</dt>
    		<dt class="right">* TTM 데이터가 없는 경우, 최근 결산 데이터로 표시됩니다.</dt>
    		<dt class="clear">* PER, PBR값이 (-)일 경우, N/A로 표기됩니다.</dt>
    	</dl>
    </div>
    
    					<div class="PageContainer">
    						<div class="PageContentContainer">
    							<div id="wrapper" class="all">
    								<!-- wrapper -->
    								<!-- company info -->
    								<h5 class="blind">요약정보</h5>
    								<div class="wrapper-row">
    									<div class="fl_le half">
    										<div class="header-table">
    											<dl class="header-table-row">
    												<dd class="header-table-cell"><h5><span>시세</span> 및 주주현황</h5></dd>
    												<dd class="header-table-cell unit">
    													<p>[기준:2021.08.13]</p>
    												</dd>
    											</dl>
    										</div>
    										<div class="body">
    											<table class="gHead" id="cTB11" summary="기업의 기본적인 시세정보(주가/전일대비/수익률,52주최고/최저,액면가,거래량/거래대금,시가총액,유동주식비율,외국인지분율,52주베타,수익률(1M/3M/6M/1Y))를 제공합니다.">
    												<caption class="blind">시세정보</caption>
    												<colgroup>
    													<col width="125" />
    													<col width="*" />
    												</colgroup>
    												<tbody>
    													<tr>
    														<th scope="row" class="txt">주가/전일대비/수익률</th>
    														<td class="num"><strong>
    															146,000</strong>원 /
    														<span class="cDn">-1,500원</span> / <span class="cDn">-1.02%</span>
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">52Weeks 최고/최저</th>
    														<td class="num">
    															173,000원 /
    														64,900원
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">액면가</th>
    														<td class="num">
    															100원
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">거래량/거래대금</th>
    														<td class="num">
    															2,285,990주 /
    														3,332억원
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">시가총액</th>
    														<td class="num">
    															649,272억원
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">52주베타</th>
    														<td class="num">
    															0.94
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">발행주식수/유동비율</th>
    														<td class="num">
    															444,707,140주 / 72.97%
    														</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt">외국인지분율</th>
    														<td class="num">
    															31.65%</td>
    													</tr>
    													<tr>
    														<th scope="row" class="txt noline-bottom">수익률 <span class="span-sub">(1M/3M/6M/1Y)</span></th>
    														<td class="num noline-bottom">
    															<span class="cDn">-9.32%</span>/ <span class="cUp">+33.33%</span>/ <span class="cUp">+49.13%</span>/ <span class="cUp">+102.50%</span>
    														</td>
    													</tr>
    												</tbody>
    											</table>
    											<dl class="annotation anno01">
    												<dd class="section01 cursor">
    													<ul>
    														<li>* 수정주가(차트포함), 보통주 기준, * 52주베타: 주간수익률 기준</li>
    													</ul>
    												</dd>
    
    											</dl>
    										</div>
    									</div>
    									<div class="fl_ri half">
    										<div class="header-table empty"></div>
    										<div class="body">
    											<div class='gHead' id='gHeadCt1'>
    												<h6 class="spanCT">주가/상대수익률</h6>
    												<div style="position:absolute; top:-2px; right:10px;">
    													<a class="btn_chart icon-sprite icon-chart1 on" data-flag="2" title="수정주가/상대수익률">주가/상대수익률</a>
    													<a class="btn_chart icon-sprite icon-chart2" data-flag="1" title="주가/거래대금">주가/거래대금</a>
    													<a class="btn_chart icon-sprite icon-chart3" data-flag="3" title="외국인지분율/기관1개월누적순매수">외국인지분율/기관1개월누적순매수</a>
    												</div>
    												<a href="#cTB12" class="blind" style="float: right"><strong>차트 건너뛰기</strong>"데이터를 차트로 제공하고 있습니다. 차트를 건너뛰고 싶은 경우 이 링크를 선택하시기 바랍니다."</a>
    												<div id='stock_price_relative_chart' class='chart-container full'></div>
    											</div>
    										</div>
    									</div>
    								</div>
    								<div class="clr"></div>
    								<div>
    									<div class="fl_le half">
    										<table class="gHead01 all-width" id="cTB12" summary="기업의 신용등급정보(BOND, CP)를 제공합니다." tabindex="0">
    											<caption class="blind">신용등급, BOND, CP 목록</caption>
    											<colgroup>
    												<col />
    												<col />
    												<col />
    											</colgroup>
    											<thead>
    												<tr>
    													<th scope="col" class="line">신용등급</th>
    													<th scope="col" class="line">BOND</th>
    													<th scope="col" class="endLine">CP</th>
    												</tr>
    											</thead>
    											<tbody>
    												
    														<tr>
    															<td class="line center">KIS</td>
    															<td class="line center">AA- &nbsp;[20201208]</td>
    															
    															<td class="noline-right center"> &nbsp;</td>
    														</tr>
    													
    														<tr>
    															<td class="line center">KR</td>
    															<td class="line center">AA- &nbsp;[20201130]</td>
    															
    															<td class="noline-right center"> &nbsp;</td>
    														</tr>
    													
    														<tr>
    															<td class="line center">NICE</td>
    															<td class="line center"> &nbsp;</td>
    															
    															<td class="noline-right center"> &nbsp;</td>
    														</tr>
    													
    														<tr>
    															<td class="line center"></td>
    															<td class="line center"> &nbsp;</td>
    															
    															<td class="noline-right center"> &nbsp;</td>
    														</tr>
    													
    											</tbody>
    										</table>
    									</div>
    									<div class="fl_ri half top_disc">
    										<div class="header-table">
    											<table class="cmp-table" style="width:100%">
    												<tr class="cmp-table-row">
    													<td class="cmp-table-cell unit" style="*margin-top:-2px;padding-right:0">[기준: 2021.08.13]</td>
    												</tr>
    											</table>
    										</div>
    										<table class="gHead01 all-width" id="cTB13" summary="기업의 주요주주의 보유 주식 수 및 (%) 정보를 제공합니다.">
    											<caption class="blind">주요주주명, 보유주식수(보통주), 보유지분(%) 목록</caption>
    											<colgroup>
    												<col width="45%" />
    												<col width="30%" />
    												<col width="25%" />
    											</colgroup>
    											<thead>
    												<tr>
    													<th scope="col" class="line">주요주주</th>
    													<th scope="col" class="line">보유주식수<span class="span-sub">(보통)</span></th>
    													<th scope="col" class="endLine">보유지분<span class="span-sub">(%)</span></th>
    												</tr>
    											</thead>
    											<tbody>
    												
    														<tr class="p_sJJ10">
    															<td class="line txt" title="김범수 외 65인">
    																<span class="cut"><a class='btn_moreE sJJ' data-nm='김범수' data-grp=10><span class='icon-sprite icon-moreE'>김범수 외 65인</span></a> 김범수 외 65인</span>
    															</td>
    															<td class="line num">107,867,853&nbsp;</td>
    															<td class="noline-right num">24.26&nbsp;</td>
    														</tr>
    													
    														<tr class="p_sJJ20">
    															<td class="line txt" title="국민연금공단">
    																<span class="cut"><span style='width:15px; display:inline-block'>&nbsp;</span>국민연금공단</span>
    															</td>
    															<td class="line num">37,386,875&nbsp;</td>
    															<td class="noline-right num">8.41&nbsp;</td>
    														</tr>
    													
    														<tr class="p_sJJ20">
    															<td class="line txt" title="MAXIMO PTE">
    																<span class="cut"><span style='width:15px; display:inline-block'>&nbsp;</span>MAXIMO PTE</span>
    															</td>
    															<td class="line num">27,999,245&nbsp;</td>
    															<td class="noline-right num">6.30&nbsp;</td>
    														</tr>
    													
    														<tr class="p_sJJ20">
    															<td class="line txt" title="BlackRock Fund Advisors 외 12인">
    																<span class="cut"><a class='btn_moreE sJJ' data-nm='BlackRock Fund Advisors' data-grp=20><span class='icon-sprite icon-moreE'>BlackRock Fund Advisors 외 12인</span></a> BlackRock Fund Advisors 외 12인</span>
    															</td>
    															<td class="line num">22,984,815&nbsp;</td>
    															<td class="noline-right num">5.17&nbsp;</td>
    														</tr>
    													
    											</tbody>
    										</table>
    										<script type="text/template" id="tmpl-sJJ">
    											<@ _.each(data, function(v, i){ @>
    											<tr class="c_sJJ<@= grp_cd @> c_sJJ">
    												<td class="line txt"><span class="cut" title="<@= v.NEBUNA @>"><@= v.NEBUNA @></span></td>
    												<td class="line num"><@= formatCurrency_price(v.VOLHSU, 0) @></td>
    												<td class="noline-right num"><@= formatCurrency_price(v.VOLHBI, 2) @></td>
    											</tr>
    											<@})@>
    										</script>
    										<p class="disc table">* 보유지분 : 보유지분주식수/지수산정주식수*100 </p>
    									</div>
    								</div>
    								<div class="tit-empty"></div>
    								<div class="all-width">
    									<div class="header-table">
    										<dl class="header-table-row">
    											<dd class="header-table-cell">
    												<h5><span>기업개요</span></h5>
    											</dd>
    											<dd class="header-table-cell unit">
    												<p>[기준:2021.06.30]</p>
    											</dd>
    										</dl>
    									</div>
    									<div class="cmp_comment">
    										<ul class="dot_cmp">
    											
    											<li class="dot_cmp" data-cd="035720">동사는 2017년 7월 10일에 유가증권시장에 신규상장하였으며 메신저, 포털, 커머스, 모빌리티, 핀테크 등 다양한 서비스를 제공함.</li>
    											
    											<li class="dot_cmp" data-cd="035720">신규사업 개발사 다음글로벌홀딩스, 컴퓨터, 멀티미디어 프로그램 개발, 제조, 판매사 디케이테크인 등의 기업을 연결대상 종속회사로 보유함.</li>
    											
    											<li class="dot_cmp" data-cd="035720">자회사인 카카오페이가 2020년 상반기 카카오페이증권을 선보임. 카카오게임즈는 2020년 9월 코스닥시장에 상장함.</li>
    											
    										</ul>
    									</div>
    								</div>
    								<div class="tit-empty"></div>
    								<h5><span>펀더멘털</span></h5>
    								<div class="fund fl_le">
    									<table class="gHead03" summary="기업 펀더멘털 실적, 컨센서스 정보 리스트입니다.PER, PBR, PCR, EV/EBITDA, EPS, BPS, EBITDA, 현금DPS, 현금배당수익률, 회계기준에 대해서 보여주는 리스트입니다.">
    										<caption class="blind">주요지표, 
    										2020/12(실적), 
    										2021/12(컨센서스)
    										</caption>
    										<colgroup>
    											<col width="34%" />
    											<col width="33%" />
    											<col width="33%" />
    										</colgroup>
    										<thead>
    											<tr>
    												<th style="padding-left:0; padding-right:0">주요지표</th>
    												<th style="padding-left:0; padding-right:0">2020/12(A)</th>
    												<th style="padding-left:0; padding-right:0" class="endLine">2021/12(E)</th>
    											</tr>
    										</thead>
    										<tbody>
    											
    											<tr>
    												<th class="left" scope="row">PER</th>
    												<td class="num">410.93</td>
    												<td class="num noline-right">66.96</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">PBR</th>
    												<td class="num">9.97</td>
    												<td class="num noline-right">8.57</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">PCR</th>
    												<td class="num">65.85</td>
    												<td class="num noline-right">48.53</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">EV/EBITDA</th>
    												<td class="num">86.07</td>
    												<td class="num noline-right">53.74</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">EPS</th>
    												<td class="num">355원</td>
    												<td class="num noline-right">2,180원</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">BPS</th>
    												<td class="num">14,647원</td>
    												<td class="num noline-right">17,042원</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">EBITDA</th>
    												<td class="num">7,223.1억원</td>
    												<td class="num noline-right">11,340.3억원</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">현금DPS</th>
    												<td class="num">30원</td>
    												<td class="num noline-right">32원</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">현금배당수익률</th>
    												<td class="num">0.02%</td>
    												<td class="num noline-right">0.02%</td>
    											</tr>
    											
    											<tr>
    												<th class="left" scope="row">회계기준</th>
    												<td class="num">연결</td>
    												<td class="num noline-right">연결</td>
    											</tr>
    											
    										</tbody>
    									</table>
    									<dl class="annotation mb-16">
    										<dd class="section01 cursor">
    											<ul>
    												<li>* (A)는 실적, (E)는 컨센서스</li>
    											</ul>
    										</dd>
    										<dd class="section02">
    											<ul>
    												<li>* 컨센서스 : 최근 3개월간 증권사 발표 추정치의 평균</li>
    												<li>* 지표 계산 시 주가 : 전 영업일 보통주 수정주가</li>
    												<li>* 연결 기업의 당기순이익 및 자본총계는 지배주주 기준</li>
    											</ul>
    										</dd>
    										<dd class="section03"><a href="javascript:;" class="off"></a></dd>
    									</dl>
    								</div>
    								<div class="fund fl_ri">
    									<table class="gHead03" id="earning_list" summary="기업 펀더멘털 어닝스프라이즈 정보 리스트입니다. 재무연월 별 영업이익, 당기순이익에 대한 컨센서스, 잠정치, Suprise, 전년동기대비 정보를 보여주는 리스트입니다.">
    										<caption class="blind">어닝서프라이즈</caption>
    										<colgroup>
    											<col width="18%" />
    											<col width="26%" />
    											<col width="28%" />
    											<col width="28%" />
    										</colgroup>
    										<thead>
    											<tr>
    												<th colspan="4" class="endLine colname">
    													<span class="fl_le">어닝서프라이즈</span>
    													<span class="fl_ri span-sub">* 단위: 억원, %</span>
    												</th>
    											</tr>
    										</thead>
    										<tbody>
    										</tbody>
    									</table>
    									<dl class="annotation mb-16">
    										<dd class="section01 cursor">
    											<ul>
    												<li>* 연결 재무제표: 당기순이익 잠정치에서 ○는 전체, ●는 지배주주 기준</li>
    											</ul>
    										</dd>
    										<dd class="section02">
    											<ul>
    												<li>* 해당 기간의 회계기준은 </li>
    												<li>
    													<ul class="number">
    														<li>최초 공시 된 잠정치 기준 (잠정치 미발표시, 실적 기준)</li>
    														<li>잠정치를 별도/연결 동시 발표할 경우, 주 재무제표 기준</li>
    														<li>별도/연결 한쪽만 발표할 경우, 잠정치의 재무제표 회계기준을 따름</li>
    													</ul>
    												</li>
    											</ul>
    										</dd>
    										<dd class="section03"><a href="javascript:;" class="off"></a></dd>
    									</dl>
    								</div>
    								<script type="text/template" id="tmpl-list">
    									<tr>
    										<th colspan="2" class="center">재무연월</th>
    										<@ _.each(yymm, function(v, i){ if(i!=0){ @>
    										<th class="<@= i==yymm.length-1?'noline-right':'' @> center"><@= RegDT(v, 0, "/") @></th>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class='ext-tit center' rowspan="4">영업이익</th>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span>컨센서스</th>
    										<@ _.each(data[0], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 1)  @></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span>잠정치</th>
    										<@ _.each(data[1], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 1)  @></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span><b>Surprise</b></th>
    										<@ _.each(data[2], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @> <@= v <0 ? 'cDn':'cUp'@>"><b><@= formatCurrency_price(v, 2)  @></b></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class="left"><a class="btn_moreE earn"><span class="icon-sprite icon-moreE">전분기대비보기</span></a> 전년동기대비</th>
    										<@ _.each(data[3], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 2)  @></td>
    										<@}})@>
    									</tr>
    									<tr class="ext0">
    										<th style="border-top:none;"></th>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span>전분기대비</th>
    										<@ _.each(data[4], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 2) @></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class='ext-tit  center' rowspan="4">당기순이익</th>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span>컨센서스</th>
    										<@ _.each(data[5], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 1)  @></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span>잠정치</th>
    										<@ _.each(data[6], function(v, i){ if(i!=1){ @>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= v==null?"":(type[i - 1]==0?"○ ":"● ") @> <@=  formatCurrency_price(v, 1)   @></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span><b>Surprise</b></th>
    										<@ _.each(data[7], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @> <@= v <0 ? 'cDn':'cUp'@>"><b><@= formatCurrency_price(v, 2)  @></b></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th class="left"><a class="btn_moreE earn"><span class="icon-sprite icon-moreE">전분기대비보기</span></a> 전년동기대비</th>
    										<@ _.each(data[8], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 2)  @></td>
    										<@}})@>
    									</tr>
    									<tr class="ext0">
    										<th style="border-top:none;"></th>
    										<th class="left"><span style="width: 12px; display: inline-block">&nbsp;</span>전분기대비</th>
    										<@ _.each(data[9], function(v, i){ if(i!=1){@>
    										<td class="num <@= i==yymm.length?'noline-right':'' @>"><@= formatCurrency_price(v, 2) @></td>
    										<@}})@>
    									</tr>
    									<tr>
    										<th colspan="2" style="padding-left: 0; text-align: center">잠정치발표(예정)일/회계기준</th>
    										<@ _.each(yymmdd, function(v, i){ if(i!=0){@>
    										<td class="<@= i==yymmdd.length-1?'noline-right':'' @>  line"><@= v @></td>
    										<@}})@>
    									</tr>
    								</script>
    
    								<div class="clr"></div>
    								<!--밴드차트-->
    								<div id="band-chart-section">
    									<table class="schbox">
    										<tr>
    											<td class="c1 left">
    												<h5 class="bg6"><span>밴드차트</span></h5>
    											</td>
    											<td class="c2 right" style="vertical-align:top">
    												<label for="bandChartGubun" class="blind">밴드차트</label>
    												<select id="bandChartGubun" name="bandChartGubun" title="재무제표 종류선택(주재무제표,K-IFRS(별도/연결),K-GAAP(개별/연결))">
    													<option value="MAIN">주재무제표</option>
    													<option value="IFRSS">K-IFRS(별도)</option>
    													<option value="IFRSL">K-IFRS(연결)</option>
    													<option value="GAAPS">K-GAAP(개별)</option>
    													<option value="GAAPL">K-GAAP(연결)</option>
    												</select>
    											    <a href="javascript:;" title="검색" id="hbandChartGubun" class="btn_search"><span>검색</span></a>
    											</td>
    										</tr>
    									</table>
    									<div class="half fl_le">
    										<div class='gHead' id='gHeadCt4'>
    											<h6 class="spanCT">PER 차트</h6>
    											<a href="#sct5" class="blind"><strong>차트 건너뛰기</strong>"데이터를 차트로 제공하고 있습니다. 차트를 건너뛰고 싶은 경우 이 링크를 선택하시기 바랍니다."</a>
    											<div id="per-chart" class='chart-container'></div>
    										</div>
    									</div>
    									<div class="half fl_ri">
    										<div class='gHead' id='gHeadCt5'>
    											<h6 class="spanCT">PBR 차트</h6>
    											<a href="#fingubun_text" class="blind"><strong>차트 건너뛰기</strong>"데이터를 차트로 제공하고 있습니다. 차트를 건너뛰고 싶은 경우 이 링크를 선택하시기 바랍니다."</a>
    											<div id="pbr-chart" class='chart-container'></div>
    										</div>
    									</div>
    								</div>
    								<div class="clr"></div>
    								<!--밴드차트-->
    
    								<div class="tit-empty"></div>
    								<!-- Financial Summary -->
    								<table class="schbox" id="finSummary">
    									<tr>
    										<td class="c1 left">
    											<h5 id="finsum_more"><span>Financial</span> Summary</h5>
    										</td>
    										<td class="c2 right"  style="vertical-align:top">
    											<select name="finGubun" id="finGubun" title="재무기준선택(주재무제표,K-IFRS(별도/연결),K-GAAP(개별/연결))">
    												<option value="MAIN">주재무제표</option>
    												<option value="IFRSS">K-IFRS(별도)</option>
    												<option value="IFRSL">K-IFRS(연결)</option>
    												<option value="GAAPS">K-GAAP(개별)</option>
    												<option value="GAAPL">K-GAAP(연결)</option>
    											</select>
    											<a href="javascript:;" title="검색" class="btn_search"><span id="btnSearch">검색</span></a>
    											<a href="javascript:;" title="도움말 새창열기" onclick="Cmd_Help_IFRS();" class="btn_etc">IFRS<span class="icon-sprite icon-question"></span></a>
    											<a id="hcalText" href="javascript:;" title="레이어로 재무계정 도움말창 열기" class="btn_etc kor">산식<span class="icon-sprite icon-question"></span></a>
    											
    										</td>
    										<td class="right" style="vertical-align:bottom;padding-bottom: 5px;">
    											<span id="unit_text">* 단위 : 억원, %, 배, 주 <span style='cursor: pointer;' class='unit_text' title="당기 누적에서 직전 분기 누적을 차감한 금액입니다.">&nbsp;&nbsp;&nbsp;&nbsp;* 분기: 순액기준</span></span>
    										</td>
    									</tr>
    								</table>
    								<div id="calculateArea">
    									<div id="draggable-section">
    										<table class="all-width" summary="재무용어에 대한 설명(재무계정명,상세기준)을 제공합니다.">
    											<caption class="blind">재무산식</caption>
    											<colgroup>
    												<col class="col1" />
    												<col class="col2" />
    											</colgroup>
    											<thead>
    												<tr>
    													<th scope="col" class="col1">항목명</th>
    													<th scope="col" class="col2">
    														<div id="column-left">상세기준</div>
    													</th>
    												</tr>
    											</thead>
    											<tbody>
    												<tr>
    													<th scope="row" class="col1">CAPEX</th>
    													<td class="col2">유형자산의증가</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">FCF</th>
    													<td class="col2">영업활동으로인한현금흐름-CAPEX</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">이자발생부채</th>
    													<td class="col2">단기사채+단기차입금+유동성장기부채+단기금융부채+사채+장기차입금+장기금융부채</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">영업이익률</th>
    													<td class="col2">영업이익/매출액(수익)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">순이익률</th>
    													<td class="col2">당기순이익/매출액(수익)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">ROE</th>
    													<td class="col2">(지배주주지분)당기순이익[당기]/((지배주주지분)자본총계[당기]+(지배주주지분)자본총계[전기])/2)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">ROA</th>
    													<td class="col2">당기순이익[당기]/(자산총계[당기]+자산총계[전기]/2)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">부채비율</th>
    													<td class="col2">부채총계/자본총계</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">자본유보율</th>
    													<td class="col2">(자본잉여금+이익잉여금)/자본금</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">EPS</th>
    													<td class="col2">(지배주주지분)당기순이익*1000/수정평균발행주식수(보통주+우선주)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">PER</th>
    													<td class="col2">보통주수정주가(기말)/EPS</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">BPS</th>
    													<td class="col2">(지배주주지분)자본총계/수정기말발행주식수(보통주+우선주, 자사주차감)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">PBR</th>
    													<td class="col2">보통주수정주가(기말)/BPS</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">수정DPS</th>
    													<td class="col2">DPS에 자본금변동이벤트 시 수정계수가 발생하는 경우 수정계수를 적용</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">현금배당수익률</th>
    													<td class="col2">수정DPS/보통주수정주가(기말)</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">현금배당성향</th>
    													<td class="col2">현금배당액(전체)/(지배주주지분)당기순이익</td>
    												</tr>
    												<tr>
    													<th scope="row" class="col1">발행주식수</th>
    													<td class="col2">보통주 기말발행주식수 (자본금 변동 이벤트 중 수정계수가 발생하는 경우 과거 데이터가 소급됨)</td>
    												</tr>
    											</tbody>
    										</table>
    										<div id="btn-close"><a id="hbtn-close" href="javascript:;" title="산식닫기"><span class="icon-sprite icon-layer-x">산식닫기</span></a></div>
    									</div>
    								</div>
    								<table class="schtab" id="cTB00">
    									<tr>
    										<td class="c0 tabstart"></td>
    										<td class="c1 center on" id="cns_td20">
    											<a href="javascript:;" id="cns_Tab20" title="분기">전체</a>
    										</td>
    										<td class="c2 center off" id="cns_td21">
    											<a href="javascript:;" id="cns_Tab21" title="연간">연간</a>
    										</td>
    										<td class="c3 center off" id="cns_td22">
    											<a href="javascript:;" id="cns_Tab22" title="분기">분기</a>
    										</td>
    										<td class="c4 tabspace"></td>
    										<td class="c5 tabend"></td>
    									</tr>
    								</table>
    								
                                    <div id="RVArcVR1a2"></div>
    
    								<div class="gibun_exp7_1 all clr">
    									
    								</div>
    								<dl class="annotation mb-16">
    									<dd class="section01 cursor">
    										<ul>											
    											<li>* 분기 ROE/ROA/PER/PBR은 직전 4개 분기 데이터로 연환산 하여 산출</li>
    											<li>* 영업이익 = 매출액 - 매출원가 - 판매비와관리비</li>
    											<li>* 재무실적은 주석반영 및 검수 후 업데이트 되며 결산은 공시 후 일주일, 분/반기는 약 15일 정도 소요됨</li>
    										</ul>
    									</dd>
    									<dd class="section02">
    										<ul>
    											<li>(금융업의 경우 지연될 수 있음)</li>
    										</ul>
    									</dd>
    									<dd class="section03"><a href="javascript:;" class="off"></a></dd>
    								</dl>
    								<!-- Financial Summary -->
    								<div class="tit-empty"></div>
    								<!--투자의견 컨센서스-->
    								<div class="all-width">
    									<div class="header-table">
    										<dl class="header-table-row">
    											<dd class="header-table-cell">
    												<h5><span>투자의견</span> 컨센서스</h5>
    											</dd>
    											<dd class="header-table-cell unit">
    												<p>[기준:2021.08.13]</p>
    											</dd>
    										</dl>
    									</div>
    									<table class="gHead all-width" id="cTB15" summary="투자의견에 대한 컨센서스의 위치를 그림으로 보여주고, 투자의견값,목표주가,EPS,PER,PBR,추정기관정보를 제공합니다.">
    										<caption class="blind">투자의견컨센서스</caption>
    										<colgroup>
    											<col class="c1" />
    											<col class="c2" />
    											<col class="c3" />
    											<col class="c4" />
    											<col class="c5" />
    											<col class="c6" />
    										</colgroup>
    										<tr>
    											<td class="line-right noline-bottom center" rowspan="2">
    												<div id="pointerBG">
    													<span id="pointer" style="LEFT: 70.9474%"></span><span id="pointerVal" class="cUp num" style="LEFT: 70.9474%">3.95</span>
    													<br />
    													<img height="25" src="/images/graph_bar.gif" alt="투자의견 컨센서스 그래프(강력매도1|매도2|중립3|매수4|강력매수5), 값:3.95" usemap="#imgmap" />
    													<map id="imgmap" name="imgmap">
    														<area shape="rect" coords="0,0,60,17" alt="강력매도" title="강력매도">
    														<area shape="rect" coords="60,0,120,17" alt="매도" title="매도">
    														<area shape="rect" coords="120,0,180,17" alt="중립" title="중립">
    														<area shape="rect" coords="180,0,240,17" alt="매수" title="매수">
    														<area shape="rect" coords="240,0,300,17" alt="강력매수" title="강력매수">
    													</map>
    												</div>
    											</td>
    											<th scope="col" class="line">투자의견</th>
    											<th scope="col" class="line">목표주가<span class="span-sub">(원)</span></th>
    											<th scope="col" class="line">EPS<span class="span-sub">(원)</span></th>
    											<th scope="col" class="line">PER<span class="span-sub">(배)</span></th>
    											<th class="noline-right" scope="col">추정기관수</th>
    										</tr>
    										
    												<tr>
    													<td class="noline-bottom line-right center cUp">
    														<b>3.95</b>
    													</td>
    													<td class="noline-bottom line-right center">178,421</td>
    													<td class="noline-bottom line-right center">2,180</td>
    													<td class="noline-bottom line-right center">66.96</td>
    													<td class="noline-bottom center">19</td>
    												</tr>
    											
    									</table>
    								</div>
    								<div class="tit-empty"></div>
    								<div class='fl_le half'>
    									<div class='gHead' id='gHeadCt2'>
    										<h6 class="spanCT">투자의견 및 목표주가</h6>
    										<a href="#sct3" class="blind"><strong>차트 건너뛰기</strong>"데이터를 차트로 제공하고 있습니다. 차트를 건너뛰고 싶은 경우 이 링크를 선택하시기 바랍니다."</a>
    										<div id='opinion_targetPrice' class='chart-container'>
    										</div>
    									</div>
    								</div>
    								<div class='fl_ri half'>
    									<div class='gHead' id='gHeadCt3'>
    										<h6 class="spanCT">투자의견 분포</h6>
    										<a href="#cTB24" class="blind"><strong>차트 건너뛰기</strong>"데이터를 차트로 제공하고 있습니다. 차트를 건너뛰고 싶은 경우 이 링크를 선택하시기 바랍니다."</a>
    										<div id='opinion' class='chart-container'>
    										</div>
    									</div>
    								</div>
    								<div class="clr"></div>
    								<table class="gHead01 all-width" id="cTB24" summary="제공처별로 최근일자순으로 목표가, 직전목표가, 변동률, 투자의견, 직전투자의견을 제공합니다." tabindex="0">
    									<caption class="blind">제공처별 투자의견 및 목표주가, 변동률 목록</caption>
    									<colgroup>
    										<col width="120" />
    										<col width="90" />
    										<col width="*" span="2" />
    										<col width="82" />
    										<col width="115" span="2" />
    									</colgroup>
    									<thead>
    										<tr>
    											<th scope="col" class="line">제공처</th>
    											<th scope="col" class="line">최종일자</th>
    											<th scope="col" class="line">목표가</th>
    											<th scope="col" class="line">직전목표가</th>
    											<th scope="col" class="line">변동률<span class="span-sub">(%)</span></th>
    											<th scope="col" class="line">투자의견</th>
    											<th scope="col" class="endLine">직전투자의견</th>
    										</tr>
    									</thead>
    									<tbody>
    										
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">IBK투자</td>
    													<td class="line center">21/08/11</td>
    													<td class="line num">176,000</td>
    													<td class="line num">134,000</td>
    													<td class="line num"><span class="cBk">31.34</span></td>
    													<td class="line center" title="매수">매수</td>
    													<td class="noline-right center" style="position: relative;" title="매수">매수</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">교보</td>
    													<td class="line center">21/08/10</td>
    													<td class="line num">190,000</td>
    													<td class="line num">190,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="Buy">Buy</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">한화투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">185,000</td>
    													<td class="line num">185,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="Buy">Buy</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">유안타</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">150,000</td>
    													<td class="line num">135,000</td>
    													<td class="line num"><span class="cBk">11.11</span></td>
    													<td class="line center" title="Hold">Hold</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">KB</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">170,000</td>
    													<td class="line num">135,000</td>
    													<td class="line num"><span class="cBk">25.93</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">삼성</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">200,000</td>
    													<td class="line num">200,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">신한금융투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">175,000</td>
    													<td class="line num">175,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="매수">매수</td>
    													<td class="noline-right center" style="position: relative;" title="매수">매수</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">DB금융투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">170,000</td>
    													<td class="line num">170,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="Buy">Buy</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">KTB투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">160,000</td>
    													<td class="line num">140,000</td>
    													<td class="line num"><span class="cBk">14.29</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">이베스트투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">182,000</td>
    													<td class="line num">182,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="Buy">Buy</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">카카오페이</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">170,000</td>
    													<td class="line num">140,000</td>
    													<td class="line num"><span class="cBk">21.43</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">현대차</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">160,000</td>
    													<td class="line num">160,000</td>
    													<td class="line num"><span class="cBk">0.00</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">메리츠</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">190,000</td>
    													<td class="line num">184,000</td>
    													<td class="line num"><span class="cBk">3.26</span></td>
    													<td class="line center" title="Buy">Buy</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">NH투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">190,000</td>
    													<td class="line num">140,000</td>
    													<td class="line num"><span class="cBk">35.71</span></td>
    													<td class="line center" title="Buy">Buy</td>
    													<td class="noline-right center" style="position: relative;" title="Buy">Buy</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">한국투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">180,000</td>
    													<td class="line num">135,000</td>
    													<td class="line num"><span class="cBk">33.33</span></td>
    													<td class="line center" title="매수">매수</td>
    													<td class="noline-right center" style="position: relative;" title="매수">매수</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">케이프투자</td>
    													<td class="line center">21/08/09</td>
    													<td class="line num">185,000</td>
    													<td class="line num">112,000</td>
    													<td class="line num"><span class="cBk">65.18</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">SK</td>
    													<td class="line center">21/08/06</td>
    													<td class="line num">175,000</td>
    													<td class="line num">140,000</td>
    													<td class="line num"><span class="cBk">25.00</span></td>
    													<td class="line center" title="매수">매수</td>
    													<td class="noline-right center" style="position: relative;" title="매수">매수</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">미래에셋</td>
    													<td class="line center">21/08/06</td>
    													<td class="line num">192,000</td>
    													<td class="line num">142,000</td>
    													<td class="line num"><span class="cBk">35.21</span></td>
    													<td class="line center" title="매수">매수</td>
    													<td class="noline-right center" style="position: relative;" title="매수">매수</td>
    												</tr>
    											
    												<tr>
    													<td style="background-color: #FFFFFF" class="line txt" scope="row">하나금융투자</td>
    													<td class="line center">21/06/21</td>
    													<td class="line num">190,000</td>
    													<td class="line num">140,000</td>
    													<td class="line num"><span class="cBk">35.71</span></td>
    													<td class="line center" title="BUY">BUY</td>
    													<td class="noline-right center" style="position: relative;" title="BUY">BUY</td>
    												</tr>
    											
    									</tbody>
    								</table>
    								<p class="disc table mb-16">* 컨센서스 : 최근 3개월간 증권사에서 발표한 추정치의 평균 </p>
    								<div class="print_hspace">
    								</div>
    								<!--투자의견 컨센서스-->
    
    								<div class="tit-empty"></div>
    								<!--추정실적 컨센서스-->
    								<table class="schbox">
    									<tr>
    										<td class="c1 left">
    											<h5><span>추정실적</span> 컨센서스</h5>
    										</td>
    										<td class="c2 right" style="vertical-align:top">
    											<select name="conGubun" id="conGubun" title="재무구분선택">
    												<option value="MAIN">주재무제표</option>
    												<option value="IFRSS">K-IFRS(별도)</option>
    												<option value="IFRSL">K-IFRS(연결)</option>
    												<option value="GAAPS">K-GAAP(개별)</option>
    												<option value="GAAPL">K-GAAP(연결)</option>
    											</select>
    											<a href="javascript:;" onclick="GetConDataReload(event,'035720','conGubun','0',document.getElementById('conGubun').value);" title="검색" id="btnsubmit" class="btn_search"><span>검색</span></a>
    										</td>
    									</tr>
    								</table>
    								<table class="schtab" id="cTB23">
    									<tr>
    										<td class="c0 tabstart"></td>
    										<td class="c1 center on" id="cns_td1">
    											<a href="javascript:;" id="cns_Tab1" title="연간">연간</a>
    										</td>
    										<td class="c2 center off" id="cns_td2">
    											<a href="javascript:;" id="cns_Tab2" title="분기">분기</a>
    										</td>
    										<td class="c3 tabspace">&nbsp;</td>
    										<td class="c4 tabend"></td>
    									</tr>
    								</table>
    								<div id="frmFS1" class="all"></div>
    								<dl class="annotation mb-16">
    									<dd class="section01 cursor">
    										<ul>
    											<li>* (A) 는 실적, (E)는 컨센서스</li>
    										</ul>
    									</dd>
    									<dd class="section02">
    										<ul>
    											<li>* 연결 기업의 당기순이익 및 자본총계는 지배주주 기준 </li>
    											<li>* 컨센서스 : 최근 3개월간 증권사에서 발표한 추정치의 평균 </li>
    										</ul>
    									</dd>
    									<dd class="section03"><a href="javascript:;" class="off"></a></dd>
    								</dl>
    								<!--추정실적컨센서스-->
    
    								
    							</div>
    							<!-- wrapper -->
    						</div>
    					</div>
    				</div>
    				<!--// contentWrap -->
    			</div>
    			<!--//all_contentWrap -->
    		</div>
    		
    	<div class="clr">&nbsp;</div> <!-- 여백 -->
        <div class="foot-wrap">
            <div></div>
            <div id="foot-section">
                <div>
                    <span></span>
                </div>
                <div>
                    <p>
                        FnGuide에서 제공하는 정보는 신뢰할 만한 자료 및 정보로부터 얻어진 것이나 그 정확성이나 완전성을 보장 할 수 없으며, 시간이 경과함에 따라 변경될 수 있습니다.
                        따라서 정보의 오류, 누락에 대하여 FnGuide 또는FnGuide에 자료를 제공하는 회사에서는 그 결과에 대해 법적인 책임을 지지 않습니다.
                        모든 콘텐츠에 대한 저작권은 FnGuide에 있으며 사전 허가없이 이를 무단으로 사용하거나, 데이터 베이스화 할 경우 민형사상 책임을 물을 수 있습니다.
                    </p>
                </div>
            </div>
            <div></div>
        </div>
    	<div class="clr">&nbsp;</div> <!-- 여백 -->
    
    		
    	</form>
    	<script type='text/javascript'>
    		_.templateSettings = {
    			interpolate: /\<\@\=(.+?)\@\>/gim,
    			evaluate: /\<\@(.+?)\@\>/gim
    		};
    		var cn = '';
    		// 주가 및 상대수익률 추이 차트
    		var chartType = 'svg';
    		// 네이버 종합 -> 기업실적분석 더보기
    		$(window).load(function () {
    			
    			var targetvalue = '';
    			var moretop = (targetvalue === 'finsum_more') ? ($('#finsum_more').offset() || {top: 0}).top : ({top: 0}).top;
    			setTimeout(function () { autoResize({ moretop: moretop }); }, 1000);
    		});
    
    		// 주가 및 상대수익률 추이 차트
    		$(document).ready(function () {
    			Company_addr();
    			company_autocomplete();
    
    			$("#hd_cmp_cd").val('');
    			$("#cmp_cd").val('');
    
    			$('#conGubun, #bandChartGubun, #finGubun').change(function(){
    				setValCookie();
    			});
    		
    			$('#btnSearch').click(function(){
    				getAddInfoData01();
    				return false;
    			});
    			$('#cTB00 .center').click(function(){
    				$(this).removeClass('off').addClass('on');
    				$(this).siblings('.center').removeClass('on').addClass('off');
    				getAddInfoData01();
    				setValCookie();
    				return false;
    			});
    
    			$("#hpopupsearch").click(function () {
    				Cmd_cmpLookup(1, $("#search").val());
    			});
    			$("#hbandChartGubun").click(function () {
    				$.cookie('finGubun', $("#bandChartGubun").val());
    				RequestBandChart();
    			});
    
    			$("#draggable-section").draggable({
    				handle: "thead"
    			});
    			$("#hcalText").click(function () {
    				$("#draggable-section").css("display", "block");
    			});
    			$("#hbtn-close").click(function () {
    				$("#draggable-section").css("display", "none");
    			});
    
    			$('#cTB23 td>a').click(function (e) {
    				Cmd_MajConsen_Cross(e);
    				setValCookie();
    			});
    
    			// 주요주주 9인 펼치기
    			$('.btn_moreE.sJJ').click(function(){
    				var grp = $(this).data('grp');
    				var nm = $(this).data('nm');
    				var obj = $(this)
    				if($('span', this).hasClass('on'))
    				{
    					$('.c_sJJ' + grp).remove();
    					$('span', obj).removeClass('on');
    				}
    				else
    				{
    					$.getJSON('/company/ajax/cF1001.aspx'
    					, {
    						flag: 4,
    						cmp_cd: '035720',
    						grp_cd: grp==10?"01":"03",
                            encparam: 'Tm9jejk4dGVNdW5JSWcwbHdIWSs3QT09'
    					}
    				, function (res) {
    					var data = []
    					_.each(res.dt, function(v, i){
    						if(v.MAJOR_NEBUNA == nm)
    							data.push(v)
    					})
    					var tmp = _.template($("#tmpl-sJJ" ).html());
    					obj.parents('.p_sJJ' + grp).after(tmp({data: data, grp_cd: grp}));
    
    					$('span', obj).addClass('on');
    
    					gtag('config', 'UA-74989022-7', {'page_path': '/company/ajax/cF1001.aspx'});
    				});
    				}
    				
    			});
    
    			// 주가 거래량 차트 가져오기
    			stockChart(2);
    
    			// 주가 거래량 차트 선택
    			$('.btn_chart').click(function(){
    				$(this).parent().find('.on').removeClass('on');
    				$(this).addClass('on');
    				$('#ct1').data('flag', "ct1_" + $(this).data('flag'));
    				$(".spanCT").eq(0).html($(this).html());
    				$('#frmCt1').height(0)
    
    				stockChart($(this).data('flag'))
    			})
    
    
    			// 컨센서스 테이블 펼치기
    			if($("#cTB24 tbody tr").length > 3)
    			{
    				$("#cTB24 tbody tr").hide();				
    				$("#cTB24 tbody tr").eq(2).find("td").eq(6).append('<a class="btn_more"><span class="icon-sprite icon-more">펼치기</span></a>');
    				$("#cTB24 tbody tr").eq(0).show();
    				$("#cTB24 tbody tr").eq(1).show();
    				$("#cTB24 tbody tr").eq(2).hide().show();
    
    				$(".btn_more").click(function () {
    					if($(this).hasClass('ext')) {
    						$("#cTB24 tbody tr").hide();
    						$("#cTB24 tbody tr").eq(0).show();
    						$("#cTB24 tbody tr").eq(1).show();
    						$("#cTB24 tbody tr").eq(2).hide().show();
    						$(this).removeClass('ext');
    						$(this).children().removeClass('on');
    					}
    					else {
    						$("#cTB24 tbody tr").show();
    						$(this).addClass('ext');
    						$(this).children().addClass('on');
    					}
    				});
    			}
    
    			//펀더멘털 > 어닝서프라이즈
    			EarnigList();
        		
    			//initFinGubun과 같은 라인에 있어야 하지만 이벤트 등록이 된 이후의 시점에서 쿠키값을 가져와 데이터를 반영한다.
    			getValCookie();
    
    			$("#btnsubmit").click(function () {
    				$('#cns_td2').removeClass('on').addClass('off');
    				$('#cns_td1').removeClass('off').addClass('on');
    			});
    
    			$(".viewCT").click(function (e) {
    				var eid = e.target.id;
    				if (eid == "" || eid == null)
    					eid = $(e.target).children().attr("id");
    				switch (eid) {
    					case "ct1":
    						Cmd_cmpPopChartTable($('.nm_k').text(), "frmCt1", $("#ct1").data('flag'), "035720;20210813");
    					break;
    				case "ct2":
    					Cmd_cmpPopChartTable($('.nm_k').text(), "frmCt2", "ct2", "035720");
    					break;
    				case "ct3":
    					Cmd_cmpPopChartTable($('.nm_k').text(), "frmCt3", "ct3", "035720;20210813");
    					break;
    				case "ct4":
    					Cmd_cmpPopChartTable($('.nm_k').text(), "frmCt4", "ct4", "035720;" + $("#bandChartGubun").val());
    					break;
    				case "ct5":
    					Cmd_cmpPopChartTable($('.nm_k').text(), "frmCt5", "ct5", "035720;" + $("#bandChartGubun").val());
    					break;
    			}
    
    		});
    
    			// 밴드차트
    			RequestBandChart(); 
    
    		});
    
    	// 주가 거래량 차트
    	function stockChart(flag) {
    		// flag 1: 주가거래대금, 2: 수정주가상대수익률, 3:외국인지분율기관1개월누적순매수
    		if (chartType != 'image')
    		{
    			$.getJSON('/company/ajax/cF1001.aspx'
    			, {
    				flag: flag,
    				cmp_cd: '035720',
                    encparam: 'Tm9jejk4dGVNdW5JSWcwbHdIWSs3QT09'
    			}
    				, function (res) {
    					gtag('config', 'UA-74989022-7', {'page_path': '/company/ajax/cF1001.aspx'});
    				var tit_left, tit_right, d_left, d_right;
    				//var qty = [];
    				//_.each(res.TRD_QTY, function(v, i){
    				//	qty.push({y: v, color: res.TRD_QTY_TYP[i]=="R"?"#CC3300":"#216BDE"})
    				//})
    				switch(flag)
    				{
    					case 1:
    						if(_.max(res.D1).toString().length > 5) {
    							tit_right = "천원";
    							d_right = 1000;
    						}
    						else {
    							tit_right = "원";
    							d_right = 1;
    						}
    						var d2_len = _.max(res.D2).toString().length; 
    						if(d2_len > 10) {
    							tit_left = "억원";
    							d_left = 100000000;
    						}
    						else if(d2_len > 6) {
    							tit_left = "만원";
    							d_left = 10000;
    						}
    						else {
    							tit_left = "원";
    							d_left = 1;
    						}
    						break;
    					case 2:
    						tit_left = "%";
    						d_left = 1;
    
    						if(_.max(res.D1).toString().length > 5) {
    							tit_right = "천원";
    							d_right = 1000;
    						}
    						else {
    							tit_right = "원";
    							d_right = 1;
    						}
    						break;
    					case 3:
    						tit_right = "%";
    						d_right = 1;
    
    						if(_.max(res.D2).toString().length > 4) {
    							tit_left = "억원";
    							d_left = 1000;
    						}
    						else {
    							tit_left = "백만원";
    							d_left = 1;
    						}
    						break;
    				}
    						
    				$('#stock_price_relative_chart').highcharts({
    					xAxis: {
    						categories: res.TRD_DT,
    						type: 'datetime',
    						tickInterval: res.TRD_DT.length / 2
    					},
    					rangeSelector: {
    						enabled: false
    					},
    					chart: {
    						marginLeft: 50,
    						marginRight: 60,
    						marginBottom: 60
    					},
    					yAxis: [{
    						title: {
    							enabled: true, 
    							align: 'high',
    							text: '['+tit_right+']',
    							rotation: 0,
    							y: -10,
    							margin:0
    						},
    						height: 120,
    						opposite: true,
    						labels: {
    							formatter: function () {
    								return flag == 3? 
    										Highcharts.numberFormat(this.value, this.axis.dataMax / d_right < 5 ? 2:0) :
    										Highcharts.numberFormat(this.value / d_right, 0);
    							}
    						},
    						maxPadding: 0,
    						minPadding: 0,
    						tickPixelInterval: 25
    					}, {
    						top: 149,
    						height: 37,
    						showLastLabel: false,
    						opposite: true,
    						offset:0,
    						tickPixelInterval:25
    					}, {
    						top: 127,
    						height: 68,
    						offset: 0,
    						labels: {
    							enabled: false
    						},
    						title: {
    							enabled: false
    						},
    						minPadding: 0,
    						tickPixelInterval: 25
    					}, {
    						height: 120,
    						title: {
    							enabled: true, 
    							align: 'high',
    							text: '['+tit_left+']',
    							rotation: 0,
    							y: -10,
    							offset:8
    						},
    						labels: {
    							formatter: function () {
    								return flag != 2? Highcharts.numberFormat(this.value / d_left, 0):this.value;
    							}
    						},
    						maxPadding: 0,
    						minPadding: 0,
    						tickPixelInterval: 25
    					}],
    					navigator: {
    						enabled: false
    					},
    					plotOptions: {
    						series: { 
    							borderWidth: 0, 
    							marker: { enabled: false},
    							shadow: false,
    							borderWidth: 0
    						}
    					},
    					scrollbar: {
    						enabled: false
    					},
    					tooltip: {
    						formatter: function () {
    							var tooltip = '<table class="chart-tooltip"><tr><td align="center" colspan="3">' + Highcharts.dateFormat('%Y/%m/%d', this.x) + '</td></tr>';
    							var len = this.points.length - 1;
    							$.each(this.points, function (i, value) {
    								//if(i == 0)
    								//{
    								//	tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + (flag==3? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_right, 0, '.')) + ' '+tit_right +'</td></tr>';
    								//}
    								//else if (i == len)
    								//{
    								//	tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.')+ (flag==3?' 원':' 주') + '</td></tr>';
    								//}
    								//else {
    								//	tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name.replace('(좌)', '') + '</td><td> : </td><td align="right">' + (flag==2? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_left, 0, '.'))+' '+tit_left+ '</td></tr>';
    								//}
    								if (flag == 2) {
    									if(value.series.name.indexOf('대비(좌)') > -1)
    									{
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name.replace('(좌)', '') + '</td><td> : </td><td align="right">' + (flag==2? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_left, 0, '.'))+' '+tit_left+ '</td></tr>';											
    									}
    									else if (value.series.name.indexOf('거래량') > -1)
    									{
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.')+ (flag==3?' 원':' 주') + '</td></tr>';
    									}
    									else {
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + (flag==3? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_right, 0, '.')) + ' '+tit_right +'</td></tr>';
    									}
    								}
    								else if (flag == 1) {
    									if(value.series.name.indexOf('대금(좌)') > -1)
    									{
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name.replace('(좌)', '') + '</td><td> : </td><td align="right">' + (flag==2? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_left, 0, '.'))+' '+tit_left+ '</td></tr>';											
    									}
    									else if (value.series.name.indexOf('거래량') > -1)
    									{
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.')+ (flag==3?' 원':' 주') + '</td></tr>';
    									}
    									else {
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + (flag==3? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_right, 0, '.')) + ' '+tit_right +'</td></tr>';
    									}
    								}
    								else {
    									if(value.series.name.indexOf('매수(좌)') > -1)
    									{
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name.replace('(좌)', '') + '</td><td> : </td><td align="right">' + (flag==2? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_left, 0, '.'))+' '+tit_left+ '</td></tr>';											
    									}
    									else if (value.series.name.indexOf('수정주가') > -1)
    									{
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.')+ (flag==3?' 원':' 주') + '</td></tr>';
    									}
    									else {
    										tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + (flag==3? Highcharts.numberFormat(value.y, 2, '.'):  Highcharts.numberFormat(value.y/d_right, 0, '.')) + ' '+tit_right +'</td></tr>';
    									}
    								}
    							});
    							tooltip += '</table>';
    							return tooltip;
    						}
    						, shared: true
    					},
    					series: [{
    						type: 'line',
    						name: res.D1_NM,
    						yAxis: 0,
    						fillOpacity: 0.1,
    						data: res.D1
    					}, {
    						type: 'line',
    						name: res.D2_NM + "(좌)",
    						yAxis: 3,
    						data: res.D2
    					}, {
    						type: 'line',
    						name: res.D3_NM + "(좌)",
    						yAxis: 3,
    						data: res.D3,
    						visible: flag!=2?false:true,
    						showInLegend: flag!=2?false:true
    					},  {
    						type: flag == 3? 'line':'column',
    						name: flag == 3? '수정주가':'거래량',
    						yAxis: 1,
    						data: flag == 3? res.TRD_ADJ_PRC:res.TRD_QTY
    					}]
    				});
    			});
    		}
    		else{
    			if($('#stock_price_relative_chart img').attr('src') == undefined)
    			{
    				$('#stock_price_relative_chart').html('<img src="http://companyinfo.stock.naver.com/chartimg/page1/chart1/035720c1.png?20210813" />')
    					
    			}
    			var src = $('#stock_price_relative_chart img').attr('src')
    			var old = src.substr(src.indexOf('png') - 3, 2);
    			$('#stock_price_relative_chart img').attr('src', src.replace(old, "c" + flag));
    		}
    	} // End Of stockChart
    
    	// 펀더멘털 > 어닝서프라이즈
    	var EarnigList = function () {
    		var res = {"yymm":["202012","202103","202106"],"data":[{"1":1425.232500000000,"2":1537.879090909100,"3":1793.491428571400},{"1":1498.430000000000,"2":1575.450000000000,"3":1626.090000000000},{"1":5.135830000000,"2":2.443030000000,"3":-9.333830000000},{"1":88.287750000000,"2":78.600740000000,"3":66.315870000000},{"1":24.646030000000,"2":5.269460000000,"3":3.214490000000},{"1":1195.731666666700,"2":1347.820000000000,"3":1987.663000000000},{"1":-1951.470000000000,"2":2245.360000000000,"3":3116.600000000000},{"1":-263.203000000000,"2":66.591980000000,"3":56.797200000000},{"1":53.866650000000,"2":189.871580000000,"3":122.994350000000},{"1":-253.025490000000,"2":218.724250000000,"3":38.801620000000}],"yymmdd":["2021/02/09(연결)","2021/05/06(연결)","2021/08/06(연결)"],"type":[1,1,1]};
    		tmp = _.template($("#tmpl-list").html());
    		$("#earning_list tbody").html(tmp(res));
    
    		$(".btn_moreE.earn").click(function(){
    			if($('span', this).hasClass('on'))
    			{
    				$(".btn_moreE.earn span").removeClass('on');
    				$('.ext0').hide();
    			}
    			else
    			{
    				$(".btn_moreE.earn span").addClass('on');
    				$('.ext0').show();
    			}
    		});
    		
    	} // End Of EarnigList
    	
    		// 재무리스트 컨센서스 보기 기능 적용
    		function getAddInfoData01(extY, extQ)
    		{
    			var _freq_typ;
    			var _fin_typ;
    
    			switch($('#cTB00 .on').attr('id'))
    			{
    				case "cns_td20": _freq_typ = "A"; break;
    				case "cns_td21": _freq_typ = "Y"; break;
    				case "cns_td22": _freq_typ = "Q"; break;
    			}
    			
    			switch($("#finGubun > option:selected").val())
    			{
    				case "MAIN" : _fin_typ = 0; break;
    				case "GAAPS": _fin_typ = 1; break;
    				case "GAAPL": _fin_typ = 2; break;
    				case "IFRSS": _fin_typ = 3; break;
    				case "IFRSL": _fin_typ = 4; break;
    			}
    			$.ajax({
    				url     : "ajax/cF1001.aspx",
    				async  : false,
    				type    : 'get',
    				dataType: 'html',
    				data: {
    					cmp_cd    : '035720'
                    , fin_typ : _fin_typ
    				, freq_typ: _freq_typ
    				, extY: extY
                    , extQ: extQ
                    , encparam: 'Tm9jejk4dGVNdW5JSWcwbHdIWSs3QT09'
                    , id: 'RVArcVR1a2' ? 'RVArcVR1a2' : ''
    				},
    				success: function (data) {
    					gtag('config', 'UA-74989022-7', {'page_path': '/company/ajax/cF1001.aspx'});
    					$('#RVArcVR1a2').html(data);
    					if(extQ==0)
    					{
    						$('.r02c07').addClass('endLine')
    					}
    					// 재무 컬럼 펼치기
    					$('.btn_moreY').click(function(){
    						if($(this).data('ext')==0){
    							getAddInfoData01(1, $('.btn_moreQ').data('ext'));
    							$(this).data('ext',1);
    						}
    						else{
    							getAddInfoData01(0, $('.btn_moreQ').data('ext'));
    							$(this).data('ext',0);
    						}
    					});
    					$('.btn_moreQ').click(function(){
    						if($(this).data('ext')==0){
    							getAddInfoData01($('.btn_moreY').data('ext'),1);
    							$(this).data('ext',1);
    						}
    						else{
    							getAddInfoData01($('.btn_moreY').data('ext'),0);
    							$(this).data('ext',0);
    						}
    					});
    				}
    			});
    		}
    
    		// 투자의견 및 목표주가 차트
    		$('#opinion_targetPrice').show();
    		if (chartType != 'image'){
    			var chartData2 = {"target_price":[{"x":1601337600000.0,"y":85840.0},{"x":1604016000000.0,"y":88167.0},{"x":1606694400000.0,"y":91435.0},{"x":1609286400000.0,"y":91625.0},{"x":1611878400000.0,"y":102448.0},{"x":1614297600000.0,"y":112075.0},{"x":1617148800000.0,"y":113557.0},{"x":1619740800000.0,"y":125304.0},{"x":1622419200000.0,"y":137318.0},{"x":1625011200000.0,"y":150429.0},{"x":1627603200000.0,"y":155364.0},{"x":1628812800000.0,"y":178421.0}],"close_price":[{"x":1601337600000.0,"y":72900.0},{"x":1604016000000.0,"y":66000.0},{"x":1606694400000.0,"y":73600.0},{"x":1609286400000.0,"y":77900.0},{"x":1611878400000.0,"y":88200.0},{"x":1614297600000.0,"y":97600.0},{"x":1617148800000.0,"y":99600.0},{"x":1619740800000.0,"y":113500.0},{"x":1622419200000.0,"y":123000.0},{"x":1625011200000.0,"y":163000.0},{"x":1627603200000.0,"y":147000.0},{"x":1628812800000.0,"y":146000.0}],"deg":[{"x":1601337600000.0,"y":3.96},{"x":1604016000000.0,"y":4.00},{"x":1606694400000.0,"y":4.00},{"x":1609286400000.0,"y":4.00},{"x":1611878400000.0,"y":4.00},{"x":1614297600000.0,"y":4.00},{"x":1617148800000.0,"y":4.00},{"x":1619740800000.0,"y":4.00},{"x":1622419200000.0,"y":4.00},{"x":1625011200000.0,"y":4.00},{"x":1627603200000.0,"y":4.00},{"x":1628812800000.0,"y":3.95}]};
    			new Highcharts.Chart({
    				chart: {
    					renderTo: 'opinion_targetPrice',
    					type: 'line'
    				}
    				, xAxis: {
    					labels: {
    						formatter: function () { return Highcharts.dateFormat('%y/%m/%d', this.value); }
    					}
    				}
    				,yAxis: [{
    					title: {
    						text: '[원]' ,align: 'high' ,y: -7 ,rotation:0, x:10 ,offset:40
    					},
    					opposite: true
    				},{
    					min:3,max:5,minPadding: 0.5, maxPadding: 0.5,tickInterval: 0.5,
    					labels: {
    						formatter: function () { return Highcharts.numberFormat(this.value, 2, '.'); }
    					}
    				}]
    				, tooltip: {
    					formatter: function () {
    						var tooltip = '<table class="chart-tooltip"><tr><td align="center" colspan="3">' + Highcharts.dateFormat('%Y/%m/%d', this.x) + '</td></tr>';
    						$.each(this.points, function (i, value) {
    							if (value.series.name.indexOf('(좌)') > 0) {
    								tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 2, '.') + '</td></tr>';
    							} else {
    								tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.') + ' 원 </td></tr>';
    							}
    						});
    						tooltip += '</table>';
    						return tooltip;
    					}
    				},
    				series: [{
    					type:'column',
    					name: '투자의견(좌)',
    					data: chartData2.deg,
    					yAxis: 1 ,
    					marker: {
    						enabled: false
    					}
    					,legendIndex:0
    				}, {
    					name: '목표주가',
    					data: chartData2.target_price,
    					marker: {
    						enabled: true,
    						symbol: 'circle'
    					}
    					,legendIndex:1
    				}, {
    					name: '수정주가',
    					data: chartData2.close_price,
    					marker: {
    						enabled: true,
    						symbol: 'triangle'
    					}
    					,legendIndex:2
    				}]
    			});
    			chartData2 = null;
    		} else {
    			$('#opinion_targetPrice').html('<img src="http://companyinfo.stock.naver.com/chartimg/page1/chart2/035720.png?20210813" />');
    		}
    
    		// 투자의견 분포 차트 
    		$('#opinion').show();
    		if (chartType != 'image'){
    			var chartData3 = {"today":[{"name":"강력매수","y":null},{"name":"매수","y":18.0},{"name":"중립","y":1.0},{"name":"매도","y":null},{"name":"강력매도","y":null}],"a_month_ago":[{"name":"강력매수","y":null},{"name":"매수","y":22.0},{"name":"중립","y":null},{"name":"매도","y":null},{"name":"강력매도","y":null}]};
    			new Highcharts.Chart({
    				chart: {
    					renderTo: 'opinion',
    					type: 'column'
    				},
    				xAxis: {
    					categories: ['강력매수', '매수','중립','매도','강력매도'],
    					labels: {
    						formatter: function () { return this.value }
    					}
    					, type: 'string'
    				},
    				tooltip:{
    					crosshairs: false,
    					formatter:function(){
    						var tooltip = '<table class="chart-tooltip"><tr><td align="center" colspan="3">투자의견:' + this.x + '</td></tr>';
    						$.each(this.points, function (i, value) {
    							tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.') + ' 건 </td></tr>';
    						});
    						tooltip += '</table>';
    						return tooltip;
    					}
    				},
    				plotOptions: {
    					column: {
    						dataLabels: {
    							enabled: true
    						}
    					}
    				},
    				series: [{
    					name: '현재',
    					data: chartData3.today
    				}, {
    					name: '한달전',
    					data: chartData3.a_month_ago 
    				}]
    			});
    			chartData3 = null;
    		} else {
    			$('#opinion').html('<img src="http://companyinfo.stock.naver.com/chartimg/page1/chart3/035720.png?20210813" />');
    		} 
    	//자동완성 상단 검색에서의 highlight기능추가하기
    	jQuery.fn.highlight = function (str, className) {
    		var regex = new RegExp("(" + str + ")", "gi");
    		return this.each(function () {
    			this.innerHTML = this.innerHTML.replace("&amp;", "&").replace(regex, "<span class=\"" + className + "\">$1</span>");
    		});
    	};
        	
    	function setValCookie()
    	{
    		var setVal = [
    			{
    				'conGubun'       : $("#conGubun > option:selected").val(),      //추정실적 컨센서스
    				'cTB23'          : $('#cTB23 td.on').attr('id'),                //연간,분기
    				'bandChartGubun' : $("#bandChartGubun > option:selected").val(),//밴드차트 구분
    				'finGubun'       : $("#finGubun > option:selected").val(),
    				'cTB00'          : $('#cTB00 td.on').attr('id')                 //전체,연간,분기
    			}
    		];
    		$.cookie("setC1010001", JSON.stringify(setVal));
    	}
    
    	function getValCookie(){
    		//만약 쿠키 값을 가져오려는데. 기존에 저장된 값이 없다면 현재 페이지값을 저장한다.
    		if($.cookie('setC1010001') == undefined || $.cookie('setC1010001') == "" || $.cookie('setC1010001') == null){
    			setValCookie();
    		}
    		
            if ($.cookie('setC1010001') != null) {
                var setVal = JSON.parse($.cookie('setC1010001'))[0];
                $('#conGubun').val(setVal.conGubun);                 //선택박스		: 추정실적컨센서스
                $('#cTB23 #' + setVal.cTB23 + '>a').trigger('click');   //탭			: 추정실적컨센서스 연간,분기 [frmFS1의 url 설정 cf1002.aspx]
                $('#bandChartGubun').val(setVal.bandChartGubun);     //선택박스		: 밴드차트
                $('#finGubun').val(setVal.finGubun);                 //선택박스		: 주재무제표,K-IFRS(별도), K-IFRS(연결), K-GAAP(개별), K-GAAP(연결)
                $('#cTB00 #' + setVal.cTB00 + '>a').trigger('click');   //탭			: 전체,연간,분기
            }
            else {
                $('#conGubun').val($("#conGubun > option:selected").val());                 //선택박스		: 추정실적컨센서스
                $('#cTB23 #' + $('#cTB23 td.on').attr('id') + '>a').trigger('click');   //탭			: 추정실적컨센서스 연간,분기 [frmFS1의 url 설정 cf1002.aspx]
                $('#bandChartGubun').val($("#bandChartGubun > option:selected").val());     //선택박스		: 밴드차트
                $('#finGubun').val($("#finGubun > option:selected").val());                 //선택박스		: 주재무제표,K-IFRS(별도), K-IFRS(연결), K-GAAP(개별), K-GAAP(연결)
                $('#cTB00 #' + $('#cTB00 td.on').attr('id') + '>a').trigger('click');   //탭			: 전체,연간,분기
            }
    	}
    
    	function getParameterByName(name) {
    		name = name.replace(/[\[]/, "\\[").replace(/[\]]/, "\\]");
    		var regex = new RegExp("[\\?&]" + name + "=([^&#]*)"),
    			results = regex.exec(location.search);
    		return results === null ? "" : decodeURIComponent(results[1].replace(/\+/g, " "));
    	}
    
    	function initFinGubun() {
    		var finGubun = ($.cookie('finGubun') != null) ? $.cookie('finGubun') : 'MAIN';
    		$('#conGubun > option[value=' + finGubun + ']').attr('selected', 'true');
    		//var url = '../company/cF1002.aspx?cmp_cd=035720&finGubun=' + finGubun;
    		//$('#frmFS1').attr('src', url);
    		$.ajax({
    			url: '../company/cF1002.aspx',
    			async : true,
    			dataType: 'html',
    			data: {
    				cmp_cd: '035720',
    				finGubun: finGubun
    			},
    			success: function (res) {
    				gtag('config', 'UA-74989022-7', {'page_path': '/company/cF1002.aspx'});
    				$("#frmFS1").html(res);
    			}
    		});
    
    		$('#bandChartGubun > option[value=' + finGubun + ']').attr('selected', 'true');
    		$('#finGubun > option[value=' + finGubun + ']').attr('selected', 'true');
    	}
    
    	function makeBandChart(res, cmp_cd, gubun) {
    		var chartType = 'svg';
    		$('#pbr-chart,#per-chart').show();
    		if (chartType != 'image') {
    			var adjPrcMax = _.max(res.bandChart1.price, function (item) { return item.y }).y;
    			var data2Max = _.max(res.bandChart1.val2, function (item) { return item.y }).y;
    			var yAxisMax = adjPrcMax > data2Max ? adjPrcMax : data2Max;
    
    
    			var pbrAdjPrcMax = _.max(res.bandChart2.price, function (item) { return item.y }).y;
    			var pbrData2Max = _.max(res.bandChart2.val2, function (item) { return item.y }).y;
    			var pbrYAxisMax = pbrAdjPrcMax > pbrData2Max ? pbrAdjPrcMax : pbrData2Max;
    
    			new Highcharts.Chart({
    				chart: {
    					renderTo: 'per-chart',
    					type: 'line'
    				},
    				yAxis: {
    					min: 0,
    					max: yAxisMax
    				},
    				legend: {
    				    labelFormatter: function () {
    				        return (this.name.indexOf('Series') > -1) ? '0.0배' : this.name;
    				    }
    				},
    				tooltip: {
    					formatter: function () {
    						var tooltip = '<table class="chart-tooltip"><tr><td align="center" colspan="3">' + Highcharts.dateFormat('%Y/%m/%d', this.x) + '</td></tr>';
    						var points = this.points[this.points.length-1];
    						if(points.series.name == "수정주가")
    						{
    							tooltip += '<tr><td style="color:' + points.series.color + '">' + points.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(points.y, 0, '.') + ' 원</td></tr>';
    						}
    						$.each(this.points, function (i, value) {
    							if(value.series.name != "수정주가")
    							{
    								tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.') + ' 원</td></tr>';
    							}
    						});
    						tooltip += '</table>';
    						return tooltip;
    					}
    				},
    				series: [{
    					name: '수정주가',
    					data: res.bandChart1.price,
    					index: 5,
    					legendIndex:1,
    					lineWidth: 3
    				}, {
    					name: res.bandChart1.name.VAL4,
    					data: res.bandChart1.val4,
    					index: 1,
    					legendIndex:2,
    					shadow: false
    				}, {
    					name: res.bandChart1.name.VAL3,
    					data: res.bandChart1.val3,
    					index: 2,
    					legendIndex:3,
    					shadow: false
    				}, {
    					name: res.bandChart1.name.VAL2,
    					data: res.bandChart1.val2,
    					index: 3,
    					legendIndex:4,
    					shadow: false
    				}, {
    					name: res.bandChart1.name.VAL1,
    					data: res.bandChart1.val1,
    					index: 4,
    					legendIndex:5,
    					shadow: false
    				}]
    			});
    			new Highcharts.Chart({
    				chart: {
    					renderTo: 'pbr-chart',
    					type: 'line'
    				},
    				yAxis: {
    					min: 0,
    					max: pbrYAxisMax
    				},
    				legend: {
    				    labelFormatter: function () {
    				        return (this.name.indexOf('Series') > -1) ? '0.0배' : this.name;
    				    }
    				},
    				tooltip: {
    					formatter: function () {
    						var tooltip = '<table class="chart-tooltip"><tr><td align="center" colspan="3">' + Highcharts.dateFormat('%Y/%m/%d', this.x) + '</td></tr>';
    						var points = this.points[this.points.length-1];
    						if(points.series.name == "수정주가")
    						{
    							tooltip += '<tr><td style="color:' + points.series.color + '">' + points.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(points.y, 0, '.') + ' 원</td></tr>';
    						}
    						$.each(this.points, function (i, value) {
    							if(value.series.name != "수정주가")
    							{
    								tooltip += '<tr><td style="color:' + value.series.color + '">' + value.series.name + '</td><td> : </td><td align="right">' + Highcharts.numberFormat(value.y, 0, '.') + ' 원</td></tr>';
    							}
    						});
    						tooltip += '</table>';
    						return tooltip;
    					}
    				},
    				series: [{
    					name: '수정주가',
    					data: res.bandChart2.price,
    					index: 5,
    					legendIndex:1,
    					lineWidth: 3
    				}, {
    					name: res.bandChart2.name.VAL4,
    					data: res.bandChart2.val4,
    					index: 1,
    					legendIndex:2,
    					shadow: false
    				}, {
    					name: res.bandChart2.name.VAL3,
    					data: res.bandChart2.val3,
    					index: 2,
    					legendIndex:3,
    					shadow: false
    				}, {
    					name: res.bandChart2.name.VAL2,
    					data: res.bandChart2.val2,
    					index: 3,
    					legendIndex:4,
    					shadow: false
    				}, {
    					name: res.bandChart2.name.VAL1,
    					data: res.bandChart2.val1,
    					index: 4,
    					legendIndex:5,
    					shadow: false
    				}]
    			});
    		}
    		else {
    			$('#per-chart').html("<img src='http://companyinfo.stock.naver.com/chartimg/bandchart/per/" + cmp_cd + "_" + gubun + ".png?20210813' alt='PER 밴드 차트 이미지'/>");
    			$('#pbr-chart').html("<img src='http://companyinfo.stock.naver.com/chartimg/bandchart/pbr/" + cmp_cd + "_" + gubun + ".png?20210813' alt='PBR 밴드 차트 이미지'/>");
    		}
    	}
    	function RequestBandChart() {
    		var chartType = 'svg';
    		var cmp_cd = "035720";
    		var chartGubun = $("#bandChartGubun").val();
    		var gubun = "4";
    		if (chartGubun == "MAIN")
    			gubun = "0";
    		else if (chartGubun == "IFRSL")
    			gubun = "4";
    		else if (chartGubun == "IFRSS")
    			gubun = "3";
    		else if (chartGubun == "GAAPL")
    			gubun = "2";
    		else if (chartGubun == "GAAPS")
    			gubun = "1";
    
    		var aurl = (chartType != 'image') ? 'http://companyinfo.stock.naver.com/common/BandChart3.aspx?cmp_cd=' + cmp_cd + '&gubun=' + gubun : 'http://companyinfo.stock.naver.com/company/chart/bandChart.aspx?cmp_cd=' + cmp_cd + '&gubun=' + gubun;
    		// json의 경우 gzip 압축이 되지 않는 문제가 있어서 text/html 형태로 받아서 json 파싱을 해주도록 한다.
    		$.ajax({
    			url: aurl,
    			async : false,
    			type  : 'get',
    			success: function (res) {
    				gtag('config', 'UA-74989022-7', {'page_path': (chartType != 'image') ? '/common/BandChart3.aspx' : '/company/chart/bandChart.aspx'});
    				res = (chartType != 'image') ? $.parseJSON(res) : res;
    				makeBandChart(res, cmp_cd, gubun);
    			}
    		});
    	}
    	function getMenuType() {
    		return "block";
    	}
    	function getMonth(str) {
    		if (!str) {
    			return ''
    		}
    		if (str != null && str != '') {
    			return str.substr(4, 2);
    		}
    		return str;
    	}
    	$(document).ajaxComplete(function() {
    		var targetvalue = '';
    		var moretop = (targetvalue === 'finsum_more') ? ($('#finsum_more').offset() || {top: 0}).top : ({top: 0}).top;
    		setTimeout(function () { autoResize({ moretop: moretop }); }, 1000);
    	});
    	</script>
    </div>
    </body>
    </html>
    
    


```python
import requests 
import re

code = "035720"

re_enc = re.compile("encparam: '(.*)'", re.IGNORECASE) 
re_id = re.compile("id: '([a-zA-Z0-9]*)' ?", re.IGNORECASE)

url = "http://companyinfo.stock.naver.com/v1/company/c1010001.aspx?cmp_cd={}".format(code) 
html = requests.get(url).text 
encparam = re_enc.search(html).group(1) 
encid = re_id.search(html).group(1)

url = "http://companyinfo.stock.naver.com/v1/company/ajax/cF1001.aspx?cmp_cd={}&fin_typ=0&freq_typ=A&encparam={}&id={}".format(code, encparam, encid) 
headers = {"Referer": "HACK"}
html = requests.get(url, headers=headers).text 
print(html)
```

    <table class="hQk80WlNFN0 gHead01 all-width" summary="주요재무정보를 제공합니다."><caption class="blind">"주요재무정보"</caption><thead><tr><th>3320</th><th>3320</th><th>3320</th><th>3320</th><th>3320</th><th>3320</th><th>3320</th><th>3320</th><th>3320</th></tr></thead><tbody><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr><tr><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td><td>3,320</td></tr></tbody></table>
    							<table class='gHead01 all-width' summary='주요재무정보를 제공합니다.'>
    								<caption class='blind'>주요재무정보</caption>
    								<thead>
    								<tr>
    									<th class="r01c01 bg " rowspan="2" style="width:125px">주요재무정보</th>
    									<th class="r01c02 bg line-bottom"colspan="4">연간<a class='btn_moreY fl_ri' data-ext='1'><span class='icon-sprite icon-moreYQ on'>연간컨센서스보기</span></a></th>
    									<th class="r01c03 bg  line-bottom endLine"colspan="4">분기<a class='btn_moreQ fl_ri' data-ext='1'><span class='icon-sprite icon-moreYQ on'>분기컨센서스보기</span></a></th>
    								</tr>
    						<tr>
    								<th class="r02c00 bg">
    									2018/12
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c01 bg">
    									2019/12
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c02 bg">
    									2020/12
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c03 bg">
    									2021/12(E)
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c04 bg ">
    									2020/09
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c05 bg ">
    									2020/12
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c06 bg ">
    									2021/03
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th>
    								<th class="r02c07 bg endLine">
    									2021/06(E)
    									<br/>
    									<span class='span-sub'>(IFRS연결)</span>
    								</th></tr></thead><tbody>
    								<tr>
    									<th class="bg txt ">매출액</th>
    									<td class="num "><span class="cBk">24,170</span></td>
    									<td class="num "><span class="cBk">30,701</span></td>
    									<td class="num "><span class="cBk">41,568</span></td>
    									<td class="num  bgE"><span class="cBk">59,656</span></td>
    									<td class="num "><span class="cBk">11,004</span></td>
    									<td class="num "><span class="cBk">12,351</span></td>
    									<td class="num "><span class="cBk">12,580</span></td>
    									<td class="bgE num noline-right "><span class="cBk">13,502</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">영업이익</th>
    									<td class="num "><span class="cBk">729</span></td>
    									<td class="num "><span class="cBk">2,068</span></td>
    									<td class="num "><span class="cBk">4,559</span></td>
    									<td class="num  bgE"><span class="cBk">8,085</span></td>
    									<td class="num "><span class="cBk">1,202</span></td>
    									<td class="num "><span class="cBk">1,497</span></td>
    									<td class="num "><span class="cBk">1,575</span></td>
    									<td class="bgE num noline-right "><span class="cBk">1,793</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">영업이익(발표기준)</th>
    									<td class="num "><span class="cBk">729</span></td>
    									<td class="num "><span class="cBk">2,068</span></td>
    									<td class="num "><span class="cBk">4,559</span></td>
    									<td class="num  bgE"></td>
    									<td class="num "><span class="cBk">1,202</span></td>
    									<td class="num "><span class="cBk">1,497</span></td>
    									<td class="num "><span class="cBk">1,575</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">세전계속사업이익</th>
    									<td class="num "><span class="cBk">1,307</span></td>
    									<td class="num "><span class="cUp">-2,343</span></td>
    									<td class="num "><span class="cBk">4,143</span></td>
    									<td class="num  bgE"><span class="cBk">13,210</span></td>
    									<td class="num "><span class="cBk">1,796</span></td>
    									<td class="num "><span class="cUp">-960</span></td>
    									<td class="num "><span class="cBk">3,187</span></td>
    									<td class="bgE num noline-right "><span class="cBk">2,788</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">당기순이익</th>
    									<td class="num "><span class="cBk">159</span></td>
    									<td class="num "><span class="cUp">-3,419</span></td>
    									<td class="num "><span class="cBk">1,734</span></td>
    									<td class="num  bgE"><span class="cBk">10,116</span></td>
    									<td class="num "><span class="cBk">1,437</span></td>
    									<td class="num "><span class="cUp">-1,955</span></td>
    									<td class="num "><span class="cBk">2,399</span></td>
    									<td class="bgE num noline-right "><span class="cBk">1,998</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">&nbsp;&nbsp;당기순이익(지배)</th>
    									<td class="num "><span class="cBk">479</span></td>
    									<td class="num "><span class="cUp">-3,010</span></td>
    									<td class="num "><span class="cBk">1,556</span></td>
    									<td class="num  bgE"><span class="cBk">9,684</span></td>
    									<td class="num "><span class="cBk">1,275</span></td>
    									<td class="num "><span class="cUp">-1,891</span></td>
    									<td class="num "><span class="cBk">2,245</span></td>
    									<td class="bgE num noline-right "><span class="cBk">1,988</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">&nbsp;&nbsp;당기순이익(비지배)</th>
    									<td class="num "><span class="cUp">-320</span></td>
    									<td class="num "><span class="cUp">-409</span></td>
    									<td class="num "><span class="cBk">177</span></td>
    									<td class="num  bgE"></td>
    									<td class="num "><span class="cBk">162</span></td>
    									<td class="num "><span class="cUp">-64</span></td>
    									<td class="num "><span class="cBk">153</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">자산총계</th>
    									<td class="num "><span class="cBk">79,595</span></td>
    									<td class="num "><span class="cBk">87,373</span></td>
    									<td class="num "><span class="cBk">119,540</span></td>
    									<td class="num  bgE"><span class="cBk">143,924</span></td>
    									<td class="num "><span class="cBk">112,326</span></td>
    									<td class="num "><span class="cBk">119,540</span></td>
    									<td class="num "><span class="cBk">135,142</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">부채총계</th>
    									<td class="num "><span class="cBk">23,324</span></td>
    									<td class="num "><span class="cBk">29,971</span></td>
    									<td class="num "><span class="cBk">45,262</span></td>
    									<td class="num  bgE"><span class="cBk">58,130</span></td>
    									<td class="num "><span class="cBk">37,628</span></td>
    									<td class="num "><span class="cBk">45,262</span></td>
    									<td class="num "><span class="cBk">56,369</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">자본총계</th>
    									<td class="num "><span class="cBk">56,272</span></td>
    									<td class="num "><span class="cBk">57,401</span></td>
    									<td class="num "><span class="cBk">74,277</span></td>
    									<td class="num  bgE"><span class="cBk">85,793</span></td>
    									<td class="num "><span class="cBk">74,698</span></td>
    									<td class="num "><span class="cBk">74,277</span></td>
    									<td class="num "><span class="cBk">78,772</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">&nbsp;&nbsp;자본총계(지배)</th>
    									<td class="num "><span class="cBk">51,369</span></td>
    									<td class="num "><span class="cBk">52,254</span></td>
    									<td class="num "><span class="cBk">62,989</span></td>
    									<td class="num  bgE"><span class="cBk">73,686</span></td>
    									<td class="num "><span class="cBk">63,931</span></td>
    									<td class="num "><span class="cBk">62,989</span></td>
    									<td class="num "><span class="cBk">66,571</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">&nbsp;&nbsp;자본총계(비지배)</th>
    									<td class="num "></td>
    									<td class="num "><span class="cBk">5,148</span></td>
    									<td class="num "><span class="cBk">11,288</span></td>
    									<td class="num  bgE"></td>
    									<td class="num "><span class="cBk">10,767</span></td>
    									<td class="num "><span class="cBk">11,288</span></td>
    									<td class="num "><span class="cBk">12,201</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">자본금</th>
    									<td class="num "><span class="cBk">417</span></td>
    									<td class="num "><span class="cBk">432</span></td>
    									<td class="num "><span class="cBk">443</span></td>
    									<td class="num  bgE"><span class="cBk">442</span></td>
    									<td class="num "><span class="cBk">442</span></td>
    									<td class="num "><span class="cBk">443</span></td>
    									<td class="num "><span class="cBk">444</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">영업활동현금흐름</th>
    									<td class="num "><span class="cBk">4,915</span></td>
    									<td class="num "><span class="cBk">7,527</span></td>
    									<td class="num "><span class="cBk">9,711</span></td>
    									<td class="num  bgE"><span class="cBk">16,348</span></td>
    									<td class="num "><span class="cBk">3,907</span></td>
    									<td class="num "><span class="cBk">3,023</span></td>
    									<td class="num "><span class="cBk">2,280</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">투자활동현금흐름</th>
    									<td class="num "><span class="cUp">-12,607</span></td>
    									<td class="num "><span class="cUp">-4,142</span></td>
    									<td class="num "><span class="cUp">-12,607</span></td>
    									<td class="num  bgE"><span class="cUp">-10,209</span></td>
    									<td class="num "><span class="cUp">-6,285</span></td>
    									<td class="num "><span class="cBk">1,170</span></td>
    									<td class="num "><span class="cUp">-8,961</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">재무활동현금흐름</th>
    									<td class="num "><span class="cBk">8,905</span></td>
    									<td class="num "><span class="cBk">3,222</span></td>
    									<td class="num "><span class="cBk">13,054</span></td>
    									<td class="num  bgE"><span class="cBk">4,943</span></td>
    									<td class="num "><span class="cBk">5,400</span></td>
    									<td class="num "><span class="cBk">3,814</span></td>
    									<td class="num "><span class="cBk">6,225</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">CAPEX</th>
    									<td class="num "><span class="cBk">972</span></td>
    									<td class="num "><span class="cBk">1,064</span></td>
    									<td class="num "><span class="cBk">1,831</span></td>
    									<td class="num  bgE"><span class="cBk">1,791</span></td>
    									<td class="num "><span class="cBk">930</span></td>
    									<td class="num "><span class="cBk">416</span></td>
    									<td class="num "><span class="cBk">388</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">FCF</th>
    									<td class="num "><span class="cBk">3,943</span></td>
    									<td class="num "><span class="cBk">6,463</span></td>
    									<td class="num "><span class="cBk">7,880</span></td>
    									<td class="num  bgE"><span class="cBk">11,793</span></td>
    									<td class="num "><span class="cBk">2,977</span></td>
    									<td class="num "><span class="cBk">2,607</span></td>
    									<td class="num "><span class="cBk">1,892</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">이자발생부채</th>
    									<td class="num "><span class="cBk">6,545</span></td>
    									<td class="num "><span class="cBk">7,539</span></td>
    									<td class="num "><span class="cBk">9,504</span></td>
    									<td class="num  bgE"></td>
    									<td class="num "><span class="cBk">4,995</span></td>
    									<td class="num "><span class="cBk">9,504</span></td>
    									<td class="num "><span class="cBk">14,856</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">영업이익률</th>
    									<td class="num "><span class="cBk">3.02</span></td>
    									<td class="num "><span class="cBk">6.73</span></td>
    									<td class="num "><span class="cBk">10.97</span></td>
    									<td class="num  bgE"><span class="cBk">13.55</span></td>
    									<td class="num "><span class="cBk">10.92</span></td>
    									<td class="num "><span class="cBk">12.12</span></td>
    									<td class="num "><span class="cBk">12.52</span></td>
    									<td class="bgE num noline-right "><span class="cBk">13.28</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">순이익률</th>
    									<td class="num "><span class="cBk">0.66</span></td>
    									<td class="num "><span class="cUp">-11.14</span></td>
    									<td class="num "><span class="cBk">4.17</span></td>
    									<td class="num  bgE"><span class="cBk">16.96</span></td>
    									<td class="num "><span class="cBk">13.06</span></td>
    									<td class="num "><span class="cUp">-15.83</span></td>
    									<td class="num "><span class="cBk">19.07</span></td>
    									<td class="bgE num noline-right "><span class="cBk">14.80</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">ROE(%)</th>
    									<td class="num "><span class="cBk">1.04</span></td>
    									<td class="num "><span class="cUp">-5.81</span></td>
    									<td class="num "><span class="cBk">2.70</span></td>
    									<td class="num  bgE"><span class="cBk">14.17</span></td>
    									<td class="num "><span class="cUp">-1.33</span></td>
    									<td class="num "><span class="cBk">2.70</span></td>
    									<td class="num "><span class="cBk">5.00</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">ROA(%)</th>
    									<td class="num "><span class="cBk">0.22</span></td>
    									<td class="num "><span class="cUp">-4.09</span></td>
    									<td class="num "><span class="cBk">1.68</span></td>
    									<td class="num  bgE"><span class="cBk">7.68</span></td>
    									<td class="num "><span class="cUp">-0.73</span></td>
    									<td class="num "><span class="cBk">1.68</span></td>
    									<td class="num "><span class="cBk">2.90</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">부채비율</th>
    									<td class="num "><span class="cBk">41.45</span></td>
    									<td class="num "><span class="cBk">52.21</span></td>
    									<td class="num "><span class="cBk">60.94</span></td>
    									<td class="num  bgE"><span class="cBk">67.76</span></td>
    									<td class="num "><span class="cBk">50.37</span></td>
    									<td class="num "><span class="cBk">60.94</span></td>
    									<td class="num "><span class="cBk">71.56</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">자본유보율</th>
    									<td class="num "><span class="cBk">12,219.62</span></td>
    									<td class="num "><span class="cBk">12,027.79</span></td>
    									<td class="num "><span class="cBk">13,881.01</span></td>
    									<td class="num  bgE"></td>
    									<td class="num "><span class="cBk">14,373.52</span></td>
    									<td class="num "><span class="cBk">13,881.01</span></td>
    									<td class="num "><span class="cBk">14,508.10</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">EPS(원)</th>
    									<td class="num "><span class="cBk">123</span></td>
    									<td class="num "><span class="cUp">-717</span></td>
    									<td class="num "><span class="cBk">355</span></td>
    									<td class="num  bgE"><span class="cBk">2,180</span></td>
    									<td class="num "><span class="cBk">290</span></td>
    									<td class="num "><span class="cUp">-428</span></td>
    									<td class="num "><span class="cBk">506</span></td>
    									<td class="bgE num noline-right "><span class="cBk">448</span></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">PER(배)</th>
    									<td class="num "><span class="cBk">168.01</span></td>
    									<td class="num ">N/A</td>
    									<td class="num "><span class="cBk">219.25</span></td>
    									<td class="num  bgE"><span class="cBk">66.96</span></td>
    									<td class="num ">N/A</td>
    									<td class="num "><span class="cBk">219.25</span></td>
    									<td class="num "><span class="cBk">144.96</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">BPS(원)</th>
    									<td class="num "><span class="cBk">12,979</span></td>
    									<td class="num "><span class="cBk">12,746</span></td>
    									<td class="num "><span class="cBk">14,647</span></td>
    									<td class="num  bgE"><span class="cBk">17,042</span></td>
    									<td class="num "><span class="cBk">14,910</span></td>
    									<td class="num "><span class="cBk">14,647</span></td>
    									<td class="num "><span class="cBk">15,428</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">PBR(배)</th>
    									<td class="num "><span class="cBk">1.59</span></td>
    									<td class="num "><span class="cBk">2.41</span></td>
    									<td class="num "><span class="cBk">5.32</span></td>
    									<td class="num  bgE"><span class="cBk">8.57</span></td>
    									<td class="num "><span class="cBk">4.89</span></td>
    									<td class="num "><span class="cBk">5.32</span></td>
    									<td class="num "><span class="cBk">6.46</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">현금DPS(원)</th>
    									<td class="num "><span class="cBk">25</span></td>
    									<td class="num "><span class="cBk">25</span></td>
    									<td class="num "><span class="cBk">30</span></td>
    									<td class="num  bgE"><span class="cBk">32</span></td>
    									<td class="num "><span class="cBk">0</span></td>
    									<td class="num "><span class="cBk">30</span></td>
    									<td class="num "><span class="cBk">0</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">현금배당수익률</th>
    									<td class="num "><span class="cBk">0.12</span></td>
    									<td class="num "><span class="cBk">0.08</span></td>
    									<td class="num "><span class="cBk">0.04</span></td>
    									<td class="num  bgE"><span class="cBk">0.02</span></td>
    									<td class="num "><span class="cBk">0.00</span></td>
    									<td class="num "><span class="cBk">0.04</span></td>
    									<td class="num "></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt ">현금배당성향(%)</th>
    									<td class="num "><span class="cBk">20.99</span></td>
    									<td class="num "><span class="cUp">-3.46</span></td>
    									<td class="num "><span class="cBk">8.29</span></td>
    									<td class="num  bgE"><span class="cBk">1.49</span></td>
    									<td class="num "><span class="cBk">0.00</span></td>
    									<td class="num "><span class="cUp">-6.82</span></td>
    									<td class="num "><span class="cBk">0.00</span></td>
    									<td class="bgE num noline-right "></td>
    								</tr>
    								
    								<tr>
    									<th class="bg txt line-bottom">발행주식수(보통주)</th>
    									<td class="num line-bottom"><span class="cBk">416,938,865</span></td>
    									<td class="num line-bottom"><span class="cBk">431,113,180</span></td>
    									<td class="num line-bottom"><span class="cBk">442,509,990</span></td>
    									<td class="num line-bottom bgE"></td>
    									<td class="num line-bottom"><span class="cBk">441,239,095</span></td>
    									<td class="num line-bottom"><span class="cBk">442,509,990</span></td>
    									<td class="num line-bottom"><span class="cBk">443,809,305</span></td>
    									<td class="bgE num noline-right line-bottom"></td>
    								</tr>
    								</tbody></table>
    


```python
import  pandas  as  pd

dfs = pd.read_html(html)
df = dfs[1]['연간연간컨센서스보기']
df.index = dfs[1]['주요재무정보'].values.flatten()
df = df.loc['현금배당수익률']
df.index = df.index.str[:7]
print(df.to_dict()) 
```

    {'2018/12': 0.12, '2019/12': 0.08, '2020/12': 0.04, '2021/12': 0.02}
    


```python
def get_financial_statements(code):
    re_enc = re.compile("encparam: '(.*)'", re.IGNORECASE)
    re_id = re.compile("id: '([a-zA-Z0-9]*)' ?", re.IGNORECASE)

    url = "http://companyinfo.stock.naver.com/v1/company/c1010001.aspx?cmp_cd={}".format(code)
    html = requests.get(url).text
    encparam = re_enc.search(html).group(1)
    encid = re_id.search(html).group(1)

    url = "http://companyinfo.stock.naver.com/v1/company/ajax/cF1001.aspx?cmp_cd={}&fin_typ=0&freq_typ=A&encparam={}&id={}".format(code, encparam, encid)
    headers = {"Referer": "HACK"}
    html = requests.get(url, headers=headers).text

    dfs = pd.read_html(html)
    df = dfs[1]['연간연간컨센서스보기']
    df.index = dfs[1]['주요재무정보'].values.flatten()
    df = df.loc['현금배당수익률']
    df.index = df.index.str[:7]

    return df.to_dict()

if __name__ == "__main__":
    dividend_dict = get_financial_statements("035720") 
    print(dividend_dict)
```

    {'2018/12': 0.12, '2019/12': 0.08, '2020/12': 0.04, '2021/12': 0.02}
    


```python

```


```python

```


```python

```


```python

```
