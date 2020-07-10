
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<!-- saved from url=(0070)file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/index.html -->
<html lang="ko"><!-- Mirrored from my.newscover.co.kr/loloc8/?ref=1090&cc=1862528 by HTTrack Website Copier/3.x [XR&CO'2014], Wed, 08 Jul 2020 09:08:07 GMT --><!-- Added by HTTrack --><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><!-- /Added by HTTrack -->


<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>:: 로또 ::</title>
<link rel="stylesheet" href="./index_files/common.css">
<link rel="stylesheet" href="./index_files/bootstrap.min.html">
<link rel="stylesheet" href="./index_files/lightslider.min.html">
<link rel="stylesheet" href="./index_files/nanumgothic.css">
<link rel="stylesheet" href="./index_files/style.css">
<style type="text/css">
/*roul container style sheet*/
.event_roul_wrap{ width:100%; max-width:600px; margin:0 auto; }
.event_roul_wrap .db_container{ display:none; }
.roulette_container{ position:relative; }
.event_roul_wrap img{ display:block; width:100%; }/*이벤트 룰렛 안의 모든 이미지 블럭요소로 변환*/

/*roul common style sheet*/
.roulette_container .roulette{ position:absolute; left:50%; top:50%; transform:translate(-50%,-50%); }
/*룰렛 링*/
.roulette_container .roulette.roul_outer{ width:90%; }
/*룰렛 판*/
.roulette_container .roulette.roul_inner{ width:75%; }
/*룰렛 회전*/
.roulette_container .roulette .roul_rotate.rotate{ animation:roul 4s forwards ease-out; }
/*룰렛 화살표*/
.roulette_container .roulette.roul_arrow{ width:8%; top:29%; }
/*룰렛 버튼*/
.roulette_container .roulette.roul_btn{ width:15%; cursor:pointer; }
/*룰렛 키프레임*/
@keyframes roul{
	0%{ transform:rotate(0deg); }
	30%{ transform:rotate(950deg); }
	60%{ transform:rotate(900deg); }
	100%{ transform:rotate(950deg); }
}

input {border:1px solid #999 !important;}
input[type="image"] {border:none !important;}
</style>
<script src="./index_files/jquery.js(1).다운로드"></script>
<script src="./index_files/common.js.다운로드"></script>
<script type="text/javascript">
function form_Check(){
	var f = document.order_form;
	var pattern	= /^(?:(010\d{4})|(01[1|6|7|8|9]\d{3,4}))(\d{4})$/;

	if(!f.phone.value){
		alert("연락처를 입력 하세요");
		return false;
	}
	if(!pattern.test(f.phone.value)){
		alert("올바른 휴대폰번호가 아닙니다.\n 정확한 번호 입력 및 숫자만 입력 가능 합니다.");
		return false;
	}
}

$(document).ready(function(){
	$("input[name=tel2]").keyup(function(){
		var idx = $(this).index("input[name=tel2]");
		if( $(this).val().length == 4 ){
		  var NextInput = $("input[name=tel3]").eq(idx).focus();
		}
	});

	/*룰렛 js*/
	$('.roul_btn').on('click', function(){
		var idx = $(this).index('.roul_btn');
		var position = $('.event_roul_wrap').eq(idx).offset().top;//룰렛 위치

		$('.roulette_container .roulette .roul_rotate').eq(idx).addClass('rotate');
		setTimeout(function(){
			$('.roulette_container').eq(idx).hide();
			$('.db_container').eq(idx).fadeIn();
			setTimeout(function(){//스크롤 이동
				$('html, body').stop().animate({scrollTop:position+'px'},100);
			},200);
		},4400);
	});
});
</script>
<script type="text/javascript" async="" src="./index_files/click_icon.js.다운로드"></script><script type="text/javascript" async="" src="file:///D:/common/js/click_icon.js"></script><script type="text/javascript" async="" src="file:///D:/common/js/click_icon.js"></script><script type="text/javascript" async="" src="./index_files/click_icon.js(1).다운로드"></script><script type="text/javascript" async="" src="file:///D:/common/js/click_icon.js"></script></head>
<body>
<header></header>
<section id="landpage-wrapper">
<div class="container" style="width: 100%;margin: 0 auto;">
	<!--상단 S-->
	<div class="header row">
		<div class="top">
			<img src="./index_files/post_logo3.png" class="logo">
			<div class="search">
				<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_dot2.png" class="post_dot"></a>
                <a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_search2.png" class="post_search"></a>
                <a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_user2.png" class="post_user"></a>
			</div>
			<div class="clearfix">
			</div>
		</div>
		<div class="clearfix">
		</div>
	</div>
	<!--상단 E-->
	<div style="max-width: 700px;margin: 0 auto; padding:0 5px;">
		<div class="contents">
			<div class="layout_fix">
				<!-- 본문박스 -->
				<div class="article_box rows">
					<div class="col-sm-12 col-md-12" style="padding: 0px;">
						<!-- 기사타이틀 -->
						<div class="article_title">
							<div style="clear:both;">
							</div>
							<span class="title-top">최신기사</span>
							<table class="titlebox">
							<tbody><tr>
								<td class="tit">
									<span class="red">[속보]</span>코로나 치료제 임상결과 대외비 정보 유출?!
								</td>
							</tr>
							</tbody></table>
							<div class="post_date2">
								<div class="post_date">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_eye1-2.png" class="post_eye"></a>
									367,378 읽음 <span class="num">
									2020-07-10									</span>
								</div>
								<div style="position: absolute;right: 0px;top: 10px;">
								</div>
							</div>
							<div style="clear:both;">
							</div>
							<table class="titlebox2" width="100%" border="0" cellspacing="0" cellpadding="0">
							<tbody><tr>
								<td class="sub_tit">
									- 기업 대외비 정보 유출..<br>
									- 정보를 얻을수있는곳이 있다?!
								</td>
							</tr>
							</tbody></table>
						</div>
						<div class="paragraph" style="margin-bottom:20px;">
							<dl>
								<dd class="txt img1" style="padding:0;text-align:center !important;">
								<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/img1_2.jpg" alt="" style="width:100%;display: block;"></a>
								
								</dd>
								<dd class="txt">
								김무명씨(가명) 코로나로인해 주식 시장 절반 이상이 치료제로 몰리고 있다는 소식을 듣고 "왜그럴까?" 이리저리 찾아보다 치료제 기업에 대외비가 유출됐다는 소문이 퍼지고있다는 걸 알게되었다. 그러다 알게된<strong style="color:#ff0000;">"메이저경제TV"</strong> 라는 유튜버이자 트레이더 분들에 대외비 유출에 대해 자세히 소개를 한적이 있었다. 그러나 분석한결과 그런일은 절때 없을꺼라며 속지 말라고 얘기를 꺼내었다 .</dd>
								<dd class="txt">
								김씨는 사기를 당한적이 한두번이 아니다라며 안타까운 소식을 전했다. 하지만 메이저경제TV 를 통해 많은것을 배우고 지금은 꾸준한 수익을 얻고있다고 전해졌다 약 <strong style="color:#ff0000;">482% 이상의 수익률을</strong> 벌었다며, 더 이상 돈 걱정 없이 살수있다고 행복한 하루를 보내고 있다.</dd>
								<dd class="txt img2" style="text-align:center !important;">
								<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/img2_1.gif" alt="" style="width:100%;display: block;"></a>
								
								</dd>
								<dd class="txt">
								메이저경제TV 에선 VIP방을 을 운영중이며, 1개월 무료로 VIP방을 누구나 조건없이 정보를 드리고있다고 전했다. <strong style="color:#ff0000;">무료 체험이 끝나면 매달 30명에게 VIP이용권 금액을 할인하여, 적은금액으로 누구나 정확한 정보제공을</strong> 받을수있다고 전해졌다.</dd>
							</dl>
						</div>
						<!-- DB박스 시작 -->
						<a name="db_table" id="db_table"></a>
						<div class="event_roul_wrap">
							<!----------------------------------------------------------roulette start------------------------------------------------------->
							<div class="roulette_container">
								<img src="./index_files/roulette_bg.jpg">

								<div class="roulette roul_inner">
									<div class="roul_rotate">
										<img src="./index_files/pan.png">
									</div>
								</div>

								<div class="roulette roul_outer">
									<img src="./index_files/roulette_1.png">
								</div>

								<div class="roulette roul_btn">
									<img src="./index_files/start.gif">
								</div>

								<div class="roulette roul_arrow">
									<img src="./index_files/check.png">
								</div>
							</div>
							<!----------------------------------------------------------roulette end------------------------------------------------------->

							<!----------------------------------------------------------db start------------------------------------------------------->
							<div class="db_container">
								<form name="order_form" class="order_form" method="POST" action="http://my.newscover.co.kr/action.html" onsubmit="return form_Check();" target="frmProc">
							        <input type="hidden" name="code" value="1090">
							        <input type="hidden" name="vt" value="">
							        <input type="hidden" name="ccode" value="1862528">
							        <input type="hidden" name="act_type" value="frm">

							        <div>
							            <img src="./index_files/roulette_2.gif">
							        </div>
							        <div style="box-sizing:border-box; padding:3% 1% 3% 1%; font-size:0; border: 1px solid #ccc; text-align:center; font-size:0;">
							            <div>
							                <div style="display:inline-block; width:25%; text-align:left;">
							                    <span style="font-size:1.05rem;">핸드폰번호</span>
							                </div>
							                <div style="display:inline-block; width:60%;">
							                    <input name="phone" id="phone" type="tel" style="width:100%; height:30px;" placeholder="핸드폰번호 (“-”없이 입력)">
							                </div>
							            </div>

							            <div class="btn" style="width:90%; margin:5% auto; text-align:center;">
							                <input type="image" src="./index_files/db_btn.png" style="width:100%;">
							            </div>
							        </div>
						    	</form>
						    </div>
						    <!----------------------------------------------------------db end------------------------------------------------------->
						</div>
<!--    0511 이벤트페이지 주석처리 lsh
						<div style="margin-top: 20px;">
							//						</div>
-->
						
						<!-- DB박스 끝 -->
						<div class="byline">
							<ul class="tag">
								<li>#주식</li>
								<li>#수익</li>
								<li>#수익률얼마야도대체</li>
								<li>#종목추천</li>
								<li>#flex</li>
								<li>#부자</li>
								<li>#공짜</li>
								<li>#무료상담</li>
								<li>#종목</li>
								<li>#메이저경제TV</li>
								<li>#급등주</li>
								<li>#해외선물</li>
								<li>#코스피</li>
								<li>#비트코인</li>
							</ul>
							<div class="byline-sns">
								<div class="like-number">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_heart.png" class="post_heart"></a>
									<span>541</span>
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/dot.jpg" class="like-dot"></a>
								</div>
								<div class="comment-number" style="padding: 3px 9px 0px 10px;">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_talk.png" class="post_talk"></a>
									<span>251</span>
								</div>
								<div class="sns-btn">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_kakao.jpg" class="mobile-no2"></a>
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_inasta.jpg" class="mobile-no2"></a>
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_face.jpg" class="mobile-no2"></a>
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_scrap.png" class="post_scrap"></a>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div style="width:100%;border-bottom: 1px solid #e5e5e5;">
	</div>
	<div style="max-width: 700px;margin: 0 auto;">
		<div class="contents">
			<div class="layout_fix">
				<div class="article_box rows">
					<div class="col-sm-12 col-md-12" style="padding: 0px;">
						<!-- 댓글영역 -->
						<div class="comment">
							<div class="top-line" style="font-size: 0px;">
								<span style="font-size: 14px;">댓글 251</span>
								<img src="./index_files/post_f5.png" class="post_f5">
							</div>
							<div class="top-line2">
								<div class="write-box">
									<textarea class="write-comment" placeholder="댓글을 작성하려면 로그인 해주세요" readonly=""></textarea>
									<button class="comment-btn">등록</button>
								</div>
							</div>
							<div class="top-line3">
								<span>전체댓글</span>
							</div>
							<div class="line line2">
								<div class="nickname">
									<img src="./index_files/post_writer2.png" class="post_writer"><span>zidn****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_best2.png" alt="" class="post_best">
									<span>지금 신청하면 되는거죠? 신청합시다 저는 2등만 되도 좋아요 제발요</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">550</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">38</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line line2">
								<div class="nickname">
									<img src="./index_files/post_writer2.png" class="post_writer"><span>dfee****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_best2.png" alt="" class="post_best">
									<span>로또 왜하나 하는 사람입니다. 주변에서 자꾸 당첨되는 사람들이 늘어나니 미치겠네요 저도해야겠습니다..</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">420</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">20</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line line2">
								<div class="nickname">
									<img src="./index_files/post_writer2.png" class="post_writer"><span>roys****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table"><img src="./index_files/post_best2.png" alt="" class="post_best">
									<span>100%무료라니까 일단 받아보지 안되도 본전이잖아요</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">310</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">37</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line">
								<div class="nickname">
									<a href="javascript:fnMove()" class="nounderline"><img src="./index_files/post_writer2.png" class="post_writer"><span>gode****</span></a>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">
									<span>혼자만 알고싶었는데... 전 매일 여기들어와서 신청남겨요ㅋㅋㅋㅋㅋㅋㅋ두번당첨됨ㅋㅋ</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">276</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">22</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line">
								<div class="nickname">
									<img src="./index_files/post_writer2.png" class="post_writer"><span>tose****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">
									<span>어쩐지 자동자동자동 으로만 돌렸더니 안됐나봐여</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">255</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">14</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line">
								<div class="nickname">
								<img src="./index_files/post_writer2.png" class="post_writer"><span>kjpr****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">
									<span>요새 로또기사 난리났는데 다여긴가봐 개쩔어 저도 되여? 어떤 번호를 주려나</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">209</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">19</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line">
								<div class="nickname">
									<img src="./index_files/post_writer2.png" class="post_writer"><span>blac****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">
									<span>저 자주가는 복덕방사장님도 어디서 번호받고 자기가게에서 사서 당첨됐다고ㅋㅋㅋ 자기갘ㅋㅋ 맨날 찾았는데 드디어 찾았다 내사랑</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">162</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">8</span>
										</div>
									</div>
								</div>
							</div>
							<div class="line">
								<div class="nickname">
									<img src="./index_files/post_writer2.png" class="post_writer"><span>hjie****</span>
								</div>
								<div class="cmt-contents">
									<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">
									<span>로또로 인생역전 될까요? 가즈아앙ㅇ어앙</span>
									</a>
								</div>
								<div class="commentdate">
									<div class="date">
										2020-07-07									</div>
									<div class="post-like">
										<div class="post-like-box">
											<img src="./index_files/post_like2.png" class="like" alt="">
											<span class="like_num">133</span>
										</div>
										<div class="post-like-box">
											<img src="./index_files/post_dislike2.png" class="like2" alt="">
											<span class="like_num">31</span>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="paging mobile-no">
							<ul>
								<li class="active">1</li>
								<li>2</li>
								<li>3</li>
								<li>맨뒤 &gt;</li>
							</ul>
							<div class="more2">
								<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">전체 댓글 더보기 &gt;</a>
							</div>
						</div>
						<div class="mobile-more web-no">
							<div class="more22">
								<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">더보기 <img src="./index_files/post_more.png" class="more22-arrow" alt=""></a>
							</div>
							<div class="more23">
								<a href="file:///D:/%EC%82%AC%EC%9D%B4%ED%8A%B8%20%EB%B3%B5%EC%82%AC/my.newscover.co.kr/loloc8/index6349.html#db_table">전체 댓글 더보기 &gt;</a>
							</div>
						</div>
						<!-- 댓글영역 끝 -->
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<div class="footer">
	 Copyright ⓒ All Rights Reserved.
</div>
</section>




<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no">
	<title>Document</title>
<!--<script type="text/javascript" src="//simg.imadrep.co.kr/js/jquery.js"></script>-->
<script type="text/javascript" src="./index_files/jquery.jscroll.js.다운로드"></script>
<script type="text/javascript">

$(document).ready(function () {
	$('#autoScroll').jscroll({
		autoTrigger: true,
		loadingHtml: '<div class="next" style="text-align:center;padding-top:15px;"><img src="/common/img/loading.gif" alt="Loading" style="width:8%; margin:0 auto;" /></div>',
		nextSelector: 'a.nextPage'
    });
});

</script>
<style type="text/css">
	#autoScroll{}
	.banner_box{}
</style>


		<div class="wrap" width="100%" style="max-width: 600px; margin: 0 auto;margin-top:15px;">
		<div style="margin-bottom: 10px;"><img src="./index_files/m_ld_title.jpg" width="100%" alt=""></div>

		<div class="banner_box" max-width="600px" style="width: 100%;">

			<div class="content_wrap" id="autoScroll"><div class="jscroll-inner">
				<iframe src="./index_files/cover_14.html" width="100%" height="1562" border="1" frameborder="0" framemargin="0" leftmargin="0" topmargin="0" marginheight="0" marginwidth="0" scrolling="no" id="frm_3556" name="frm_3556"></iframe>
								<div class="next jscroll-next-parent" style="display: none;"><a href="http://my.newscover.co.kr/common/inc/nlist.html?mode=auto&amp;page=2" class="nextPage">다음 페이지</a></div>
							<div class="jscroll-added"><div class="jscroll-loading" id="jscroll-loading"><div class="next" style="text-align:center;padding-top:15px;"><img src="file:///D:/common/img/loading.gif" alt="Loading" style="width:8%; margin:0 auto;"></div></div></div></div></div>

			<div class="cover_footer" style="margin:15px 0 10px 0;max-width:600px;"><img src="./index_files/m_ld_footer.jpg" width="100%" alt=""></div>
		</div>
	</div>
	



<!-- Mirrored from my.newscover.co.kr/loloc8/?ref=1090&cc=1862528 by HTTrack Website Copier/3.x [XR&CO'2014], Wed, 08 Jul 2020 09:08:58 GMT -->
<iframe name="frmProc" style="width:0;height:0;" src="./index_files/saved_resource.html"></iframe>


<script type="text/Javascript">
var zc = "1090";

if(zc != 1170){

var app_item = [];
app_item['u'] = "http://my.newscover.co.kr/shortcut.html?uu=%2Floloc8%2F%3Fref%3D1090%26cc%3D1862528";
app_item['icon'] = "../../simg.imadrep.co.kr/img/m/app_icon_1862527.png";
app_item['title'] = encodeURI("이번주 1 등번호");
app_item['url'] = encodeURIComponent(decodeURIComponent(app_item['u']).replace(/cc=([0-9].*)/g ,"cc="+app_item['icon'].replace(/[^0-9]/g, '')));
(function () {
var head = document.getElementsByTagName('head')[0];
var script = document.createElement('script');
script.type = 'text/javascript';
script.async = true;
script.src = '../common/js/click_icon.js';
head.appendChild(script);
})();
}
</script>

</body></html>
