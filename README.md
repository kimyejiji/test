<div id="btnKakao">
    <img src="/img/sns_kakao.png" id="kakao-link-btn" alt="카카오톡 링크 공유하기">
</div>
 
 
<script src="//developers.kakao.com/sdk/js/kakao.min.js"></script>
<script type='text/javascript'>
    //<![CDATA[
    // // 사용할 앱의 JavaScript 키를 설정해 주세요.
    Kakao.init('cd2d454bc7ef7b2d0add48dcc08a5837');
    // // 카카오링크 버튼을 생성합니다. 처음 한번만 호출하면 됩니다.
    Kakao.Link.createScrapButton({
        container: '#kakao-link-btn',
        requestUrl: 'URL 주소 입력',
        templateId : 98757
    });
    //]]>
</script>
