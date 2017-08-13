---
layout: page
title: "Roadmap"
subheadline: "ToDo-List &amp; Ideas"
teaser: "Here are some ideas and features I want to implement in the future."
header:
   image_fullwidth: "header_roadmap_3.jpg"
permalink: "/roadmap/"
---

<!-- * Daum 지도 - 지도퍼가기 -->
<!-- 1. 지도 노드 -->
<div id="daumRoughmapContainer1502587565319" class="root_daum_roughmap root_daum_roughmap_landing"></div>

<!--
	2. 설치 스크립트
	* 지도 퍼가기 서비스를 2개 이상 넣을 경우, 설치 스크립트는 하나만 삽입합니다.
-->
<script charset="UTF-8" class="daum_roughmap_loader_script" src="https://spi.maps.daum.net/imap/map_js_init/roughmapLoader.js"></script>

<!-- 3. 실행 스크립트 -->
<script charset="UTF-8">
	new daum.roughmap.Lander({
		"timestamp" : "1502587565319",
		"key" : "j4uf",
		"mapWidth" : "600",
		"mapHeight" : "500"
	}).render();
</script>



