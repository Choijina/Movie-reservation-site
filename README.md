# HTML-CSS
간단한 영화 예매 사이트를 제작했습니다. DB가 연동 되어 있지 않아 완벽하진 않습니다.

메인 페이지에서 영화의 포스터를 누르면
- 상단에서 영화의 스틸컷 3장을 보여주고 있습니다. 이 영화가 전체적으로 어떤 분위기인지, 어떤 등장인물들이 나오는지 고객이 파악할 수 있습니다. <div> 태그를 이용해서 백그라운드 이미지를 넣었고, 또 그 안에 <div> 태그를 이용해 흰색 테두리를 만든 다음 이미지를 넣었습니다.

- 중앙에서는 영화의 세부적인 정보를 보여주고 있습니다. 이 영화의 평점이 어떤지, 예매율은 어떤지, 장르가 무엇인지 등등 영화의 상세 정보를 고객이 알 수 있습니다. 이곳에서는  왼쪽에 있는 포스터 하나, 영화 제목과 세부정보 하나, 줄거리 하나 이렇게 나눠서 <div> 태그를 총 3개 사용하고 있습니다. 또한, 폰트 효과를 각자 다르게(제목, 세부정보, 줄거리 폰트 각자 다름) 설정함과 동시에 <hr> 태그를 이용해 중간에 선을 그어서 정보의 구분이 더욱 쉽도록 만들었습니다.

- 하단에 있는 ‘창닫기’ 버튼을 누르면 이 창을 닫을 수 있습니다. 자바스크립트 close() 메소드를 이용했습니다. close() 앞에 self.를 붙여서 버튼을 누르면 이 창이 닫히도록 만들었습니다.
